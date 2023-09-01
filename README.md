# IAT-Hooker-x64

IAT Hooker is a tool that I recently developed to hook any function within the Import Address Table (IAT). It serves as a universal hooker designed for hooking x64 PE files with a custom DLL injector. IAT Hooking (T0874) is categorized as a Privilege Escalation and Execution tactic, as listed in the MITRE Enterprise framework.

## Using custom fucntion

Steps for injecting your own functionality:

* Create a file named task.dll.
* Replace the MessageBoxW function with your own code. Keep rest of the code as it is.
* Make sure that 'task.dll', 'hookIAT.exe' and 'r_Src.dll' files are in the same directory.


<img width="1440" alt="Screenshot 2023-09-01 at 8 24 06 AM" src="https://github.com/SmeetSabalpara/IAT-Hooker-x64/assets/59355395/1c06ca76-e24d-4c21-84d5-c12704570f40">

## Demonstration 

https://www.linkedin.com/posts/smeetsabalpara_mitreattack-privilegeescalation-hooking-activity-7103064476840603648-NJpq?utm_source=share&utm_medium=member_desktop
