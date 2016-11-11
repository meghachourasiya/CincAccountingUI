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
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell1_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_148012"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_148012_S_D"><span class="dxKBSW"><input id="cb_148012_S" name="cb_148012" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_1648585186" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_148012',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_148012');
dxo.InitGlobalVariable('cb_148012');
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
</script><input type="hidden" id="hdnAssocID_148012_322" value="148012"><input type="hidden" id="hd148012_64356" value="68.03"></td><td id="InvoicesGridView_tccell1_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=148012&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','148012')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell1_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell1_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00148012</td><td id="InvoicesGridView_tccell1_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$68.03</span></td><td id="InvoicesGridView_tccell1_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt148012" name="payamt148012" value="68.03"><span>$68.03</span></td><td id="InvoicesGridView_tccell1_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status148012" name="status148012" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval148012" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(148012, this)">0/1</a></span><input type="hidden" id="assocId148012" name="assocId148012" value="322"><input type="hidden" id="payType148012" name="payType148012" value="-2"></td><td id="InvoicesGridView_tccell1_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow1" class="dxgvPreviewRow_CincAccounting">

	</tr><tr id="InvoicesGridView_DXDataRow2" class="dxgvDataRow_CincAccounting dxgvDataRowAlt_CincAccounting" style="background-color: rgb(237, 237, 237);">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell2_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_148220"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_148220_S_D"><span class="dxKBSW"><input id="cb_148220_S" name="cb_148220" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_41834512" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_148220',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_148220');
dxo.InitGlobalVariable('cb_148220');
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
</script><input type="hidden" id="hdnAssocID_148220_322" value="148220"><input type="hidden" id="hd148220_64356" value="47.03"></td><td id="InvoicesGridView_tccell2_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=148220&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','148220')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell2_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell2_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00148220</td><td id="InvoicesGridView_tccell2_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$47.03</span></td><td id="InvoicesGridView_tccell2_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt148220" name="payamt148220" value="47.03"><span>$47.03</span></td><td id="InvoicesGridView_tccell2_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status148220" name="status148220" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval148220" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(148220, this)">0/1</a></span><input type="hidden" id="assocId148220" name="assocId148220" value="322"><input type="hidden" id="payType148220" name="payType148220" value="-2"></td><td id="InvoicesGridView_tccell2_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow2" class="dxgvPreviewRow_CincAccounting" style="background-color:#EDEDED;">

	</tr><tr id="InvoicesGridView_DXDataRow3" class="dxgvDataRow_CincAccounting">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell3_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_148428"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_148428_S_D"><span class="dxKBSW"><input id="cb_148428_S" name="cb_148428" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_1377701355" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_148428',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_148428');
dxo.InitGlobalVariable('cb_148428');
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
</script><input type="hidden" id="hdnAssocID_148428_322" value="148428"><input type="hidden" id="hd148428_64356" value="689.25"></td><td id="InvoicesGridView_tccell3_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=148428&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','148428')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell3_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell3_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00148428</td><td id="InvoicesGridView_tccell3_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$689.25</span></td><td id="InvoicesGridView_tccell3_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt148428" name="payamt148428" value="689.25"><span>$689.25</span></td><td id="InvoicesGridView_tccell3_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status148428" name="status148428" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval148428" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(148428, this)">0/1</a></span><input type="hidden" id="assocId148428" name="assocId148428" value="322"><input type="hidden" id="payType148428" name="payType148428" value="-2"></td><td id="InvoicesGridView_tccell3_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow3" class="dxgvPreviewRow_CincAccounting">

	</tr><tr id="InvoicesGridView_DXDataRow4" class="dxgvDataRow_CincAccounting dxgvDataRowAlt_CincAccounting" style="background-color: rgb(237, 237, 237);">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell4_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_148636"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_148636_S_D"><span class="dxKBSW"><input id="cb_148636_S" name="cb_148636" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_1247830338" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_148636',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_148636');
dxo.InitGlobalVariable('cb_148636');
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
</script><input type="hidden" id="hdnAssocID_148636_322" value="148636"><input type="hidden" id="hd148636_64356" value="111.07"></td><td id="InvoicesGridView_tccell4_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=148636&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','148636')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell4_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell4_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00148636</td><td id="InvoicesGridView_tccell4_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$111.07</span></td><td id="InvoicesGridView_tccell4_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt148636" name="payamt148636" value="111.07"><span>$111.07</span></td><td id="InvoicesGridView_tccell4_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status148636" name="status148636" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval148636" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(148636, this)">0/1</a></span><input type="hidden" id="assocId148636" name="assocId148636" value="322"><input type="hidden" id="payType148636" name="payType148636" value="-2"></td><td id="InvoicesGridView_tccell4_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow4" class="dxgvPreviewRow_CincAccounting" style="background-color:#EDEDED;">

	</tr><tr id="InvoicesGridView_DXDataRow5" class="dxgvDataRow_CincAccounting">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell5_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_148844"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_148844_S_D"><span class="dxKBSW"><input id="cb_148844_S" name="cb_148844" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_205323233" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_148844',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_148844');
