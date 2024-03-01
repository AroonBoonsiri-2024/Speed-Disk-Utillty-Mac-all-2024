display dialog " (เปลี่ยนภาษาเป็นภาษาอังกฤษก่อน Run APP / Change the language to English before running the APP.)  " buttons {"OK"} default button "OK"
repeat 20 times
	do shell script "diskutil verifyVolume  / "
	delay 1
end repeat

display dialog "  ขอให้สนุกกับความเร็วที่ได้ สนับสนุนผู้พัฒนาได้  
( Enjoy unprecedented speed.  ) " buttons {"OK"} default button "OK"
tell application "Disk Utility" to activate
