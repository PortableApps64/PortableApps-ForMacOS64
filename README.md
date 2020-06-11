<style type="text/css"> /*<br/>
 &#160; If You Can See This &lt;style>..&lt;/style> Block Shown On This README&#46;md,<br/>
 &#160; Then GitHub Has Disabled Usage Of This CSS-&lt;style> HTML Tag Command <a href="https://github.com/github/html-pipeline/blob/master/lib/html/pipeline/sanitization_filter.rb">here</a>.<br/>
 &#160; It Appaers That, To Support "GitHub-Pages"-Hosting/DEAL$/..., GitHub...Has Disabled<br/>
 &#160; CSS, JS, etc Here, & Directing Users To Use "GitHub-Pages" For CSS/JS/etc.<br/>
 &#160; But We Need It Here, As it(&lt;style>) Helps Developers/Users To Define Simple CSS<br/>
 &#160; To Present Distinct-Contents Distinctly+Accurately.<br/>
 &#160; GitHub Already <a href="https://github.com/github/html-pipeline/blob/master/lib/html/pipeline/sanitization_filter.rb">Applying</a> Filtering/Restrictions On HTML Commands, So Contact<br/>
 &#160; GitHub-Support & Request Them To Unblock+Enable Essential Function(s), Tell<br/>
 &#160; GitHub-Support To Apply Filtering Also For CSS/JS Commands Inside "&lt;STYLE> & "&lt;SCRIPT>" Commands,<br/>
 &#160; To AtLeast Allow CSS & JS With Limited/Restricted Functionalities/Abilities, like:<br/>
 &#160; Element+Text Coloring, Positioning, Width/Margin/Padding/Height/etc Controlling, etc,etc.<br/>
 &#160; For This README&#46;md Page, Few Txt/Inl/Blk/etc Element’s Style(Look/Appearance/etc)<br/>
 &#160; OverRiding CSS Rules Are Defined Below:<br/>
BEGIN CSS RULES:<br/> Square Boxes:<br/> */
.UatErik50{ float:left; position:relative; width:30%; padding-bottom:30%; margin:1.66%; overflow:hidden; }
/* <br/> Content inside SqrBox:<br/> */
.UatErik51{ position:absolute; height:80%; width:90%; padding:10% 5%; }
/* <br/> Table For Vertical Allignment:<br/> */
.UatErik52{ display:table; height:100%; width:100%; }
/* <br/> Cell in Vert Tbl:<br/> */
.UatErik53{ display:table-cell; vertical-align:middle; height:100%; width:100%; }
/* <br/> No-Border:<br/> */
.UatErik70{ border-collapse:collapse; border-spacing:0px; width:100%; border-width:0px; border-style:none; border:none; margin:0px; padding:0px;}
/* <br/> Border-1:<br/> */
.UatErik81{ border-width:1px; width:100%; margin:0px; padding:0px; }
/* <br/> Top & Bottom Border Without Sides:<br/> */
.UatErik82{ border-width:1px; border-width-top:1px; border-width-bottom:1px; border-width-left:0px; border-width-right:0px; width:100%; }
/* <br/> Only Bottom Border:<br/> */
.UatErik83{ border-width:1px; border-width-top:0px; border-width-bottom:1px; border-width-left:0px; border-width-right:0px; width:100%; } /* <br/> END of CSS STYLEs: */
</style>

# PORTABLE FIREFOX OSX script
<br/><!-- “.” is &#46; -->

A ‘script’ To Run "Firefox&#46;app" As an OSX PortableApps, From Inside the<br/>
"Portable AppName&#46;app" bundle in MacOSX.  So We Are ( Working-on & Developing & )<br/>
Modifying & Updating This ‘script’ To Include/Use 64bit Pashua dialog, 64bit Platypus,<br/>
etc To Execute/Run/Use it On Both 64bit-Only (Current) macOSX and Also On 64bit+32bit<br/>
(older) macOSX. New-‘script’ Can Also Be Modified/Adapted To Use With Any Other<br/>
“Portable OSX Apps”.
<br/>

<dl><dd>
 • FF = Firefox . A web-browser from Mozilla Foundation. Since v57 its using <a href="https://en.wikipedia.org/wiki/Quantum%5F%28Mozilla%29#Quantum">Quantum</a>/Servo engines, before v57 it used <a href="https://en.wikipedia.org/wiki/Gecko%5F%28software%29">Gecko</a>.<br/>
 • PA = Portable Apps . Ususally run from an External/Portable drives/storage.<br/>
 • OS = Operating System . A collection/set of vast numbers+types of programs, to assist interactions between computer User and computer hardwares & softwares and computer networks.<br/>
 • OSX = 🍎︎&#xFE0E; = macOS X = macOSX . An OS developed by Apple, Inc. ClosedSource OS.<br/>
 • Win = ❖ = Windows OS . An OS developed by Microsoft corp. ClosedSource OS.<br/>
 • Lnx = 🐐&#xFE0E;GNU-🐧&#xFE0E;Linux OS, though most users shorten/call/know it as "Linux OS". Various distros developed by various groups & individuals. OpenSource OS.
</dd></dl>

