<table width="95%" border="0" cellspacing="8" cellpadding="8">
                <tbody><tr valign="top"> 
                  <td> 
						
                    <table width="100%" style="table-layout: fixed;" name="titlebar" id="titlebar" border="0" cellspacing="0" cellpadding="0" background="images/green_gradient.gif" height="20">
                      <tbody><tr nowrap=""> 
					    <td width="*" valign="middle" style="overflow: hidden; text-overflow: ellipsis; white-space: nowrap;" class="titlebar" nowrap="">&nbsp;Primary&nbsp;Homeowner&nbsp;Information</td>
                        <td width="23" valign="top" nowrap=""> 
                          <table width="13" border="0" cellspacing="2" cellpadding="2">
                            <tbody><tr nowrap=""> 
                              <td nowrap="">
      <input type="image" border="0" onmouseover="MM_swapImage('btnClose','','images/checkbox_on.gif',1)" onmouseout="MM_swapImgRestore()" class="input_noborder" name="btnClose" id="btnClose" src="images/checkbox_off.gif" width="15" height="15" onclick="javascript:nClose=1;">
							  </td>
                            </tr>
                          </tbody></table>
                        </td>
                      </tr>
                    </tbody></table>
<script language="JavaScript" type="text/JavaScript">
<!--
    function HideLoadingdiv()
    {
        localStorage.LocalToGlobalVar = "GenerateCoupon";
        nGen=1;
    }
function MM_swapImgRestore() { //v3.0
  var i,x,a=document.MM_sr; for(i=0;a&&i<a.length&&(x=a[i])&&x.oSrc;i++) x.src=x.oSrc;
}
function popupHelp(pTitle) 
{
  window.parent.window.document.getElementById('loadingDialog').style.display = 'none';

	window.open('./help/hlp_propertyform.asp?'+pTitle, 'helpPopup', "'alwaysRaised=yes,dependent=yes,top=215,left=100,height=550,width=557,resizable=no,scrollbars=1'");

}
//-->

function swapImage(elmID, state, imgPath) {
    var btn = document.getElementById(elmID);
    var btnName = elmID.replace('btn', '');

    if (btnName == 'CloseVoid')
        btnName = 'Close'

    var imgPath = "images/icon_btn_" + btnName + state + '.gif';
                
    if (btn != null) {
        btn.src = imgPath;
    }
}

</script>

<table width="100%" border="0" cellpadding="0" cellspacing="0">
  <tbody><tr>
    <td bgcolor="#99CCCC">

		    <input accesskey="s" type="image" border="0" class="input_noborder" name="btnSave" id="btnSave" src="images/icon_btn_save.gif" onmouseover="swapImage(this.name,'_on')" onmouseout="swapImage(this.name,'')" width="64" height="24" onclick="javascript:nSave=1;">

	        <input accesskey="n" type="image" border="0" onmouseover="swapImage(this.name,'_on')" onmouseout="swapImage(this.name,'')" class="input_noborder" name="btnSaveNew" id="btnSaveNew" src="images/icon_btn_savenew.gif" onclick="javascript:nSave=1;">

    	    <input accesskey="x" type="image" border="0" onmouseover="swapImage(this.name,'_on')" onmouseout="swapImage(this.name,'')" class="input_noborder" name="btnCancel" id="btnCancel" src="images/icon_btn_cancel.gif" width="74" height="24" onclick="javascript:nCancel=1;">

    </td>
 </tr>
