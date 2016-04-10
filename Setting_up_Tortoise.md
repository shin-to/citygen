#Instructions to get up and running with Tortoise (mercurial) on Vista or Win7 64bit.

# Introduction #

This page describes how to set up TortoiseHg on 64bit Vista and Win7 (since that is tricky and most of us seem to be on those systems).  Tortoise is a graphical User interface for mercurial which is the software that we use to synchronize our code and work collaboratively from across the world.

## Step 1 - Install TortoiseHg ##

Download and install the .exe file here in the "uploads" section.<br><br>
<a href='http://bitbucket.org/tortoisehg/stable/downloads/'>http://bitbucket.org/tortoisehg/stable/downloads/</a><br><br>You'll have to reboot.<br>
<br>
<h2>Step 2 - Vista 64bit</h2>

Tortoise installs itself into the Explorer right click menu.  But it does not work with the 64 bit explorer.  So to use it, you must run the 32 bit explorer that comes with Vista.  And to make it easy, just set up a shortcut on your desktop to it.  Use these settings:<br><br>
<b>Target = %windir%\syswow64\explorer.exe /separate</b><br>
Start In = %windir%\syswow64<br><br>
Now Tortoise will work in that explorer.<br>
<br>
<h2>Step 2 - Win 7 64bit</h2>

The workaround listed above for Vista does not work with Win 7 unfortunately.<br><br>

You need to install <a href='http://www.freecommander.com/fc_downl_en.htm'>Free Commander</a> to get TortoiseHg to work.  FreeCommander is a File Explorer that can be used in place of the default one (which is good, because TortoiseHg does not work with the default 64bit File Browser at this point).  At this point, you should have TortoiseHg installed and Free commander.<br><br>

<h2>Step 3 - Everything Working?</h2>

So once you have the Free Commander installed, You should be able to rickght click on any file or folder and see a TortoiseHG menu.