<b>OLD SCRIPT:</b><br/>
<div> Original & Last ‘script’ v4.1 is here<b>:</b> http://www.FreeSMUG.org/portableapps:code:firefox<br/>
( You can also check 1st commit of this ‘script’ file in Github to view the v4.1 code )<br/>
The ‘script’ v4.1 was written by Carlo Gandolfi and Paolo Portaluri and others,<br/>
Copyright 2010 by Carlo Gandolfi, and, Paolo Portaluri, Released under GPL v3.<br/>
Project’s SF page: https://SourceForge.net/projects/osxportableapps/<br/>
Project Website: http://www.FreeSMUG.org/<br/>
Portable Firefox OSX is here<b>:</b><br/>
&#160; https://SourceForge.net/projects/osxportableapps/files/Portable%20Firefox%20OS%20X/<br/>
The ‘script’ v4.1 is now distributed via a ZIP file located here<b>:</b><br/>
&#160; https://prdownloads.SourceForge.net/osxportableapps/PortableFirefoxScript_r4.1.txt.zip?download<br/>
Last “Portable Firefox OSX” app<b>:</b> "PortableFirefox_4.0.1_en-US-OSX_r4.1&#46;dmg", 28.2 MBytes,
<dl><dd>
 sha1: 50ff626452dfadb9cbb6a2a5e2ddf60848adf256,<br/>
 md5: fa6691336e22a2d83e5629533b830300.<br/>
 https://SourceForge.net/projects/osxportableapps/files/Portable%20Firefox%20OS%20X/4.0.1%20r4.1/
</dd></dl>
</div><br/>


<b>WHAT TYPE OF ‘script’ FILE:</b><br/>
The ‘<b>script</b>’ is a bash shell script file, Executable file.<br/>
<br/>


<b>NEW SCRIPT:</b>🆕<br/>

