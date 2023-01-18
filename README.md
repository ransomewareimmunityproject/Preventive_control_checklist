# Meet the state of art preventive control checklist
enable Attack Surface Reduction modules in Windows

enables network protection of Windows Defender


Disable all LOLBin binaries in Windows system32 and netframework


block modification of Windows services except default services of Windows


disable scheduled task creation


blocks executables compiled in debug mode from execution using applocker


block executables which are not signed from execution using applocker


block process from modification of autorun in registry using applocker


blocks cmd.exe


blocks powershell.exe


enable protected folder


script allow dll loading from program files directory only using applocker


script allow exe loading from program files directory only using applocker


blocks downloads in edge and internet explorer


Disable Remote Desktop


Send NTLMv2 response only/refuse LM and NTLM


Do not allow anonymous enumeration of SAM accounts and shares


Restrict Anonymous Access


Disable IE Password Cache


Disable Edge Password Cache


Run lsass.exe as protected process using GPO


Disable HTA using GPO


Disable remote sharing using GPO


prevent 16 bit exe using GPO


prohibit new task creation


Turn off windows installer


block exclusion path


harden SMB


Run only allowed exe


block .scr and .cab


Allow execution of signed powershell only from a specfic directory


block wsf , vbs , .bat


Disable DCOM


disable priviledged COM objects


disable UAC Auto Approved COM objects


make UAC always notify
