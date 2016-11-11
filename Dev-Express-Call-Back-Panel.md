### Dev Express Callback Panel with Combo Box:

<div class="dxpnlControl_CincAccounting" id="ComboBoxPanel">
<input type="hidden" name="corrTemplateID$State" id="corrTemplateID_State" value="{&amp;quot;rawValue&amp;quot;:&amp;quot;&amp;quot;}"><table class="dxeButtonEditSys dxeButtonEdit_CincAccounting dxeNullText_CincAccounting dxh0" id="corrTemplateID" style="width:96%;" savedspellcheck="[object Object]" spellcheck="false">
	<tbody><tr>
		<td style="display:none;"><input id="corrTemplateID_VI" name="corrTemplateID_VI" type="hidden"></td><td class="dxic" onmousedown="return ASPx.DDDropDown('corrTemplateID', event)" style="width:100%;"><input class="dxeEditArea_CincAccounting dxeEditAreaSys dxh0" id="corrTemplateID_I" name="corrTemplateID" onfocus="ASPx.EGotFocus('corrTemplateID')" onblur="ASPx.ELostFocus('corrTemplateID')" onchange="ASPx.ETextChanged('corrTemplateID')" value="(Select a Template)" type="text" autocomplete="off" savedspellcheck="[object Object]" spellcheck="false"></td><td id="corrTemplateID_B0" class="dxeButton dxeButtonEditButton_CincAccounting" onclick="ASPx.BEClick('corrTemplateID',0)">Go</td><td id="corrTemplateID_B-1" class="dxeButton dxeButtonEditButton_CincAccounting" onmousedown="return ASPx.DDDropDown('corrTemplateID', event)" style="-webkit-user-select:none;"><img id="corrTemplateID_B-1Img" class="dxEditors_edtDropDown_CincAccounting" src="/AccountingDev/DXR.axd?r=1_35-pHoKd" alt="v"></td>
	</tr>
</tbody></table><input type="hidden" name="corrTemplateID$DDDState" id="corrTemplateID_DDD_State" value="{&amp;quot;windowsState&amp;quot;:&amp;quot;0:0:-1:0:0:0:-10000:-10000:1:0:0:0&amp;quot;}"><div id="corrTemplateID_DDD_PW-1" class="dxpcDropDown_CincAccounting dxpclW dxpc-ddSys" style="width:0px;cursor:default;z-index:10000;display:none;visibility:hidden;">
	<div class="dxpc-mainDiv dxpc-shadow">
		<div class="dxpc-contentWrapper">
			<div class="dxpc-content" id="corrTemplateID_DDD_PWC-1">
				<input type="hidden" name="corrTemplateID$DDD$L$State" id="corrTemplateID_DDD_L_State" value="{&amp;quot;CustomCallback&amp;quot;:&amp;quot;&amp;quot;}"><table class="dxeListBox_CincAccounting" id="corrTemplateID_DDD_L" style="border-collapse:separate;">
					<tbody><tr>
						<td style="vertical-align:Top;"><div id="corrTemplateID_DDD_L_D" class="dxlbd" style="width:100%;overflow-x:hidden;overflow-y:auto;">
							<input id="corrTemplateID_DDD_L_VI" type="hidden" name="corrTemplateID$DDD$L" value=""><table style="border-collapse:separate;visibility:hidden!important;display:none!important;">
								<tbody><tr id="corrTemplateID_DDD_L_LBI-1" class="dxeListBoxItemRow_CincAccounting">
									<td id="corrTemplateID_DDD_L_LBI-1T0" class="dxeListBoxItem_CincAccounting">&nbsp;</td>
								</tr>
							</tbody></table><table id="corrTemplateID_DDD_L_LBT" style="width:100%;border-collapse:separate;">
								<tbody><tr class="dxeListBoxItemRow_CincAccounting">
									<td class="dxeListBoxItem_CincAccounting" id="corrTemplateID_DDD_L_LBI0T0">Megha</td>
								</tr><tr class="dxeListBoxItemRow_CincAccounting">
									<td class="dxeListBoxItem_CincAccounting" id="corrTemplateID_DDD_L_LBI1T0">Sample</td>
								</tr><tr class="dxeListBoxItemRow_CincAccounting">
									<td class="dxeListBoxItem_CincAccounting" id="corrTemplateID_DDD_L_LBI2T0">Test</td>
								</tr><tr class="dxeListBoxItemRow_CincAccounting">
									<td class="dxeListBoxItem_CincAccounting" id="corrTemplateID_DDD_L_LBI3T0">Test CCA273</td>
								</tr><tr class="dxeListBoxItemRow_CincAccounting">
									<td class="dxeListBoxItem_CincAccounting" id="corrTemplateID_DDD_L_LBI4T0">What a Bug !!</td>
								</tr>
							</tbody></table>
						</div></td>
					</tr>
				</tbody></table><script id="dxss_825332699" type="text/javascript">