dxo.InitGlobalVariable('cb_148844');
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
</script><input type="hidden" id="hdnAssocID_148844_322" value="148844"><input type="hidden" id="hd148844_64356" value="474.21"></td><td id="InvoicesGridView_tccell5_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=148844&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','148844')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell5_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell5_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00148844</td><td id="InvoicesGridView_tccell5_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$474.21</span></td><td id="InvoicesGridView_tccell5_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt148844" name="payamt148844" value="474.21"><span>$474.21</span></td><td id="InvoicesGridView_tccell5_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status148844" name="status148844" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval148844" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(148844, this)">0/1</a></span><input type="hidden" id="assocId148844" name="assocId148844" value="322"><input type="hidden" id="payType148844" name="payType148844" value="-2"></td><td id="InvoicesGridView_tccell5_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow5" class="dxgvPreviewRow_CincAccounting">

	</tr><tr id="InvoicesGridView_DXDataRow6" class="dxgvDataRow_CincAccounting dxgvDataRowAlt_CincAccounting" style="background-color: rgb(237, 237, 237);">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell6_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_149052"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_149052_S_D"><span class="dxKBSW"><input id="cb_149052_S" name="cb_149052" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_1829609110" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_149052',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_149052');
dxo.InitGlobalVariable('cb_149052');
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
</script><input type="hidden" id="hdnAssocID_149052_322" value="149052"><input type="hidden" id="hd149052_64356" value="645.29"></td><td id="InvoicesGridView_tccell6_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=149052&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','149052')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell6_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell6_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00149052</td><td id="InvoicesGridView_tccell6_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$645.29</span></td><td id="InvoicesGridView_tccell6_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt149052" name="payamt149052" value="645.29"><span>$645.29</span></td><td id="InvoicesGridView_tccell6_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status149052" name="status149052" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval149052" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(149052, this)">0/1</a></span><input type="hidden" id="assocId149052" name="assocId149052" value="322"><input type="hidden" id="payType149052" name="payType149052" value="-2"></td><td id="InvoicesGridView_tccell6_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow6" class="dxgvPreviewRow_CincAccounting" style="background-color:#EDEDED;">

	</tr><tr id="InvoicesGridView_DXDataRow7" class="dxgvDataRow_CincAccounting">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell7_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_149260"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_149260_S_D"><span class="dxKBSW"><input id="cb_149260_S" name="cb_149260" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_1993641316" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_149260',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_149260');
dxo.InitGlobalVariable('cb_149260');
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
</script><input type="hidden" id="hdnAssocID_149260_322" value="149260"><input type="hidden" id="hd149260_64356" value="410.16"></td><td id="InvoicesGridView_tccell7_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=149260&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','149260')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell7_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell7_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00149260</td><td id="InvoicesGridView_tccell7_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$410.16</span></td><td id="InvoicesGridView_tccell7_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt149260" name="payamt149260" value="410.16"><span>$410.16</span></td><td id="InvoicesGridView_tccell7_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status149260" name="status149260" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval149260" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(149260, this)">0/1</a></span><input type="hidden" id="assocId149260" name="assocId149260" value="322"><input type="hidden" id="payType149260" name="payType149260" value="-2"></td><td id="InvoicesGridView_tccell7_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow7" class="dxgvPreviewRow_CincAccounting">

	</tr><tr id="InvoicesGridView_DXDataRow8" class="dxgvDataRow_CincAccounting dxgvDataRowAlt_CincAccounting" style="background-color: rgb(237, 237, 237);">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell8_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_149468"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_149468_S_D"><span class="dxKBSW"><input id="cb_149468_S" name="cb_149468" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_1140358221" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_149468',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_149468');
