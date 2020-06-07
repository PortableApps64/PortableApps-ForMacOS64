<b>PORTABLE FIREFOX OSX script</b><br/>
<br/>

A 'script' To Run "Firefox.app" As an OSX PortableApps, From Inside the<br/>
"Portable AppName.app" bundle in MacOSX.  So We Are ( Working-On & Developing & )<br/>
Modifying & Updating This 'script' To Include/Use 64bit Pashua dialog, 64bit Platypus,<br/>
etc To Execute/Run it On Both 64bit-Only macOSX & Also On 64bit+32bit macOSX.<br/>
Codes From This New-'script' Can Also Be Modified/Applied/Used With Any Other<br/>
"OSX Portable Apps".
<br/>

<center><table border="0" width="90%" cellspacing="0px" align="center" style="border-collapse:collapse!important; border-spacing:0px!important; width:90%!important; broder:0px; border-width:0px!important; border-style:none!important;"><tr><td style="border-left:0px!important; border-top:0px!important; border-bottom:0px!important; border-top-style:none!important; border-bottom-style:none!important; border-left-style:none!important;">&#160;</td><td>FF = Firefox . A web-browser from Mozilla Foundation.<br/>
PA = Portable Apps . Ususally run from an External/Portable drives/storage.<br/>
OS = Operating System . A collection/set of vast numbers+types of programs, to assist interactions between User and computer hardwares & softwares.<br/>
OSX = macOS X . An OS from Apple, Inc.<br/>
Win = Windows OS . An OS from Microsoft corp.</td></tr></table></center><br/>

<b>OLD SCRIPT:</b><br/>
Original & Last 'script' v4.1 is here: http://www.FreeSMUG.org/portableapps:code:firefox<br/>
( You can also check 1st commit of this 'script' file in Github to view the v4.1 code )<br/>
The 'script' v4.1 was written by Carlo Gandolfi, and, Paolo Portaluri, Copyright 2010,<br/>
Released under GPL v3.<br/>
Project's SF page: https://SourceForge.net/projects/osxportableapps/<br/>
Portable Firefox OSX is here:<br/>
https://SourceForge.net/projects/osxportableapps/files/Portable%20Firefox%20OS%20X/<br/>
The 'script' v4.1 is now distributed via a ZIP file located here:<br/>
https://prdownloads.SourceForge.net/osxportableapps/PortableFirefoxScript_r4.1.txt.zip?download<br/>
Last "Portable Firefox OSX" app: "PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg", 28.2 MBytes,<br/>
&#160;&#160; sha1: 50ff626452dfadb9cbb6a2a5e2ddf60848adf256,<br/>
&#160;&#160; md5: fa6691336e22a2d83e5629533b830300.<br/>
&#160;&#160; https://SourceForge.net/projects/osxportableapps/files/Portable%20Firefox%20OS%20X/4.0.1%20r4.1/<br/>
Website: http://www.FreeSMUG.org/<br/>
<br/>


<b>WHAT TYPE OF 'script' FILE:</b><br/>
The '<b>script</b>' is a bash shell script file, Executable file.<br/>
<br/>


<b>NEW SCRIPT:🆕</b><br/>
New 'script' v4.1.x Are released under below Licenses + Restrictions + Permissions:<br/>
&#160;&#160; - GNU General Public License Version 3  (GPL v3)<br/>
&#160;&#160; - Do Not Use This To Kill/Harm (or Steal from) (Any) Human/Community/Earth/etc<br/>
New 'script' v4.1.x are: Copyright 2020 by Erik T Ashfolk - &lt;atErik＠OutLꝏk·ⓒⓞⓜ&gt;(＠=@,ꝏ=oo,·=.,ⓒ=c,ⓞ=o,ⓜ=m)<br/>

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
&#160;&#160; New website:  https://Sveinbjorn.org/platypus<br/>
&#160;&#160; GitHub: https://GitHub.com/sveinbjornt/Platypus<br/>
Platypus seems to be able to generate 64bit-only app bundles,<br/>
but it does not (digitally) sign or provide option to sign the generated app bundle,<br/>
so an Admin level privileged user can use+run generated apps,<br/>
in 64bit-only macOSX(Catalina/...)<br/>
<br/>


<b>COCOA-DIALOG:</b><br/>
The OSX PortableApps used CocoaDialog (.app bundle)<br/>
inside "PortableFirefoxOSX" v4.0.1 (the last/old release)<br/>

