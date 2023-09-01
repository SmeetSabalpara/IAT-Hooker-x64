# IAT-Hooker-x64

IAT Hooker is a tool that I recently developed to hook any function within the Import Address Table (IAT). It serves as a universal hooker designed for hooking x64 PE files with a custom DLL injector. IAT Hooking (T0874) is categorized as a Privilege Escalation and Execution tactic, as listed in the MITRE Enterprise framework.

# Using custom DLL

In the "task.dll" file replace the MessageBoxW function with your own code. Keep rest of the code as it is.

<img width="1440" alt="Screenshot 2023-09-01 at 8 24 06 AM" src="https://github.com/SmeetSabalpara/IAT-Hooker-x64/assets/59355395/1c06ca76-e24d-4c21-84d5-c12704570f40">