dxo.InitGlobalVariable('cb_149468');
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
</script><input type="hidden" id="hdnAssocID_149468_322" value="149468"><input type="hidden" id="hd149468_64356" value="505.21"></td><td id="InvoicesGridView_tccell8_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=149468&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','149468')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell8_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell8_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00149468</td><td id="InvoicesGridView_tccell8_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$505.21</span></td><td id="InvoicesGridView_tccell8_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt149468" name="payamt149468" value="505.21"><span>$505.21</span></td><td id="InvoicesGridView_tccell8_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status149468" name="status149468" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval149468" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(149468, this)">0/1</a></span><input type="hidden" id="assocId149468" name="assocId149468" value="322"><input type="hidden" id="payType149468" name="payType149468" value="-2"></td><td id="InvoicesGridView_tccell8_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow8" class="dxgvPreviewRow_CincAccounting" style="background-color:#EDEDED;">

	</tr><tr id="InvoicesGridView_DXDataRow9" class="dxgvDataRow_CincAccounting">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell9_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_149676"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_149676_S_D"><span class="dxKBSW"><input id="cb_149676_S" name="cb_149676" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_944707176" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_149676',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_149676');
dxo.InitGlobalVariable('cb_149676');
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
</script><input type="hidden" id="hdnAssocID_149676_322" value="149676"><input type="hidden" id="hd149676_64356" value="585.26"></td><td id="InvoicesGridView_tccell9_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=149676&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','149676')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell9_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell9_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00149676</td><td id="InvoicesGridView_tccell9_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$585.26</span></td><td id="InvoicesGridView_tccell9_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt149676" name="payamt149676" value="585.26"><span>$585.26</span></td><td id="InvoicesGridView_tccell9_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status149676" name="status149676" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval149676" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(149676, this)">0/1</a></span><input type="hidden" id="assocId149676" name="assocId149676" value="322"><input type="hidden" id="payType149676" name="payType149676" value="-2"></td><td id="InvoicesGridView_tccell9_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow9" class="dxgvPreviewRow_CincAccounting">

	</tr><tr id="InvoicesGridView_DXDataRow10" class="dxgvDataRow_CincAccounting dxgvDataRowAlt_CincAccounting" style="background-color: rgb(237, 237, 237);">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell10_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_149884"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_149884_S_D"><span class="dxKBSW"><input id="cb_149884_S" name="cb_149884" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_451269580" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_149884',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_149884');
dxo.InitGlobalVariable('cb_149884');
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
</script><input type="hidden" id="hdnAssocID_149884_322" value="149884"><input type="hidden" id="hd149884_64356" value="638.26"></td><td id="InvoicesGridView_tccell10_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=149884&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','149884')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell10_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell10_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00149884</td><td id="InvoicesGridView_tccell10_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$638.26</span></td><td id="InvoicesGridView_tccell10_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt149884" name="payamt149884" value="638.26"><span>$638.26</span></td><td id="InvoicesGridView_tccell10_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status149884" name="status149884" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval149884" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(149884, this)">0/1</a></span><input type="hidden" id="assocId149884" name="assocId149884" value="322"><input type="hidden" id="payType149884" name="payType149884" value="-2"></td><td id="InvoicesGridView_tccell10_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow10" class="dxgvPreviewRow_CincAccounting" style="background-color:#EDEDED;">

	</tr><tr id="InvoicesGridView_DXDataRow11" class="dxgvDataRow_CincAccounting">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell11_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_150092"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_150092_S_D"><span class="dxKBSW"><input id="cb_150092_S" name="cb_150092" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_659337711" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_150092',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_150092');
dxo.InitGlobalVariable('cb_150092');
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
</script><input type="hidden" id="hdnAssocID_150092_322" value="150092"><input type="hidden" id="hd150092_64356" value="512.27"></td><td id="InvoicesGridView_tccell11_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=150092&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','150092')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell11_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell11_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00150092</td><td id="InvoicesGridView_tccell11_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$512.27</span></td><td id="InvoicesGridView_tccell11_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt150092" name="payamt150092" value="512.27"><span>$512.27</span></td><td id="InvoicesGridView_tccell11_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status150092" name="status150092" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval150092" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(150092, this)">0/1</a></span><input type="hidden" id="assocId150092" name="assocId150092" value="322"><input type="hidden" id="payType150092" name="payType150092" value="-2"></td><td id="InvoicesGridView_tccell11_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow11" class="dxgvPreviewRow_CincAccounting">

	</tr><tr id="InvoicesGridView_DXDataRow12" class="dxgvDataRow_CincAccounting dxgvDataRowAlt_CincAccounting" style="background-color: rgb(237, 237, 237);">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell12_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_150300"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_150300_S_D"><span class="dxKBSW"><input id="cb_150300_S" name="cb_150300" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_1231036807" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_150300',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_150300');