<!--
ASPx.AddDisabledItems('corrTemplateID_DDD_L',[[['dxeDisabled_CincAccounting'],[''],['']]]);

var dxo = new ASPxClientListBox('corrTemplateID_DDD_L');
dxo.InitGlobalVariable('corrTemplateID_DDD_L');
dxo.SetProperties({
	'uniqueID':'corrTemplateID$DDD$L',
	'stateObject':{'CustomCallback':''},
	'itemsValue':['9164','9041','9163','9167','9165'],
	'isComboBoxList':true,
	'hasSampleItem':true,
	'hoverClasses':['dxeListBoxItemHover_CincAccounting'],
	'selectedClasses':['dxeListBoxItemSelected_CincAccounting'],
	'disabledClasses':['dxeDisabled_CincAccounting']
});
dxo.SetEvents({
	'SelectedIndexChanged':function (s, e) { ASPx.CBLBSelectedIndexChanged('corrTemplateID', e); },
	'ItemClick':function (s, e) { ASPx.CBLBItemMouseUp('corrTemplateID', e); }
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
</div><script id="dxss_432161149" type="text/javascript">
<!--
ASPx.AddHoverItems('corrTemplateID_DDD',[[['dxpc-closeBtnHover'],[''],['HCB-1']]]);

var dxo = new ASPxClientPopupControl('corrTemplateID_DDD');
dxo.InitGlobalVariable('corrTemplateID_DDD');
dxo.SetProperties({
	'uniqueID':'corrTemplateID$DDD',
	'adjustInnerControlsSizeOnShow':false,
	'popupAnimationType':'slide',
	'closeAction':'CloseButton',
	'popupHorizontalAlign':'LeftSides',
	'popupVerticalAlign':'Below'
});
dxo.SetEvents({
	'Shown':function (s, e) { ASPx.DDBPCShown('corrTemplateID', e); }
});
dxo.AfterCreate();

//-->
</script><script id="dxss_102499374" type="text/javascript">
<!--
ASPx.AddHoverItems('corrTemplateID',[[['dxeButtonEditButtonHover_CincAccounting'],[''],['B0','B-1']]]);
ASPx.RemoveHoverItems('corrTemplateID',[[['B-100']]]);
ASPx.AddPressedItems('corrTemplateID',[[['dxeButtonEditButtonPressed_CincAccounting'],[''],['B0','B-1']]]);
ASPx.RemovePressedItems('corrTemplateID',[[['B-100']]]);
ASPx.AddDisabledItems('corrTemplateID',[[['dxeDisabled_CincAccounting'],[''],['','I']],[['dxeDisabled_CincAccounting dxeButtonDisabled_CincAccounting'],[''],['B0','B-1'],,[[null],[{'spriteCssClass':'dxEditors_edtDropDownDisabled_CincAccounting'}]],['Img']]]);
ASPx.RemoveDisabledItems('corrTemplateID',[[['B-100'],]]);

var dxo = new MVCxClientComboBox('corrTemplateID');
dxo.InitGlobalVariable('corrTemplateID');
dxo.SetProperties({
	'stateObject':{'rawValue':''},
	'nullText':'(Select a Template)',
	'autoCompleteAttribute':{'name':'autocomplete','value':'off'},
	'buttonCount':1,
	'lastSuccessValue':null,
	'islastSuccessValueInit':true
});
dxo.SetEvents({
	'ButtonClick':loadTemplate
});
dxo.InitializeProperties({
	'decorationStyles':[
		{'key':'F','className':'dxeFocused_CincAccounting','cssText':''},
		{'key':'N','className':'dxeNullText_CincAccounting','cssText':''}
	]
});
dxo.AfterCreate();

//-->
</script>
</div>