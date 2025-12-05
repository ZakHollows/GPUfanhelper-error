# GPUfanhelper-error

GPUfanhelper error fast fail

# Ticket
Apon start up error appears stating the following image

# Diagnosis steps
- Update Drivers for GPU, Nvidia game ready and AI suite 3
- Issue persists
- Research online for a similar issue to try and find source 
- Several sites suggestions to verify disk integrity, use command prompt sfk /scannow to find corrupted files.
- after a little more research finding out the gpufanhelper was not a core system, meaning it has to be an app. and further research found it was part of Asus ai suite 3. with further research indicating compatability issues with generations of motherboards
- checked Asus sites for motherboard specs and compatability with ai suite 3 after using run box using command misinfo 32 to see full PC specs
- uninstall ai suite 3 and restart PC
- error no long appears
- fresh install after using asus cleaner tool to fully wipe ai suite 3 from system
- restart PC
- error reappears. due to incompatibility issues, and recent nvidia game ready driver update creating new issue. whislt this could of been rolled back, the priority for gaming ability on pc was more important than fan control and some minor abilities of the ai suite 3. as a safety precaution redownloaded nvida game ready app and driver, using custom installation setting to select fresh install. And using Armourycrate application for future fan control above BIOS for ease of use, instead of needing to enter the BIOS each time to adjust fan settings