dxo.InitGlobalVariable('cb_150300');
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
</script><input type="hidden" id="hdnAssocID_150300_322" value="150300"><input type="hidden" id="hd150300_64356" value="290.13"></td><td id="InvoicesGridView_tccell12_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=150300&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','150300')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell12_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell12_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00150300</td><td id="InvoicesGridView_tccell12_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$290.13</span></td><td id="InvoicesGridView_tccell12_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt150300" name="payamt150300" value="290.13"><span>$290.13</span></td><td id="InvoicesGridView_tccell12_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status150300" name="status150300" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval150300" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(150300, this)">0/1</a></span><input type="hidden" id="assocId150300" name="assocId150300" value="322"><input type="hidden" id="payType150300" name="payType150300" value="-2"></td><td id="InvoicesGridView_tccell12_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow12" class="dxgvPreviewRow_CincAccounting" style="background-color:#EDEDED;">

	</tr><tr id="InvoicesGridView_DXDataRow13" class="dxgvDataRow_CincAccounting">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell13_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_150508"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_150508_S_D"><span class="dxKBSW"><input id="cb_150508_S" name="cb_150508" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_1588867383" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_150508',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_150508');
dxo.InitGlobalVariable('cb_150508');
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
</script><input type="hidden" id="hdnAssocID_150508_322" value="150508"><input type="hidden" id="hd150508_64356" value="220.09"></td><td id="InvoicesGridView_tccell13_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=150508&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','150508')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell13_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell13_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00150508</td><td id="InvoicesGridView_tccell13_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$220.09</span></td><td id="InvoicesGridView_tccell13_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt150508" name="payamt150508" value="220.09"><span>$220.09</span></td><td id="InvoicesGridView_tccell13_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status150508" name="status150508" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval150508" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(150508, this)">0/1</a></span><input type="hidden" id="assocId150508" name="assocId150508" value="322"><input type="hidden" id="payType150508" name="payType150508" value="-2"></td><td id="InvoicesGridView_tccell13_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow13" class="dxgvPreviewRow_CincAccounting">

	</tr><tr id="InvoicesGridView_DXDataRow14" class="dxgvDataRow_CincAccounting dxgvDataRowAlt_CincAccounting" style="background-color: rgb(237, 237, 237);">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell14_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_150716"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_150716_S_D"><span class="dxKBSW"><input id="cb_150716_S" name="cb_150716" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_1270680370" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_150716',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_150716');
dxo.InitGlobalVariable('cb_150716');
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
</script><input type="hidden" id="hdnAssocID_150716_322" value="150716"><input type="hidden" id="hd150716_64356" value="442.18"></td><td id="InvoicesGridView_tccell14_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=150716&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','150716')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell14_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell14_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00150716</td><td id="InvoicesGridView_tccell14_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$442.18</span></td><td id="InvoicesGridView_tccell14_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt150716" name="payamt150716" value="442.18"><span>$442.18</span></td><td id="InvoicesGridView_tccell14_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status150716" name="status150716" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval150716" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(150716, this)">0/1</a></span><input type="hidden" id="assocId150716" name="assocId150716" value="322"><input type="hidden" id="payType150716" name="payType150716" value="-2"></td><td id="InvoicesGridView_tccell14_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow14" class="dxgvPreviewRow_CincAccounting" style="background-color:#EDEDED;">

	</tr><tr id="InvoicesGridView_DXDataRow15" class="dxgvDataRow_CincAccounting">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell15_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_150924"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_150924_S_D"><span class="dxKBSW"><input id="cb_150924_S" name="cb_150924" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_368123358" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_150924',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_150924');
dxo.InitGlobalVariable('cb_150924');
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
</script><input type="hidden" id="hdnAssocID_150924_322" value="150924"><input type="hidden" id="hd150924_64356" value="369.18"></td><td id="InvoicesGridView_tccell15_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=150924&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','150924')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell15_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell15_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00150924</td><td id="InvoicesGridView_tccell15_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$369.18</span></td><td id="InvoicesGridView_tccell15_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt150924" name="payamt150924" value="369.18"><span>$369.18</span></td><td id="InvoicesGridView_tccell15_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status150924" name="status150924" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval150924" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(150924, this)">0/1</a></span><input type="hidden" id="assocId150924" name="assocId150924" value="322"><input type="hidden" id="payType150924" name="payType150924" value="-2"></td><td id="InvoicesGridView_tccell15_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow15" class="dxgvPreviewRow_CincAccounting">

	</tr><tr id="InvoicesGridView_DXDataRow16" class="dxgvDataRow_CincAccounting dxgvDataRowAlt_CincAccounting" style="background-color: rgb(237, 237, 237);">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell16_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_151132"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_151132_S_D"><span class="dxKBSW"><input id="cb_151132_S" name="cb_151132" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_66434257" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_151132',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_151132');
