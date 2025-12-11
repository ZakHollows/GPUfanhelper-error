# GPUfanhelper-error

# Project Sumaary

This issue was brought to me by a colleague, with thier only comments being the GPU game ready driver recently updated. Started by restarting to see the error for code myself as it only appeared at the log in page or soon after. Updated drivers in background whilst looking online for sources of the error other users may have had. After using a troublshooting methods given online of verifying disk integrity, which found some corrupt files and repaired them, the error persisted. More research found the issue came from AI suite 3, and if uninstalled the error stopped. The update to the Nvidia game ready driver created a need for AI suite 3 to also update, which created the error messsage as it was unable to update due to incompatability with the motherboard. Motherboard was unable to update to a version AI suite 3 could communicate with due to the motherboards discontinued support. User only used AI suite 3 for fan control, Armoury crate was a suitable alternative instead of defaulting back to BIOS settings, and was already installed on the PC.

From this I learned how to narrow down what the issue was through online research and troubleshooting steps. And to be able to isolate it and identify what exactly the issue was and offer a solution that didnt impact the user.

# Ticket

Below is the steps taken from start to finish of diagnosis and completion of fixing an error code that appeared on PC start up.

GPUfanhelper error fast fail


Apon start up, either at log in screen or after logging in, error appears stating the following [error](https://github.com/ZakHollows/GPUfanhelper-error/blob/a68120a4f4259772ba965201a0f6e5ee022a0673/GPUfanhelper%20error%20.png)
This error appeared after Nvidia game ready driver updated, but has seemingly had no impact apon system for performance

# Diagnosis steps

- Restart system to see error message
- Update windows and drivers on system for GPU
- Error persists
- Research online for a similar issue to try and find source 
- Several sites suggestions to verify disk integrity, use command prompt sfc /scannow to find corrupted files.
- Use command console and type "sfc /scannow as" as shown in screen shot [Screenshot command console](https://github.com/ZakHollows/GPUfanhelper-error/blob/a68120a4f4259772ba965201a0f6e5ee022a0673/command%20console%20scannow.png)
- Log from scan showing some corrupt files, automatically fixed by scan [screenshot](https://github.com/ZakHollows/GPUfanhelper-error/blob/80540c5070898cf8ea59f76d5d32c3ce145555ce/Corrupt%20files%20log.png)
- Restart PC, error persists
- Further research into the source of the gpufanhelper error found it was not a core system, meaning it has to be an application/program. The research found it was an error other users have had with Asus AI suite 3. This program is meant to support the motherboard with updates, and functions such as fan control.
- Users reporting online that the error generated is from incompatability issues with the motherboard. This issue persists regardless of version of application used as requires the motherboard to have the compatability 
- Checked Asus sites for motherboard specs and compatability with ai suite 3 after using run box using command misinfo 32 to see full PC specs
- Confirmation that the motherboard in use, PRIME b760m-a wifi, is not compatible with ai suite 3
- Uninstall ai suite 3 and restart PC
- Error no long appears
- Fresh install of AI suite 3 after using ASUS cleaner tool to fully wipe ai suite 3 from system
- Restart PC
- Error reappears.
- Uninstall of AI suite 3 and using ASUS cleaner tool for full wipe
- Restart PC error no longer appears
- As a precautionary measure due to this error appearing after Nvdia game ready driver update, fresh install of this driver was completed using the following steps:
   - Nvdia game ready driver official website [Nvidia](https://www.nvidia.com/en-us/geforce/game-ready-drivers/)
   - Scroll down and click download for desktop
   - Once page has loaded click on "download now" on the newest released version, for this installation this was version "591.44 - WHQL"
   - Once download has completed click on file to initiate installation
   - During installation process, select custom installation instead of express installation [Screenshot](https://github.com/ZakHollows/GPUfanhelper-error/blob/6c9130b4492642828b3bb029ccd645a1aadeea54/Custom%20installation.png)
   - Click on "perform a clean installation" [Screenshot](https://github.com/ZakHollows/GPUfanhelper-error/blob/6c9130b4492642828b3bb029ccd645a1aadeea54/Clean%20Installation.png)
   - Following rest of installation instructions to finish
- Restart PC, ensure Nvdia app is working and showing newest version of game ready driver
- As a replacement software for AI suite 3, Armoury crate application has been used for fan control over BIOS settings for client ease of use. This application was previously installed and controlled the RGB for the system, and runs in the background apon start up.

# Cause for error

Recent update to Nvidia game ready driver caused an error to appear with AI suite 3 fan control. Whilst this issue was caused by the Nvidia update, the incompatability of AI suite 3 was highlighted because of the error and showed this to be the source of the issue. After uninstalling application error no longer appeared and system ran smoother and with better performance than before.


# Ticket closed
