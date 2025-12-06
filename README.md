# GPUfanhelper-error

GPUfanhelper error fast fail

# Ticket

Apon start up, either at log in screen or after logging in, error appears stating the following [error](https://github.com/ZakHollows/GPUfanhelper-error/blob/a68120a4f4259772ba965201a0f6e5ee022a0673/GPUfanhelper%20error%20.png)
This error appeared after Nvidia game ready driver updated, but has seemingly had no impact apon system for performance

# Diagnosis steps

- Update Drivers for GPU, Nvidia game ready driver via application
- Issue persists
- Research online for a similar issue to try and find source 
- Several sites suggestions to verify disk integrity, use command prompt sfc /scannow to find corrupted files.
- Use command console and type "sfc /scannow as" as shown in screen shot [Screenshot command console](https://github.com/ZakHollows/GPUfanhelper-error/blob/a68120a4f4259772ba965201a0f6e5ee022a0673/command%20console%20scannow.png)
- Log from scan showing some corrupt files, automatically fixed by scan [screenshot](https://github.com/ZakHollows/GPUfanhelper-error/blob/80540c5070898cf8ea59f76d5d32c3ce145555ce/Corrupt%20files%20log.png)
- Restart PC, error persists
- More research finding out the gpufanhelper was not a core system, meaning it has to be an application/program. Further research found it was an error other users have had with Asus AI suite 3. This program is meant to support the motherboard with updates, and functions such as fan control.
- Users reporting online that the error generated is from incompatability issues with the motherboard. This issue persists regardless of version of application used as requires the motherboard to have the compatability 
- Checked Asus sites for motherboard specs and compatability with ai suite 3 after using run box using command misinfo 32 to see full PC specs
- Confirmation that the motherboard in use, PRIME b760m-a wifi, is not compatible with ai suite 3
- Uninstall ai suite 3 and restart PC
- Error no long appears
- Fresh install of AI suite 3 after using ASUS cleaner tool to fully wipe ai suite 3 from system
- Restart PC
- Error reappears.
- Uninstall of AI suite 3 and using ASUS cleaner tool for full wipe
- Due to incompatibility issues, and recent nvidia game ready driver update creating new issue. whislt this could of been rolled back, the priority for gaming ability on pc was more important than fan control and some minor abilities of the ai suite 3. as a safety precaution redownloaded nvida game ready app and driver, using custom installation setting to select fresh install. And using Armourycrate application for future fan control above BIOS for ease of use, instead of needing to enter the BIOS each time to adjust fan settings

- Log from scan showing some corrupt files, automatically fixed by scan [screenshot](https://github.com/ZakHollows/GPUfanhelper-error/blob/80540c5070898cf8ea59f76d5d32c3ce145555ce/Corrupt%20files%20log.png)
  