dxo.InitGlobalVariable('cb_151132');
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
</script><input type="hidden" id="hdnAssocID_151132_322" value="151132"><input type="hidden" id="hd151132_64356" value="577.22"></td><td id="InvoicesGridView_tccell16_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=151132&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','151132')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell16_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell16_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00151132</td><td id="InvoicesGridView_tccell16_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$577.22</span></td><td id="InvoicesGridView_tccell16_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt151132" name="payamt151132" value="577.22"><span>$577.22</span></td><td id="InvoicesGridView_tccell16_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status151132" name="status151132" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval151132" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(151132, this)">0/1</a></span><input type="hidden" id="assocId151132" name="assocId151132" value="322"><input type="hidden" id="payType151132" name="payType151132" value="-2"></td><td id="InvoicesGridView_tccell16_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow16" class="dxgvPreviewRow_CincAccounting" style="background-color:#EDEDED;">

	</tr><tr id="InvoicesGridView_DXDataRow17" class="dxgvDataRow_CincAccounting">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell17_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_151340"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_151340_S_D"><span class="dxKBSW"><input id="cb_151340_S" name="cb_151340" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_459102001" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_151340',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_151340');
dxo.InitGlobalVariable('cb_151340');
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
</script><input type="hidden" id="hdnAssocID_151340_322" value="151340"><input type="hidden" id="hd151340_64356" value="375.14"></td><td id="InvoicesGridView_tccell17_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=151340&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','151340')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell17_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell17_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00151340</td><td id="InvoicesGridView_tccell17_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$375.14</span></td><td id="InvoicesGridView_tccell17_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt151340" name="payamt151340" value="375.14"><span>$375.14</span></td><td id="InvoicesGridView_tccell17_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status151340" name="status151340" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval151340" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(151340, this)">0/1</a></span><input type="hidden" id="assocId151340" name="assocId151340" value="322"><input type="hidden" id="payType151340" name="payType151340" value="-2"></td><td id="InvoicesGridView_tccell17_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow17" class="dxgvPreviewRow_CincAccounting">

	</tr><tr id="InvoicesGridView_DXDataRow18" class="dxgvDataRow_CincAccounting dxgvDataRowAlt_CincAccounting" style="background-color: rgb(237, 237, 237);">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell18_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_151548"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_151548_S_D"><span class="dxKBSW"><input id="cb_151548_S" name="cb_151548" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_2053247378" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_151548',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_151548');
dxo.InitGlobalVariable('cb_151548');
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
</script><input type="hidden" id="hdnAssocID_151548_322" value="151548"><input type="hidden" id="hd151548_64356" value="559.22"></td><td id="InvoicesGridView_tccell18_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=151548&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','151548')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell18_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell18_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00151548</td><td id="InvoicesGridView_tccell18_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$559.22</span></td><td id="InvoicesGridView_tccell18_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt151548" name="payamt151548" value="559.22"><span>$559.22</span></td><td id="InvoicesGridView_tccell18_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status151548" name="status151548" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval151548" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(151548, this)">0/1</a></span><input type="hidden" id="assocId151548" name="assocId151548" value="322"><input type="hidden" id="payType151548" name="payType151548" value="-2"></td><td id="InvoicesGridView_tccell18_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow18" class="dxgvPreviewRow_CincAccounting" style="background-color:#EDEDED;">

	</tr><tr id="InvoicesGridView_DXDataRow19" class="dxgvDataRow_CincAccounting">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell19_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_151756"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_151756_S_D"><span class="dxKBSW"><input id="cb_151756_S" name="cb_151756" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_595143708" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_151756',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_151756');
dxo.InitGlobalVariable('cb_151756');
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
</script><input type="hidden" id="hdnAssocID_151756_322" value="151756"><input type="hidden" id="hd151756_64356" value="398.13"></td><td id="InvoicesGridView_tccell19_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=151756&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','151756')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell19_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell19_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00151756</td><td id="InvoicesGridView_tccell19_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$398.13</span></td><td id="InvoicesGridView_tccell19_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt151756" name="payamt151756" value="398.13"><span>$398.13</span></td><td id="InvoicesGridView_tccell19_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status151756" name="status151756" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval151756" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(151756, this)">0/1</a></span><input type="hidden" id="assocId151756" name="assocId151756" value="322"><input type="hidden" id="payType151756" name="payType151756" value="-2"></td><td id="InvoicesGridView_tccell19_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow19" class="dxgvPreviewRow_CincAccounting">

	</tr><tr id="InvoicesGridView_DXDataRow20" class="dxgvDataRow_CincAccounting dxgvDataRowAlt_CincAccounting" style="background-color: rgb(237, 237, 237);">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell20_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_151964"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_151964_S_D"><span class="dxKBSW"><input id="cb_151964_S" name="cb_151964" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_566658429" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_151964',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_151964');