New ‘<a href="https://github.com/atErik/Portable-Firefox-OSX-script/blob/master/script">script</a>’ v4.1.x (v4.1.4) Are released under below <b>Licenses</b> + <b>Restrictions</b> + <b>Permissions:</b><br/>
&#160;&#160; - GNU General Public License Version 3  (GPL v3)<br/>
&#160;&#160; - Do Not Use This To Kill/Harm (or Steal from) (Any) Human/Community/Earth/etc<br/>
New ‘script’ v4.1.x are: Copyright 2020 by Erik T Ashfolk - &lt;atErik＠OutLထk·ⓒⓞⓜ&gt;(＠=@,ထ=oo,·=&#46;,ⓒ=c,ⓞ=o,ⓜ=m)<br/>


This ‘script’ v4.1/v4.1.x file is usually used from such (i.e) location, in macOSX<b>:</b><br/>
&#160;&#160;"/MyPortableDrive/PortableApps/FF_for_Test/Portable Firefox OS X/Portable Firefox&#46;app/Contents/Resources/script"<br/><!-- “.” is &#46; -->

This ‘script’ v4.1/v4.1.x is (i.e) used by the below binary “Portable Firefox” executable file<b>:</b><br/>
&#160;&#160;"/MyPortableDrive/PortableApps/FF_for_Test/Portable Firefox OS X/Portable Firefox&#46;app/Contents/MacOS/Portable Firefox"<br/><!-- “.” is &#46; -->

<div> The binary “Portable Firefox” is created by Platypus,<br/>
Platypus also creates the <code>“Portable Firefox.app”</code> bundle.
<dl><dd>
 A developer/user can either place/compress that <code>Portable-*.app</code> bundle inside a <code>.dmg</code> file to share it with users for downloading, from developer/user’s website.
</dd><dd>
 Or, a developer/user can build the <code>Portable-*.app</code> with an (older) unmodified (Firefox) app, and share with Users that file & an accompanying instruction file on How-To update to use latest (Firefox) app.
</dd></dl>
</div><br/>


<b>PLATYPUS:</b><br/>

<div>The "Portable Firefox&#46;app" is packaged using the Platypus script wrapper (aka app builder) from http://sveinbjorn.sytes.net/platypus
<dl><dd><!-- “.” is &#46; -->
 New website: https://Sveinbjorn.org/platypus<br/>
 GitHub: https://GitHub.com/sveinbjornt/Platypus<br/>
 <br/>
 Platypus (v5.3 & later version) seems to be able to generate 64bit-only app bundles,<br/>
 but it does not (digitally) sign or provide option to sign the generated app bundle,<br/>
 so it seems only Admin level privileged user can use+run Platypus generated apps,<br/>
 in 64bit-only macOSX(Catalina & after...) and also in 64bit+32bit supported macOSX(Mojave & earlier...)
</dd></dl>
</div><br/>


<b>COCOA-DIALOG:</b><br/>

<div>The OSX PortableApps used CocoaDialog (&#46;app bundle) inside “PortableFirefoxOSX” v4.0.1 (the last/old release).
<dl><dd><!-- “.” is &#46; -->
 But (old) CocoaDialog is NOT compatible with 64bit-only-macOSX yet, afaik.<br/>
 <br/>
 Website: https://CocoaDialog.com/<br/>
 <br/>
 So Apps/DMG which includes old CocoaDialog cannot run on 64bit-only macOSX (Catalina & later...)<br/>
 and app⒮ built/wrapped with older Platypus also cannot run in 64bit-only macOSX,<br/>
 as old Platypus was not fully 64bit compatible.
</dd></dl>
</div>
So we must change existing dialog program (a program to assist interaction between user & script) functions in ‘script’, into something else.<br/>
<br/>


<b>PASHUA:</b><br/>
<div> Pashua dialog seems to be a good choice for now (as a ‘dialog’/interaction assistor), Check here<b>:</b>
<dl><dd>
 Website: https://www.BlueM.net/en/projects/pashua/<br/>
 Github: https://GitHub.com/BlueM/Pashua
</dd></dl>
</div><br/>


## PRE-BUILD:
<b>BRING TOGETHER BUILD-RELATED ITEMS/OBJECTS,ETC (PREPARATION):</b>

<div> Suppose, We are working-on/building this project from below example folder<b>:</b>
<dl><dd>
 <code>"/System/Volumes/Data/MyProjects/PortableFirefox/"</code><br/>
 ( alternatively you may/can also create a developement folder “PortableFirefox” here<b>:</b>
<dl><dd>
  <code>"/Users/MyUserName/MyProjects/PortableFirefox/"</code> )
</dd></dl>
</dd></dl>
</div>
<div> When Platypus generates the <code>“Portable Firefox OSX.app”</code> bundle, it places the bundle here<b>:</b>
<dl><dd>
 <code>"/System/Volumes/Data/MyProjects/PortableFirefox/Portable Firefox OSX.app"</code>
</dd></dl>
</div>
<div> To build with Platypus, we will have to choose (various needed files, directories & bundles, etc from above location), inside the Platypus GUI interface/settings,<br/>
then Platypus will place/copy them, inside below folder location, inside the <code>.app</code> bundle<b>:</b>
<dl><dd>
 <code>"/System/Volumes/Data/MyProjects/PortableFirefox/Portable Firefox OSX.app/Contents/Resources/"</code>
</dd></dl>
</div><br/>

So obtain NEW Platypus (at the time of writing this README&#46;md, it is/was v5.3),<br/>
&#160;&#160; from here: https://Sveinbjorn.org/platypus<br/>
and install in your (64bit-only macOSX(Catalina & later) based) mac computer.<br/>
Or get Platypus v4.9, as that is the last 32bit supported ( & working) Platypus,<br/>
to build/wrap macOS app⒮ in 64bit+32bit suppported macOSX (Mojave & earlier).<br/>

<div>Obtain Pashua dialog from here : https://www.BlueM.net/en/projects/pashua/<br/>
Open dmg installer, Copy "Pashua&#46;app", "Pashua&#46;sh" into below folder<b>:</b>
<dl><dd><!-- “.” is &#46; -->
 <code>"/System/Volumes/Data/MyProjects/PortableFirefox/"</code><br/>
 ( or here: <code>"/Users/MyUserName/MyProjects/PortableFirefox/"</code> )
</dd></dl>
</div><br/>

<div>Get last Gecko-based old <code>"Firefox-*.dmg"</code> (which has old <code>“Firefox.app”</code> inside it) from below URLs,<br/>
or Get last Quantum/Servo-based new <code>"Firefox-*.dmg"</code> from https://www.Mozilla.org/<br/>
& extract/get/copy the <code>“Firefox.app”</code>, & place/paste it into below folder<b>:</b>
<dl><dd>
 <code>"/System/Volumes/Data/MyProjects/PortableFirefox/"</code><br/>
 ( or here: <code>"/Users/MyUserName/MyProjects/PortableFirefox/"</code> )
</dd></dl>
</div>
<dl><dd>The last security-updated gecko-based non-ESR old Firefox<b>:</b><dl>
  <dd>
  FF v56.0.2 dmg file’s sha1: 79a0013664134ced2307c8e1ffa5d36f6256e8f,<br/>
  md5: a5608df45832df3ff302a7ccbe7ec3f6, 54.5 MBytes,<br/>
  https://ftp.Mozilla.org/pub/firefox/releases/56.0.2/
  </dd><dl>
</dd><dd>The last gecko-based old Firefox-ESR<b>:</b><dl>
  <dd>
  FF v52.9.0 ESR dmg file’s sha1: d879f5423d79393f2384e0f97a5581f9d89d7977,<br/>
  md5: 34e8280bb9b33ca202ba22cf9daf25e4, 82.8 MBytes,<br/>
  https://ftp.Mozilla.org/pub/firefox/releases/52.9.0esr/
  </dd></dl>
</dd><dd>Note: ESR = Extended Support Release.
</dd></dl>
<br/>

Extract/Obtain 2-folders `"English.lproj"` & `"profile"` from<br/><!-- “.” is &#46; -->
old Portable Firefox OSX `"PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg"` file<br/>
(and you can find download link⒮ shown few-paragraphs above),<br/>
and then you would need to get/extract the `“Portable Firefox.app”` bundle from<br/>
inside that `"PortableFirefox_4.0.1_*.dmg"` file.<br/>
Those 2-folders are located inside the "Resources" folder shown below<b>:</b><br/>
&#160;&#160; `Portable Firefox.app/Contents/Resources/`<br/>
&#160;&#160; (Right-Click/Secondary-Click/Tap-with-2-Fingers-&-Hold on the `Portable-*.app` & select `“Show Package Contents”` option)<br/>
Or, obtain those 2-folders from your existing/old “Portable Firefox OSX” that<br/>
you use/run from your portable/external drive, (to keep your existing/custom preferences/etc).<br/>
Copy/Paste those 2-folders into below (destination) build/project folder<b>:</b><br/>
&#160;&#160; `"/System/Volumes/Data/MyProjects/PortableFirefox/"`<br/>
&#160;&#160; ( or `"/Users/MyUserName/MyProjects/PortableFirefox/"` )<br/>
<br/>


## BUILD:
<b>BUILD/WRAP/GENERATE WITH PLATYPUS:</b>

<div> Test the ‘script’ file, before using it to build OSX PortableApp<b>:</b><br/>
Tips<b>:</b> a good practice from beginning would-be, After getting this <code>‘script’</code><br/>
(inside the shown/recommended folder that is shown few paragraphs above), 1st Rename<br/>
it to <code>"script.sh"</code>, then Open <code>"script.sh"</code> with your choice of code editing/developing<br/>
editor/build software,<br/>
Improve/Modify, Save, then<br/>
Use below commands to test if bash code syntaxes are right or where the fault⒮ is/are<b>:</b>
<dl><dd>
 <tt>０┌─────────────────</tt><br/>
 <tt>１│</tt>MacNm:~ UsrNm$ <b>sh -n</b> /System/Volumes/Data/MyProjects/PortableFirefox/script&#46;sh<br/>
 <tt>２│</tt>MacNm:~ UsrNm$ echo &#36;?<!-- “.” written as &#46; , $ as &#36; --><br/>
 <tt>３│</tt>0<br/>
 <tt>４│</tt>MacNm:~ UsrNm$<br/>
 <tt>５└─────────────────</tt><br/><br/>
 When there is no syntax-error, (in other words, When the output is “0”), then<br/>
 copy the <code>"script.sh"</code> in same folder,<br/>
 & Rename the <code>"script.sh Copy"</code> into <code>"script"</code>,<br/>
 then follow next/below stage/procedures.
</dd></dl>
</div><br/>

<div>Build the final <code>“PortableAppName.app”</code> bundle, by using Platypus<b>:</b>
<dl><dd>
 To build new <code>“Portable Firefox.app”</code>,<br/>
 choose these below files, directories, bundles inside Platypus GUI interface<b>:</b>
<dl><dd><!-- “.” is &#46; -->
  <b>◦</b> directory : English&#46;lproj<br/>
  <b>◦</b> directory : profile<br/>
  <b>◦</b> bundle : Firefox&#46;app<br/>
  <b>◦</b> bundle : Pashua&#46;app<br/>
  <b>◦</b> icon-file : P_Firefox_Caution&#46;icns<br/>
  <b>◦</b> icon-file : appIcon&#46;icns<br/>
  <b>◦</b> sh-script-file : pashua&#46;sh<br/>
  <b>◦</b> sh-script-file : script
</dd></dl>
</dd></dl>
</div><br/>

<div> Then you may use, these type of settings in Platypus GUI interface<b>:</b>
<dl><dd>
 <b>◦</b> Script Type : Shell : /bin/sh<br/>
 <b>◦</b> Script Path : <code>/System/Volumes/Data/MyProjects/PortableFirefox/script</code><br/>
 <b>◦</b> Interface : Text Window<br/>
 <b>◦</b> Unselected options : Run with root privileges , Run in background , Accept dropped items<br/>
 <b>◦</b> Selected/Check-Marked options : Remain running after execution<br/>
 <b>◦</b> Fill in other boxes: app name, identifier, author, etc
</dd></dl>
</div><br/>

Then tap/click/select/press the <code>“Create App”</code> button.<br/><!-- “.” is &#46; -->
It will create/generate a new <code>“Portable Firefox.app”</code>, that is<br/>
compatible with 64-only macOSX(Catalina/...)<br/>

Run/execute/TEST it.
<br/>

<b>ERRORs/PROBLEMs:</b><br/>

Write down what error⒮ you’re getting, try to research & try to solve as much possible,<br/>
then let us know in FreeSMUG forum about your unsolved errors & share your code changes<b>:</b><br/>
&#160;&#160; http://www.FreeSMUG.org/forum/t-13404441/<br/>
If no errors, then please share your final working code in FreeSMUG & also in GitHub, Thank-you.<br/>
<br/>

<b>HELP TO BUILD:</b><br/>

Please help+contribute+collaborate+improve+rectify current codes to build this<br/>
bash-shell ‘script’ (so-that, this ‘script’ can be run/used by Platypus<br/>
to run macOSX apps (i.e: `“Firefox.app”`) on (64-bit) macOSX from portable/external<br/>
drive/storage⒮).<br/>
Thanks in advance.<br/>
<br/>
<br/>


## EXTRA-NOTES:

<table border="0" width="100%" cellspacing="0" cellpadding="0" align="center" class="UatErik70"><tr><td border="1" width="100%" class="UatErik81"> To create "MyProjects" folder in mac hard drive (not under your user-name), you may edit <code>synthetic.conf</code><b>:</b>
<dl><dd><!-- “.” is &#46; -->
 <tt>０┌─────────────────</tt><br/>
 <tt>１│</tt>sudo nano /etc/synthetic&#46;conf<br/>
 <tt>２└─────────────────</tt>
</dd></dl>
and then add below 2-lines of settings<b>:</b>
<dl><dd>
 <tt>０┌─────────────────</tt><br/>
 <tt>１│</tt>MyProjects&#9;	System/Volumes/Data/MyProjects<br/>
 <tt>２│</tt>Development&#9;	System/Volumes/Data/Development<br/>
 <tt>３└─────────────────</tt>
</dd><dd>
 then Press <code>Ctrl+X</code> (to Exit), and Nano prompts/asks you to press “Y” (to Save) or “N” (to Discard) changes, so press “Y” (to Save), then Nano shows target/destination filename <code>/etc/synthetic.conf</code> (and allows you to change name), So press <code>Enter</code> to select it & Save+Exit.<br/>
 Note<b>:</b> you must press <code>tab</code>-button after typing "MyProjects"/"Development". More on <a href="https://www.nano-editor.org/dist/latest/cheatsheet.html" target="_blank">Nano</a>
</dd></dl><!-- “.” is &#46; -->
and Execute below Terminal/shell command⒮ to create those 2-folders<b>:</b>
<dl><dd>
 <tt>０┌─────────────────</tt><br/>
 <tt>１│</tt>sudo mkdir -p /System/Volumes/Data/MyProjects<br/>
 <tt>２│</tt>sudo mkdir -p /System/Volumes/Data/Development<br/>
 <tt>３└─────────────────</tt>
</dd></dl>
... and then you must Reboot.<br/>
<br/>
</td></tr>
</table>

<table border="0" width="100%" cellspacing="0" cellpadding="0" align="center" class="UatErik70"><tr><td border="1" width="100%" class="UatErik81"> To see all files in <code>Finder</code> (inlcuding Hidden/System), i executed below 2-commands<b>:</b>
<dl><dd><!-- “.” is &#46; -->
 <tt>０┌─────────────────</tt><br/>
 <tt>１│</tt>defaults write com&#46;apple&#46;finder AppleShowAllFiles TRUE<br/>
 <tt>２│</tt>killall Finder<br/>
 <tt>３└─────────────────</tt>
</dd><dd>
 or, in <code>Finder</code>, press these 3-buttons together at-same-time: [⇧Shift]&#43;[⌘Command]&#43;[&#8239;<sup>&gt;</sup><sub>.</sub>&#8239;]<br/><!-- + written as &#43; , nnbsp is &#8239; -->
</dd></dl>
</td></tr>
</table>

List Of Few Useful (Unicode) Characters/Symbols, & How To Use/Show Them<b>:</b><br/>
( We will use some of these in our dialog messages from this ‘script’ )
<table width="100%" border="0" cellspacing="0" cellpadding="0" align="center" class="UatErik70">
<tr><td width="100%"> • Char = Character • Grph = Graphic • Emj ~= Emoji ~= Emoticons • Txt = Textual Glyph • U = Unicode • h = H = x = hex = HexaDecimal • A = ASCII </td></tr>
</table>
<table width="100%" border="0" cellspacing="0" cellpadding="0" align="center" class="UatErik70">
<tr><td width="32%">• Low-Density Dotted Grph Char ░ &amp;#9617; 176 </td><td width="32%">• Medium-Density Dotted ▒ &amp;#9618; 177 </td><td>• High-Density Dotted ▓ &amp;#9619; 178 </td></tr>
<tr><td>• Block █ &amp;#9608; &amp;block; 219 </td><td>• Bottom Half-Block ▄ &amp;#9604; &amp;lhblk; 220 </td><td>• Top Half-Block ▀ &amp;#9600; &amp;uhblk; 223 </td></tr>
</table>
<table width="100%" border="0" cellspacing="0" cellpadding="0" align="center" class="UatErik70">
<tr><td width="32%"> Box-Drawings: </td><td width="32%"> &#160; </td><td> &#160; </td></tr>
<tr><td>• Light-Horizontal ─ &amp;#9472; </td><td>• Light-Vertical │ &amp;#9474; </td><td>• Light-Down&Right ┌ &amp;#9484; </td></tr>
<tr><td>• Light-Down&Left ┐ &amp;#9488; </td><td>• Light-Up&Right └ &amp;#9492; </td><td>• Light-Up&Left ┘ &amp;#9496; </td></tr>
<tr><td>• Light-Vert&Right ├ &amp;#9500; </td><td>• Light-Vert&Left ┤ &amp;#9508; </td><td>• Light-Down&Horizontal ┬ &amp;#9516; </td></tr>
<tr><td>• Light-Up&Horizontal ┴ &amp;#9524; </td><td>• Light-Vert.&Horiz. ┼ &amp;#9532; </td><td> &#160; </td></tr>
</table>
<table width="100%" border="0" cellspacing="0" cellpadding="0" align="center" class="UatErik70">
<tr><td width="32%">• 📁 1F4C1, File Folder. Closed </td><td width="32%">• 📂 1F4C2, Open File Folder </td><td>• 📃 1F4C3, Page with curl. Rolled Paper </td></tr>
<tr><td>• 📄＜1F4C4, Page facing Up. Page/Paper/Files </td><td>• 📤 1F4E4, Outbox Tray. For Send Out. Copy </td><td>• 📥 1F4E5, Inbox Tray. For Receiving. Paste </td></tr>
<tr><td>• Warning Sign ⚠&#xFE0E; (Txt) U+26A0 Alert. Notification </td><td>• Warning Sign ⚠️ (Emj). Alert. Notification </td><td>• Left-Pointing Magnifying Glass 🔍 U+1F50D </td></tr>
<tr><td>• Right-Pointing Magnifying Glass 🔎 U+1F50E </td><td>• Computer (Laptop) 💻 U+1F4BB </td><td>• Monitor/Screen 🖳 </td></tr>
<tr><td>• Computer (Desktop) 🖥 U+1F5A5 </td><td> &#160; </td><td> &#160; </td></tr>
</table>
<table width="100%" border="0" cellspacing="0" cellpadding="0" align="center" class="UatErik70">
<tr><td width="32%">• Middot · &amp;#183; 🍎︎&#xFE0E;⌥Opt+⇧Shift+9 ❖Alt+250 / ❖Alt+0183 </td><td width="32%">• Bullet • &amp;#8226; 🍎︎&#xFE0E;⌥Opt+8 ❖Alt+249 </td><td> &#160; </td></tr>
<tr><td>• Apostrophe (aka Vertical Single-Quote) &#39; &amp;#39; &amp;apos; </td><td>• (Vertical/Straight/Double) Quotation-Mark &quot; &amp;#34; &amp;quot; </td><td>• Grave-Accent (aka Backtick/Tick, DiacriticalGrave) &#96; (&#96;) &amp;grave; &amp;#96; </td></tr>
<tr><td>• Acute-Accent ´ &amp;#180; </td><td>• Full-Width Quotation-Mark ＂ </td><td>• Full-Width Apostrophe ＇ </td></tr>
<tr><td>• (Curved/Curly) Left Double Quotation-Mark: “ (&ldquo;) (&amp;#8220;) &amp;ldquo; 🍎︎&#xFE0E;⌥Opt+[ ❖Alt+0147 </td><td>• (Curved/Curly) Right Double Quotation-Mark: ” (&rdquo;) (&amp;#8221;) &amp;rdquo; 🍎︎&#xFE0E;⌥Opt+⇧Shift+] ❖Alt+0148 </td><td>• Double High-Reversed-9 Quotation-Mark ‟ &amp;#8223; </td></tr>
<tr><td>• (Curved/Curly) Left Single-Quotation-Mark ‘ (&lsquo;) &amp;#8216; &amp;lsquo; 🍎︎&#xFE0E;⌥Opt+] ❖Alt+0145 </td><td>• (Curved/Curly) Right Single-Quotation-Mark ’ (&rsquo;) &amp;#8217; &amp;rsquo; 🍎︎&#xFE0E;⌥Opt+⇧Shift+] ❖Alt+0146 </td><td>• Single High-Reversed-9 Quotation-Mark ‛ &amp;#8219; </td></tr>
<tr><td>• (Single)-Vertical-Line (aka Pipe Char) • &amp;#124; &amp;verbar; &amp;vert; </td><td>• (Single)-Broken-Bar ¦ &amp;#166; &amp;brvbar; ❖AltGr+&#96; ❖AltGr+6 ❖AltGr+⇧Shift+Right\ </td><td> &#160; </td></tr>
<tr><td>• Ampersand (aka And) & &amp;#38; &amp;amp; </td><td>• Less-Than &lt; &amp;#60; &amp;lt; </td><td>• Greater-Than &gt; &amp;#62; &amp;gt; </td></tr>
<tr><td>• Non-Breaking Space "&#160;" &amp;#160; &amp;nbsp; 🍎︎&#xFE0E;⌥Opt+Space ❖Alt+0160 ❖Alt+255 </td><td>• Narrow No-Break Space "&#8239;" &amp;#8239; </td><td>• Space " " &amp;#32; </td></tr>
<tr><td>• Percent % &amp;#37; </td><td>• Asterisk * &amp;#42; &amp;ast; </td><td>• Exclamation ! &amp;#33; &amp;excl; </td></tr>
<tr><td>• Number (aka Hash, Pound-Sign) # &amp;#35; &amp;num; </td><td>• Plus + &amp;#43; &amp;plus; </td><td>• Comma , &amp;#44; &amp;comma; </td></tr>
<tr><td>• Period (aka dot, full stop) . &amp;#46; &amp;period; </td><td>• Solidus (Forward-Slash) / &amp;#47; &amp;sol; </td><td>• Colon : &amp;#58; &amp;colon; </td></tr>
<tr><td>• SemiColon ; &amp;#59; &amp;semi; </td><td>• Equals = &amp;#61; &amp;equals; </td><td>• Question ? &amp;#63; &amp;quest; </td></tr>
<tr><td>• Commercial-At @ &amp;#64; &amp;commat; </td><td>• Square-Bracket &#91; &#93; &amp;#91; &amp;#93; &amp;lsqb; &amp;rsqb; </td><td>• Reverse-Solidus (Back-Slash) &#92; &amp;#92; &amp;bsol; </td></tr>
<tr><td>• Circumflex-Accent (Hat) (Caret) &#94; &amp;#94; &amp;Hat; </td><td>• Low-Line (aka LowBar, UnderBar, UnderScore) &#95; &amp;#95; &amp;lowbar; </td><td> &#160; </td></tr>
<tr><td>• Registered-Trademark: ® &amp;#174; 🍎︎&#xFE0E;⌥Opt+r ❖Alt+0174 </td><td>• Copyright: © &amp;#169; 🍎︎&#xFE0E;⌥Opt+g ❖Alt+0169 </td><td>• Trademark: ™ &amp;#8482; 🍎︎&#xFE0E;⌥Opt+⇧Shift+2 ❖Alt+0153 </td></tr>
<tr><td>• Copyleft © (ɔ) </td><td> &#160; </td><td> &#160; </td></tr>
<tr><td>• Euro: € &amp;#8364; 🍎︎&#xFE0E;⌥Opt+2 ❖Alt+0128 </td><td>• Cent: ¢ &amp;#162; 🍎︎&#xFE0E;⌥Opt+4 ❖Alt+155 </td><td>• Yen: ¥ &amp;#165; 🍎︎&#xFE0E;⌥Opt+y ❖Alt+157 </td></tr>
<tr><td>• Pound (Currency-Sign) £ &amp;#163; 🍎︎&#xFE0E;⌥Opt+3 ❖Alt+156 </td><td>• Dollar $ &amp;#36; &amp;dollar; </td><td> &#160; </td></tr>
</table>
<table width="100%" border="0" cellspacing="0" cellpadding="0" align="center" class="UatErik70">
<tr><td width="32%">• Apple symbol  &amp;#63743; U+F8FF 🍎︎&#xFE0E;⌥Opt+⇧Shift+k (macOS) </td><td width="32%">• Red Apple 🍎 U+E345 &amp;#58181; &amp;#xe345; 🍎&#xFE0E;(txt) </td><td>• Green Apple 🍏 U+1F34F &amp;#127823; &amp;#x1f34f; 🍏&#xFE0E;(txt) </td></tr>
<tr><td>• “Squared-Plus” ⊞ U+229E &amp;#8862; used by Wikipedia as Windows Logo/Flag Key symbol, ❖Win+B ❖Win </td><td>• “Black Diamond Minus White X” ❖ U+2756 &amp;#10070; used by others+me as Windows Logo/Flag Key symbol </td><td>• Goat 🐐 (emj) &amp;#128016; U+1F410 🐐&#xFE0E;(txt) often used to indicate GNU software, GNU/GPL-License, GNU-Hurd OS, GNU-BSD OS, etc, As 🐐it looks like wildebeest </td></tr>
<tr><td>• Penguin 🐧 (emj) &amp;#128039; U+1F427 🐧&#xFE0E;(txt) often used to indicate GNU-Linux-OS, As 🐧it looks like Tux </td><td> &#160; </td><td> &#160; </td></tr>
</table>
<table width="100%" border="0" cellspacing="0" cellpadding="0" align="center" class="UatErik70">
<tr><td width="32%">• Congruence Relation Symbol ≡ &amp;#8801; &amp;equiv; A 240 U+2261 </td><td width="32%">• Vertical Ellipsis ⋮ U+22EE vellip </td><td>• Menu/App key ▤ </td></tr>
<tr><td>• Identical To ≡ </td><td>• Strictly Identical To ≣ </td><td>• Greek Capital Letter Xi Ξ </td></tr>
<tr><td>• Not-Equal-To ≠ &amp;#8800; &amp;ne; 🍎︎&#xFE0E;⌥Opt&#46;= </td><td>• Almost-Equal-To ≈ &amp;#8776; &amp;asymp; &amp;ap; &amp;approx; 🍎︎&#xFE0E;⌥Opt+x </td><td>• Division ÷ &amp;#247; 🍎︎&#xFE0E;⌥Opt+? 🍎︎&#xFE0E;⌥Opt+/ ❖Alt+0247 </td></tr>
<tr><td>• Plus-Minus ± &amp;#177; 🍎︎&#xFE0E;⌥Opt+⇧Shift+= ❖Alt+241 </td><td>• Infinity ∞ &amp;#8734; &amp;infin; 🍎︎&#xFE0E;⌥Opt+5 </td><td> &#160; </td></tr>
</table>
<table width="100%" border="0" cellspacing="0" cellpadding="0" align="center" class="UatErik70">
<tr><td width="32%">• White Frowning Face ☹&#xFE0E;/&#65039; &amp;#9785;/&amp;#65039; &amp;#x2639;/&amp;#xFE0F; </td><td width="32%">• Worried Face 😟 0x1F61F &amp;#128543; </td><td>• White Smiling Face ☺&#xFE0E; 0x263A &amp;#9786; </td></tr>
<tr><td>• Slightly Smiling Face 🙂 0x1F642 &amp;#128578; </td><td>• Black Smiling Face ☻&#xFE0E; 0x263B &amp;#9787; </td><td> &#160; </td></tr>
</table>
<table width="100%" border="0" cellspacing="0" cellpadding="0" align="center" class="UatErik70">
<tr><td width="32%">• Ballot Box ☐ &amp;#9744; U+2610 </td><td width="32%">• Ballot Box with Check ☑ &amp;#9745; U+2611 ☑&#xFE0E;(txt) </td><td>• Ballot Box with X ☒ &amp;#9746; U+2612 ☒&#xFE0E;(txt) </td></tr>
</table>
<table width="100%" border="0" cellspacing="0" cellpadding="0" align="center" class="UatErik70">
<tr><td width="100%"> To display an Emoji/Emoticon(emj) as a Textual(txt) glyph (if available/renderable), Use this after the emoji : &amp;#xFE0E;<br/>
(or apply CSS, i.e: <code>span.gray { -webkit-filter&#58; grayscale(100%); filter&#58; grayscale(100%); }</code>)<br/>
(More on <a href="https://en.wikipedia.org/wiki/Variant_form_(Unicode)#Variation_Selectors_block">VS15</a>) </td></tr>
<tr><td> http://liberties.wikidot.com/symbols1<br/>http://liberties.wikidot.com/ligatures1 </td></tr>
</table>

<table border="0" width="100%" cellspacing="0" cellpadding="0" align="center" class="UatErik70"><tr><td border="1" width="100%" class="UatErik81"> In macOSX, Calculate & Compare hash/checksum/digest code (it is a very unique identity code) of a file/bundle<b>:</b><br/>
In macOSX in shell (“<code>Terminal</code>” utility) window, type command (<code>shasum</code>) & press <code>space</code> key,<br/>
then drag the <code>.dmg</code> file from <code>Finder</code>(file browser) window & drop it into <code>Terminal</code> window<b>:</b><br/>
The <code>shasum</code> tool by-default calculates the “SHA1” hash-code, & <code>openssl</code> usage also shown<b>:</b>
<dl><dd><!-- “.” is &#46; -->
 <tt>０┌─────────────────</tt><br/>
 <tt>１│</tt>MacNm:~ UsrNm$ <b>shasum</b> /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1&#46;dmg<br/>
 <tt>２│</tt>50ff626452dfadb9cbb6a2a5e2ddf60848adf256  /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1&#46;dmg<br/>
 <tt>３│</tt>MacNm:~ UsrNm$ <b>shasum -a 1</b> /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1&#46;dmg<br/>
 <tt>４│</tt>50ff626452dfadb9cbb6a2a5e2ddf60848adf256  /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1&#46;dmg<br/>
 <tt>５│</tt>MacNm:~ UsrNm$ <b>openssl sha1</b> /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1&#46;dmg<br/>
 <tt>６│</tt>SHA1(/Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg)= 50ff626452dfadb9cbb6a2a5e2ddf60848adf256<br/>
 <tt>７└─────────────────</tt>
</dd></dl>
To calculate “SHA256” hash-code, use <code>-a 256</code> option in <code>shasum</code>, & <code>openssl</code> usage also shown<b>:</b>
<dl><dd><!-- “.” is &#46; -->
 <tt>０┌─────────────────</tt><br/>
 <tt>１│</tt>MacNm:~ UsrNm$ <b>shasum -a 256</b> /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1&#46;dmg<br/>
 <tt>２│</tt>e0052b8423cc117c99371a97e51a6ef9948510ac9a9c0ec1f2537be3597bad57  /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1&#46;dmg<br/>
 <tt>３│</tt>MacNm:~ UsrNm$ <b>openssl sha256</b> /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1&#46;dmg<br/>
 <tt>４│</tt>SHA256(/Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1&#46;dmg)= e0052b8423cc117c99371a97e51a6ef9948510ac9a9c0ec1f2537be3597bad57<br/>
 <tt>５└─────────────────</tt>
</dd></dl>
To calculate “MD5” hash-code, use <code>md5</code> option in <code>openssl</code><b>:</b>
<dl><dd><!-- “.” is &#46; -->
 <tt>０┌─────────────────</tt><br/>
 <tt>１│</tt>MacNm:~ UsrNm$ <b>openssl md5</b> /Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1&#46;dmg<br/>
 <tt>２│</tt>MD5(/Users/UsrNm/Downlo…/PortableFirefox_4.0.1_en-US-OSX_r4.1&#46;dmg)= fa6691336e22a2d83e5629533b830300<br/>
 <tt>３└─────────────────</tt>
</dd></dl>
</td></tr>
</table>

<table border="0" width="100%" cellspacing="0" cellpadding="0" align="center" class="UatErik70">
<tr><td border="1" width="100%" class="UatErik81"> Sign (aka: “codesign”, aka: add digital-signature) a macOSX binary app, without being in the Mac Developer Program:<br/>
&#160;&#160; https://stackoverflow.com/questions/27474751/ </td></tr>
<tr><td border="1" width="100%" class="UatErik81"> &#160; </td></tr>
</table>

<br/>