But (old) CocoaDialog is not 64bit-only macOSX compatible yet afaik.<br/>
&#160;&#160; Website: https://CocoaDialog.com/<br/>

So Apps/DMG bundled with old CocoaDialog cannot run on 64bit-only macOSX (Catalina/...)<br/>
And apps built/wrapped with older Platypus also cannot run in 64bit-only macOSX,<br/>
as old Platypus was not fully 64bit compatible.<br/>

So we must change existing dialog (a program to assist interaction<br/>
between user & script) functions, into something else.<br/>
<br/>


<b>PASHUA:</b><br/>
Pashua dialog seems to be a good choice for now for this.<br/>
&#160;&#160; Website: https://www.BlueM.net/en/projects/pashua/<br/>
&#160;&#160; Github: https://GitHub.com/BlueM/Pashua<br/>
<br/>


<b>PRE-BUILD: BRING TOGETHER BUILD-RELATED ITEMS/OBJECTS,ETC:</b><br/>
Suppose, we are working-on/building this project from below example folder:<br/>
&#160;&#160; `"/System/Volumes/Data/MyProjects/PortableFirefox/"`<br/>
&#160;&#160; ( alternatively you may/can also create a developement folder "PortableFirefox" here:<br/>
&#160;&#160;&#160; `"/Users/MyUserName/MyProjects/PortableFirefox/"` )<br/>
When Platypus generates the "Portable Firefox OSX.app" bundle, it places the bundle here:<br/>
&#160;&#160; `"/System/Volumes/Data/MyProjects/PortableFirefox/Portable Firefox OSX.app"`<br/>
To build with Platypus, we will have to choose (various needed files, directories<br/>
& bundles, etc from above location), inside the Platypus GUI interface/settings,<br/>
then Platypus will place them inside below folder location:<br/>
&#160;&#160; `"/System/Volumes/Data/MyProjects/PortableFirefox/Portable Firefox OSX.app/Contents/Resources/"`<br/>

So obtain NEW Platypus (at the time of writing this README.md, it is/was v5.3),<br/>
from here: https://Sveinbjorn.org/platypus<br/>
and install in your (64bit-only macOSX(Catalina/...) based) mac computer.<br/>
Or get Platypus v4.9, as that is the last 32bit supported ( & working) Platypus,<br/>
to build/wrap macOS apps in 64bit+32bit suppported macOSX (Mojave & earlier).<br/>

Obtain Pashua dialog from here : https://www.BlueM.net/en/projects/pashua/<br/>
Open dmg installer, Copy "Pashua.app", "Pashua.sh" into below folder:<br/>
&#160;&#160; `"/System/Volumes/Data/MyProjects/PortableFirefox/"`<br/>
&#160;&#160; ( or here: `"/Users/MyUserName/MyProjects/PortableFirefox/"` )<br/>

Get last Gecko-based old "`Firefox*.dmg`" (which has old "`Firefox.app`" inside it) from below URLs,<br/>
or Get last Quantum/Servo-based new "`Firefox*.dmg`" from https://www.Mozilla.org/<br/>
& extract/get/copy the "`Firefox.app`", & place/paste it into below folder:<br/>
&#160;&#160; `"/System/Volumes/Data/MyProjects/PortableFirefox/"`<br/>
&#160;&#160; ( or here: `"/Users/MyUserName/MyProjects/PortableFirefox/"` )<br/>
The last security-updated gecko-based non-ESR old Firefox:<br/>
&#160;&#160; FF v56.0.2 dmg file's sha1: 79a0013664134ced2307c8e1ffa5d36f6256e8f,<br/>
&#160;&#160; md5: a5608df45832df3ff302a7ccbe7ec3f6, 54.5 MBytes,<br/>
&#160;&#160; https://ftp.Mozilla.org/pub/firefox/releases/56.0.2/<br/>
The last gecko-based old Firefox-ESR:<br/>
&#160;&#160; FF v52.9.0 ESR dmg file's sha1: d879f5423d79393f2384e0f97a5581f9d89d7977,<br/>
&#160;&#160; md5: 34e8280bb9b33ca202ba22cf9daf25e4, 82.8 MBytes,<br/>
&#160;&#160; https://ftp.Mozilla.org/pub/firefox/releases/52.9.0esr/<br/>
Note: ESR = Extended Support Release<br/>
<br/>