dxo.InitGlobalVariable('cb_151964');
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
</script><input type="hidden" id="hdnAssocID_151964_322" value="151964"><input type="hidden" id="hd151964_64356" value="169.06"></td><td id="InvoicesGridView_tccell20_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=151964&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','151964')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell20_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell20_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00151964</td><td id="InvoicesGridView_tccell20_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$169.06</span></td><td id="InvoicesGridView_tccell20_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt151964" name="payamt151964" value="169.06"><span>$169.06</span></td><td id="InvoicesGridView_tccell20_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status151964" name="status151964" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval151964" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(151964, this)">0/1</a></span><input type="hidden" id="assocId151964" name="assocId151964" value="322"><input type="hidden" id="payType151964" name="payType151964" value="-2"></td><td id="InvoicesGridView_tccell20_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow20" class="dxgvPreviewRow_CincAccounting" style="background-color:#EDEDED;">

	</tr><tr id="InvoicesGridView_DXDataRow21" class="dxgvDataRow_CincAccounting">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell21_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_152172"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_152172_S_D"><span class="dxKBSW"><input id="cb_152172_S" name="cb_152172" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_1961828800" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_152172',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_152172');
dxo.InitGlobalVariable('cb_152172');
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
</script><input type="hidden" id="hdnAssocID_152172_322" value="152172"><input type="hidden" id="hd152172_64356" value="175.08"></td><td id="InvoicesGridView_tccell21_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=152172&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','152172')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell21_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell21_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00152172</td><td id="InvoicesGridView_tccell21_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$175.08</span></td><td id="InvoicesGridView_tccell21_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt152172" name="payamt152172" value="175.08"><span>$175.08</span></td><td id="InvoicesGridView_tccell21_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status152172" name="status152172" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval152172" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(152172, this)">0/1</a></span><input type="hidden" id="assocId152172" name="assocId152172" value="322"><input type="hidden" id="payType152172" name="payType152172" value="-2"></td><td id="InvoicesGridView_tccell21_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow21" class="dxgvPreviewRow_CincAccounting">

	</tr><tr id="InvoicesGridView_DXDataRow22" class="dxgvDataRow_CincAccounting dxgvDataRowAlt_CincAccounting" style="background-color: rgb(237, 237, 237);">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell22_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_152380"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_152380_S_D"><span class="dxKBSW"><input id="cb_152380_S" name="cb_152380" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_1154702837" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_152380',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_152380');
dxo.InitGlobalVariable('cb_152380');
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
</script><input type="hidden" id="hdnAssocID_152380_322" value="152380"><input type="hidden" id="hd152380_64356" value="336.14"></td><td id="InvoicesGridView_tccell22_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=152380&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','152380')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell22_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell22_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00152380</td><td id="InvoicesGridView_tccell22_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$336.14</span></td><td id="InvoicesGridView_tccell22_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt152380" name="payamt152380" value="336.14"><span>$336.14</span></td><td id="InvoicesGridView_tccell22_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status152380" name="status152380" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval152380" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(152380, this)">0/1</a></span><input type="hidden" id="assocId152380" name="assocId152380" value="322"><input type="hidden" id="payType152380" name="payType152380" value="-2"></td><td id="InvoicesGridView_tccell22_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow22" class="dxgvPreviewRow_CincAccounting" style="background-color:#EDEDED;">

	</tr><tr id="InvoicesGridView_DXDataRow23" class="dxgvDataRow_CincAccounting">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell23_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_152588"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_152588_S_D"><span class="dxKBSW"><input id="cb_152588_S" name="cb_152588" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_1165010378" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_152588',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_152588');
dxo.InitGlobalVariable('cb_152588');
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
</script><input type="hidden" id="hdnAssocID_152588_322" value="152588"><input type="hidden" id="hd152588_64356" value="262.08"></td><td id="InvoicesGridView_tccell23_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=152588&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','152588')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell23_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell23_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00152588</td><td id="InvoicesGridView_tccell23_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$262.08</span></td><td id="InvoicesGridView_tccell23_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt152588" name="payamt152588" value="262.08"><span>$262.08</span></td><td id="InvoicesGridView_tccell23_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status152588" name="status152588" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval152588" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(152588, this)">0/1</a></span><input type="hidden" id="assocId152588" name="assocId152588" value="322"><input type="hidden" id="payType152588" name="payType152588" value="-2"></td><td id="InvoicesGridView_tccell23_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow23" class="dxgvPreviewRow_CincAccounting">

	</tr><tr id="InvoicesGridView_DXDataRow24" class="dxgvDataRow_CincAccounting dxgvDataRowAlt_CincAccounting" style="background-color: rgb(237, 237, 237);">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell24_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_152796"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_152796_S_D"><span class="dxKBSW"><input id="cb_152796_S" name="cb_152796" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_1096714935" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_152796',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_152796');
