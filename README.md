# PORTABLE FIREFOX OSX script
<br/>

A 'script' To Run "Firefox.app" As an OSX PortableApps, From Inside the<br/>
"Portable AppName.app" bundle in MacOSX.  So We Are ( Working-On & Developing & )<br/>
Modifying & Updating This 'script' To Include/Use 64bit Pashua dialog, 64bit Platypus,<br/>
etc To Execute/Run it On Both 64bit-Only macOSX & Also On 64bit+32bit macOSX.<br/>
Codes From This New-'script' Can Also Be Modified/Applied/Used With Any Other<br/>
"OSX Portable Apps".
<br/>

* **◦** FF = Firefox . A web-browser from Mozilla Foundation.<br/>
**◦** PA = Portable Apps . Ususally run from an External/Portable drives/storage.<br/>
**◦** OS = Operating System . A collection/set of vast numbers+types of programs, to assist interactions between computer User and computer hardwares & softwares and computer networks.<br/>
**◦** OSX =  = macOS X . An OS developed by Apple, Inc . ClosedSource OS.<br/>
**◦** Win = ❖ = Windows OS . An OS developed by Microsoft corp . ClosedSource OS.<br/>
**◦** Lnx = 🐧&#xFE0E; = Linux OS . Most distros should be called GNU-Linux OS. Various distros developed by various groups & individuals . OpenSource OS.


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
&#160;&#160;"/MyPortableDrive/PortableApps/FF_for_Test/Portable Firefox OS X/Portable Firefox&#46;app/Contents/Resources/script"<br/><!-- . written as #46 -->

This 'script' v4.1/v4.1.x is (i.e) used by the below binary "Portable Firefox" executable file:<br/>
&#160;&#160;"/MyPortableDrive/PortableApps/FF_for_Test/Portable Firefox OS X/Portable Firefox&#46;app/Contents/MacOS/Portable Firefox"<br/><!-- . written as #46 -->

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
And app⒮ built/wrapped with older Platypus also cannot run in 64bit-only macOSX,<br/>
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
to build/wrap macOS app⒮ in 64bit+32bit suppported macOSX (Mojave & earlier).<br/>

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
Tips: a good practice from beginning would-be, After getting this `'script'`<br/>
(inside the shown/recommended folder that is shown few paragraphs above), 1st Rename<br/>
it to `"script.sh"`, then Open `"script.sh"` with your choice of code editing/developing<br/>
editor/build software,<br/>
Improve/Modify, Save, then<br/>
Use below commands to test if bash code syntaxes are right or where the fault(s) is/are:<br/>
&#160;&#160;０┌──────────────────────────<br/>
&#160;&#160;１￨MacNm:~ UsrNm$ <b>sh -n</b> /System/Volumes/Data/MyProjects/PortableFirefox/script&#46;sh<br/>
&#160;&#160;２￨MacNm:~ UsrNm$ echo &#36;?<br/><!-- . written as #46 , $ as #36 -->
&#160;&#160;３￨0<br/>
&#160;&#160;４￨MacNm:~ UsrNm$<br/>
&#160;&#160;５└──────────────────────────<br/>
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
Write down what error(s) you're getting, try to research & try to solve as much possible,<br/>
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


