# Indirect-Syscall-Shellcode-Executon-via-Powershell
meh why not do malicious shit not detected by amsi

small explanation
any exe can be turned into shellcode meaning you can hardcode a exe into this and run malicious code undetected by any antivirus



Versions
1. Explorer (injects into explorer.exe)
2. Self (injects into itself)


amsi somehow doesnt catch onto this the next step for me is dll unhooking

# TODO 

ill make it adaptive so like it doesnt get fucked when your dumbass swaps out the shellcode but forgets to swap out the parameters

# Answering questions
🤓: erm this will get detected by defender when loaded into memory
Obfuscate it same goes for the 2 antivirus that actually properly scan powershell code
🤓: erm but it will get detected by memory scans
this is beta code ill so dll unhooking using powershell soon for self injection code
