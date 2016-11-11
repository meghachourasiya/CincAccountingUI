<table class="dxgvControl_CincAccounting" id="InvoicesGridView" style="width:100%;border-collapse:separate;">
	<tbody><tr>
		<td><table id="InvoicesGridView_DXMainTable" class="dxgvTable_CincAccounting" onclick="ASPx.GTableClick('InvoicesGridView', event);" style="width:100%;empty-cells:show;">
	<tbody><tr id="InvoicesGridView_DXHeadersRow0">
		<td class="dxgvHeader_CincAccounting" style="width:0.1%;border-top-width:0px;border-left-width:0px;cursor:default;"><img class="dxGridView_gvExpandedButton_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="" style="visibility:hidden;"></td><td id="InvoicesGridView_col0" class="dxgvHeader_CincAccounting" onmousedown="ASPx.GHeaderMouseDown('InvoicesGridView', this, event);" style="width:30px;border-top-width:0px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="CheckAllInvoices"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="CheckAllInvoices_S_D"><span class="dxKBSW"><input id="CheckAllInvoices_S" name="CheckAllInvoices" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_1497983527" type="text/javascript">
<!--
ASPx.AddDisabledItems('CheckAllInvoices',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('CheckAllInvoices');
dxo.InitGlobalVariable('CheckAllInvoices');
dxo.SetProperties({
	'imageProperties':{
	'4':['dxWeb_edtCheckBoxChecked_CincAccounting','dxWeb_edtCheckBoxUnchecked_CincAccounting'],
	'8':['dxWeb_edtCheckBoxCheckedDisabled_CincAccounting','dxWeb_edtCheckBoxUncheckedDisabled_CincAccounting']
},
	'icbFocusedStyle':['dxICBFocused_CincAccounting','']
});
dxo.SetEvents({
	'CheckedChanged':OnCheckedAllChanged
});
dxo.InitializeProperties({
	'decorationStyles':[]
});
dxo.AfterCreate();

//-->
</script></td><td id="InvoicesGridView_col4" class="dxgvHeader_CincAccounting" onmousedown="ASPx.GHeaderMouseDown('InvoicesGridView', this, event);" style="width:75px;border-top-width:0px;border-left-width:0px;"><table style="width:100%;">
			<tbody><tr>
				<td>Invoice Date</td><td style="width:1px;text-align:right;"><span class="dx-vam">&nbsp;</span><img class="dxGridView_gvHeaderSortUp_CincAccounting dx-vam" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="(Ascending)" style="margin-left:5px;"></td>
			</tr>
		</tbody></table></td><td id="InvoicesGridView_col5" class="dxgvHeader_CincAccounting" onmousedown="ASPx.GHeaderMouseDown('InvoicesGridView', this, event);" style="width:75px;border-top-width:0px;border-left-width:0px;"><table style="width:100%;">
			<tbody><tr>
				<td>Due Date</td><td style="width:1px;text-align:right;"><span class="dx-vam">&nbsp;</span></td>
			</tr>
		</tbody></table></td><td id="InvoicesGridView_col6" class="dxgvHeader_CincAccounting" onmousedown="ASPx.GHeaderMouseDown('InvoicesGridView', this, event);" style="width:110px;border-top-width:0px;border-left-width:0px;"><table style="width:100%;">
			<tbody><tr>
				<td>Invoice Number</td><td style="width:1px;text-align:right;"><span class="dx-vam">&nbsp;</span></td>
			</tr>
		</tbody></table></td><td id="InvoicesGridView_col7" class="dxgvHeader_CincAccounting" onmousedown="ASPx.GHeaderMouseDown('InvoicesGridView', this, event);" style="width:110px;border-top-width:0px;border-left-width:0px;"><table style="width:100%;">
			<tbody><tr>
				<td>Invoice Amount</td><td style="width:1px;text-align:right;"><span class="dx-vam">&nbsp;</span></td>
			</tr>
		</tbody></table></td><td id="InvoicesGridView_col8" class="dxgvHeader_CincAccounting" onmousedown="ASPx.GHeaderMouseDown('InvoicesGridView', this, event);" style="width:110px;border-top-width:0px;border-left-width:0px;"><table style="width:100%;">
			<tbody><tr>
				<td>Balance</td><td style="width:1px;text-align:right;"><span class="dx-vam">&nbsp;</span></td>
			</tr>
		</tbody></table></td><td id="InvoicesGridView_col9" class="dxgvHeader_CincAccounting" onmousedown="ASPx.GHeaderMouseDown('InvoicesGridView', this, event);" style="width:90px;border-top-width:0px;border-left-width:0px;"><table style="width:100%;">
			<tbody><tr>
				<td>Status</td><td style="width:1px;text-align:right;"><span class="dx-vam">&nbsp;</span></td>
			</tr>
		</tbody></table></td><td id="InvoicesGridView_col10" class="dxgvHeader_CincAccounting" onmousedown="ASPx.GHeaderMouseDown('InvoicesGridView', this, event);" style="width:250px;border-top-width:0px;border-left-width:0px;border-right-width:0px;"><table style="width:100%;">
			<tbody><tr>
				<td>Vendor Name</td><td style="width:1px;text-align:right;"><span class="dx-vam">&nbsp;</span></td>
			</tr>
		</tbody></table></td>
	</tr><tr id="InvoicesGridView_DXFilterRow" class="dxgvFilterRow_CincAccounting">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;">&nbsp;</td><td class="dxgv"><a id="clearFilterId" href="#" onclick="clearFilters()" style="display: none;">Clear</a></td><td class="dxgv"><table style="width:100%;">
			<tbody><tr>
				<td style="width:100%;padding-right:2px;"><script id="dxss_158016664" type="text/javascript">
<!--
(function(){var a = ({'monthDay':'MMMM dd','longDate':'dddd, MMMM dd, yyyy','yearMonth':'MMMM, yyyy'});for(var b in a) ASPx.CultureInfo[b] = a[b];})();
//-->
</script><table id="InvoicesGridView_DXFREditorcol4_LP" class="dxeLoadingPanel_CincAccounting dxlpLoadingPanel_CincAccounting" style="left:0px;top:0px;z-index:30000;display:none;">
					<tbody><tr>
						<td class="dx" style="padding-right:0px;"><img class="dxlp-loadingImage dxlp-imgPosLeft" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="" style="vertical-align:middle;"></td><td class="dx" style="padding-left:0px;"><span id="InvoicesGridView_DXFREditorcol4_TL">Loading…</span></td>
					</tr>
				</tbody></table><table class="dxeButtonEditSys dxeButtonEdit_CincAccounting" id="InvoicesGridView_DXFREditorcol4" style="width:100%;">
					<tbody><tr>
						<td class="dxic" onmousedown="return ASPx.DDMC_MD('InvoicesGridView_DXFREditorcol4', event)" style="width:100%;"><input class="dxeEditArea_CincAccounting dxeEditAreaSys" id="InvoicesGridView_DXFREditorcol4_I" name="InvoicesGridView$DXFREditorcol4" onfocus="ASPx.EGotFocus('InvoicesGridView_DXFREditorcol4')" onblur="ASPx.ELostFocus('InvoicesGridView_DXFREditorcol4')" onchange="ASPx.ETextChanged('InvoicesGridView_DXFREditorcol4')" type="text" autocomplete="off"></td><td id="InvoicesGridView_DXFREditorcol4_B-1" class="dxeButton dxeButtonEditButton_CincAccounting" onmousedown="return ASPx.DDDropDown('InvoicesGridView_DXFREditorcol4', event)" style="-webkit-user-select:none;"><img id="InvoicesGridView_DXFREditorcol4_B-1Img" class="dxEditors_edtDropDown_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="v"></td>
					</tr>
				</tbody></table><div id="InvoicesGridView_DXFREditorcol4_DDD_PW-1" class="dxpcDropDown_CincAccounting dxpclW dxpc-ddSys" style="width:0px;cursor:default;z-index:10000;display:none;visibility:hidden;">
					<div class="dxpc-mainDiv dxpc-shadow">
						<div class="dxpc-contentWrapper">
							<div class="dxpc-content" id="InvoicesGridView_DXFREditorcol4_DDD_PWC-1">
								<table style="display:none;">
									<tbody><tr>
										<td id="InvoicesGridView_DXFREditorcol4_DDD_C_EC_D" class="dxeCalendarDay_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol4_DDD_C_EC_DS" class="dxeCalendarSelected_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol4_DDD_C_EC_DA" class="dxeCalendarOtherMonth_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol4_DDD_C_EC_DW" class="dxeCalendarWeekend_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol4_DDD_C_EC_DO" class="dxeCalendarOutOfRange_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol4_DDD_C_EC_DDD" class="dxeCalendarDayDisabled_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol4_DDD_C_EC_DT" class="dxeCalendarToday_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol4_DDD_C_EC_DD" class="dxeDisabled_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol4_DDD_C_EC_FNM" class="dxeCalendarFastNavMonth_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol4_DDD_C_EC_FNMS" class="dxeCalendarFastNavMonthSelected_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol4_DDD_C_EC_FNY" class="dxeCalendarFastNavYear_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol4_DDD_C_EC_FNYS" class="dxeCalendarFastNavYearSelected_CincAccounting"></td>
									</tr>
								</tbody></table><table class="dxeCalendar_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C" style="border-color:Silver;border-width:1px;border-style:Solid;border-width:1px;">
									<tbody><tr>
										<td style="vertical-align:Top;"><table style="width:100%;border-collapse:collapse;">
											<tbody><tr>
												<td class="dxeCalendarHeader_CincAccounting" style="border-top:0;"><table style="width:100%;border-collapse:collapse;">
													<tbody><tr>
														<td id="InvoicesGridView_DXFREditorcol4_DDD_C_PYC" class="dxe" onclick="ASPx.CalShiftMonth('InvoicesGridView_DXFREditorcol4_DDD_C', -12);"><img id="InvoicesGridView_DXFREditorcol4_DDD_C_PYCImg" class="dxEditors_edtCalendarPrevYear_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="<<"></td><td class="dxeCHS"></td><td id="InvoicesGridView_DXFREditorcol4_DDD_C_PMC" class="dxe" onclick="ASPx.CalShiftMonth('InvoicesGridView_DXFREditorcol4_DDD_C', -1);"><img id="InvoicesGridView_DXFREditorcol4_DDD_C_PMCImg" class="dxEditors_edtCalendarPrevMonth_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="<"></td><td id="InvoicesGridView_DXFREditorcol4_DDD_C_TC" class="dxe" style="width:100%;cursor:default;"><span id="InvoicesGridView_DXFREditorcol4_DDD_C_T" onclick="ASPx.CalTitleClick('InvoicesGridView_DXFREditorcol4_DDD_C', 0, 0)" style="cursor:pointer;">November, 2016</span></td><td id="InvoicesGridView_DXFREditorcol4_DDD_C_NMC" class="dxe" onclick="ASPx.CalShiftMonth('InvoicesGridView_DXFREditorcol4_DDD_C', 1);"><img id="InvoicesGridView_DXFREditorcol4_DDD_C_NMCImg" class="dxEditors_edtCalendarNextMonth_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt=">"></td><td class="dxeCHS"></td><td id="InvoicesGridView_DXFREditorcol4_DDD_C_NYC" class="dxe" onclick="ASPx.CalShiftMonth('InvoicesGridView_DXFREditorcol4_DDD_C', 12);"><img id="InvoicesGridView_DXFREditorcol4_DDD_C_NYCImg" class="dxEditors_edtCalendarNextYear_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt=">>"></td>
													</tr>
												</tbody></table></td>
											</tr><tr>
												<td id="InvoicesGridView_DXFREditorcol4_DDD_C_mc" class="dxMonthGridWithWeekNumbers" style="padding-left:0px;padding-right:0px;padding-top:0px;padding-bottom:0px;-webkit-user-select:none;"><table id="InvoicesGridView_DXFREditorcol4_DDD_C_mt" style="width:100%;border-collapse:separate;">
													<tbody><tr class="dx-ac">
														<td id="InvoicesGridView_DXFREditorcol4_DDD_C_AUX_0_0_0"></td><td class="dxeCalendarDayHeader_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_AUX_0_0_1">Sun</td><td class="dxeCalendarDayHeader_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_AUX_0_0_2">Mon</td><td class="dxeCalendarDayHeader_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_AUX_0_0_3">Tue</td><td class="dxeCalendarDayHeader_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_AUX_0_0_4">Wed</td><td class="dxeCalendarDayHeader_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_AUX_0_0_5">Thu</td><td class="dxeCalendarDayHeader_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_AUX_0_0_6">Fri</td><td class="dxeCalendarDayHeader_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_AUX_0_0_7">Sat</td>
													</tr><tr>
														<td class="dxeCalendarWeekNumber_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_AUX_0_0_8">44</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">30</td><td class="dxeCalendarDay_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">31</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">1</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">2</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">3</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">4</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">5</td>
													</tr><tr>
														<td class="dxeCalendarWeekNumber_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_AUX_0_0_9">45</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">6</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">7</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">8</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">9</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">10</td><td class="dxeCalendarDay_CincAccounting dxeCalendarToday_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">11</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">12</td>
													</tr><tr>
														<td class="dxeCalendarWeekNumber_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_AUX_0_0_10">46</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">13</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">14</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">15</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">16</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">17</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">18</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">19</td>
													</tr><tr>
														<td class="dxeCalendarWeekNumber_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_AUX_0_0_11">47</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">20</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">21</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">22</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">23</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">24</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">25</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">26</td>
													</tr><tr>
														<td class="dxeCalendarWeekNumber_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_AUX_0_0_12">48</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">27</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">28</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">29</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">30</td><td class="dxeCalendarDay_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">1</td><td class="dxeCalendarDay_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">2</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">3</td>
													</tr><tr>
														<td class="dxeCalendarWeekNumber_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_AUX_0_0_13">49</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">4</td><td class="dxeCalendarDay_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">5</td><td class="dxeCalendarDay_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">6</td><td class="dxeCalendarDay_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">7</td><td class="dxeCalendarDay_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">8</td><td class="dxeCalendarDay_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">9</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">10</td>
													</tr>
												</tbody></table></td>
											</tr>
										</tbody></table></td>
									</tr><tr>
										<td class="dxeCalendarFooter_CincAccounting dx-ac"><table style="border-collapse:collapse;">
											<tbody><tr>
												<td id="InvoicesGridView_DXFREditorcol4_DDD_C_BT" class="dxeCalendarButton_CincAccounting" onclick="ASPx.CalTodayClick('InvoicesGridView_DXFREditorcol4_DDD_C');">Today</td><td class="dxeCFS"></td><td id="InvoicesGridView_DXFREditorcol4_DDD_C_BC" class="dxeCalendarButton_CincAccounting" onclick="ASPx.CalClearClick('InvoicesGridView_DXFREditorcol4_DDD_C');">Clear</td>
											</tr>
										</tbody></table></td>
									</tr>
								</tbody></table><div id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_PW-1" class="dxpcDropDown_CincAccounting dxpclW dxpc-ddSys" style="width:0px;cursor:default;z-index:10000;display:none;visibility:hidden;">
									<div class="dxpc-mainDiv dxpc-shadow">
										<div class="dxpc-contentWrapper">
											<div class="dxpc-content" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_PWC-1">
												<div class="dxeCalendarFastNav_CincAccounting">
													<div class="dxeCalendarFastNavMonthArea_CincAccounting">
														<table id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_m" style="width:100%;border-collapse:separate;">
															<tbody><tr>
																<td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_M0">Jan</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_M1">Feb</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_M2">Mar</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_M3">Apr</td>
															</tr><tr>
																<td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_M4">May</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_M5">Jun</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_M6">Jul</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_M7">Aug</td>
															</tr><tr>
																<td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_M8">Sep</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_M9">Oct</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_M10">Nov</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_M11">Dec</td>
															</tr>
														</tbody></table>
													</div><div class="dxeCalendarFastNavYearArea_CincAccounting">
														<table id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_y" style="width:100%;border-collapse:separate;">
															<tbody><tr>
																<td onclick="ASPx.CalFNYShuffle('InvoicesGridView_DXFREditorcol4_DDD_C', -10)" rowspan="2" style="cursor:pointer;"><img class="dxEditors_edtCalendarFNPrevYear_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="<"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_Y0"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_Y1"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_Y2"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_Y3"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_Y4"></td><td onclick="ASPx.CalFNYShuffle('InvoicesGridView_DXFREditorcol4_DDD_C', 10)" rowspan="2" style="cursor:pointer;"><img class="dxEditors_edtCalendarFNNextYear_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt=">"></td>
															</tr><tr>
																<td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_Y5"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_Y6"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_Y7"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_Y8"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_Y9"></td>
															</tr>
														</tbody></table>
													</div>
												</div><div class="dxeCalendarFastNavFooter_CincAccounting dx-ac">
													<table>
														<tbody><tr>
															<td id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_BO" class="dxeCalendarButton_CincAccounting" onclick="ASPx.CalFNBClick('InvoicesGridView_DXFREditorcol4_DDD_C', 'ok')">OK</td><td class="dxeCFNFS"></td><td id="InvoicesGridView_DXFREditorcol4_DDD_C_FNP_BC" class="dxeCalendarButton_CincAccounting" onclick="ASPx.CalFNBClick('InvoicesGridView_DXFREditorcol4_DDD_C', 'cancel')">Cancel</td>
														</tr>
													</tbody></table>
												</div>
											</div>
										</div>
									</div>
								</div><script id="dxss_1260921934" type="text/javascript">
<!--
ASPx.AddHoverItems('InvoicesGridView_DXFREditorcol4_DDD_C_FNP',[[['dxpc-closeBtnHover'],[''],['HCB-1']]]);

var dxo = new ASPxClientPopupControl('InvoicesGridView_DXFREditorcol4_DDD_C_FNP');
dxo.InitGlobalVariable('InvoicesGridView_DXFREditorcol4_DDD_C_FNP');
dxo.SetProperties({'uniqueID':'InvoicesGridView$DXFREditorcol4$DDD$C$FNP','adjustInnerControlsSizeOnShow':false,'popupAnimationType':'fade'});
dxo.AfterCreate();

//-->
</script><script id="dxss_21255792" type="text/javascript">
<!--
ASPx.AddHoverItems('InvoicesGridView_DXFREditorcol4_DDD_C',[[['dxeCalendarButtonHover_CincAccounting'],[''],['BT','BC','BO','BCN','FNP_BO','FNP_BC']],[['dxeCalendarFastNavMonthHover_CincAccounting'],[''],['FNP_M0','FNP_M1','FNP_M2','FNP_M3','FNP_M4','FNP_M5','FNP_M6','FNP_M7','FNP_M8','FNP_M9','FNP_M10','FNP_M11']],[['dxeCalendarFastNavYearHover_CincAccounting'],[''],['FNP_Y0','FNP_Y1','FNP_Y2','FNP_Y3','FNP_Y4','FNP_Y5','FNP_Y6','FNP_Y7','FNP_Y8','FNP_Y9']]]);
ASPx.AddPressedItems('InvoicesGridView_DXFREditorcol4_DDD_C',[[['dxeCalendarButtonPressed_CincAccounting'],[''],['BT','BC','BO','BCN','FNP_BO','FNP_BC']]]);
ASPx.AddDisabledItems('InvoicesGridView_DXFREditorcol4_DDD_C',[[['dxeDisabled_CincAccounting'],[''],['']],[['dxeDisabled_CincAccounting dxeButtonDisabled_CincAccounting'],[''],['BT','BC','BO','BCN','FNP_BO','FNP_BC']],[[''],[''],['PYC','PMC','NMC','NYC'],,[[{'spriteCssClass':'dxEditors_edtCalendarPrevYearDisabled_CincAccounting'}],[{'spriteCssClass':'dxEditors_edtCalendarPrevMonthDisabled_CincAccounting'}],[{'spriteCssClass':'dxEditors_edtCalendarNextMonthDisabled_CincAccounting'}],[{'spriteCssClass':'dxEditors_edtCalendarNextYearDisabled_CincAccounting'}]],['Img']]]);

var dxo = new ASPxClientCalendar('InvoicesGridView_DXFREditorcol4_DDD_C');
dxo.InitGlobalVariable('InvoicesGridView_DXFREditorcol4_DDD_C');
dxo.SetProperties({
	'encodeHtml':false,
	'uniqueID':'InvoicesGridView$DXFREditorcol4$DDD$C',
	'serverCurrentDate':new Date(2016,10,11,0,0,0,0),
	'visibleDate':new Date(2016,10,11,0,0,0,0),
	'isDateEditCalendar':true
});
dxo.InitializeProperties({
	'decorationStyles':[
		{'key':'F','className':'dxeFocused_CincAccounting','cssText':''}
	]
});
dxo.AfterCreate();

//-->
</script>
							</div>
						</div>
					</div>
				</div><script id="dxss_1157545875" type="text/javascript">
<!--
ASPx.AddHoverItems('InvoicesGridView_DXFREditorcol4_DDD',[[['dxpc-closeBtnHover'],[''],['HCB-1']]]);

var dxo = new ASPxClientPopupControl('InvoicesGridView_DXFREditorcol4_DDD');
dxo.InitGlobalVariable('InvoicesGridView_DXFREditorcol4_DDD');
dxo.SetProperties({
	'uniqueID':'InvoicesGridView$DXFREditorcol4$DDD',
	'adjustInnerControlsSizeOnShow':false,
	'popupAnimationType':'slide',
	'closeAction':'CloseButton',
	'popupHorizontalAlign':'LeftSides',
	'popupVerticalAlign':'Below'
});
dxo.SetEvents({
	'Shown':function (s, e) { ASPx.DDBPCShown('InvoicesGridView_DXFREditorcol4', e); }
});
dxo.AfterCreate();

//-->
</script><script id="dxss_617084050" type="text/javascript">
<!--
ASPx.AddHoverItems('InvoicesGridView_DXFREditorcol4',[[['dxeButtonEditButtonHover_CincAccounting'],[''],['B-1']]]);
ASPx.RemoveHoverItems('InvoicesGridView_DXFREditorcol4',[[['B-100']]]);
ASPx.AddPressedItems('InvoicesGridView_DXFREditorcol4',[[['dxeButtonEditButtonPressed_CincAccounting'],[''],['B-1']]]);
ASPx.RemovePressedItems('InvoicesGridView_DXFREditorcol4',[[['B-100']]]);
ASPx.AddDisabledItems('InvoicesGridView_DXFREditorcol4',[[['dxeDisabled_CincAccounting'],[''],['','I']],[['dxeDisabled_CincAccounting dxeButtonDisabled_CincAccounting'],[''],['B-1'],,[[{'spriteCssClass':'dxEditors_edtDropDownDisabled_CincAccounting'}]],['Img']]]);
ASPx.RemoveDisabledItems('InvoicesGridView_DXFREditorcol4',[[['B-100'],]]);

var dxo = new ASPxClientDateEdit('InvoicesGridView_DXFREditorcol4');
dxo.InitGlobalVariable('InvoicesGridView_DXFREditorcol4');
dxo.SetProperties({
	'encodeHtml':false,
	'callBack':function(arg) { ; },
	'uniqueID':'InvoicesGridView$DXFREditorcol4',
	'stateObject':{'rawValue':'N'},
	'displayFormat':'{0:MM/dd/yyyy}',
	'autoCompleteAttribute':{'name':'autocomplete','value':'off'},
	'outOfRangeWarningClassName':'dxeOutOfRWarn_CincAccounting dxeOutOfRWarnRight_CincAccounting',
	'outOfRangeWarningMessages':['The date must be in the range {0}...{1}', 'The date must be greater than or equal to {0}', 'The date must be less than or equal to {0}'],
	'clearButtonDisplayMode':'Never',
	'forceShowClearButtonAlways':true,
	'dateFormatter':ASPx.DateFormatter.Create('MM/dd/yyyy')
});
dxo.SetEvents({
	'ValueChanged':function(s, event) { ASPx.GVFilterChanged('InvoicesGridView',s); },
	'KeyDown':function(s, event) { ASPx.GVFilterSpecKeyPress('InvoicesGridView', s, event); }
});
dxo.InitializeProperties({
	'decorationStyles':[
		{'key':'F','className':'dxeFocused_CincAccounting','cssText':''}
	]
});
dxo.AfterCreate();

//-->
</script></td><td><img class="dxGridView_gvFilterRowButton_CincAccounting" onclick="ASPx.GVFilterRowMenu('InvoicesGridView',4,this)" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="Open filter row popup menu" style="cursor:pointer;"></td>
			</tr>
		</tbody></table></td><td class="dxgv"><table style="width:100%;">
			<tbody><tr>
				<td style="width:100%;padding-right:2px;"><table id="InvoicesGridView_DXFREditorcol5_LP" class="dxeLoadingPanel_CincAccounting dxlpLoadingPanel_CincAccounting" style="left:0px;top:0px;z-index:30000;display:none;">
					<tbody><tr>
						<td class="dx" style="padding-right:0px;"><img class="dxlp-loadingImage dxlp-imgPosLeft" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="" style="vertical-align:middle;"></td><td class="dx" style="padding-left:0px;"><span id="InvoicesGridView_DXFREditorcol5_TL">Loading…</span></td>
					</tr>
				</tbody></table><table class="dxeButtonEditSys dxeButtonEdit_CincAccounting" id="InvoicesGridView_DXFREditorcol5" style="width:100%;">
					<tbody><tr>
						<td class="dxic" onmousedown="return ASPx.DDMC_MD('InvoicesGridView_DXFREditorcol5', event)" style="width:100%;"><input class="dxeEditArea_CincAccounting dxeEditAreaSys" id="InvoicesGridView_DXFREditorcol5_I" name="InvoicesGridView$DXFREditorcol5" onfocus="ASPx.EGotFocus('InvoicesGridView_DXFREditorcol5')" onblur="ASPx.ELostFocus('InvoicesGridView_DXFREditorcol5')" onchange="ASPx.ETextChanged('InvoicesGridView_DXFREditorcol5')" type="text" autocomplete="off"></td><td id="InvoicesGridView_DXFREditorcol5_B-1" class="dxeButton dxeButtonEditButton_CincAccounting" onmousedown="return ASPx.DDDropDown('InvoicesGridView_DXFREditorcol5', event)" style="-webkit-user-select:none;"><img id="InvoicesGridView_DXFREditorcol5_B-1Img" class="dxEditors_edtDropDown_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="v"></td>
					</tr>
				</tbody></table><div id="InvoicesGridView_DXFREditorcol5_DDD_PW-1" class="dxpcDropDown_CincAccounting dxpclW dxpc-ddSys" style="width:0px;cursor:default;z-index:10000;display:none;visibility:hidden;">
					<div class="dxpc-mainDiv dxpc-shadow">
						<div class="dxpc-contentWrapper">
							<div class="dxpc-content" id="InvoicesGridView_DXFREditorcol5_DDD_PWC-1">
								<table style="display:none;">
									<tbody><tr>
										<td id="InvoicesGridView_DXFREditorcol5_DDD_C_EC_D" class="dxeCalendarDay_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol5_DDD_C_EC_DS" class="dxeCalendarSelected_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol5_DDD_C_EC_DA" class="dxeCalendarOtherMonth_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol5_DDD_C_EC_DW" class="dxeCalendarWeekend_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol5_DDD_C_EC_DO" class="dxeCalendarOutOfRange_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol5_DDD_C_EC_DDD" class="dxeCalendarDayDisabled_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol5_DDD_C_EC_DT" class="dxeCalendarToday_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol5_DDD_C_EC_DD" class="dxeDisabled_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol5_DDD_C_EC_FNM" class="dxeCalendarFastNavMonth_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol5_DDD_C_EC_FNMS" class="dxeCalendarFastNavMonthSelected_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol5_DDD_C_EC_FNY" class="dxeCalendarFastNavYear_CincAccounting"></td><td id="InvoicesGridView_DXFREditorcol5_DDD_C_EC_FNYS" class="dxeCalendarFastNavYearSelected_CincAccounting"></td>
									</tr>
								</tbody></table><table class="dxeCalendar_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C" style="border-color:Silver;border-width:1px;border-style:Solid;border-width:1px;">
									<tbody><tr>
										<td style="vertical-align:Top;"><table style="width:100%;border-collapse:collapse;">
											<tbody><tr>
												<td class="dxeCalendarHeader_CincAccounting" style="border-top:0;"><table style="width:100%;border-collapse:collapse;">
													<tbody><tr>
														<td id="InvoicesGridView_DXFREditorcol5_DDD_C_PYC" class="dxe" onclick="ASPx.CalShiftMonth('InvoicesGridView_DXFREditorcol5_DDD_C', -12);"><img id="InvoicesGridView_DXFREditorcol5_DDD_C_PYCImg" class="dxEditors_edtCalendarPrevYear_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="<<"></td><td class="dxeCHS"></td><td id="InvoicesGridView_DXFREditorcol5_DDD_C_PMC" class="dxe" onclick="ASPx.CalShiftMonth('InvoicesGridView_DXFREditorcol5_DDD_C', -1);"><img id="InvoicesGridView_DXFREditorcol5_DDD_C_PMCImg" class="dxEditors_edtCalendarPrevMonth_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="<"></td><td id="InvoicesGridView_DXFREditorcol5_DDD_C_TC" class="dxe" style="width:100%;cursor:default;"><span id="InvoicesGridView_DXFREditorcol5_DDD_C_T" onclick="ASPx.CalTitleClick('InvoicesGridView_DXFREditorcol5_DDD_C', 0, 0)" style="cursor:pointer;">November, 2016</span></td><td id="InvoicesGridView_DXFREditorcol5_DDD_C_NMC" class="dxe" onclick="ASPx.CalShiftMonth('InvoicesGridView_DXFREditorcol5_DDD_C', 1);"><img id="InvoicesGridView_DXFREditorcol5_DDD_C_NMCImg" class="dxEditors_edtCalendarNextMonth_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt=">"></td><td class="dxeCHS"></td><td id="InvoicesGridView_DXFREditorcol5_DDD_C_NYC" class="dxe" onclick="ASPx.CalShiftMonth('InvoicesGridView_DXFREditorcol5_DDD_C', 12);"><img id="InvoicesGridView_DXFREditorcol5_DDD_C_NYCImg" class="dxEditors_edtCalendarNextYear_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt=">>"></td>
													</tr>
												</tbody></table></td>
											</tr><tr>
												<td id="InvoicesGridView_DXFREditorcol5_DDD_C_mc" class="dxMonthGridWithWeekNumbers" style="padding-left:0px;padding-right:0px;padding-top:0px;padding-bottom:0px;-webkit-user-select:none;"><table id="InvoicesGridView_DXFREditorcol5_DDD_C_mt" style="width:100%;border-collapse:separate;">
													<tbody><tr class="dx-ac">
														<td id="InvoicesGridView_DXFREditorcol5_DDD_C_AUX_0_0_0"></td><td class="dxeCalendarDayHeader_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_AUX_0_0_1">Sun</td><td class="dxeCalendarDayHeader_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_AUX_0_0_2">Mon</td><td class="dxeCalendarDayHeader_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_AUX_0_0_3">Tue</td><td class="dxeCalendarDayHeader_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_AUX_0_0_4">Wed</td><td class="dxeCalendarDayHeader_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_AUX_0_0_5">Thu</td><td class="dxeCalendarDayHeader_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_AUX_0_0_6">Fri</td><td class="dxeCalendarDayHeader_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_AUX_0_0_7">Sat</td>
													</tr><tr>
														<td class="dxeCalendarWeekNumber_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_AUX_0_0_8">44</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">30</td><td class="dxeCalendarDay_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">31</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">1</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">2</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">3</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">4</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">5</td>
													</tr><tr>
														<td class="dxeCalendarWeekNumber_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_AUX_0_0_9">45</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">6</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">7</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">8</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">9</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">10</td><td class="dxeCalendarDay_CincAccounting dxeCalendarToday_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">11</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">12</td>
													</tr><tr>
														<td class="dxeCalendarWeekNumber_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_AUX_0_0_10">46</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">13</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">14</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">15</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">16</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">17</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">18</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">19</td>
													</tr><tr>
														<td class="dxeCalendarWeekNumber_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_AUX_0_0_11">47</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">20</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">21</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">22</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">23</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">24</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">25</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">26</td>
													</tr><tr>
														<td class="dxeCalendarWeekNumber_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_AUX_0_0_12">48</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">27</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">28</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">29</td><td class="dxeCalendarDay_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">30</td><td class="dxeCalendarDay_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">1</td><td class="dxeCalendarDay_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">2</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">3</td>
													</tr><tr>
														<td class="dxeCalendarWeekNumber_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_AUX_0_0_13">49</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">4</td><td class="dxeCalendarDay_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">5</td><td class="dxeCalendarDay_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">6</td><td class="dxeCalendarDay_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">7</td><td class="dxeCalendarDay_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">8</td><td class="dxeCalendarDay_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">9</td><td class="dxeCalendarDay_CincAccounting dxeCalendarWeekend_CincAccounting dxeCalendarOtherMonth_CincAccounting" savedcursor="[object Object]" style="cursor: pointer;">10</td>
													</tr>
												</tbody></table></td>
											</tr>
										</tbody></table></td>
									</tr><tr>
										<td class="dxeCalendarFooter_CincAccounting dx-ac"><table style="border-collapse:collapse;">
											<tbody><tr>
												<td id="InvoicesGridView_DXFREditorcol5_DDD_C_BT" class="dxeCalendarButton_CincAccounting" onclick="ASPx.CalTodayClick('InvoicesGridView_DXFREditorcol5_DDD_C');">Today</td><td class="dxeCFS"></td><td id="InvoicesGridView_DXFREditorcol5_DDD_C_BC" class="dxeCalendarButton_CincAccounting" onclick="ASPx.CalClearClick('InvoicesGridView_DXFREditorcol5_DDD_C');">Clear</td>
											</tr>
										</tbody></table></td>
									</tr>
								</tbody></table><div id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_PW-1" class="dxpcDropDown_CincAccounting dxpclW dxpc-ddSys" style="width:0px;cursor:default;z-index:10000;display:none;visibility:hidden;">
									<div class="dxpc-mainDiv dxpc-shadow">
										<div class="dxpc-contentWrapper">
											<div class="dxpc-content" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_PWC-1">
												<div class="dxeCalendarFastNav_CincAccounting">
													<div class="dxeCalendarFastNavMonthArea_CincAccounting">
														<table id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_m" style="width:100%;border-collapse:separate;">
															<tbody><tr>
																<td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_M0">Jan</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_M1">Feb</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_M2">Mar</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_M3">Apr</td>
															</tr><tr>
																<td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_M4">May</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_M5">Jun</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_M6">Jul</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_M7">Aug</td>
															</tr><tr>
																<td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_M8">Sep</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_M9">Oct</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_M10">Nov</td><td class="dxeCalendarFastNavMonth_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_M11">Dec</td>
															</tr>
														</tbody></table>
													</div><div class="dxeCalendarFastNavYearArea_CincAccounting">
														<table id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_y" style="width:100%;border-collapse:separate;">
															<tbody><tr>
																<td onclick="ASPx.CalFNYShuffle('InvoicesGridView_DXFREditorcol5_DDD_C', -10)" rowspan="2" style="cursor:pointer;"><img class="dxEditors_edtCalendarFNPrevYear_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="<"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_Y0"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_Y1"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_Y2"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_Y3"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_Y4"></td><td onclick="ASPx.CalFNYShuffle('InvoicesGridView_DXFREditorcol5_DDD_C', 10)" rowspan="2" style="cursor:pointer;"><img class="dxEditors_edtCalendarFNNextYear_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt=">"></td>
															</tr><tr>
																<td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_Y5"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_Y6"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_Y7"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_Y8"></td><td class="dxeCalendarFastNavYear_CincAccounting" id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_Y9"></td>
															</tr>
														</tbody></table>
													</div>
												</div><div class="dxeCalendarFastNavFooter_CincAccounting dx-ac">
													<table>
														<tbody><tr>
															<td id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_BO" class="dxeCalendarButton_CincAccounting" onclick="ASPx.CalFNBClick('InvoicesGridView_DXFREditorcol5_DDD_C', 'ok')">OK</td><td class="dxeCFNFS"></td><td id="InvoicesGridView_DXFREditorcol5_DDD_C_FNP_BC" class="dxeCalendarButton_CincAccounting" onclick="ASPx.CalFNBClick('InvoicesGridView_DXFREditorcol5_DDD_C', 'cancel')">Cancel</td>
														</tr>
													</tbody></table>
												</div>
											</div>
										</div>
									</div>
								</div><script id="dxss_641829559" type="text/javascript">
<!--
ASPx.AddHoverItems('InvoicesGridView_DXFREditorcol5_DDD_C_FNP',[[['dxpc-closeBtnHover'],[''],['HCB-1']]]);

var dxo = new ASPxClientPopupControl('InvoicesGridView_DXFREditorcol5_DDD_C_FNP');
dxo.InitGlobalVariable('InvoicesGridView_DXFREditorcol5_DDD_C_FNP');
dxo.SetProperties({'uniqueID':'InvoicesGridView$DXFREditorcol5$DDD$C$FNP','adjustInnerControlsSizeOnShow':false,'popupAnimationType':'fade'});
dxo.AfterCreate();

//-->
</script><script id="dxss_945163799" type="text/javascript">
<!--
ASPx.AddHoverItems('InvoicesGridView_DXFREditorcol5_DDD_C',[[['dxeCalendarButtonHover_CincAccounting'],[''],['BT','BC','BO','BCN','FNP_BO','FNP_BC']],[['dxeCalendarFastNavMonthHover_CincAccounting'],[''],['FNP_M0','FNP_M1','FNP_M2','FNP_M3','FNP_M4','FNP_M5','FNP_M6','FNP_M7','FNP_M8','FNP_M9','FNP_M10','FNP_M11']],[['dxeCalendarFastNavYearHover_CincAccounting'],[''],['FNP_Y0','FNP_Y1','FNP_Y2','FNP_Y3','FNP_Y4','FNP_Y5','FNP_Y6','FNP_Y7','FNP_Y8','FNP_Y9']]]);
ASPx.AddPressedItems('InvoicesGridView_DXFREditorcol5_DDD_C',[[['dxeCalendarButtonPressed_CincAccounting'],[''],['BT','BC','BO','BCN','FNP_BO','FNP_BC']]]);
ASPx.AddDisabledItems('InvoicesGridView_DXFREditorcol5_DDD_C',[[['dxeDisabled_CincAccounting'],[''],['']],[['dxeDisabled_CincAccounting dxeButtonDisabled_CincAccounting'],[''],['BT','BC','BO','BCN','FNP_BO','FNP_BC']],[[''],[''],['PYC','PMC','NMC','NYC'],,[[{'spriteCssClass':'dxEditors_edtCalendarPrevYearDisabled_CincAccounting'}],[{'spriteCssClass':'dxEditors_edtCalendarPrevMonthDisabled_CincAccounting'}],[{'spriteCssClass':'dxEditors_edtCalendarNextMonthDisabled_CincAccounting'}],[{'spriteCssClass':'dxEditors_edtCalendarNextYearDisabled_CincAccounting'}]],['Img']]]);

var dxo = new ASPxClientCalendar('InvoicesGridView_DXFREditorcol5_DDD_C');
dxo.InitGlobalVariable('InvoicesGridView_DXFREditorcol5_DDD_C');
dxo.SetProperties({
	'encodeHtml':false,
	'uniqueID':'InvoicesGridView$DXFREditorcol5$DDD$C',
	'serverCurrentDate':new Date(2016,10,11,0,0,0,0),
	'visibleDate':new Date(2016,10,11,0,0,0,0),
	'isDateEditCalendar':true
});
dxo.InitializeProperties({
	'decorationStyles':[
		{'key':'F','className':'dxeFocused_CincAccounting','cssText':''}
	]
});
dxo.AfterCreate();

//-->
</script>
							</div>
						</div>
					</div>
				</div><script id="dxss_816455588" type="text/javascript">
<!--
ASPx.AddHoverItems('InvoicesGridView_DXFREditorcol5_DDD',[[['dxpc-closeBtnHover'],[''],['HCB-1']]]);

var dxo = new ASPxClientPopupControl('InvoicesGridView_DXFREditorcol5_DDD');
dxo.InitGlobalVariable('InvoicesGridView_DXFREditorcol5_DDD');
dxo.SetProperties({
	'uniqueID':'InvoicesGridView$DXFREditorcol5$DDD',
	'adjustInnerControlsSizeOnShow':false,
	'popupAnimationType':'slide',
	'closeAction':'CloseButton',
	'popupHorizontalAlign':'LeftSides',
	'popupVerticalAlign':'Below'
});
dxo.SetEvents({
	'Shown':function (s, e) { ASPx.DDBPCShown('InvoicesGridView_DXFREditorcol5', e); }
});
dxo.AfterCreate();

//-->
</script><script id="dxss_436851374" type="text/javascript">
<!--
ASPx.AddHoverItems('InvoicesGridView_DXFREditorcol5',[[['dxeButtonEditButtonHover_CincAccounting'],[''],['B-1']]]);
ASPx.RemoveHoverItems('InvoicesGridView_DXFREditorcol5',[[['B-100']]]);
ASPx.AddPressedItems('InvoicesGridView_DXFREditorcol5',[[['dxeButtonEditButtonPressed_CincAccounting'],[''],['B-1']]]);
ASPx.RemovePressedItems('InvoicesGridView_DXFREditorcol5',[[['B-100']]]);
ASPx.AddDisabledItems('InvoicesGridView_DXFREditorcol5',[[['dxeDisabled_CincAccounting'],[''],['','I']],[['dxeDisabled_CincAccounting dxeButtonDisabled_CincAccounting'],[''],['B-1'],,[[{'spriteCssClass':'dxEditors_edtDropDownDisabled_CincAccounting'}]],['Img']]]);
ASPx.RemoveDisabledItems('InvoicesGridView_DXFREditorcol5',[[['B-100'],]]);

var dxo = new ASPxClientDateEdit('InvoicesGridView_DXFREditorcol5');
dxo.InitGlobalVariable('InvoicesGridView_DXFREditorcol5');
dxo.SetProperties({
	'encodeHtml':false,
	'callBack':function(arg) { ; },
	'uniqueID':'InvoicesGridView$DXFREditorcol5',
	'stateObject':{'rawValue':'N'},
	'displayFormat':'{0:MM/dd/yyyy}',
	'autoCompleteAttribute':{'name':'autocomplete','value':'off'},
	'outOfRangeWarningClassName':'dxeOutOfRWarn_CincAccounting dxeOutOfRWarnRight_CincAccounting',
	'outOfRangeWarningMessages':['The date must be in the range {0}...{1}', 'The date must be greater than or equal to {0}', 'The date must be less than or equal to {0}'],
	'clearButtonDisplayMode':'Never',
	'forceShowClearButtonAlways':true,
	'dateFormatter':ASPx.DateFormatter.Create('MM/dd/yyyy')
});
dxo.SetEvents({
	'ValueChanged':function(s, event) { ASPx.GVFilterChanged('InvoicesGridView',s); },
	'KeyDown':function(s, event) { ASPx.GVFilterSpecKeyPress('InvoicesGridView', s, event); }
});
dxo.InitializeProperties({
	'decorationStyles':[
		{'key':'F','className':'dxeFocused_CincAccounting','cssText':''}
	]
});
dxo.AfterCreate();

//-->
</script></td><td><img class="dxGridView_gvFilterRowButton_CincAccounting" onclick="ASPx.GVFilterRowMenu('InvoicesGridView',5,this)" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="Open filter row popup menu" style="cursor:pointer;"></td>
			</tr>
		</tbody></table></td><td class="dxgv"><table style="width:100%;">
			<tbody><tr>
				<td style="width:100%;padding-right:2px;"><table class="dxeTextBoxSys dxeTextBox_CincAccounting dxeTextBoxDefaultWidthSys" id="InvoicesGridView_DXFREditorcol6" style="width:100%;">
					<tbody><tr>
						<td class="dxic" style="width:100%;"><input class="dxeEditArea_CincAccounting dxeEditAreaSys" id="InvoicesGridView_DXFREditorcol6_I" name="InvoicesGridView$DXFREditorcol6" onfocus="ASPx.EGotFocus('InvoicesGridView_DXFREditorcol6')" onblur="ASPx.ELostFocus('InvoicesGridView_DXFREditorcol6')" onchange="ASPx.EValueChanged('InvoicesGridView_DXFREditorcol6')" type="text"></td>
					</tr>
				</tbody></table><script id="dxss_1528514166" type="text/javascript">
<!--
ASPx.AddDisabledItems('InvoicesGridView_DXFREditorcol6',[[['dxeDisabled_CincAccounting'],[''],['','I']]]);

var dxo = new ASPxClientTextBox('InvoicesGridView_DXFREditorcol6');
dxo.InitGlobalVariable('InvoicesGridView_DXFREditorcol6');
dxo.SetProperties({'uniqueID':'InvoicesGridView$DXFREditorcol6'});
dxo.SetEvents({
	'ValueChanged':function(s, event) { ASPx.GVFilterChanged('InvoicesGridView',s); },
	'KeyDown':function(s, event) { ASPx.GVFilterKeyPress('InvoicesGridView',s,event); }
});
dxo.InitializeProperties({
	'decorationStyles':[
		{'key':'F','className':'dxeFocused_CincAccounting','cssText':''}
	]
});
dxo.AfterCreate();

//-->
</script></td><td><img class="dxGridView_gvFilterRowButton_CincAccounting" onclick="ASPx.GVFilterRowMenu('InvoicesGridView',6,this)" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="Open filter row popup menu" style="cursor:pointer;"></td>
			</tr>
		</tbody></table></td><td class="dxgv" style="text-align:Right;"><table style="width:100%;">
			<tbody><tr>
				<td style="width:100%;padding-right:2px;"><table class="dxeTextBoxSys dxeTextBox_CincAccounting dxeTextBoxDefaultWidthSys" id="InvoicesGridView_DXFREditorcol7" style="width:100%;">
					<tbody><tr>
						<td class="dxic" style="width:100%;"><input class="dxeEditArea_CincAccounting dxeEditAreaSys" id="InvoicesGridView_DXFREditorcol7_I" name="InvoicesGridView$DXFREditorcol7" onfocus="ASPx.EGotFocus('InvoicesGridView_DXFREditorcol7')" onblur="ASPx.ELostFocus('InvoicesGridView_DXFREditorcol7')" onchange="ASPx.EValueChanged('InvoicesGridView_DXFREditorcol7')" type="text"></td>
					</tr>
				</tbody></table><script id="dxss_2138058286" type="text/javascript">
<!--
ASPx.AddDisabledItems('InvoicesGridView_DXFREditorcol7',[[['dxeDisabled_CincAccounting'],[''],['','I']]]);

var dxo = new ASPxClientTextBox('InvoicesGridView_DXFREditorcol7');
dxo.InitGlobalVariable('InvoicesGridView_DXFREditorcol7');
dxo.SetProperties({'uniqueID':'InvoicesGridView$DXFREditorcol7'});
dxo.SetEvents({
	'ValueChanged':function(s, event) { ASPx.GVFilterChanged('InvoicesGridView',s); },
	'KeyDown':function(s, event) { ASPx.GVFilterKeyPress('InvoicesGridView',s,event); }
});
dxo.InitializeProperties({
	'decorationStyles':[
		{'key':'F','className':'dxeFocused_CincAccounting','cssText':''}
	]
});
dxo.AfterCreate();

//-->
</script></td><td><img class="dxGridView_gvFilterRowButton_CincAccounting" onclick="ASPx.GVFilterRowMenu('InvoicesGridView',7,this)" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="Open filter row popup menu" style="cursor:pointer;"></td>
			</tr>
		</tbody></table></td><td class="dxgv" style="text-align:Right;"><table style="width:100%;">
			<tbody><tr>
				<td style="width:100%;padding-right:2px;"><table class="dxeTextBoxSys dxeTextBox_CincAccounting dxeTextBoxDefaultWidthSys" id="InvoicesGridView_DXFREditorcol8" style="width:100%;">
					<tbody><tr>
						<td class="dxic" style="width:100%;"><input class="dxeEditArea_CincAccounting dxeEditAreaSys" id="InvoicesGridView_DXFREditorcol8_I" name="InvoicesGridView$DXFREditorcol8" onfocus="ASPx.EGotFocus('InvoicesGridView_DXFREditorcol8')" onblur="ASPx.ELostFocus('InvoicesGridView_DXFREditorcol8')" onchange="ASPx.EValueChanged('InvoicesGridView_DXFREditorcol8')" type="text"></td>
					</tr>
				</tbody></table><script id="dxss_785449145" type="text/javascript">
<!--
ASPx.AddDisabledItems('InvoicesGridView_DXFREditorcol8',[[['dxeDisabled_CincAccounting'],[''],['','I']]]);

var dxo = new ASPxClientTextBox('InvoicesGridView_DXFREditorcol8');
dxo.InitGlobalVariable('InvoicesGridView_DXFREditorcol8');
dxo.SetProperties({'uniqueID':'InvoicesGridView$DXFREditorcol8'});
dxo.SetEvents({
	'ValueChanged':function(s, event) { ASPx.GVFilterChanged('InvoicesGridView',s); },
	'KeyDown':function(s, event) { ASPx.GVFilterKeyPress('InvoicesGridView',s,event); }
});
dxo.InitializeProperties({
	'decorationStyles':[
		{'key':'F','className':'dxeFocused_CincAccounting','cssText':''}
	]
});
dxo.AfterCreate();

//-->
</script></td><td><img class="dxGridView_gvFilterRowButton_CincAccounting" onclick="ASPx.GVFilterRowMenu('InvoicesGridView',8,this)" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="Open filter row popup menu" style="cursor:pointer;"></td>
			</tr>
		</tbody></table></td><td class="dxgv"><table style="width:100%;">
			<tbody><tr>
				<td style="width:100%;padding-right:2px;"><table class="dxeTextBoxSys dxeTextBox_CincAccounting dxeTextBoxDefaultWidthSys" id="InvoicesGridView_DXFREditorcol9" style="width:100%;">
					<tbody><tr>
						<td class="dxic" style="width:100%;"><input class="dxeEditArea_CincAccounting dxeEditAreaSys" id="InvoicesGridView_DXFREditorcol9_I" name="InvoicesGridView$DXFREditorcol9" onfocus="ASPx.EGotFocus('InvoicesGridView_DXFREditorcol9')" onblur="ASPx.ELostFocus('InvoicesGridView_DXFREditorcol9')" onchange="ASPx.EValueChanged('InvoicesGridView_DXFREditorcol9')" type="text"></td>
					</tr>
				</tbody></table><script id="dxss_589021992" type="text/javascript">
<!--
ASPx.AddDisabledItems('InvoicesGridView_DXFREditorcol9',[[['dxeDisabled_CincAccounting'],[''],['','I']]]);

var dxo = new ASPxClientTextBox('InvoicesGridView_DXFREditorcol9');
dxo.InitGlobalVariable('InvoicesGridView_DXFREditorcol9');
dxo.SetProperties({'uniqueID':'InvoicesGridView$DXFREditorcol9'});
dxo.SetEvents({
	'ValueChanged':function(s, event) { ASPx.GVFilterChanged('InvoicesGridView',s); },
	'KeyDown':function(s, event) { ASPx.GVFilterKeyPress('InvoicesGridView',s,event); }
});
dxo.InitializeProperties({
	'decorationStyles':[
		{'key':'F','className':'dxeFocused_CincAccounting','cssText':''}
	]
});
dxo.AfterCreate();

//-->
</script></td><td><img class="dxGridView_gvFilterRowButton_CincAccounting" onclick="ASPx.GVFilterRowMenu('InvoicesGridView',9,this)" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="Open filter row popup menu" style="cursor:pointer;"></td>
			</tr>
		</tbody></table></td><td class="dxgv" style="border-right-width:0px;"><table style="width:100%;">
			<tbody><tr>
				<td style="width:100%;padding-right:2px;"><table class="dxeTextBoxSys dxeTextBox_CincAccounting dxeTextBoxDefaultWidthSys" id="InvoicesGridView_DXFREditorcol10" style="width:100%;">
					<tbody><tr>
						<td class="dxic" style="width:100%;"><input class="dxeEditArea_CincAccounting dxeEditAreaSys" id="InvoicesGridView_DXFREditorcol10_I" name="InvoicesGridView$DXFREditorcol10" onfocus="ASPx.EGotFocus('InvoicesGridView_DXFREditorcol10')" onblur="ASPx.ELostFocus('InvoicesGridView_DXFREditorcol10')" onchange="ASPx.EValueChanged('InvoicesGridView_DXFREditorcol10')" type="text"></td>
					</tr>
				</tbody></table><script id="dxss_1568080598" type="text/javascript">
<!--
ASPx.AddDisabledItems('InvoicesGridView_DXFREditorcol10',[[['dxeDisabled_CincAccounting'],[''],['','I']]]);

var dxo = new ASPxClientTextBox('InvoicesGridView_DXFREditorcol10');
dxo.InitGlobalVariable('InvoicesGridView_DXFREditorcol10');
dxo.SetProperties({'uniqueID':'InvoicesGridView$DXFREditorcol10'});
dxo.SetEvents({
	'ValueChanged':function(s, event) { ASPx.GVFilterChanged('InvoicesGridView',s); },
	'KeyDown':function(s, event) { ASPx.GVFilterKeyPress('InvoicesGridView',s,event); }
});
dxo.InitializeProperties({
	'decorationStyles':[
		{'key':'F','className':'dxeFocused_CincAccounting','cssText':''}
	]
});
dxo.AfterCreate();

//-->
</script></td><td><img class="dxGridView_gvFilterRowButton_CincAccounting" onclick="ASPx.GVFilterRowMenu('InvoicesGridView',10,this)" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="Open filter row popup menu" style="cursor:pointer;"></td>
			</tr>
		</tbody></table></td>
	</tr><tr id="InvoicesGridView_DXGroupRowExp0" class="dxgvGroupRow_CincAccounting">
		<td id="InvoicesGridView_tcgr0_3" class="dxgv" colspan="8"><table style="width:100%;background-color:#99CCCC;"><tbody><tr><td style="width: 20px;padding-left: 3px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="CheckAllInvoicesAssoc322"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="CheckAllInvoicesAssoc322_S_D"><span class="dxKBSW"><input id="CheckAllInvoicesAssoc322_S" name="CheckAllInvoicesAssoc322" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_1437921267" type="text/javascript">
<!--
ASPx.AddDisabledItems('CheckAllInvoicesAssoc322',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('CheckAllInvoicesAssoc322');
dxo.InitGlobalVariable('CheckAllInvoicesAssoc322');
dxo.SetProperties({
	'imageProperties':{
	'4':['dxWeb_edtCheckBoxChecked_CincAccounting','dxWeb_edtCheckBoxUnchecked_CincAccounting'],
	'8':['dxWeb_edtCheckBoxCheckedDisabled_CincAccounting','dxWeb_edtCheckBoxUncheckedDisabled_CincAccounting']
},
	'icbFocusedStyle':['dxICBFocused_CincAccounting','']
});
dxo.SetEvents({
	'CheckedChanged':OnCheckedAllChangedAssociation
});
dxo.InitializeProperties({
	'decorationStyles':[]
});
dxo.AfterCreate();

//-->
</script></td><td><div style="font-size:11px;font-weight:700;padding:3px;letter-spacing: 0.02em;">&nbsp;1002 Hillsborough Street Residential Condo HOA, Inc.</div></td></tr></tbody></table></td>
	</tr><tr id="InvoicesGridView_DXDataRow1" class="dxgvDataRow_CincAccounting">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell1_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_153212"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_153212_S_D"><span class="dxKBSW"><input id="cb_153212_S" name="cb_153212" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_798175239" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_153212',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_153212');
dxo.InitGlobalVariable('cb_153212');
dxo.SetProperties({
	'imageProperties':{
	'4':['dxWeb_edtCheckBoxChecked_CincAccounting','dxWeb_edtCheckBoxUnchecked_CincAccounting'],
	'8':['dxWeb_edtCheckBoxCheckedDisabled_CincAccounting','dxWeb_edtCheckBoxUncheckedDisabled_CincAccounting']
},
	'icbFocusedStyle':['dxICBFocused_CincAccounting','']
});
dxo.SetEvents({
	'CheckedChanged':OnCheckedChanged
});
dxo.InitializeProperties({
	'decorationStyles':[]
});
dxo.AfterCreate();

//-->
</script><input type="hidden" id="hdnAssocID_153212_322" value="153212"><input type="hidden" id="hd153212_64356" value="47.02"></td><td id="InvoicesGridView_tccell1_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=153212&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','153212')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell1_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell1_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00153212</td><td id="InvoicesGridView_tccell1_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$47.02</span></td><td id="InvoicesGridView_tccell1_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt153212" name="payamt153212" value="47.02"><span>$47.02</span></td><td id="InvoicesGridView_tccell1_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status153212" name="status153212" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval153212" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(153212, this)">0/1</a></span><input type="hidden" id="assocId153212" name="assocId153212" value="322"><input type="hidden" id="payType153212" name="payType153212" value="-2"></td><td id="InvoicesGridView_tccell1_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow1" class="dxgvPreviewRow_CincAccounting dxgvLVR">

	</tr>
</tbody></table><div class="dxmLite_CincAccounting dxm-ltr">
	<div id="InvoicesGridView_DXFilterRowMenu" style="z-index: 20000; display: none; position: absolute;">
		<div class="dxm-popupMain dxm-shadow dxm-popup" id="InvoicesGridView_DXFilterRowMenu_DXME_">
			<ul class="dx dxm-gutter">
				<li class="dxm-item" id="InvoicesGridView_DXFilterRowMenu_DXI0_"><div class="dxm-content dxm-hasText" id="InvoicesGridView_DXFilterRowMenu_DXI0_T">
					<img class="dxWeb_mSubMenuItem_CincAccounting dxm-image dx-vam" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="" id="InvoicesGridView_DXFilterRowMenu_DXI0_Img"><span class="dx-vam">Begins with</span>
				</div><b class="dx-clear"></b></li><li class="dxm-spacing" id="InvoicesGridView_DXFilterRowMenu_DXI1_II"></li><li class="dxm-item" id="InvoicesGridView_DXFilterRowMenu_DXI1_"><div class="dxm-content dxm-hasText" id="InvoicesGridView_DXFilterRowMenu_DXI1_T">
					<img class="dxWeb_mSubMenuItem_CincAccounting dxm-image dx-vam" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="" id="InvoicesGridView_DXFilterRowMenu_DXI1_Img"><span class="dx-vam">Contains</span>
				</div><b class="dx-clear"></b></li><li class="dxm-spacing" id="InvoicesGridView_DXFilterRowMenu_DXI2_II"></li><li class="dxm-item" id="InvoicesGridView_DXFilterRowMenu_DXI2_"><div class="dxm-content dxm-hasText" id="InvoicesGridView_DXFilterRowMenu_DXI2_T">
					<img class="dxWeb_mSubMenuItem_CincAccounting dxm-image dx-vam" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="" id="InvoicesGridView_DXFilterRowMenu_DXI2_Img"><span class="dx-vam">Doesn't contain</span>
				</div><b class="dx-clear"></b></li><li class="dxm-spacing" id="InvoicesGridView_DXFilterRowMenu_DXI3_II"></li><li class="dxm-item" id="InvoicesGridView_DXFilterRowMenu_DXI3_"><div class="dxm-content dxm-hasText" id="InvoicesGridView_DXFilterRowMenu_DXI3_T">
					<img class="dxWeb_mSubMenuItem_CincAccounting dxm-image dx-vam" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="" id="InvoicesGridView_DXFilterRowMenu_DXI3_Img"><span class="dx-vam">Ends with</span>
				</div><b class="dx-clear"></b></li><li class="dxm-spacing" id="InvoicesGridView_DXFilterRowMenu_DXI4_II"></li><li class="dxm-item" id="InvoicesGridView_DXFilterRowMenu_DXI4_"><div class="dxm-content dxm-hasText" id="InvoicesGridView_DXFilterRowMenu_DXI4_T">
					<img class="dxWeb_mSubMenuItem_CincAccounting dxm-image dx-vam" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="" id="InvoicesGridView_DXFilterRowMenu_DXI4_Img"><span class="dx-vam">Equals</span>
				</div><b class="dx-clear"></b></li><li class="dxm-spacing" id="InvoicesGridView_DXFilterRowMenu_DXI5_II"></li><li class="dxm-item" id="InvoicesGridView_DXFilterRowMenu_DXI5_"><div class="dxm-content dxm-hasText" id="InvoicesGridView_DXFilterRowMenu_DXI5_T">
					<img class="dxWeb_mSubMenuItem_CincAccounting dxm-image dx-vam" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="" id="InvoicesGridView_DXFilterRowMenu_DXI5_Img"><span class="dx-vam">Doesn't equal</span>
				</div><b class="dx-clear"></b></li><li class="dxm-spacing" id="InvoicesGridView_DXFilterRowMenu_DXI6_II"></li><li class="dxm-item" id="InvoicesGridView_DXFilterRowMenu_DXI6_"><div class="dxm-content dxm-hasText" id="InvoicesGridView_DXFilterRowMenu_DXI6_T">
					<img class="dxWeb_mSubMenuItem_CincAccounting dxm-image dx-vam" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="" id="InvoicesGridView_DXFilterRowMenu_DXI6_Img"><span class="dx-vam">Is less than</span>
				</div><b class="dx-clear"></b></li><li class="dxm-spacing" id="InvoicesGridView_DXFilterRowMenu_DXI7_II"></li><li class="dxm-item" id="InvoicesGridView_DXFilterRowMenu_DXI7_"><div class="dxm-content dxm-hasText" id="InvoicesGridView_DXFilterRowMenu_DXI7_T">
					<img class="dxWeb_mSubMenuItem_CincAccounting dxm-image dx-vam" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="" id="InvoicesGridView_DXFilterRowMenu_DXI7_Img"><span class="dx-vam">Is less than or equal to</span>
				</div><b class="dx-clear"></b></li><li class="dxm-spacing" id="InvoicesGridView_DXFilterRowMenu_DXI8_II"></li><li class="dxm-item" id="InvoicesGridView_DXFilterRowMenu_DXI8_"><div class="dxm-content dxm-hasText" id="InvoicesGridView_DXFilterRowMenu_DXI8_T">
					<img class="dxWeb_mSubMenuItem_CincAccounting dxm-image dx-vam" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="" id="InvoicesGridView_DXFilterRowMenu_DXI8_Img"><span class="dx-vam">Is greater than</span>
				</div><b class="dx-clear"></b></li><li class="dxm-spacing" id="InvoicesGridView_DXFilterRowMenu_DXI9_II"></li><li class="dxm-item" id="InvoicesGridView_DXFilterRowMenu_DXI9_"><div class="dxm-content dxm-hasText" id="InvoicesGridView_DXFilterRowMenu_DXI9_T">
					<img class="dxWeb_mSubMenuItem_CincAccounting dxm-image dx-vam" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="" id="InvoicesGridView_DXFilterRowMenu_DXI9_Img"><span class="dx-vam">Is greater than or equal to</span>
				</div><b class="dx-clear"></b></li><li class="dxm-spacing" id="InvoicesGridView_DXFilterRowMenu_DXI10_II"></li><li title="Two wildcard symbols are supported:
 '%' substitutes zero or more characters;
 '_' substitutes a single character." class="dxm-item" id="InvoicesGridView_DXFilterRowMenu_DXI10_"><div class="dxm-content dxm-hasText" id="InvoicesGridView_DXFilterRowMenu_DXI10_T">
					<img title="Two wildcard symbols are supported:
 '%' substitutes zero or more characters;
 '_' substitutes a single character." class="dxWeb_mSubMenuItem_CincAccounting dxm-image dx-vam" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="" id="InvoicesGridView_DXFilterRowMenu_DXI10_Img"><span title="Two wildcard symbols are supported:
 '%' substitutes zero or more characters;
 '_' substitutes a single character." class="dx-vam">Like ('%', '_')</span>
				</div><b class="dx-clear"></b></li>
			</ul>
		</div>
	</div>
</div><script id="dxss_58458385" type="text/javascript">
<!--
ASPx.AddHoverItems('InvoicesGridView_DXFilterRowMenu',[[[''],[''],['DXME_']],[['dxm-hovered',''],['',''],['DXI0_','DXI1_','DXI2_','DXI3_','DXI4_','DXI5_','DXI6_','DXI7_','DXI8_','DXI9_','DXI10_'],['','T']]]);
ASPx.AddSelectedItems('InvoicesGridView_DXFilterRowMenu',[[['dxm-checked',''],['',''],['DXI0_','DXI1_','DXI2_','DXI3_','DXI4_','DXI5_','DXI6_','DXI7_','DXI8_','DXI9_','DXI10_'],['','T'],[[{'spriteCssClass':'dxWeb_mSubMenuItemChecked_CincAccounting'}],[{'spriteCssClass':'dxWeb_mSubMenuItemChecked_CincAccounting'}],[{'spriteCssClass':'dxWeb_mSubMenuItemChecked_CincAccounting'}],[{'spriteCssClass':'dxWeb_mSubMenuItemChecked_CincAccounting'}],[{'spriteCssClass':'dxWeb_mSubMenuItemChecked_CincAccounting'}],[{'spriteCssClass':'dxWeb_mSubMenuItemChecked_CincAccounting'}],[{'spriteCssClass':'dxWeb_mSubMenuItemChecked_CincAccounting'}],[{'spriteCssClass':'dxWeb_mSubMenuItemChecked_CincAccounting'}],[{'spriteCssClass':'dxWeb_mSubMenuItemChecked_CincAccounting'}],[{'spriteCssClass':'dxWeb_mSubMenuItemChecked_CincAccounting'}],[{'spriteCssClass':'dxWeb_mSubMenuItemChecked_CincAccounting'}]],['Img','PImg']]]);
ASPx.AddDisabledItems('InvoicesGridView_DXFilterRowMenu',[[['dxm-disabled'],[''],['DXI0_','DXI1_','DXI2_','DXI3_','DXI4_','DXI5_','DXI6_','DXI7_','DXI8_','DXI9_','DXI10_'],['','T']]]);

var dxo = new ASPxClientPopupMenu('InvoicesGridView_DXFilterRowMenu');
dxo.InitGlobalVariable('InvoicesGridView_DXFilterRowMenu');
dxo.SetProperties({
	'uniqueID':'InvoicesGridView$DXFilterRowMenu',
	'renderData':{
		'':[[0],[1],[2],[3],[4],[5],[6],[7],[8],[9],[10]]
	},
	'allowCheckItems':true,
	'checkedState':'',
	'itemCheckedGroups':[['0','1','2','3','4','5','6','7','8','9','10']],
	'popupVerticalAlign':'Below',
	'isContextMenu':true
});
dxo.SetEvents({
	'ItemClick':function(s,e){ASPx.GVFilterRowMenuClick('InvoicesGridView',e)}
});
dxo.InitializeProperties({
	'items':[
		{'name':'1|S'},
		{'name':'3|S'},
		{'name':'4|S'},
		{'name':'2|S'},
		{'name':'5|SN'},
		{'name':'10|SN'},
		{'name':'6|N'},
		{'name':'7|N'},
		{'name':'8|N'},
		{'name':'9|N'},
		{'name':'11|L'}
	]
});
dxo.AfterCreate();

//-->
</script><img id="InvoicesGridView_IADD" class="dxGridView_gvDragAndDropArrowDown_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="|" style="position:absolute;visibility:hidden;top:-100px;"><img id="InvoicesGridView_IADU" class="dxGridView_gvDragAndDropArrowUp_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="|" style="position:absolute;visibility:hidden;top:-100px;"><img id="InvoicesGridView_IADL" class="dxGridView_gvDragAndDropArrowLeft_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="|" style="position:absolute;visibility:hidden;top:-100px;"><img id="InvoicesGridView_IADR" class="dxGridView_gvDragAndDropArrowRight_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="|" style="position:absolute;visibility:hidden;top:-100px;"><img id="InvoicesGridView_IDHF" class="dxGridView_gvDragAndDropHideColumn_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="Hide" style="position:absolute;visibility:hidden;top:-100px;"><script id="dxss_1863721633" type="text/javascript">
<!--
var dxo = ASPx.GetControlCollection().Get('InvoicesGridView');
dxo.SetProperties({
	'callBacksEnabled':true,
	'pageRowCount':2,
	'pageRowSize':10,
	'pageIndex':-1,
	'pageCount':1,
	'selectedWithoutPageRowCount':0,
	'visibleStartIndex':0,
	'focusedRowIndex':-1,
	'allowFocusedRow':false,
	'allowSelectByItemClick':false,
	'allowSelectSingleRowOnly':false,
	'callbackOnFocusedRowChanged':false,
	'callbackOnSelectionChanged':false,
	'editState':0,
	'editItemVisibleIndex':-1,
	'searchPanelFilter':'',
	'columns':[
		new ASPxClientGridViewColumn('',0,-1,'InvoiceCheckbox',true,'S',false,true,false,true,false,false,0,0),
		new ASPxClientGridViewColumn('',1,-1,'numInvoiceID',false,'N',false,true,true,true,false,true,0,0),
		new ASPxClientGridViewColumn('',2,-1,'AssocID',false,'N',false,true,true,true,false,true,0,0),
		new ASPxClientGridViewColumn('',3,-1,'AssocName',true,'S',false,true,true,true,false,false,0,0),
		new ASPxClientGridViewColumn('',4,-1,'dteInvoiceDate',true,'N',false,true,true,false,true,false,0,0),
		new ASPxClientGridViewColumn('',5,-1,'dteDueDate',true,'N',false,true,true,false,true,false,0,0),
		new ASPxClientGridViewColumn('',6,-1,'txtVendorInvoiceNum',true,'S',false,true,true,false,false,false,0,0),
		new ASPxClientGridViewColumn('',7,-1,'mnyInvoiceTotal',true,'N',false,true,true,false,false,false,0,0),
		new ASPxClientGridViewColumn('',8,-1,'Balance',true,'N',false,true,true,false,false,false,0,0),
		new ASPxClientGridViewColumn('',9,-1,'txtInvStatus',true,'S',false,true,true,false,false,false,0,0),
		new ASPxClientGridViewColumn('',10,-1,'txtVendorName',true,'S',false,true,true,false,false,false,0,0)
	],
	'editMode':2,
	'indentColumnCount':1,
	'allowMultiColumnAutoFilter':false,
	'autoFilterDelay':1200,
	'rowsLayoutInfo':{'mode':0},
	'filterRowConditions':{
		'10':3,
		'9':3,
		'8':5,
		'7':5,
		'6':3,
		'5':5,
		'4':5,
		'3':1,
		'2':5,
		'1':5,
		'0':1
	},
	'editingItemVisibleIndex':-1
});

//-->
</script><script id="dxss_352228249" type="text/javascript">
<!--
ASPxClientGridBase.InitializeStyles('InvoicesGridView',({
	'sel':{'css':'dxgvSelectedRow_CincAccounting'},
	'fi':{'css':'dxgvFocusedRow_CincAccounting'},
	'ei':'<tr class="dxgvEditingErrorRow_CincAccounting">\r\n\t<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;">&nbsp;</td><td class="dxgv" data-colSpan="8" style="border-right-width:0px;"></td>\r\n</tr>',
	'fc':{'css':'dxgvFocusedCell_CincAccounting'},
	'bec':{'css':'dxgvBatchEditCell_CincAccounting dxGridCellWordBreak dxgv'},
	'bemc':{'css':'dxgvBatchEditModifiedCell_CincAccounting dxGridCellWordBreak dxgv'},
	'bemergmc':{'css':'dxgvBatchEditCell_CincAccounting dxGridCellWordBreak dxgvBatchEditModifiedCell_CincAccounting dxgv'},
	'fgi':{'css':'dxgvFocusedGroupRow_CincAccounting'}
}),[])
//-->
</script>
<input type="hidden" id="OnHoldHdn" name="OnHoldHdn" value="11"></td>
	</tr>
</tbody></table>