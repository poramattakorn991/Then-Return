# Then-Return
Func _IsEmptyFolder($sPath)     Local $s = FileFindFirstFile($sPath &amp; '\*')     If $s = -1 Then Return 1     FileClose($s)
