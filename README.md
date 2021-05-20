# Fixed_Wakfu_Files
This place hosts the fixed intel graphic driverfiles for wakfu 1.60 to get it running in system's with windows 10 on intel processors. 

The issue can be accessed here : https://www.wakfu.com/en/forum/327-1-59-bug-reports/233895-update-1-59-breaks-wakfu-client-pc-with-intel-integrated-graphics

I had the same issue so i went  around looking for solutions to get the game running on my system.

Original post from where i got the solution : https://github.com/LWJGL/lwjgl/issues/119#issuecomment-173983180

Required tool : https://github.com/LWJGL/lwjgl/files/1174591/Intel.HD.Graphics.Driver.Win10.32-bit.64-bit.Fix.by.MST.zip


Note : This procedure is aimed at Intel i3 based machines who has a display driver version above **15.22.58.64.2993 / 8.15.10.2993**

**| If your display driver version is below the one mentioned above, then please look up ways to upgrade your graphics drivers to the version mentioned above or higher before using the methods. Unless the drivers are above the version number mentioned, It has a very low chance of working. |**


    1. The Basic Required Drivers from Intel : Intel Graphics Media Accelerator Driver : http://bit.ly/Intel2993
    2. Driver Installation : How to Manually Install the Drivers : http://bit.ly/H2GMI
    3. Cannot Install the driver? : How to Install Unsigned Drivers in Windows : http://bit.ly/UnsignD


# Recommended Method :

Driver update and patching the files is the recommended way now. 

 Method After Updating the display drivers :

 Run the tool below to patch the files. (Ignore any error messages)

Requiredtool:https://github.com/LWJGL/lwjgl/files/1174591/Intel.HD.Graphics.Driver.Win10.32-bit.64-bit.Fix.by.MST.zip [Gives Virus warnings now. Updated version added.]

https://raw.githubusercontent.com/A-Charvin/Fixed_Wakfu_Files/master/intel.hd.graphics.driver.win10.fix.wakfu.-patch.zip


**Procedure for i3,i5 - Driver Version check / Manual installation**

1. Check graphics driver version, : How to check version
![image](https://user-images.githubusercontent.com/20741723/118933288-a6224a80-b966-11eb-8f7f-9a9a7a6c7437.png)

Check whether if it is lower than **15.22.58.64.2993 or 8.15.10.2993**
Proceed to the next steps if the version if it is lower
(_If it is higher then follow the patching guide above_)

2. Download the modified intel driver in zip format : [http://bit.ly/DWin2993

3. Attempt manual installation of the drives again following the same guide above. It should get installed.
4. Run the game, If it works fine then it's done, Else download the patch and patch the files and run wakfu.

# Welcome back to Wakfu.

P.S. This is a harmless procedure to your system. But be cautious just in case not to cause any other issues by tweaking the commands. Follow the procedure.
The tool might trigger some alarms in some av's. If that scares you, then just follow the reccomended method.
The Manual files, how ever is not generic so you have better luck with the patch any way.

# Updates :
Updated on 20/05/2021
