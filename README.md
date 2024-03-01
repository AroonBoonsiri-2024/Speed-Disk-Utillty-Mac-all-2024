# Speed-Disk-Utillty-Mac-all-2024 


display dialog " (เปลี่ยนภาษาเป็นภาษาอังกฤษก่อน Run APP / Change the language to English before running the APP.)  " buttons {"OK"} default button "OK"
repeat 20 times
	do shell script "diskutil verifyVolume /"
	delay 1
end repeat

display dialog "  ขอให้สนุกกับความเร็วที่ได้ สนับสนุนผู้พัฒนาได้  เลขบัญชี 136-1-81187-5 กสิกรไทย ผู้พัฒนา นาย อรุณ บุญศิริ Aroon Boonsiri 
( Enjoy unprecedented speed. Can support the developer: Kasikorn Bank : Bank of Thailand , account number 136-1-81187-5, developer Mr. Aroon Boonsiri, ) " buttons {"OK"} default button "OK"
tell application "Disk Utility" to activate
