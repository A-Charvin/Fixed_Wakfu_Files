# Fixed_Wakfu_Files
This place hosts the fixed opengl files for wakfu 1.60 to get it running in system's with windows 10 on intel processors. 

The issue can be accessed here : https://www.wakfu.com/en/forum/327-1-59-bug-reports/233895-update-1-59-breaks-wakfu-client-pc-with-intel-integrated-graphics

I had the same issue so i went  around looking for solutions to get the game running on my system.

Original post from where i got the solution : https://github.com/LWJGL/lwjgl/issues/119#issuecomment-173983180

Required tool : https://github.com/LWJGL/lwjgl/files/1174591/Intel.HD.Graphics.Driver.Win10.32-bit.64-bit.Fix.by.MST.zip.

Recommended Method :

1. Open CMD as Admin (Windows + X --> Command Prompt (Admin))
2.  paste this line into the cmd and press enter.

`copy C:\WINDOWS\system32\ig4icd64.dll C:\WINDOWS\SysWOW64\ig4icd64.dll`

3. Run the tool above to patch the files. (Ignore any error messages)
4. Paste this line after patching is done into cmd.

`copy C:\WINDOWS\SysWOW64\ig4icd64.dll C:\WINDOWS\system32\ig4icd64.dll` .


Manual Method :

If you don't want to go through the steps above, then just extract the archive and copy paste the files into System32 and SysWOW64 folders.

Files : https://goo.gl/gE7m58

Launch the game from the client and it should be running fine. 
Welcome back once again to wakfu.

P.S. This is a harmless procedure to your system. But be cautious just in case not to cause any other issues by tweaking the commands. Follow the procedure.