</tbody></table>

                    <table width="100%" border="0" cellspacing="1" cellpadding="1" bgcolor="#99CC99">
                      <tbody><tr valign="top"> 
                        <td> 
                          <table width="100%" border="0" class="bodytext tableLinks" bgcolor="#FFFFFF">
                            <tbody><tr> 
                              <td class="formlabel" id="toptier">Association</td>
                              <td colspan="3">
							  
  <script language="JavaScript">
    // 'Sprint - 30 : To be modified in the future:
    parent.window.SaveSelectedAssociationSilently(62,true)      
    parent.window.RefreshAssocHTMLItems(62,'601 Queens Condominium Association, Inc','00000155');
  </script>

  <script language="JavaScript">
  {
  	if(document.getElementById("lblAssocCode"))
  		document.getElementById("lblAssocCode").innerHTML = '00000155<span>601 Queens Condominium Association, Inc</span>';
    if (parent.document.getElementById("lblAssocCode") != null) 			
      parent.document.getElementById("lblAssocCode").innerHTML = '00000155<span>601 Queens Condominium Association, Inc</span>';
  }
  </script>


	<script language="JavaScript">
	function ShowAssocList(nIndex,sPage,nTop,nLeft,nHeight,nWidth,nAssoc,nValue)
	{
		nField = nIndex;
		var IfrRef = document.getElementById('DropDown');
		// Use IMaxRight to define the furthest right point that any ShowList frame should be displayed.
		var IMaxRight = 790;
		IfrRef.style.width = nWidth;
		IfrRef.style.height = nHeight;
		IfrRef.style.top = nTop;
		if (nWidth + nLeft > IMaxRight)
		{
			IfrRef.style.left = IMaxRight - nWidth;
		}
		else
		{
			IfrRef.style.left = nLeft;
		}
		IfrRef.style.zIndex = 0;
		IfrRef.src = sPage + "&a=" + nAssoc + "&w=" + nValue;
		IfrRef.style.display = "block";
		window.parent.window.document.getElementById('loadingDialog').style.display = 'none';
	}
	function SelectAssoc(sText,nValue,sDescr)
	{
		document.frmproperty.target = "_self";
		document.frmproperty.numAssocID.value = nValue;
		document.frmproperty.txtAssocName.value = "";
		document.getElementById("AssocNameDisplay").innerHTML = sText;

    var sCodeMVC, sTextMVC, sValueMVC 
    
		if (sDescr.indexOf("~") != -1)
		{
			var a = sDescr.split("~");
			if(document.getElementById("lblAssocCode"))
				document.getElementById("lblAssocCode").innerHTML = a[0] + "<span>" + a[1] + "</span>";
      // Added by Migration - Sprint 12:
      sCodeMVC = a[0];
      sTextMVC = sText;
      sValueMVC = nValue;
		}
		else
		{
			nValue = 0;
			if(document.getElementById("lblAssocCode"))
				document.getElementById("lblAssocCode").innerHTML = "(All Associations)<span>(All Associations)</span>";
      // Added by Migration - Sprint 12:
      sCodeMVC = "All Associations";
      sTextMVC = "All Associations";
      sValueMVC = nValue;
		}
		
		// This AJAX call will save the Navigator's state to session.
		// We don't need a callback function because nothing happens
		// once said state is saved.

		var url = "savesessionassocid.asp?id=" + nValue;
		try
		{
			// Internet Explorer
			req = new ActiveXObject("Microsoft.XMLHTTP");
		}
		catch (e)
		{
			// Firefox, Opera 8.0+, Safari
			req = new XMLHttpRequest();
		}
		req.open("POST", url, true);				
		req.send();
		
		if(window.AssociationChanged)
			AssociationChanged();
      
		if (document.frmproperty.name == 'splitpymt') {
		    parent.parent.window.SaveSelectedAssociation(sValueMVC,sTextMVC,sCodeMVC);
		} else {
		    parent.window.SaveSelectedAssociation(sValueMVC,sTextMVC,sCodeMVC);
		}
    
		CloseList();
	}
	</script>
		<div style="">
			<div style="min-width:135px; float:right; vertical-align:top">
				<input name="txtAssocName" id="txtAssocName" type="text" value="" size="15" maxlength="50">
				<input type="hidden" name="numAssocID" value="62"><a href="javascript:ShowAssocList(0,'associationselectlist.asp?allassocs=0',getElementPosition('txtAssocName', 'top')+20,getElementPosition('txtAssocName', 'left'),150,550,document.frmproperty.numAssocID.value,document.frmproperty.txtAssocName.value);"><img src="images/icon_lookup.gif" width="20" height="21" border="0" align="absbottom"></a>
			</div>
			<div style="width:5px; float:right"></div><!-- Spacer div to use instead of &nbsp;, in case the association name wraps to multiple lines -->
			<div id="AssocNameDisplay" style="float:right; vertical-align:top" align="right">601 Queens Condominium Association, Inc</div>
		</div>
	
							 </td>
                            </tr>
                            <tr> 
                              <td class="formlabel">Settled</td>
                              <td>
							  	
							  	<input type="text" name="dteSettled" id="dteSettled" size="10" maxlength="10" value="">
								
								<a href="javascript:ShowCalendar('document.frmproperty.',document.frmproperty.dteSettled,getElementPosition('dteSettled', 'top')+20,getElementPosition('dteSettled', 'left'));"><img src="images/icon_calendar.gif" width="20" height="21" border="0" align="absbottom"></a>
								
							  </td>
                              <td class="formlabel">Drive Order</td>
                              <td><input name="numDriveOrder" type="text" value="0" size="10" maxlength="10"></td>
                            </tr>
                            <tr> 
                              <td class="formlabel">Status</td>
                              <td> <select name="numPropertyStatusID" onchange="javascript:nSave=0;">
                                  <option value="16">30 Day Collections Letter</option><option value="17">60 Day Collections Letter</option><option value="18">90 Day Collections Letter</option><option value="42">ACH Payment Plan - Association</option><option value="43">ACH Payment Plan - Attorney</option><option value="48">Collections Agency</option><option value="23">Developer Owned </option><option value="22">Developer Owned - No Dues</option><option value="51">Developer Owned - No Dues - No Mgt Fee</option><option value="49">Foreclosed by Association - H.O. Repayment Plan</option><option value="40">Foreclosed by Association - Pending Possession</option><option value="47">Foreclosure Affidavit Received - Pending FC</option><option value="4">In Escrow</option><option value="3">In Foreclosure - Association</option><option value="14">In Foreclosure - Lender</option><option value="8">Lien</option><option value="38">Lien - Hold per BOD</option><option value="13">Model Home</option><option value="1">Occupied</option><option value="45">Occupied - ASK FOR PASSWORD</option><option value="44">Occupied - Part Time</option><option value="10">Payment Plan - Association</option><option value="15">Payment Plan - Attorney</option><option value="46">Pending Board Approval for Foreclosure</option><option value="37">Pending Collections Hearing</option><option value="6">Post-bankruptcy</option><option value="39">Post-bankruptcy - PAYMENT PLAN</option><option value="11">Pre (In) Bankruptcy</option><option value="20">Pre-Foreclosure Collections Letter</option><option value="19">Pre-Lien Collections Letter</option><option value="35">Pre-Water Disconnection</option><option value="-1">Previous Owner</option><option value="50">Previous Owner - Collections Agency</option><option value="12">Rental</option><option value="25">Test Status</option><option value="2">Unoccupied</option><option value="41">Vacant Lot</option><option value="36">Vacant Lot - Developer Owned - No Dues</option><option value="52">Vacant Lot - Developer Owned - No Dues -No Mgt Fee</option><option value="34">Water Disconnection</option> </select> </td>
							  <td class="formlabel">Block Payments</td>
							  <td>
							  	
							  	<input class="input_noborder" name="numBlockPayments" type="checkbox">
							  </td>
                            </tr>
							<tr>
								<td class="formlabel">Mgmt Rental Ratio</td>
								<td><input name="pctMRRPercent" id="pctMRRPercent" type="text" value="0" size="15" maxlength="15">%</td>
								
								<td colspan="2">&nbsp;</td>
								
							</tr>
                             <tr> 
                              <td class="formlabel">Collection Status</td>
                              <td colspan="3"> <select name="numCollectionLevelID" onchange="javascript:nSave=0;">
							  	  <option value="0">(No Status)</option>
                                  <option value="2709"></option><option value="2710"></option><option value="433">30 Days Late</option><option value="432">60 Days Late</option><option value="431">90 Days Late</option><option value="427">Foreclosure</option><option value="428">Lien</option><option value="1118">Pending Address Verification</option><option value="1578">Pending Board Approval for Foreclosure</option><option value="429">Pre-Foreclosure</option><option value="430">Pre-Lien</option> </select>
								  &nbsp;&nbsp;<a href="javascript:ShowList(2,'collactivitylog.asp',getElementPosition('toptier', 'top'),getElementPosition('toptier','left'),450,680,0,'0');">Activity Log</a></td>
                            </tr>
                             <tr> 
                              <td class="formlabel">Attorney</td>
                              <td colspan="3"> <select name="numVendorID" onchange="javascript:nSave=0;">
							  	  <option value="0">(None)</option>
                                  <option value="1446">Assessment Recovery, Limited</option><option value="1221">Assessment Recovery, LLC</option><option value="820">Ballard Spahr LLP</option><option value="955">Bolick &amp; Associates, PA</option><option value="724">Charles S. Bradford, P.A.</option><option value="1087">Clark, Griffin &amp; McCollum, LLP</option><option value="3000">Cool Vendor</option><option value="1499">David B. Sample</option><option value="654">Donnan &amp; Morton, PA</option><option value="985">Dungan, Kilbourne &amp; Stahl, P.A.</option><option value="3038">Fake Attorney</option><option value="1062">Hatch Little &amp; Bunn, LLP</option><option value="1802">Hedrick Gardner Kincheloe &amp; Garofalo LLP</option><option value="13">Horack, Talley, Pharr &amp; Lowndes PA</option><option value="1329">J. Thomas Mikell PC</option><option value="809">James R. Snell, Jr.</option><option value="1395">James, McElroy &amp; Diehl</option><option value="1102">Joel R. Weaver, PA</option><option value="117">Jordan, Price, Wall, Gray, Jones &amp; Carlton</option><option value="3001">Keep Vendor</option><option value="576">Kilby and Hurley, Attorneys at Law</option><option value="14">Koehler &amp; Cordes</option><option value="1374">Law Offices of Chris Karrenstein, PA</option><option value="31">Law Offices of Chris Karrenstein, PA</option><option value="1677">Marshall, Roth &amp; Gregory, PC</option><option value="1588">Metcalfe &amp; Atkinson, LLC</option><option value="1456">Moore &amp; Alphin PLLC</option><option value="1733">Prince, Youngblood &amp; Massagee PLLC</option><option value="629">Pruitt &amp; Pruitt</option><option value="1104">Roger W. Knight, PA</option><option value="324">Rossabi Black Slaughter, P.A.</option><option value="188">Sellers, Hinshaw, Ayers, Dortch &amp; Lyons, P.A.</option><option value="805">Setzler &amp; Scott, PA</option><option value="101">Smith Debnam Narron Wyche Saintsing &amp; Myers, LLP</option><option value="2993">TESTING 2015.1</option><option value="1307">The Cranford Law Firm</option><option value="230">Thurman, Wilson &amp; Boutwell &amp; Galvin, P.A.</option><option value="949">Van Winkle, Buck, Wall, Starnes and Davis, PA</option><option value="1544">Vernon Vernon Wootgen Brown Andrews &amp; Garrett, PA</option><option value="996">Weaver, Bennett &amp; Bland, PA</option><option value="1740">Weissman, Nowack, Curry &amp; Wilco, P.C.</option><option value="1432">Wishart Norris Henninger &amp; Pittman, PA</option><option value="1807">Woodall Law Firm</option><option value="1770">Wyrick Robbins Yates &amp; Ponton LLP</option><option value="529">Zachary M. Moretz</option> </select> </td>
                            </tr>
							<tr> 
							  <td class="formlabel">Hold Collections</td>
							  <td>
							  	<select name="numHoldCollections" onchange="javascript:nSave=0;SetResumeDays()">
							  	  <option value="0">(None)</option>

								  <option value="5">ACH Payment Plan Hold - Awaiting Form</option>

								  <option value="2">Board Hearing Requested (45 days)</option>

								  <option value="1">General Hold (10 Days)</option>

								  <option value="4">Hold (one year)</option>

								  <option value="3">Owner Research (10 Days)</option>
								  
								</select><input type="hidden" name="numHoldDays" value="0,12,45,10,365,10">
							  </td>
							  <td class="formlabel">Resume Collections</td>
							  <td>
							  	
							  	<input type="text" name="dteResumeCollections" id="dteResumeCollections" size="10" maxlength="10" value="">
								
								<a href="javascript:ShowCalendar('document.frmproperty.',document.frmproperty.dteResumeCollections,getElementPosition('dteResumeCollections', 'top')+20,getElementPosition('dteResumeCollections', 'left'));"><img src="images/icon_calendar.gif" width="20" height="21" border="0" align="absbottom"></a>
								
							  </td>
                            </tr>
                            <tr> 
                              <td class="formlabel">Payment Plan</td>
							  <td colspan="3">
							    <select name="numPayPlanStatusID" onchange="javascript:nSave=0;">
							  	  <option value="0" selected="">(None)</option>
                                  <option value="1">Active</option>
								  <option value="2">In Default of Payment Plan</option>
								</select>
						
							  </td>
							</tr>
                            <tr> 
                              <td class="formlabel">Account No</td>
                              <td colspan="3"><input name="txtPropertyHOID" type="text" value="" size="20" maxlength="16">
							  Owner #&nbsp;<input name="numOwnerNo" id="numOwnerNo" type="text" value="1" size="2" maxlength="2">
							  <input name="numCheckDigit" type="hidden" value="" size="2" maxlength="1" readonly="">
		
							  </td>
                            </tr>
                            <tr> 
                              <td class="formlabel">Name</td>
                              <td colspan="3">
							  <input name="txtPropertyFName" type="text" value="" size="20" maxlength="50">
							  <input name="txtPropertyName" id="txtPropertyName" type="text" value="" size="25" maxlength="80">
							  <a href="javascript:ShowList(0,'priorownerselect.asp',getElementPosition('txtPropertyName', 'top')+20,getElementPosition('txtPropertyName', 'left'),125,600,document.frmproperty.numAssocID.value,document.frmproperty.txtPropertyHOID.value);"><img src="images/icon_lookup.gif" width="20" height="21" border="0" align="absbottom"></a>
							  </td>
                            </tr>
                            <tr> 
                              <td class="formlabel">Second Name</td>
                              <td colspan="3">
							  <input name="txtPropertyFName2" type="text" value="" size="20" maxlength="50">
							  <input name="txtPropertyName2" type="text" value="" size="25" maxlength="80">							  
							  </td>
                            </tr>
                            <tr> 
                              <td class="formlabel">Address</td>
                              <td colspan="3">
							  <input name="numStreetNo" type="text" value="" size="5" maxlength="10">
							  <input name="txtPropertyAddress1" id="txtPropertyAddress1" type="text" value="" size="40" maxlength="255">
							  <b><a href="javascript:ShowList(0,'addressselect.asp',getElementPosition('txtPropertyAddress1', 'top')+20,getElementPosition('txtPropertyAddress1', 'left'),100,400,document.frmproperty.numAssocID.value,'');"><img src="images/icon_lookup.gif" width="20" height="21" border="0" align="absbottom"></a></b></td>
                            </tr>
                            <tr> 
                              <td class="formlabel">&nbsp;</td>
                              <td colspan="3" nowrap=""><input name="txtPropertyAddress2" type="text" value="" size="40" maxlength="255">
							  &nbsp;&nbsp;
							  
							  Owner Mailing Address? 
							  <input class="input_noborder" name="numOwnerAddr" type="checkbox" checked="">
							  </td>
                            </tr>
                            <tr> 
                              <td class="formlabel">City, State Zip</td>
                              <td colspan="3"><input name="txtPropertyCity" type="text" value="" size="30" maxlength="255"> 
                                <select name="txtPropertyState" onchange="javascript:nSave=0;">
                                  <option value=" "> </option><option value="AE">AE</option><option value="AK">AK</option><option value="AL">AL</option><option value="AR">AR</option><option value="AZ">AZ</option><option value="CA">CA</option><option value="CO">CO</option><option value="CT">CT</option><option value="DC">DC</option><option value="DE">DE</option><option value="FL">FL</option><option value="GA">GA</option><option value="HI">HI</option><option value="IA">IA</option><option value="ID">ID</option><option value="IL">IL</option><option value="IN">IN</option><option value="KS">KS</option><option value="KY">KY</option><option value="LA">LA</option><option value="MA">MA</option><option value="MD">MD</option><option value="ME">ME</option><option value="MI">MI</option><option value="MN">MN</option><option value="MO">MO</option><option value="MS">MS</option><option value="MT">MT</option><option value="NC">NC</option><option value="ND">ND</option><option value="NE">NE</option><option value="NH">NH</option><option value="NJ">NJ</option><option value="NM">NM</option><option value="NV">NV</option><option value="NY">NY</option><option value="OH">OH</option><option value="OK">OK</option><option value="OR">OR</option><option value="PA">PA</option><option value="RI">RI</option><option value="SC">SC</option><option value="SD">SD</option><option value="TN">TN</option><option value="TX">TX</option><option value="UT">UT</option><option value="VA">VA</option><option value="VI">VI</option><option value="VT">VT</option><option value="WA">WA</option><option value="WI">WI</option><option value="WV">WV</option><option value="WY">WY</option> </select> <input name="zipPropertyZip" type="text" id="zipPropertyZip" value="" size="12" maxlength="50">
								  
								  </td>
                            </tr>
                            <tr> 
                              <td class="formlabel">Country</td>
                              <td><input name="txtPropertyCountry" type="text" value="" size="20" maxlength="50"></td>
                              <td>&nbsp;</td>
                              <td>&nbsp;</td>
                            </tr>
							<tr> 
                              <td class="formlabel">Unit #</td>
                              <td><input name="txtUnitNo" type="text" value="" size="20" maxlength="50"></td>
                              <td class="formlabel">Lot #</td>
                              <td><input name="txtLotNo" type="text" value="" size="20" maxlength="50"></td>
                            </tr>
							<tr> 
                              <td class="formlabel">Phase #</td>
                              <td><input name="txtPhaseNo" type="text" value="" size="20" maxlength="50"></td>
                              <td class="formlabel">Village #</td>
                              <td><input name="txtVillageNo" type="text" value="" size="20" maxlength="50"></td>
                            </tr>
							<tr> 
                              <td class="formlabel">Block #</td>
                              <td><input name="txtBlockNo" type="text" value="" size="20" maxlength="50"></td>
                              <td>&nbsp;</td>
                              <td>&nbsp;</td>
							</tr>
                            <tr> 
                              <td class="formlabel">Home Phone</td>
                              <td><input name="phnPropertyHome" type="text" value="" size="20" maxlength="50"></td>
                              <td class="formlabel">Work Phone</td>
                              <td><input name="phnPropertyWork" type="text" value="" size="20" maxlength="50"></td>
                            </tr>
                            <tr> 
                              <td class="formlabel">Mobile Phone</td>
                              <td><input name="phnPropertyMobile" type="text" value="" size="20" maxlength="50"></td>
                              <td class="formlabel"> 
                                Email 
                                 </td>
                              <td><input name="emlPropertyEmail" type="text" value="" size="30" maxlength="255"></td>
                            </tr>
                            <tr>
                              <td class="formlabel">Billing Type</td>
                              <td>
							  
								  <select name="numBillingTypeID" onchange="javascript:nSave=0;">
									<option value="0">(None)</option>
									  <option value="3">Automatic ACH</option><option value="4">Coupons</option><option value="1">eStatements</option><option value="2" selected="">Statements</option> 
									</select>
							  
							  </td>
                              <td class="formlabel">ACH Start Date</td>
                              <td>
							  
							  
							  	<input type="text" name="dteACHStart" id="dteACHStart" size="10" maxlength="10" value="">
								
								<a href="javascript:ShowCalendar('document.frmproperty.',document.frmproperty.dteACHStart,getElementPosition('dteACHStart', 'top')+20,getElementPosition('dteACHStart', 'left'));"><img src="images/icon_calendar.gif" width="20" height="21" border="0" align="absbottom"></a>
								
							  </td>
                            </tr>

							<tr>
                              <td class="formlabel">Account Type</td>
                              <td> <select name="numAccountType" onchange="javascript:nSave=0;">
                              	<option value="0" selected="">Checking</option>
 								<option value="1">Savings</option>
                                </select></td>
                              <td class="formlabel">Generate Prenote</td>
							  
                              <td><input class="input_noborder" name="numPrenote" type="checkbox"></td>
                            </tr>
                            <tr>
                              <td class="formlabel">Routing No.</td>
                              <td><input name="txtRoutingNo" type="text" value="" size="20" maxlength="9" onkeyup="doPrenote(0);"></td>
                              <td class="formlabel">Account No.</td>
                              <td><input name="txtAccountNo" type="text" value="" size="20" maxlength="50" onkeyup="doPrenote(0);"></td>
                            </tr>
							
                            
							<tr>
								<td class="formlabel">Lien Date</td>
                                <td colspan="3"><input name="txtUserDefined1" type="text" value="" size="70" maxlength="255"></td>
							</tr>
							<tr>
								<td class="formlabel">FC Hearing Date</td>
                                <td colspan="3"><input name="txtUserDefined2" type="text" value="" size="70" maxlength="255"></td>
							</tr>
							<tr>
								<td class="formlabel">Docket #</td>
                                <td colspan="3"><input name="txtUserDefined3" type="text" value="" size="70" maxlength="255"></td>
							</tr>
							<tr>
								<td class="formlabel">SP#</td>
                                <td colspan="3"><input name="txtUserDefined4" type="text" value="" size="70" maxlength="255"></td>
							</tr>
                          </tbody></table>
                       </td>
                      </tr>
                    </tbody></table>
				   
                  </td>
                </tr>
              </tbody></table>