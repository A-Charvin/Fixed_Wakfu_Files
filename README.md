# Fixed_Wakfu_Files
This place hosts the fixed intel graphic driverfiles for wakfu 1.60 to get it running in system's with windows 10 on intel processors. 

The issue can be accessed here : https://www.wakfu.com/en/forum/327-1-59-bug-reports/233895-update-1-59-breaks-wakfu-client-pc-with-intel-integrated-graphics

I had the same issue so i went  around looking for solutions to get the game running on my system.

Original post from where i got the solution : https://github.com/LWJGL/lwjgl/issues/119#issuecomment-173983180

Required tool : https://github.com/LWJGL/lwjgl/files/1174591/Intel.HD.Graphics.Driver.Win10.32-bit.64-bit.Fix.by.MST.zip

# Recommended Method :

The cleanest way to get Java x64 OpenGL programs working: just install this shim with double-click on the .cmd file after extracting the zip archive. That's all. No DLL patching needed. Admin privileges are requested at launch so no run as admin is needed.

For both 32 bit and 64 Bit : https://github.com/LWJGL/lwjgl/files/1774275/legacy-igpu.zip

# Manual Method :

If you don't want to go through the steps above, then just extract the archive and copy paste the files into WINDOWS/system32 and Windows/SysWOW64 folders.
Files : https://goo.gl/gE7m58 <- Not Generic

# Alternate Method :

1. Open CMD as Admin (Windows + X --> Command Prompt (Admin))
2.  Paste this line into the cmd and press enter.

`copy C:\WINDOWS\system32\ig4icd64.dll C:\WINDOWS\SysWOW64\ig4icd64.dll`

3. Run the tool below to patch the files. (Ignore any error messages)

Requiredtool:https://github.com/LWJGL/lwjgl/files/1174591/Intel.HD.Graphics.Driver.Win10.32-bit.64-bit.Fix.by.MST.zip [Gives Virus warnings now. Updated version added.]

https://raw.githubusercontent.com/A-Charvin/Fixed_Wakfu_Files/master/intel.hd.graphics.driver.win10.fix.wakfu.-patch.zip

4. Paste this line after patching is done into cmd.

`copy C:\WINDOWS\SysWOW64\ig4icd64.dll C:\WINDOWS\system32\ig4icd64.dll`

Launch the game from the client and it should be running fine. 

# Welcome back to Wakfu.

P.S. This is a harmless procedure to your system. But be cautious just in case not to cause any other issues by tweaking the commands. Follow the procedure.
The tool might trigger some alarms in some av's. If that scares you, then just follow the reccomended method.
The Manual files, how ever is not generic so you have better luck with the patch any way.

# Updates :
Title from 1.59 to 1.60
Alternate and Recommended methods swapped for easy implementation. 