Extract/Obtain two directories "`English.lproj`" & "`profile`" from<br/>
old Portable Firefox OSX "`PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg`" file<br/>
(download link is shown few-paragraphs above)<br/>
and then you would need to get/extract the "`Portable Firefox.app`" bundle<br/>
from inside that "`PortableFirefox_4.0.1_*.dmg`" file,<br/>
Those 2-folders are located inside "Resources" folder shown here:<br/>
&#160;&#160; `Portable Firefox.app/Contents/Resources/`<br/>
Or, obtain those 2-folders from your existing old "Portable Firefox OSX"<br/>
that you use/run from your portable/external drive.<br/>
Copy/Paste those 2-folders into below destination pre-build folder:<br/>
&#160;&#160; `"/System/Volumes/Data/MyProjects/PortableFirefox/"`<br/>
&#160;&#160; ( or `"/Users/MyUserName/MyProjects/PortableFirefox/"` )<br/>
<br/>


<b>BUILD/WRAP/GENERATE WITH PLATYPUS:</b><br/>
Test the 'script' file, before using it to build OSX PortableApp:<br/>
Tips: a good practice would-be, After getting this `'script'` (inside the shown/recommended folder<br/>
that is shown few paragraphs above), 1st Rename it to `"script.sh"`,<br/>
Open `"script.sh"` with your choice of code editing/developing editor/build software,<br/>
Improve/Modify, Save, then<br/>
Use below commands to test if bash code syntaxes are right or where the fault(s) is/are:
<pre style="padding:0px!important; margin:0px!important"><code style="padding:0px!important; margin:0px!important">┌────────────────────────────────────────────
│MacName:~ MyUserName$ sh -n /System/Volumes/Data/MyProjects/PortableFirefox/script.sh<br/>
│MacName:~ MyUserName$ echo $?<br/>
│MacName:~ MyUserName$ 0<br/>
└────────────────────────────────────────────</code></pre>
When there is no syntax-error (that is when the output is "0"),<br/>
then copy the `"script.sh"` in same folder,<br/>
& Rename the `"script.sh copy"` into `'script'`,<br/>
then follow next/below stage/procedures.<br/>

Build the final `"PortableAppName.app"` bundle:<br/>
To build new `"Portable Firefox.app"`,<br/>
choose these below files, directories, bundles inside Platypus GUI interface:<br/>
&#160; directory : English.lproj<br/>
&#160; directory : profile<br/>
&#160; bundle : Firefox.app<br/>
&#160; bundle : Pashua.app<br/>
&#160; icon-file : P_Firefox_Caution.icns<br/>
&#160; icon-file : appIcon.icns<br/>
&#160; sh-script-file : pashua.sh<br/>
&#160; sh-script-file : script<br/>

Then you may use these type of settings in Platypus GUI interface:<br/>
&#160;&#160; Script Type : Shell : /bin/sh<br/>
&#160;&#160; Script Path : `/System/Volumes/Data/MyProjects/PortableFirefox/script`<br/>
&#160;&#160; Interface : Text Window<br/>
&#160;&#160; Unselected options : Run with root privileges , Run in background , Accept dropped items<br/>
&#160;&#160; Selected/Check-Marked options : Remain running after execution<br/>
&#160;&#160; Fill in other boxes: app name, identifier, author, etc
Then tap/click/select/press the "`Create App`" button.<br/>
It will create/generate a new `"Portable Firefox.app"`, that is<br/>
compatible with 64-only macOSX(Catalina/...)<br/>
<br/>
Run/execute/TEST it.<br/>
<br/>


<b>ERRORs/PROBLEMs:</b><br/>
Write down what error(s) you're getting, try to research & solve as much possible,<br/>
then let us know in FreeSMUG forum about your unsolved errors & share your code changes:<br/>
&#160;&#160; http://www.FreeSMUG.org/forum/t-13404441/<br/>
If no errors, then please share your final working code in FreeSMUG & also in GitHub, Thank-you.<br/>
<br/>

<b>HELP TO BUILD:</b><br/>
Please help+contribute+collaborate+improve+rectify current codes to build this<br/>
bash-shell 'script' (so-that, this 'script' can be run/used by Platypus<br/>
to run macOSX apps (i.e: `"Firefox.app"`) on (64-bit) macOSX from portable/external<br/>
drive/storage⒮).<br/>
Thanks in advance.<br/>
<br/>
<br/>


