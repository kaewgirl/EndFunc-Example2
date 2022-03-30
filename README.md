# EndFunc-Example2
   GUICtrlCreateButton("say hi", 8, 8)     GUICtrlSetOnEvent(-1, "GuiTwoSayHi")     GUISetState(@SW_SHOW)      While 1 ; Loop until the user exits.         Sleep(100)         If $iExitLoop Then ExitLoop     WEnd     $iExitLoop = 0     GUIDelete($hGUIParent2) EndFunc   ;==>Example2   Func OnEvent_CLOSE_ONE()     ConsoleWrite('- Func OnEvent_CLOSE_ONE()' &amp; @CRLF)
