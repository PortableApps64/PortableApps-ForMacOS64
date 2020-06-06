<b>PORTABLE FIREFOX OSX script</b><br/>

A 'script' To Run "Firefox.app" As an OSX PortableApps in macOSX,<br/>
by updating it to use 64bit Pashua dialog, 64bit Platypus, etc<br/>
for both 64bit-only macOSX & also for 64+32bit macOSX.<br/>

&#160;&#160;FF = Firefox , a web-browser from Mozilla Foundation.

<b>OLD SCRIPT:</b><br/>
Original & Last 'script' v4.1 is here: http://www.FreeSMUG.org/portableapps:code:firefox<br/>
( You can also check 1st commit of this 'script' file in Github to view the v4.1 code )<br/>
The 'script' v4.1 was written by Carlo Gandolfi, and, Paolo Portaluri, Copyright 2010,<br/>
Released under GPL v3.<br/>
Project SF page: https://SourceForge.net/projects/osxportableapps/<br/>
Portable Firefox OSX is here:<br/>
https://SourceForge.net/projects/osxportableapps/files/Portable%20Firefox%20OS%20X/<br/>
The 'script' v4.1 is now distributed via a ZIP file located here:<br/>
https://prdownloads.SourceForge.net/osxportableapps/PortableFirefoxScript_r4.1.txt.zip?download<br/>
Last "Portable Firefox OSX" app: "PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg", 28.2 MBytes,<br/>
&#160;&#160;sha1: 50ff626452dfadb9cbb6a2a5e2ddf60848adf256,<br/>
&#160;&#160;md5: fa6691336e22a2d83e5629533b830300.<br/>
&#160;&#160;https://SourceForge.net/projects/osxportableapps/files/Portable%20Firefox%20OS%20X/4.0.1%20r4.1/<br/>
Website: http://www.FreeSMUG.org/<br/>
<br/>


<b>WHAT TYPE OF 'script' FILE:</b><br/>
The '<b>script</b>' is a bash shell script file, Executable file.<br/>
<br/>


<b>NEW SCRIPT:</b><br/>
New 'script' v4.1.x Are released under below License + Restrictions + Permissions:<br/>
 - GNU General Public License Version 3  (GPL v3)<br/>
 - Do Not Use My+Our Contributions To Kill/Harm(or Steal from) (Any) Human/Community/Earth/etc<br/>
New 'script' v4.1.x are: Copyright 2020 by Erik T Ashfolk - <atErik at Out Look dot com><br/>

This 'script' v4.1/v4.1.x file is usually used from such (i.e) location, in macOSX:<br/>
&#160;&#160;"/MyPortableDrive/PortableApps/FF_for_Test/Portable Firefox OS X/Portable Firefox.app/Contents/Resources/script"<br/>

This 'script' v4.1/v4.1.x is (i.e) used by the below binary "Portable Firefox" executable file:<br/>
&#160;&#160;"/MyPortableDrive/PortableApps/FF_for_Test/Portable Firefox OS X/Portable Firefox.app/Contents/MacOS/Portable Firefox"<br/>

The binary "Portable Firefox" is created by Platypus,<br/>
Platypus also creates the "Portable Firefox.app" bundle.<br/>
<br/>


<b>PLATYPUS:</b><br/>
The "Portable Firefox.app" is packaged using the Platypus script wrapper (aka app builder)<br/>
from http://sveinbjorn.sytes.net/platypus<br/>
&#160;&#160;New website:  https://Sveinbjorn.org/platypus<br/>
&#160;&#160;GitHub: https://GitHub.com/sveinbjornt/Platypus<br/>
Platypus seems to be able to generate 64bit-only app bundles,<br/>
but it does not (digitally) sign or provide option to sign the generated app bundle,<br/>
so an Admin level privileged user can use+run generated apps,<br/>
in 64bit-only macOSX(Catalina/...)<br/>
<br/>


<b>COCOA-DIALOG:</b><br/>
The OSX PortableApps used CocoaDialog (.app bundle)<br/>
inside "PortableFirefoxOSX" v4.0.1 (the last/old release)<br/>

But (old) CocoaDialog is not 64bit-only macOSX compatible yet afaik.<br/>
&#160;&#160;Website: https://CocoaDialog.com/<br/>

So Apps/DMG bundled with old CocoaDialog cannot run on 64bit-only macOSX (Catalina/...)<br/>
And apps built/wrapped with older Platypus also cannot run in 64bit-only macOSX,<br/>
as old Platypus was not fully 64bit compatible.<br/>

So we must change existing dialog (a program to assist interaction<br/>
between user & script) functions, into something else.<br/>
<br/>


<b>PASHUA:</b><br/>
Pashua dialog seems to be a good choice for now for this.<br/>
&#160;&#160;Website: https://www.BlueM.net/en/projects/pashua/<br/>
&#160;&#160;Github: https://GitHub.com/BlueM/Pashua<br/>
<br/>


<b>PRE-BUILD: BRING TOGETHER BUILD-RELATED ITEMS/OBJECTS,ETC:</b><br/>
Suppose, we are working-on/building this project from below example folder:<br/>
&#160;&#160;"/System/Volumes/Data/MyProjects/PortableFirefox/"<br/>
&#160;&#160;( alternatively you may/can also create a developement folder "PortableFirefox" here:<br/>
&#160;&#160;&#160;"/Users/MyUserName/MyProjects/PortableFirefox/" )<br/>
When Platypus generates the "Portable Firefox OSX.app" bundle, it places the bundle here:<br/>
&#160;&#160;"/System/Volumes/Data/MyProjects/PortableFirefox/Portable Firefox OSX.app"<br/>
To build with Platypus, we will have to choose (various needed files, directories<br/>
& bundles, etc from above location), inside the Platypus GUI interface/settings,<br/>
then Platypus will place them inside below folder location:<br/>
&#160;&#160;"/System/Volumes/Data/MyProjects/PortableFirefox/Portable Firefox OSX.app/Contents/Resources/"<br/>