dxo.InitGlobalVariable('cb_152796');
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
</script><input type="hidden" id="hdnAssocID_152796_322" value="152796"><input type="hidden" id="hd152796_64356" value="203.10"></td><td id="InvoicesGridView_tccell24_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=152796&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','152796')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell24_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell24_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00152796</td><td id="InvoicesGridView_tccell24_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$203.10</span></td><td id="InvoicesGridView_tccell24_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt152796" name="payamt152796" value="203.10"><span>$203.10</span></td><td id="InvoicesGridView_tccell24_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status152796" name="status152796" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval152796" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(152796, this)">0/1</a></span><input type="hidden" id="assocId152796" name="assocId152796" value="322"><input type="hidden" id="payType152796" name="payType152796" value="-2"></td><td id="InvoicesGridView_tccell24_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow24" class="dxgvPreviewRow_CincAccounting" style="background-color:#EDEDED;">

	</tr><tr id="InvoicesGridView_DXDataRow25" class="dxgvDataRow_CincAccounting">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell25_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_153004"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_153004_S_D"><span class="dxKBSW"><input id="cb_153004_S" name="cb_153004" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_311430335" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_153004',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_153004');
dxo.InitGlobalVariable('cb_153004');
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
</script><input type="hidden" id="hdnAssocID_153004_322" value="153004"><input type="hidden" id="hd153004_64356" value="550.21"></td><td id="InvoicesGridView_tccell25_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=153004&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','153004')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell25_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell25_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00153004</td><td id="InvoicesGridView_tccell25_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$550.21</span></td><td id="InvoicesGridView_tccell25_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt153004" name="payamt153004" value="550.21"><span>$550.21</span></td><td id="InvoicesGridView_tccell25_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status153004" name="status153004" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval153004" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(153004, this)">0/1</a></span><input type="hidden" id="assocId153004" name="assocId153004" value="322"><input type="hidden" id="payType153004" name="payType153004" value="-2"></td><td id="InvoicesGridView_tccell25_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow25" class="dxgvPreviewRow_CincAccounting">

	</tr><tr id="InvoicesGridView_DXDataRow26" class="dxgvDataRow_CincAccounting dxgvDataRowAlt_CincAccounting" style="background-color: rgb(237, 237, 237);">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell26_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_153212"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_153212_S_D"><span class="dxKBSW"><input id="cb_153212_S" name="cb_153212" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_798175239" type="text/javascript">
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
</script><input type="hidden" id="hdnAssocID_153212_322" value="153212"><input type="hidden" id="hd153212_64356" value="47.02"></td><td id="InvoicesGridView_tccell26_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=153212&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','153212')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell26_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell26_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00153212</td><td id="InvoicesGridView_tccell26_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$47.02</span></td><td id="InvoicesGridView_tccell26_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt153212" name="payamt153212" value="47.02"><span>$47.02</span></td><td id="InvoicesGridView_tccell26_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status153212" name="status153212" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval153212" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(153212, this)">0/1</a></span><input type="hidden" id="assocId153212" name="assocId153212" value="322"><input type="hidden" id="payType153212" name="payType153212" value="-2"></td><td id="InvoicesGridView_tccell26_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow26" class="dxgvPreviewRow_CincAccounting" style="background-color:#EDEDED;">

	</tr><tr id="InvoicesGridView_DXDataRow27" class="dxgvDataRow_CincAccounting">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell27_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_153420"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_153420_S_D"><span class="dxKBSW"><input id="cb_153420_S" name="cb_153420" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_1420005454" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_153420',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_153420');