## EXTRA-NOTES:
<center><table border="0" width="100%" cellspacing="0px" align="center" class="border border-0" style="border-collapse:collapse!important; border-spacing:0px!important; width:100%!important; border-width:0px!important; border:none!important; border-style:none!important;"><tr><td border=1>To create "MyProjects" folder in mac hard drive (not under your user-name), you may edit <code>synthetic.conf</code>:<br/>
&#160;&#160;０┌──────────────────────────<br/>
&#160;&#160;１￨sudo nano /etc/synthetic.conf<br/>
&#160;&#160;２└──────────────────────────<br/>
and then add below 2-lines of settings:<br/>
&#160;&#160;０┌──────────────────────────<br/>
&#160;&#160;１￨MyProjects	System/Volumes/Data/MyProjects<br/>
&#160;&#160;２￨Development	System/Volumes/Data/Development<br/>
&#160;&#160;３└──────────────────────────<br/>
then Press <code>Ctrl+X</code> & press <code>Enter</code>. Note: press <code>tab</code>-button after typing "MyProjects"/"Development". More on <a href="https://www.nano-editor.org/dist/latest/cheatsheet.html" target="_blank">Nano</a><br/>
and Execute below Terminal/shell command⒮ to create those 2-folders:<br/>
&#160;&#160;０┌──────────────────────────<br/>
&#160;&#160;１￨sudo mkdir -p /System/Volumes/Data/MyProjects<br/>
&#160;&#160;２￨sudo mkdir -p /System/Volumes/Data/Development<br/>
&#160;&#160;３└──────────────────────────<br/>
... and then you must Reboot.<br/>
<br/>
</td></tr>
<tr><td border=1>To see all files in <code>Finder</code> (inlcuding Hidden/System), i executed below 2-commands:<br/>
&#160;&#160;０┌──────────────────────────<br/>
&#160;&#160;１￨defaults write com.apple.finder AppleShowAllFiles TRUE<br/>
&#160;&#160;２￨killall Finder<br/>
&#160;&#160;３└──────────────────────────<br/>
or, in <code>Finder</code>, press these 3-buttons together at-same-time: [⇧Shift]&#43;[⌘Command]&#43;[&#8239;<sup>&gt;</sup><sub>.</sub>&#8239;]<br/><!-- + written as #43 , nnbsp is #8239 -->
<br/>
</td></tr>
</table></center>
<center><table border="0" width="100%" cellspacing="0px" align="center" class="border border-0" style="border-collapse:collapse!important; border-spacing:0px!important; width:100%!important; border-width:0px!important; border:none!important; border-style:none!important;"><tr><td border=1>List Of Few Useful (Unicode) Characters/Symbols, & How To Use/Show Them:
<table border="0" width="100%" cellspacing="0px" align="center" class="border border-0" style="border-collapse:collapse!important; border-spacing:0px!important; width:100%!important; border-width:0px!important; border:none!important; border-style:none!important;"><tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">• Low-Density Dotted Grph Char ░ &amp;#9617; 176 • Medium-Density Dotted ▒ &amp;#9618; 177 • High-Density Dotted ▓ &amp;#9619; 178<br/>
• Block █ &amp;#9608; &amp;block; 219 • Bottom Half-Block ▄ &amp;#9604; &amp;lhblk; 220 • Top Half-Block ▀ &amp;#9600; &amp;uhblk; 223 </td></tr>
<tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">• Box Drawings ( • Light-Horizontal ─ &amp;#9472;  • Light-Vertical │ &amp;#9474; • Light-Down&Right ┌ &amp;#9484; • ┐ &amp;#9488; • └ &amp;#9492; • ┘ &amp;#9496; )</td></tr>
<tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">• Char = Character • Grph = Graphic </td></tr>
<tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">• Middot · &amp;#183; ⌥Opt+⇧Shift+9 ❖Alt+250 / ❖Alt+0183 • Bullet • &amp;#8226; ⌥Opt+8 ❖Alt+249 <br/>
<tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">• Apostrophe (aka Vertical Single-Quote) &#39; &amp;#39; &amp;apos; • (Vertical/Stright/Double) Quotation-Mark &quot; &amp;#34; &amp;quot;<br/>
• Grave-Accent (aka Backtick/Tick, DiacriticalGrave) &#96; (&#96;) &amp;grave; &amp;#96; • Acute-Accent ´ &amp;#180; • Full-Width Quotation-Mark ＂<br/>
• Full-Width Apostrophe ＇ </td></tr>
<tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">• (Curved/Curly) Double Quotation-Mark “ (&ldquo;) ” (&rdquo;) &amp;#8220; &amp;#8221; &amp;ldquo; &amp;rdquo; ⌥Opt+[ ⌥Opt+⇧Shift+] ❖Alt+0147 / ❖Alt+0148 <br/>
• Double High-Reversed-9 Quotation-Mark ‟ &amp;#8223; </td></tr>
<tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">• (Curved/Curly) Single-Quotation-Mark	\‘ (&lsquo;) \’ (&rsquo;) &amp;#8216; &amp;#8217; &amp;lsquo; &amp;rsquo; ⌥Opt+] ⌥Opt+⇧Shift+] ❖Alt+0145 ❖Alt+0146 <br/>
• Single High-Reversed-9 Quotation-Mark ‛ &amp;#8219; </td></tr>
<tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">• (Single)-Vertical-Line (aka Pipe Char) • &amp;#124; &amp;verbar; &amp;vert;<br/>
• (Single)-Broken-Bar ¦ &amp;#166; &amp;brvbar; ❖AltGr+&#96; ❖AltGr+6 AltGr+⇧Shift+Right\ </td></tr>
<tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">• Ampersand (aka And) & &amp;amp; &amp;#38; • Less-Than &lt; &amp;lt; &amp;#60; • Greater-Than &gt; &amp;#62; &amp;gt;<br/>
• Non-Breaking Space "&#160;" &amp;#160; &amp;nbsp; ⌥Opt+Space ❖Alt+0160 ❖Alt+255 • Narrow No-Break Space "&#8239;" &amp;#8239; • Space " " &amp;#32;<br/>
• Percent % &amp;#37; • Asterisk * &amp;#42; &amp;ast; • Exclamation ! &amp;#33; &amp;excl; • Number (aka Hash, Pound-Sign) # &amp;#35; &amp;num;<br/>
• Plus + &amp;#43; &amp;plus; • Comma , &amp;#44; &amp;comma; • Period (aka dot, full stop) . &amp;#46; &amp;period; • Solidus (Forward-Slash) / &amp;#47; &amp;sol;<br/>
• Colon : &amp;#58; &amp;colon; • SemiColon ; &amp;#59; &amp;semi; • Equals = &amp;#61; &amp;equals;<br/>
• Question ? &amp;#63; &amp;quest; • Commercial-At @ &amp;#64; &amp;commat; • Square-Bracket &#91; &#93; &amp;#91; &amp;#93; &amp;lsqb; &amp;rsqb;<br/>
• Reverse-Solidus (Back-Slash) &#92; &amp;#92; &amp;bsol; • Circumflex-Accent (Hat) (Caret) &#94; &amp;#94; &amp;Hat; • Low-Line (aka LowBar, UnderBar, UnderScore) &#95; &amp;#95; &amp;lowbar; </td></tr>
<tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">• Registered-Trademark: ® &amp;#174; ⌥Opt+r ❖Alt+0174 • Copyright: © &amp;#169; ⌥Opt+g ❖Alt+0169<br/>
• Trademark: ™ &amp;#8482; ⌥Opt+⇧Shift+2 ❖Alt+0153 • Copyleft © (ɔ) </td></tr>
<tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">• Euro: € &amp;#8364; ⌥Opt+2 ❖Alt+0128 • Cent: ¢ &amp;#162; ⌥Opt+4 ❖Alt+155 • Yen: ¥ &amp;#165; ⌥Opt+y ❖Alt+157<br/>
• Pound (Currency-Sign) £ &amp;#163; ⌥Opt+3 ❖Alt+156 • Dollar $ &amp;#36; &amp;dollar; </td></tr>
<tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">• Apple symbol  (Textual) U+F8FF &amp;#63743; ⌥Opt+⇧Shift+k (macOS) • Red Apple 🍎 U+E345 &amp;#58181; &amp;#xe345; 🍎&#xFE0E;(Textual) • Green Apple 🍏 U+1F34F &amp;#127823; &amp;#x1f34f; 🍏&#xFE0E;(Textual)<br/>
• Squared-Plus ⊞ U+229E &amp;#8862; used by Wikipedia as WindowsOS Logo/Flag Key symbol , ⊞ Win+B ⊞ Win <br/>
• “Black Diamond Minus White X” ❖ used by others+me as Windows Logo Key (aka Winddows Flag Key) U+2756 &amp;#10070;<br/>
• Penguin 🐧 (emoji) U+1F427 &amp;#128039; 🐧&#xFE0E;(Textual) , often used to indicate GNU-Linux-OS</td></tr>
<tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">• Congruence Relation Symbol ≡ 240 • </td></tr>
<tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">• Not-Equal-To ≠ &amp;#8800; &amp;ne; ⌥Opt&#46;= • Almost-Equal-To ≈ &amp;#8776; &amp;asymp; &amp;ap; &amp;approx; ⌥Opt+x<br/>
• Division ÷ &amp;#247; ⌥Opt+? ⌥Opt+/ ❖Alt+0247<br/>
• Plus-Minus ± &amp;#177; ⌥Opt+⇧Shift+= ❖Alt+241 • Infinity ∞ &amp;#8734; &amp;infin; ⌥Opt+5 </td></tr>
<tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">• White Frowning Face ☹&#xFE0E;/&#65039; &amp;#9785;/&amp;#65039; &amp;#x2639;/&amp;#xFE0F; • Worried Face 😟 0x1F61F &amp;#128543;<br/>
• White Smiling Face ☺&#xFE0E; 0x263A &amp;#9786; • Slightly Smiling Face 🙂 0x1F642 &amp;#128578;<br/>
• Black Smiling Face ☻&#xFE0E; 0x263B &amp;#9787;</td></tr>
<tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">• Ballot Box ☐ &amp;#9744; U+2610 • Ballot Box with Check ☑ &amp;#9745; U+2611 ☑&#xFE0E;(Textual) • Ballot Box with X ☒ &amp;#9746; U+2612 ☒&#xFE0E;(Textual)</td></tr>
<tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">To display an Emoji/Emoticon as a Textual glyph (if available/renderable), Use this<br/>
after the emoji : &amp;#xFE0E; (or apply CSS, i.e: <code>span&#46;gray { -webkit-filter&#58; grayscale(100%); filter&#58; grayscale(100%); }</code>)<br/>
(More on <a href="https://en.wikipedia.org/wiki/Variant_form_(Unicode)#Variation_Selectors_block">VS15</a>)</td></tr>
<tr><td border=1 class="border border-left-0 border-right-0" style="border-width:1px!important; border-left:none!important; border-right:none!important;">http://liberties.wikidot.com/symbols1<br/>http://liberties.wikidot.com/ligatures1<br/><br/></td></tr>
</table>
</td></tr>
</table></center>
<center><table
border="0" width="100%" cellspacing="0px" align="center" class="border border-0" style="border-collapse:collapse!important; border-spacing:0px!important; width:100%!important; border-width:0px!important; border:none!important; border-style:none!important;"><tr><td border=1>In macOSX, Calculate & Compare hash/checksum/digest code (it is a very unique identity code) of a file/bundle:<br/>
In macOSX in shell ("<code>Terminal</code>" utility) window, type command (<code>shasum</code>) & press <code>space</code> key,<br/>
then drag the <code>.dmg</code> file from <code>Finder</code>(file browser) window & drop it into <code>Terminal</code> window:<br/>
The <code>shasum</code> tool by-default calculates the "SHA1" hash-code, & <code>openssl</code> usage also shown:<br/>
&#160;&#160;０┌──────────────────────────<br/>
&#160;&#160;１￨MacNm:~ UsrNm$ <b>shasum</b> /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg<br/>
&#160;&#160;２￨50ff626452dfadb9cbb6a2a5e2ddf60848adf256  /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg<br/>
&#160;&#160;３￨MacNm:~ UsrNm$ <b>shasum -a 1</b> /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg<br/>
&#160;&#160;４￨50ff626452dfadb9cbb6a2a5e2ddf60848adf256  /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg<br/>
&#160;&#160;５￨MacNm:~ UsrNm$ <b>openssl sha1</b> /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg<br/>
&#160;&#160;６￨SHA1(/Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg)= 50ff626452dfadb9cbb6a2a5e2ddf60848adf256<br/>
&#160;&#160;７└──────────────────────────<br/>
To calculate "SHA256" hash-code, use <code>-a 256</code> option in <code>shasum</code>, & <code>openssl</code> usage also shown:<br/>
&#160;&#160;０┌──────────────────────────<br/>
&#160;&#160;１￨MacNm:~ UsrNm$ <b>shasum -a 256</b> /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg<br/>
&#160;&#160;２￨e0052b8423cc117c99371a97e51a6ef9948510ac9a9c0ec1f2537be3597bad57  /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg<br/>
&#160;&#160;３￨MacNm:~ UsrNm$ <b>openssl sha256</b> /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg<br/>
&#160;&#160;４￨SHA256(/Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg)= e0052b8423cc117c99371a97e51a6ef9948510ac9a9c0ec1f2537be3597bad57<br/>
&#160;&#160;５└──────────────────────────<br/>
To calculate "MD5" hash-code, use <code>md5</code> option in <code>openssl</code>:<br/>
&#160;&#160;０┌──────────────────────────<br/>
&#160;&#160;１￨MacNm:~ UsrNm$ <b>openssl md5</b> /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg<br/>
&#160;&#160;２￨MD5(/Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg)= fa6691336e22a2d83e5629533b830300<br/>
&#160;&#160;３└──────────────────────────<br/>
</td></tr>
</table></center><br/>