So obtain NEW Platypus (at the time of writing this README.md, it is/was v5.3),<br/>
from here: https://Sveinbjorn.org/platypus<br/>
and install in your (64bit-only macOSX(Catalina/...) based) mac computer.<br/>
Or get Platypus v4.9, as that is the last 32bit supported ( & working) Platypus,<br/>
to build/wrap macOS apps in 64bit+32bit suppported macOSX (Mojave & earlier).<br/>

Obtain Pashua dialog from here : https://www.BlueM.net/en/projects/pashua/<br/>
Open dmg installer, Copy "Pashua.app", "Pashua.sh" into below folder:<br/>
&#160;&#160;"/System/Volumes/Data/MyProjects/PortableFirefox/"<br/>
&#160;&#160;( or here: "/Users/MyUserName/MyProjects/PortableFirefox/" )<br/>

Get last Gecko-based old "Firefox*.dmg" (which has old "Firefox.app" inside it) from below URLs,<br/>
or Get last Quantum/Servo-based new "Firefox*.dmg" from https://www.Mozilla.org/<br/>
& extract/get/copy the "Firefox.app", & place/paste it into below folder:<br/>
&#160;&#160;"/System/Volumes/Data/MyProjects/PortableFirefox/"<br/>
&#160;&#160;( or here: "/Users/MyUserName/MyProjects/PortableFirefox/" )<br/>
The last security-updated gecko-based non-ESR old Firefox:<br/>
&#160;&#160;FF v56.0.2 dmg file's sha1: 79a0013664134ced2307c8e1ffa5d36f6256e8f,<br/>
&#160;&#160;md5: a5608df45832df3ff302a7ccbe7ec3f6, 54.5 MBytes,<br/>
&#160;&#160;https://ftp.Mozilla.org/pub/firefox/releases/56.0.2/<br/>
The last gecko-based old Firefox-ESR:<br/>
&#160;&#160;FF v52.9.0 ESR dmg file's sha1: d879f5423d79393f2384e0f97a5581f9d89d7977,<br/>
&#160;&#160;md5: 34e8280bb9b33ca202ba22cf9daf25e4, 82.8 MBytes,<br/>
&#160;&#160;https://ftp.Mozilla.org/pub/firefox/releases/52.9.0esr/<br/>
ESR = Extended Support Release<br/>
<br/>

Extract/Obtain two directories "English.lproj" & "profile" from<br/>
old Portable Firefox OSX "PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg" file<br/>
(download link is shown few-paragraphs above)<br/>
and then you would need to get/extract the "Portable Firefox.app" bundle<br/>
from inside that "PortableFirefox_4.0.1_*.dmg" file,<br/>
Those 2-folders are located inside "Resources" folder shown here:<br/>
&#160;&#160;Portable Firefox.app/Contents/Resources/<br/>
Or, obtain those 2-folders from your existing old "Portable Firefox OSX"<br/>
that you use/run from your portable/external drive.<br/>
Copy/Paste those 2-folders into below destination pre-build folder:<br/>
&#160;&#160;"/System/Volumes/Data/MyProjects/PortableFirefox/"<br/>
&#160;&#160;( or "/Users/MyUserName/MyProjects/PortableFirefox/" )<br/>
<br/>


<b>BUILD/WRAP/GENERATE WITH PLATYPUS:</b><br/>
Build the final "PortableAppName.app" bundle:<br/>
To build new "Portable Firefox.app",<br/>
choose these below files, directories, bundles inside Platypus GUI interface:<br/>
directory : English.lproj<br/>
directory : profile<br/>
bundle : Firefox.app<br/>
bundle : Pashua.app<br/>
icon-file : P_Firefox_Caution.icns<br/>
icon-file : appIcon.icns<br/>
sh-script-file : pashua.sh<br/>
sh-script-file : script<br/>

Then i'm currently using these type of settings in Platypus GUI interface:<br/>
&#160;&#160;Script Type : Shell : /bin/sh<br/>
&#160;&#160;Script Path : /System/Volumes/Data/MyProjects/PortableFirefox/script<br/>
&#160;&#160;Interface : Text Window<br/>
&#160;&#160;Unselected options : Run with root privileges , Run in background , Accept dropped items<br/>
&#160;&#160;Selected/Check-Marked options : Remain running after execution<br/>
&#160;&#160;Fill in other boxes: app name, identifier, author, etc
Then tap/click/select/press "Create App" button.<br/>
It will create/generate a new "Portable Firefox.app", that is<br/>
compatible with 64-only macOSX(Catalina/...)<br/>
<br/>


<b>ERRORs/PROBLEMs:</b><br/>
Write down what error(s) you're getting, let us know in FreeSMUG forum:<br/>
&#160;&#160;http://www.FreeSMUG.org/forum/t-13404441/<br/>


<b>HELP TO BUILD:</b><br/>
Please help+contribute+collaborate+improve+rectify codes<br/>
to build this 'script' (a bash shell code).<br/>
Thanks in advance.<br/>