<b>EXTRA-NOTES:</b><br/>
<center><table border="0" width="100%" cellspacing="0px" align="center" style="border-collapse:collapse!important; border-spacing:0px!important; width:100%!important; broder:0px; border-width:0px!important; border-style:none!important;"><tr><td>To create "MyProjects" folder in my mac hard drive, i had to do these: Edit:
<pre style="padding:0px!important; margin:0px!important"><code style="padding:0px!important; margin:0px!important">┌───────────────────────<br/>
│sudo nano /etc/synthetic.conf<br/>
└───────────────────────</code></pre>
and then add below 2-lines of settings:
<pre style="padding:0px!important; margin:0px!important"><code style="padding:0px!important; margin:0px!important">┌───────────────────────<br/>
│MyProjects	System/Volumes/Data/MyProjects<br/>
│Development	System/Volumes/Data/Development<br/>
└───────────────────────</code></pre>
then Press Ctrl+X , Enter . Note: press "tab"-button after typing "MyProjects"/"Development"<br/>
and Execute below Terminal/shell command⒮ to create those 2-folders:
<pre style="padding:0px!important; margin:0px!important"><code style="padding:0px!important; margin:0px!important">┌───────────────────────<br/>
│sudo mkdir -p /System/Volumes/Data/MyProjects<br/>
│sudo mkdir -p /System/Volumes/Data/Development<br/>
└───────────────────────</code></pre>
and then you must Reboot.
</td></tr>
<tr><td>To see all files in Finder (inlcuding Hidden/System), i executed below 2-commands:
<pre style="padding:0px!important; margin:0px!important"><code style="padding:0px!important; margin:0px!important">┌───────────────────────<br/>
│defaults write com.apple.finder AppleShowAllFiles TRUE<br/>
│killall Finder<br/>
└───────────────────────</code></pre>
or, in "Finder", press these 3-buttons together at-same-time: [⇧Shift]&#8239;+&#8239;[⌘Command]&#8239;+&#8239;[&#8239;<sup>&gt;</sup><sub>.</sub>&#8239;]
</td></tr>
<tr><td>List Of Few Useful Characters/Symbols, & How To Use/Show Them:
<table border="0" width="100%" cellspacing="0px" align="center" style="border-collapse:collapse!important; border-spacing:0px!important; width:100%!important; broder:0px; border-width:0px!important; border-style:none!important;"><tr><td>Low-Density Dotted Grph Char ░ 176 &#124; Medium-Density Dotted ▒ 177 &#124; High-Density Dotted ▓ 178 &#124;<br/>
Block █ 219 &#124; Bottom Half-Block ▄ 220 &#124; Top Half-Block ▀ 223 </td></tr>
<tr><td>Char = Character &#124; Grph = Graphic </td></tr>
<tr><td>Middot · ⌥Opt+⇧Shift+9 (macOS) Alt+250 or Alt+0183 (WinOS) &#124; Bullet • ⌥Opt+8 (macOS) Alt+249 (WinOS)<br/>
<tr><td>Apostrophe (aka Vertical Single-Quote) &#39; &amp;#39; &amp;apos; &#124; (Vertical/Stright/Double) Quotation-Mark &quot; &amp;quot; &#124;<br/>
Grave-Accent (aka Backtick/Tick, DiacriticalGrave) &#96; (&#96;) &amp;grave; &amp;#96; &#124; Acute-Accent ´ &#124; Full-Width Quotation-Mark ＂ &#124;<br/>
Full-Width Apostrophe ＇ </td></tr>
<tr><td>(Curved/Curly) Double Quotation-Mark “ (&ldquo;) ” (&rdquo;) &amp;ldquo; &amp;rdquo; ⌥Opt+[ ⌥Opt+⇧Shift+] (macOS) Alt+0147 Alt+0148 (WinOS) &#124;<br/>
Double High-Reversed-9 Quotation-Mark ‟ &amp;#8223; </td></tr>
<tr><td>(Curved/Curly) Single-Quotation-Mark	\‘ (&lsquo;) \’ (&rsquo;) &amp;lsquo; &amp;rsquo; ⌥Opt+] ⌥Opt+⇧Shift+] (macOS) Alt+0145 Alt+0146 (WinOS) &#124;<br/>
Single High-Reversed-9 Quotation-Mark ‛ &amp;#8219; </td></tr>
<tr><td>(Single)-Vertical-Line (aka Pipe Char) &#124; &amp;#124; &amp;verbar; &amp;vert; &#124;<br/>
(Single)-Broken-Bar ¦ &amp;#166; &amp;brvbar; AltGr+&#96; AltGr+6 AltGr+⇧Shift+Right\ (WinOS) </td></tr>
<tr><td>Ampersand (aka And) & &amp;amp; &amp;#38; &#124; Less-Than &lt; &amp;lt; &amp;#60; &#124; Greater-Than &gt; &amp;#62; &amp;gt; &#124;<br/>
Non-Breaking Space "&#160;" &amp;#160; &amp;nbsp; ⌥Opt+Space (macOS) Alt+0160 Alt+255 (WinOS) &#124; Narrow No-Break Space "&#8239;" &amp;#8239; &#124; Space " " &amp;#32; &#124;<br/>
Percent % &amp;#37; &#124; Asterisk * &amp;#42; &amp;ast; &#124; Exclamation ! &amp;#33; &amp;excl; &#124; Number (aka Hash, Pound-Sign) # &amp;#35; &amp;num; &#124;<br/>
Plus + &amp;#43; &amp;plus; &#124; Comma , &amp;#44; &amp;comma; &#124; Period (full stop) . &amp;#46; &amp;period; &#124; Solidus (Forward-Slash) / &amp;#47; &amp;sol; &#124;<br/>
Colon : &amp;#58; &amp;colon; &#124; Exclamation ! &amp;#33; &amp;excl; &#124; SemiColon ; &amp;#59; &amp;semi; &#124; Equals = &amp;#61; &amp;equals; &#124;<br/>
Question ? &amp;#63; &amp;quest; &#124; Commercial-At @ &amp;#64; &amp;commat; &#124; Square-Bracket &#91; &#93; &amp;#91; &amp;#93; &amp;lsqb; &amp;rsqb; &#124;<br/>
Reverse-Solidus (Back-Slash) &#92; &amp;#92; &amp;bsol; &#124; Circumflex-Accent (Hat) (Caret) &#94; &amp;#94; &amp;Hat; &#124; Low-Line (aka LowBar, UnderBar, UnderScore) &#95; &amp;#95; &amp;lowbar; </td></tr>
<tr><td>Registered-Trademark: ® ⌥Opt+r (macOS) Alt+0174 (WinOS) &#124; Copyright: © ⌥Opt+g (macOS) Alt+0169 (WinOS) &#124;<br/>
Trademark: ™ ⌥Opt+⇧Shift+2 (macOS) Alt+0153 (WinOS) &#124; Copyleft © (ɔ) </td></tr>
<tr><td>Euro: € ⌥Opt+2 (macOS) Alt 0128 (WinOS) &#124; Cent: ¢ ⌥Opt+4 (macOS) Alt+155 (WinOS) &#124; Yen: ¥ ⌥Opt+y (macOS) Alt+157 (WinOS) &#124;<br/>
Pound (Currency-Sign) £ ⌥Opt+3 (macOS) Alt+156 (WinOS) &#124; Dollar $ &amp;#33; &amp;dollar; </td></tr>
<tr><td>Apple symbol  ⌥Opt+⇧Shift+k (macOS) &#124; Squared-Plus ⊞ used by Wikipedia as WindowsOS Flag/Logo Key symbol 229E,<br/>
Others uses ❖ “Black Diamond Minus White X” symbol as Windows Logo Key 0x2756 &amp;#10070; &#124;<br/>
Penguin 🐧 U+1F427 &amp;#128039; &#124;<br/>
Congruence Relation Symbol ≡ 240 &#124; http://liberties.wikidot.com/symbols1 </td></tr>
<tr><td>Not-Equal-To ≠ ⌥Opt+= (macOS) &#124; Almost-Equal-To ≈ ⌥Opt+x (macOS) &#124; Division ÷ ⌥Opt+? ⌥Opt+/ (macOS) Alt+0247 (WinOS) &#124;<br/>
Plus-Minus ± ⌥Opt+⇧Shift+= (macOS) Alt+241 (WinOS) &#124; Infinity ∞ ⌥Opt+5 (macOS) </td></tr>
</table>
</td></tr>
</table></center><br/>