dxo.InitGlobalVariable('cb_153420');
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
</script><input type="hidden" id="hdnAssocID_153420_322" value="153420"><input type="hidden" id="hd153420_64356" value="112.07"></td><td id="InvoicesGridView_tccell27_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=153420&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','153420')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell27_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell27_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00153420</td><td id="InvoicesGridView_tccell27_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$112.07</span></td><td id="InvoicesGridView_tccell27_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt153420" name="payamt153420" value="112.07"><span>$112.07</span></td><td id="InvoicesGridView_tccell27_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status153420" name="status153420" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval153420" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(153420, this)">0/1</a></span><input type="hidden" id="assocId153420" name="assocId153420" value="322"><input type="hidden" id="payType153420" name="payType153420" value="-2"></td><td id="InvoicesGridView_tccell27_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow27" class="dxgvPreviewRow_CincAccounting">

	</tr><tr id="InvoicesGridView_DXDataRow28" class="dxgvDataRow_CincAccounting dxgvDataRowAlt_CincAccounting" style="background-color: rgb(237, 237, 237);">
		<td class="dxgvIndentCell dxgv" style="width:0px;border-left-width:0px;border-bottom-width:0px;">&nbsp;</td><td id="InvoicesGridView_tccell28_0" class="dxGridCellWordBreak dxgv" style="background-color:#9900CC;padding-left:2px;border-left-width:0px;"><span class="dxichCellSys dxeBase_CincAccounting dxeTAR" id="cb_153628"><span class="dxWeb_edtCheckBoxUnchecked_CincAccounting dxICheckBox_CincAccounting dxichSys" id="cb_153628_S_D"><span class="dxKBSW"><input id="cb_153628_S" name="cb_153628" value="I" type="text" readonly="readonly" style="opacity:0;width:0;height:0;position:relative;background-color:transparent;display:block;margin:0;padding:0;border-width:0;font-size:0pt;"></span></span></span><script id="dxss_848776046" type="text/javascript">
<!--
ASPx.AddDisabledItems('cb_153628',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientCheckBox('cb_153628');
dxo.InitGlobalVariable('cb_153628');
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
</script><input type="hidden" id="hdnAssocID_153628_322" value="153628"><input type="hidden" id="hd153628_64356" value="408.19"></td><td id="InvoicesGridView_tccell28_4" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><table style="width:100%"><tbody><tr><td><input type="hidden" class="IsClosedPeriod" value="1"></td></tr><tr><td><a class="linkwithonclick-nocolor" data-open="/AccountingDev/CincSystem/apinvoice.asp?numInvoiceID=153628&amp;fromMVC=1" onclick="Edit('/AccountingDev/CincSystem/apinvoice.asp','153628')">10/27/2016</a></td></tr></tbody></table></td><td id="InvoicesGridView_tccell28_5" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;">&nbsp;</td><td id="InvoicesGridView_tccell28_6" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;">Inv-00153628</td><td id="InvoicesGridView_tccell28_7" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><span>$408.19</span></td><td id="InvoicesGridView_tccell28_8" class="dxGridCellWordBreak dxgv dx-ar" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="payamt153628" name="payamt153628" value="408.19"><span>$408.19</span></td><td id="InvoicesGridView_tccell28_9" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;"><input type="hidden" size="10" maxsize="10" id="status153628" name="status153628" value="-1"><span style="color:black">Pending Approval&nbsp;<a id="AApproval153628" class="linkwithonclick-nocolor disableNewTab" onclick="ShowApprovals(153628, this)">0/1</a></span><input type="hidden" id="assocId153628" name="assocId153628" value="322"><input type="hidden" id="payType153628" name="payType153628" value="-2"></td><td id="InvoicesGridView_tccell28_10" class="dxGridCellWordBreak dxgv" style="vertical-align:Top;border-right-width:0px;">Community Association Management, Limited</td>
	</tr><tr id="InvoicesGridView_DXPRow28" class="dxgvPreviewRow_CincAccounting dxgvLVR" style="background-color:#EDEDED;">

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
</script><img id="InvoicesGridView_IADD" class="dxGridView_gvDragAndDropArrowDown_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="|" style="position:absolute;visibility:hidden;top:-100px;"><img id="InvoicesGridView_IADU" class="dxGridView_gvDragAndDropArrowUp_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="|" style="position:absolute;visibility:hidden;top:-100px;"><img id="InvoicesGridView_IADL" class="dxGridView_gvDragAndDropArrowLeft_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="|" style="position:absolute;visibility:hidden;top:-100px;"><img id="InvoicesGridView_IADR" class="dxGridView_gvDragAndDropArrowRight_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="|" style="position:absolute;visibility:hidden;top:-100px;"><img id="InvoicesGridView_IDHF" class="dxGridView_gvDragAndDropHideColumn_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="Hide" style="position:absolute;visibility:hidden;top:-100px;"><script id="dxss_1197925173" type="text/javascript">
<!--
var dxo = ASPx.GetControlCollection().Get('InvoicesGridView');
dxo.SetProperties({
	'callBacksEnabled':true,
	'pageRowCount':29,
	'pageRowSize':10,
	'pageIndex':-1,
	'pageCount':3,
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