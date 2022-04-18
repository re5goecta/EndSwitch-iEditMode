# EndSwitch-iEditMode
MsgBox(0, "Right", "Empty Array") EndIf Case $cCombo_Row Switch GUICtrlRead($cCombo_Row) Case 0 GUICtrlSetData($cCombo_Col, 0) Case Else If GUICtrlRead($cCombo_Col) = 0 Then GUICtrlSetData($cCombo_Col, GUICtrlRead($cCombo_Row)) EndIf EndSwitch $iEditMode = Number(GUICtrlRead($cCombo_Row) &amp; GUICtrlRead($cCombo_Col)
