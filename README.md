# oscp-exam-cheatsheet
OSCP Exam Cheat Sheet 
Updated 2020

                                            |All usefull commands and scripts for exam| 
                                             
                                            Enumeration(BEST). Thanks for Tib3rius for awesome project
 https://github.com/Tib3rius/AutoRecon - This project safe my life))
 https://github.com/21y4d/nmapAutomator
 ------------------------------------------------------------------------------------------------------------------------------                                       
                                                Windows PrivEsc Scripts 
https://github.com/PowerShellEmpire/PowerTools/blob/master/PowerUp/PowerUp.ps1
https://github.com/rasta-mouse/Sherlock/blob/master/Sherlock.ps1
------------------------------------------------------------------------------------------------------------------------------
                                                 Linux PrivEsc Scripts(Best)
https://github.com/diego-treitos/linux-smart-enumeration
 ------------------------------------------------------------------------------------------------------------------------------
                                            
                                                 WEB APP
 	Wfuzz - The web brute forcer
	• wfuzz -c -w /usr/share/wfuzz/wordlist/general/megabeast.txt $ip:60080/?FUZZ=test
	• wfuzz -c --hw 114 -w /usr/share/wfuzz/wordlist/general/megabeast.txt $ip:60080/?page=FUZZ
	• wfuzz -c -w /usr/share/wfuzz/wordlist/general/common.txt "$ip:60080/?page=mailer&mail=FUZZ"
	• wfuzz -c -w /usr/share/seclists/Discovery/Web_Content/common.txt --hc 404 $ip/FUZZ
	Recurse level 3
  wfuzz -c -w /usr/share/seclists/Discovery/Web_Content/common.txt -R 3 --sc 200 $ip/FUZZ
 ------------------------------------------------------------------------------------------------------------------------------
