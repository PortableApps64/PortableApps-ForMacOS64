<style type="text/css"> /*<br/><dl><dd>
 Scroll-down to see main content of README.md, or Press/Tap on "View all of README.md".<br/>
 If this Line/Paragraph/&lt;style>..&lt;/style>-CSS-Block is Shown On This README&#46;md,<br/>
 Then GitHub <a href="https://github.com/github/html-pipeline/blob/master/lib/html/pipeline/sanitization%5Ffilter%2Erb">Disabled</a> Usage Of &lt;style>-CSS HTML Tag/Command for all GitHub users!<br/>
 It Appaers That, To Support "GitHub-Pages"-Hosting/DEAL$/…/… GitHub,… Disabled<br/>
 CSS, JS, etc Here, & Directing Users To Use "GitHub-Pages" For CSS/JS/etc.<br/>
 But We Need Basic-CSS Here, As it(&lt;style>) Helps Developers/Users To Define Simple CSS<br/>
 To Present/Show Distinct-Contents Distinctly+Accurately.<br/>
 GitHub Already <a href="https://github.com/github/html-pipeline/blob/master/lib/html/pipeline/sanitization%5Ffilter%2Erb">Applying</a> Filtering/Restrictions On HTML Commands, So Contact<br/>
 GitHub-Support & Request Them To Unblock+Enable Essential Function(s), Tell<br/>
 GitHub-Support To Apply Filtering Also For CSS/JS Commands Inside "&lt;STYLE>" & "&lt;SCRIPT>" Commands,<br/>
 to AtLeast Allow CSS & JS With Limited/Restricted Functionalities/Abilities, like:<br/>
 Element+Text Coloring, Positioning, Width/Margin/Padding/Height/etc Controlling, etc,etc.<br/>
 For This README&#46;md Page, Few Txt/Inl/Blk/etc Element’s Style(Look/Appearance/etc)<br/>
 OverRiding CSS Rules Are Defined Below:</dd></dl>
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
/* <br/> Table-Cell-Border for Borderless-Table:<br/> */
.UatErik70 td,.UatErik70 th,.UatErik70 tbody td,.UatErik70 tbody th{ border-width:1px; margin:0px; padding:0px; }
/* <br/> Border-1:<br/> */
.UatErik81{ border-width:1px; width:100%; margin:0px; padding:0px; }
/* <br/> Top & Bottom Border Without Sides:<br/> */
.UatErik82{ border-width:1px; border-width-top:1px; border-width-bottom:1px; border-width-left:0px; border-width-right:0px; width:100%; }
/* <br/> Only Bottom Border:<br/> */
.UatErik83{ border-width:1px; border-width-top:0px; border-width-bottom:1px; border-width-left:0px; border-width-right:0px; width:100%; } /* <br/> END of CSS STYLEs: */
</style>

<a name="intro"></a>
# PORTABLE FIREFOX OS X 64
<br/><!-- “.” is &#46; -->

Script, Config(s), Setting(s), instruction(s), etc for Portable Firefox OS X 64

<a name="index"></a><!-- “:” = &#58; -->
<dl><dd>Content/Index List<b>:</b> ¦ <a href="#intro">Intro</a> 
 ¦ <a href="#Old-Script">Old-Script</a> 
 ¦ <a href="#Script-Type">Script-Type</a> ¦ <a href="#New-Script">New-Script</a> 
 ¦ <a href="#BuildTools">Build/Run-Tools</a> ( <a href="#PA-OSX64">Portable-Apps-OS-X-64</a> 
  ¦ <a href="#Xcode">Xcode</a> ¦ <a href="#Platypus">Platypus</a> 
  ¦ <a href="#Cocoa-Dialog">Cocoa-Dialog</a> ¦ <a href="#Pashua">Pashua</a> ) 
 ¦ <a href="#pre-build">Pre-Build</a> 
  ( <a href="#pb-1">PB-1</a> ¦ <a href="#pb-2">PB-2</a> ¦ <a href="#pb-3">PB-3</a> 
  ¦ <a href="#pb-4">PB-4</a> ¦ <a href="#pb-5">PB-5</a> ) 
 ¦ <a href="#build">Build</a> 
  ( <a href="#b-1">B-1</a> ¦ <a href="#b-2">B-2</a> ¦ <a href="#b-3">B-3</a>
  ¦ <a href="#b-4">B-4</a> ¦ <a href="#b-5">B-5</a> ) 
 ¦ <a href="#Errors">Errors</a> 
 ¦ <a href="#HelpToBuild">Help-To-Build</a> 
 ¦ <a href="#extra-notes">Extra-Notes</a> 
  ( <a href="#VerifyFileAuthenticity">Verify File Authenticity</a> ) 
 ¦</dd>
<dd><div align="center">
 <b>◦</b> macOSX Catalina version is 10.15.x (mostly 64bit-only)<br/>
 <b>◦</b> macOSX Mojave version is 10.14.x (64bit+32bit)
</div></dd>
</dl>

<a name="Old-Script"></a>
<b>OLD SCRIPT:</b><br/><!-- %2E is "." , %3A is ":" , %20 is " "(space), %5F is "_" -->
<div> Original & Last ‘script’ v4.1 is here<b>:</b> 
 <a href="http://www.FreeSMUG.org/portableapps%3Acode%3Afirefox" target="_blank">http://www.FreeSMUG.org/portableapps:code:firefox</a><br/>
 ( You can also check 1st commit of this ‘script’ file here in Github 
 to view the v4.1 code )<br/>
 The ‘script’ v4.1 was written by Carlo Gandolfi and Paolo Portaluri and others,<br/>
 Copyright 2010 by Carlo Gandolfi, and, Paolo Portaluri, Released under 
 <a href="https://www.GNU.org/licenses/gpl-3.0.en.html" target="_blank">GPL v3</a>.<br/>
 Project’s SF page: 
 <a href="https://SourceForge.net/projects/osxportableapps/" target="_blank">https://SourceForge.net/projects/osxportableapps/</a><br/>
Project Website: <a href="http://www.FreeSMUG.org/" target="_blank">http://www.FreeSMUG.org/</a><br/>
Portable Firefox OSX (GPL-v3, 
<a href="https://www.Mozilla.org/en-US/MPL/1.1/" target="_blank">MPL-1.1</a>) is here<b>:</b><br/>
&#160;<a href="https://SourceForge.net/projects/osxportableapps/files/Portable%20Firefox%20OS%20X/" target="_blank">https://SourceForge.net/projects/osxportableapps/files/Portable Firefox OS X/</a><br/>
The ‘script’ v4.1 is now distributed via a ZIP file located here<b>:</b><br/>
&#160;<a href="https://prdownloads.SourceForge.net/osxportableapps/PortableFirefoxScript%5Fr4%2E1%2Etxt%2Ezip?download" target="_blank">https://prdownloads.SourceForge.net/osxportableapps/PortableFirefoxScript_r4.1.txt.zip?download</a><br/>
Last “Portable Firefox OSX” app<b>:</b> "PortableFirefox_4.0.1_en-US-OSX_r4.1&#46;dmg", 28.2 MBytes,
<dl><dd>
 sha1: 50ff626452dfadb9cbb6a2a5e2ddf60848adf256,<br/>
 md5: fa6691336e22a2d83e5629533b830300.<br/>
 <a href="https://SourceForge.net/projects/osxportableapps/files/Portable%20Firefox%20OS%20X/4%2E0%2E1%20r4%2E1/" target="_blank">https://SourceForge.net/projects/osxportableapps/files/Portable Firefox OS X/4.0.1 r4.1/</a>
</dd></dl>
</div><br/>


<a name="Script-Type"></a>
<b>WHAT TYPE OF ‘script’ FILE:</b><br/>
The ‘<b>script</b>’ is a bash shell script file, Executable file, and it is also the source code file.<br/>
<br/>


<a name="New-Script"></a><a name="License"></a>
<b>NEW SCRIPT:</b>🆕<br/><!-- “(” = %28 , “)” = %29 , “.” = &#46; -->

New ‘<a href="script">script</a>’ v4.1.x (v4.1.4) Are released with+under below (multiple) <b>License</b>(s) + 
 <b>Restrictions</b>+<b>Permissions:</b><br/>
&#160;&#160;<b>◦</b> GNU General Public License Version 3 
 (<a href="https://www.GNU.org/licenses/gpl-3.0.en.html" target="_blank">GPL v3</a>)<br/>
&#160;&#160;<b>◦</b> Do Not Use This To Kill/Harm/Violate (or Steal from) (Any) Human/Community,Earth,etc<br/>
&#160;&#160;<b>◦</b> Copyright <b>©</b> 2020 Erik T Ashfolk (&lt;at&#69;rik＠Ö&#965;ťĹö&#333;ķ·ċ&#333;m;
 at&#69;rik＠&#65;śh&#70;ölķ·ć&#333;m&gt; 
 Use <a href="https://en.Wikipedia.org/wiki/Basic_Latin_%28Unicode_block%29" target="_blank">basic-latin</a> char. 
 No soliciting permitted)&#46; All rights reserved.<br/>
&#160;&#160;<b>◦</b> (All other trademarks, etc cited here are the property of their respective owners&#46;)<br/>
&#160;&#160;<b>◦</b> (All other copyright items cited here are the copyright of their respective author/creator&#46;)

This ‘script’ v4.1/v4.1.x file is usually used from such (i.e) location, in macOSX<b>:</b><br/>
&#160;&#160;"/MyPortableDriveName/PortableAppsOSX/MyPortableFF_for_Test/Portable Firefox OS X/Portable Firefox&#46;app/Contents/Resources/script"<br/>
<!-- “.” is &#46; -->
This ‘script’ v4.1/v4.1.x is used by the below “Portable Firefox”, a binary executable file<b>:</b><br/>
&#160;&#160;"/MyPortableDriveName/PortableAppsOSX/MyPortableFF_for_Test/Portable Firefox OS X/Portable Firefox&#46;app/Contents/MacOS/Portable Firefox"<br/>
<!-- “.” is &#46; -->
<div> That binary “Portable Firefox” is created by Platypus,<br/>
Platypus also creates the <code>“Portable Firefox.app”</code> bundle.<br/>
That binary is then placed inside the <code>“Portable Firefox.app”</code> bundle.<dl>
<dd>
 <b>◦</b> A developer/user can either place/compress that <code>Portable-*.app</code> 
  bundle inside a <code>*.dmg</code> file, to share it with users/others for downloading, 
  from developer/user’s website, (Note: pkg must include all license(s) & source files).<br/>
 <b>◦</b> Or, a developer/user can build the <code>Portable-*.app</code> with an (older) 
  unmodified (official Firefox) app, and share with Users the <code>*.app</code> or 
  <code>*.dmg</code> bundle/file with an accompanying instruction/readme file on 
  How-To update/change included Firefox, into latest or another Firefox app. 
  (Note: pkg must include all license(s) & source files).
</dd><dd><div width="100%" align="center">Goto <a href="#intro">Top</a> or <a href="#index">Index</a></div></dd></dl>
</div>

<a name="BuildTools"></a><a name="RunTools"></a>
## BUILD TOOLS & EXECUTION/RUN TOOLS:
We use various (mentioned in below) tools to build our binary executable, 
 & we also use (mentioned in below) tools to assist our-project 
 tool during execution, & for executing the App either as portable 
 app or as multi-instance of same app.

<a name="PA-OSX64"><a name="License"></a>
<div><b>Portable Apps OSX 64:</b><br/>
 Script(s)/Tool(s), Config(s)/Settings, etc For “Portable-Apps-OS-X-64" 
 (this project) are released with following <b>License</b>(s) + Restrictions + 
 Permissions<b>:</b><dl>
 <dd> 
  <b>◦</b> GNU General Public License Version 3 
  (<a href="https://www.GNU.org/licenses/gpl-3.0.en.html" target="_blank">GPL v3</a>)<br/>
  <b>◦</b> Do Not Use This To Kill/Harm/Violate (or Steal-from)(Any) Human/Community,Earth,etc<br/>
  <b>◦</b> Copyright <b>©</b> 2020 Erik T Ashfolk (&lt;at&#69;rik＠Ö&#965;ťĹö&#333;ķ·ċ&#333;m;
  at&#69;rik＠&#65;śh&#70;ölķ·ć&#333;m&gt; Use 
  <a href="https://en.Wikipedia.org/wiki/Basic_Latin_%28Unicode_block%29" target="_blank">basic-latin</a> 
  char. No soliciting permitted)&#46; All rights reserved.<br/>
  <b>◦</b> (All other trademarks, etc cited here are the property of their respective owners&#46;)<br/>
  <b>◦</b> (All other copyright items cited here are the copyright of their respective author/creator&#46;)</dd>
 </dl>
</div>

<a name="Xcode"></a>
<div><b>Xcode:</b><br/>
 Xcode is released by Apple. It can perform verious functionalities: 
 App building/developing IDE, source-code management, compiler, command-line compiler, 
 etc, etc, etc, etc.<br/>
 At currrent stage of this project, we will-be/are using Xcode 
 command-line tools, mostly.
</div>

<a name="Platypus"></a>
<div><b>PLATYPUS:</b><br/>
 The "Portable Firefox&#46;app" is packaged using the Platypus script 
 wrapper (aka app builder) from <a href="http://sveinbjorn.sytes.net/platypus" target="_blank">http://sveinbjorn.sytes.net/platypus</a>
<dl><dd><!-- “.” is &#46; -->
 New website: <a href="https://Sveinbjorn.org/platypus" target="_blank">https://Sveinbjorn.org/platypus</a><br/>
 GitHub: https://GitHub.com/sveinbjornt/Platypus<br/>
 Platypus is licensed under <a href="BSD-3-clause.txt">BSD-3-clause</a>, 
 & Platypus (v5.3 & later version) seems to be able to generate 64bit-only 
 compatible app bundles, but it does not (digitally) sign or provides any 
 option to sign the generated app bundle, So it seems, only Admin level 
 privileged user can use+run Platypus generated apps in 64bit-only 
 macOSX(Catalina & macOSX after it), and in 64bit+32bit supported 
 macOSX(Mojave & macOSX before it) less privileged user can run it.
</dd></dl>
</div><br/>

<a name="Cocoa-Dialog"></a>
<div><b>COCOA-DIALOG:</b><br/>
 The OSX PortableApps used CocoaDialog (&#46;app bundle) inside “PortableFirefoxOSX” v4.0.1 
 (the last/old release). CocoaDialog is licensed under 
 <a href="https://www.GNU.org/licenses/old-licenses/lgpl-2.0.html" target="_blank">GPL-2.0</a>.
<dl><dd><!-- “.” is &#46; -->
 But (old) CocoaDialog is NOT compatible with 64bit-only-macOSX yet, afaik.<br/>
 Website: <a href="https://CocoaDialog.com/" target="_blank">https://CocoaDialog.com/</a><br/>
 GitHub: https://github.com/cocoadialog/cocoadialog<br/>
 So App-bundle/DMG etc which includes old CocoaDialog cannot run on 
 64bit-only macOSX (Catalina & later...)<br/>
 and app⒮ built/wrapped with older Platypus also cannot run in 64bit-only macOSX,<br/>
 as old Platypus was not completely 64bit compatible.
</dd></dl>
</div>
So we must change existing dialog program (a program to assist in interaction between user & script) functions 
 in old ‘script’, into something else, like: Pashua, & create a new ‘script’.<br/>
<br/>

<a name="Pashua"></a>
<div><b>PASHUA:</b><br/>
 Pashua dialog seems to be a good choice for now (as a ‘dialog’/interaction assistor), 
 (its licensed-under <a href="BSD-3-clause.txt">BSD-3-clause</a>), Check here<b>:</b>
<dl width="100%"><dd width="100%">
 Website: <a href="https://www.BlueM.net/en/projects/pashua/" target="_blank">https://www.BlueM.net/en/projects/pashua/</a><br/>
 Github: https://GitHub.com/BlueM/Pashua
</dd><dd><div width="100%" align="center">Goto <a href="#intro">Top</a> or <a href="#index">Index</a></div></dd></dl>
</div><br/>

## PRE-BUILD:
<b>BRING TOGETHER BUILD-RELATED ITEMS/OBJECTS,ETC (PREPARATION):</b>

<div><a name="pb-1"></a>PB-1: Suppose, We are working-on/building this project from below (example) folder<b>:</b>
<dl><dd><!-- “:” = &#58; -->
 <code>"/System/Volumes/Data/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/"</code><br/>
<dl><dd>Above folder can also be accessed in this shorter way in (Catalina or) macOS (after it)<b>:</b><br/>
 &#160;<code>"/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/"</code><br/>
 Follow <a href="../../README.md#LoadFoldersUnderRootFolder">Create Folder(s) Under RootFolder</a> section for Catalina or macOS after it.
</dd></dl>
 Another option is to create a build/developement related folder “PA-Firefox-OSX64” inside your own userspace<b>:</b>
<dl><dd>
  <code>"/Users/MyUserName/MyProjects/PA-OSX64/PA-Firefox-OSX64/"</code><br/>
  PA = Portable App
</dd></dl>
</dd></dl>
</div>
<div> So when Platypus will generate the new <code>“Portable Firefox OSX64.app”</code> bundle, 
 it will be placed here<b>:</b>
<dl><dd>
 <code>"/System/Volumes/Data/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/Portable Firefox OSX64.app"</code><br/>
 (or, in its shorter form, here: 
 <code>"/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/Portable Firefox OSX64.app"</code>)
</dd></dl>
</div>
<div> To build with Platypus, we will have to choose (various needed files, directories & 
 bundles, etc from above location), inside the Platypus GUI interface/settings. After Platypus 
 builds a <code>*.app</code> bundle, Platypus places/copies those inside the bundle-folder 
 location shown below<b>:</b>
<dl><dd>
 <code>"/System/Volumes/Data/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/Portable Firefox OSX64.app/Contents/Resources/"</code><br/>
 ( above location’s shorter form is: 
 <code>"/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/Portable Firefox OSX64.app/Contents/Resources/"</code> )
</dd></dl>
</div><br/>

<a name="pb-2"></a>PB-2: So obtain NEW Platypus (at the time of writing this README&#46;md, it is/was v5.3),<br/>
&#160;&#160; from here: 
<a href="https://Sveinbjorn.org/platypus" target="_blank">https://Sveinbjorn.org/platypus</a><br/>
and install in your (64bit-only macOSX(Catalina & later) based) Mac computer.<br/>
Or get Platypus v4.9, as that is the last 32bit supported ( & working) Platypus,<br/>
to build/wrap macOS app⒮ inside 64bit+32bit suppported macOSX (Mojave or earlier macOSX).<br/>

<div><a name="pb-3"></a>PB-3: Obtain Pashua dialog from here : 
 <a href="https://www.BlueM.net/en/projects/pashua/" target="_blank">https://www.BlueM.net/en/projects/pashua/</a>
<dl><dd>Open dmg installer, Copy "Pashua&#46;app", "Pashua&#46;sh" into below build related folder<b>:</b><br/>
<!-- “.” = &#46; -->&#160;<code>"/System/Volumes/Data/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/"</code><br/>
&#160;( shorter form of above location is: 
 <code>"/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/"</code> )<br/>
&#160;( or, Copy in your Userspace: 
 <code>"/Users/MyUserName/MyProjects/PA-OSX64/PA-Firefox-OSX64/"</code> )<br/>
&#160;( PA = Portable App )
</dd></dl>
</div><br/>

<div><a name="pb-4"></a>PB-4: Get last Gecko-based (Gecko-WithOut-Servo) old 
 <code>"Firefox-*.dmg"</code> (which has old <code>“Firefox.app”</code> inside it) 
 from below URLs,<br/>
 or Get last/new Quantum(Servo-based) <code>"Firefox-*.dmg"</code> from 
 <a href="https://www.Mozilla.org/" target="_blank">https://www.Mozilla.org/</a><br/>
 & extract/get/copy the <code>“Firefox.app”</code> from it, & place/paste it into 
 our build related folder<b>:</b>
<dl><dd>
 <code>"/System/Volumes/Data/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/"</code><br/>
 ( above location’s shorter form is: 
 <code>"/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/"</code> )<br/>
 ( or Paste in your Userspace: 
 <code>"/Users/MyUserName/MyProjects/PA-OSX64/PA-Firefox-OSX64/"</code> )<br/>
 ( PA = Portable App )
</dd></dl>
</div>
<dl><dd>The last security-updated Gecko-based & non-ESR (old) Firefox<b>:</b><dl>
  <dd>
  FF v56.0.2 dmg file’s sha1: 79a0013664134ced2307c8e1ffa5d36f6256e8f,<br/>
  md5: a5608df45832df3ff302a7ccbe7ec3f6, 54.5 MBytes,<br/>
  <a href="https://ftp.Mozilla.org/pub/firefox/releases/56%2E0%2E2/" target="_blank">https://ftp.Mozilla.org/pub/firefox/releases/56.0.2/</a>
  </dd><dl>
</dd><dd>The last gecko-based old Firefox-ESR<b>:</b><dl>
  <dd>
  FF v52.9.0 ESR dmg file’s sha1: d879f5423d79393f2384e0f97a5581f9d89d7977,<br/>
  md5: 34e8280bb9b33ca202ba22cf9daf25e4, 82.8 MBytes,<br/>
  <a href="https://ftp.Mozilla.org/pub/firefox/releases/52%2E9%2E0esr/" target="_blank">https://ftp.Mozilla.org/pub/firefox/releases/52.9.0esr/</a>
  </dd></dl><!-- “.” = %2E -->
</dd><dd>Note: ESR = Extended Support Release.
</dd></dl>
<br/>

<div><a name="pb-5"></a>PB-5: Get (Language, Profile, License, etc) build related 
 files/folders/bundles:<br/>
<b>a:</b> Use GitHub’s “Clone or Download” button & select “Download ZIP”, save zip file, 
 goto default download location folder “Downloads”, double-click/tap on zip file (to 
 decompress it), you’ll get a folder with same-name (without the “zip” extension), 
 then Copy all files inside that folder, & Paste into our build folder:<dl><dd> 
 <code>"/System/Volumes/Data/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/"</code><br/>
 ( above location’s shorter form is: 
 <code>"/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/"</code> )<br/>
 ( or Paste into your userspace: 
 <code>"/Users/MyUserName/MyProjects/PA-OSX64/PA-Firefox-OSX64/"</code> )</dd></dl></div>
<b>b:</b> Skip below files/steps which you’ve already obtained/exists or already done.<br/>
<b>c:</b> Obtain old PortableFirefoxOSX App. (Download <a href="#Old-Script">link⒮</a> 
 shown few-paragraphs above).<br/>
<b>d:</b> Double-Click/Tap on `"PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg"` file to view 
 internal contents(files, bundles, folders, etc).<br/>
<div><b>e:</b><!-- “:” = &#58; --> Copy these 2-files (if does not exist in destination)&#58; 
 `"MPL-1.1.txt"`, `"Read me.txt"`, & Paste into below OSX64 build location:<dl><dd> 
 <code>"/System/Volumes/Data/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/"</code><br/>
 ( above location’s shorter form is: 
 <code>"/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/"</code> )<br/>
 ( or Paste into your userspace: 
 <code>"/Users/MyUserName/MyProjects/PA-OSX64/PA-Firefox-OSX64/"</code> )</dd></dl></div>
<b>f:</b> Create a sub-dir/sub-folder <code>"PA-Firefox-OSX-Old"</code> in same 
 location shown above in PB-5-a step.<br/>
<div><b>g:</b> Copy the <code>"Portable Firefox OS X"</code> folder/directory from opened 
 content of <code>"PortableFirefox_4.0.1_en-US-OSX_r4.1.dmg"</code>, & place/paste it 
 in below sub-dir/sub-folder location:<dl><dd> 
  <code>"/System/Volumes/Data/Projects/Portable-Apps-OS-X-64/F/PA-Firefox-OSX-Old/"</code><br/>
  ( above location’s shorter form is: 
  <code>"/Projects/Portable-Apps-OS-X-64/F/PA-Firefox-OSX-Old/"</code> )<br/>
  ( or Paste in your userpsace: 
  <code>"/Users/MyUserName/MyProjects/PA-OSX64/PA-Firefox-OSX-Old/"</code> )</dd></dl></div>
<div><b>h:</b> Right-click (or Tap with double-finger) on <code>"Portable Firefox.app"</code> 
 bundle which is here:<dl><dd> 
 <code>"/System/Volumes/Data/Projects/Portable-Apps-OS-X-64/F/PA-Firefox-OSX-Old/Portable Firefox OS X/Portable Firefox.app"</code><br/>
 ( above location’s shorter form is: 
 <code>"/Projects/Portable-Apps-OS-X-64/F/PA-Firefox-OSX-Old/Portable Firefox OS X/Portable Firefox.app"</code> )<br/>
 ( or access it from your userspace: 
 <code>"/Users/MyUserName/MyProjects/PA-OSX64/PA-Firefox-OSX-Old/Portable Firefox OS X/Portable Firefox.app"</code> )<br/>
 and select <code>“Show Package Contents”</code> option, to go inside the bundle.</dd></dl></div>
<div><b>i-1:</b><!-- “:” = &#58; --> Copy these 2-folders: <code>"English.lproj"</code> (and <code>"profile"</code> 
 if it exists), from below location (inside the bundle)&#58;<dl><dd> 
 <code>"/System/Volumes/Data/Projects/Portable-Apps-OS-X-64/F/PA-Firefox-OSX-Old/Portable Firefox OS X/Portable Firefox.app/Contents/Resources/"</code><br/>
 ( above location’s shorter form is: 
 <code>"/Projects/Portable-Apps-OS-X-64/F/PA-Firefox-OSX-Old/Portable Firefox OS X/Portable Firefox.app/Contents/Resources/"</code> )<br/>
 ( or here: 
 <code>"/Users/MyUserName/MyProjects/PA-OSX64/PA-Firefox-OSX-Old/Portable Firefox OS X/Portable Firefox.app/Contents/Resources/"</code> )<br/>
 <b>i-2:</b> If you want to use your existing Firefox settings/profile from 
 <code>"Portable Firefox OS X"</code> in your external storage/drive, then Copy 
 <code>"profile"</code> folder from that, & Paste into our build location.<br/>
 <b>i-3:</b> If you want to use your existing Firefox settings/“profile” 
 in your/current system (in your internal drive), with the newer “Portable 
 Firefox OSX64”, then copy below “profile” folder:<br/>
 &#160;&#160;<code>"/Users/MyUserName/Library/Applications Support/Firefox/Profiles/********.default/"</code></dd></dl></div>
<div><b>j:</b> Paste the “profile” folder inside our build related (destination) folder:<dl><dd> 
 <code>"/System/Volumes/Data/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/"</code><br/>
 ( above location’s shorter form is: 
 <code>"/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/"</code> )<br/>
 ( or Paste in your Userspace: 
 <code>"/Users/MyUserName/MyProjects/PA-OSX64/PA-Firefox-OSX64/"</code> 
 )</dd><dd><div width="100%" align="center">Goto <a href="#intro">Top</a> or <a href="#index">Index</a></div></dd>
</dl></div>


## BUILD:
<b>BUILD/WRAP/GENERATE WITH PLATYPUS:</b>

<div><a name="b-1"></a>B-1: Test the ‘script’ file, before using it to build 
 Portable App for OS X 64<b>:</b><br/>
 Tips<b>:</b> a good practice from beginning would-be, After getting this 
 <code>‘script’</code><br/>
 (inside the recommended folder, that is shown few paragraphs above),<br/>
 1st Rename it to <code>"script.sh"</code>, then Open <code>"script.sh"</code> 
 with your choice of code editing/developing editor/build software,<br/>
 Improve/Modify source code, Save,<br/>
 then Use below commands to test if bash code syntaxes are right or where the fault⒮ is/are<b>:</b>
<dl><dd>
 <tt>０┌─────────────────</tt><br/>
 <tt>１│</tt>MacNm:~ UsrNm$ <b>sh -n</b> /System/Volumes/Data/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/script&#46;sh<br/>
 <tt>２│</tt>MacNm:~ UsrNm$ echo &#36;?<!-- “.” = &#46; , “$” = &#36; --><br/>
 <tt>３│</tt>0<br/>
 <tt>４│</tt>MacNm:~ UsrNm$<br/>
 <tt>５└─────────────────</tt><br/><br/>
 ( the above ‘script’ can also be accessed using its short form: 
 <code>"/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/script.sh"</code> )<br/>
( if you're developing from your userspace: 
 <code>"/Users/MyUserName/MyProjects/PA-OSX64/PA-Firefox-OSX64/script.sh"</code> )<br/> 
 When there is no syntax-error, (in other words, When the output is “0”),<br/>
 then copy the <code>"script.sh"</code> in same folder,<br/>
 & Rename the <code>"script.sh Copy"</code> into <code>"script"</code>,<br/>
 then follow next/below stage/procedures.
</dd></dl>
</div><br/>

<div><a name="b-2"></a>B-2: Build the final <code>“Portable Firefox OSX64.app”</code> 
 bundle, by using Platypus<b>:</b>
<dl><dd>
 To build new <code>“Portable Firefox OSX64.app”</code> bundle,<br/>
 choose these below files, directories, bundles, etc inside the Platypus GUI interface<b>:</b>
<dl><dd><!-- “.” is &#46; -->
  <b>◦</b> directory : English&#46;lproj<br/>
  <b>◦</b> directory (optional) : profile<br/>
  <b>◦</b> bundle : Firefox&#46;app<br/>
  <b>◦</b> bundle : Pashua&#46;app<br/>
  <b>◦</b> icon-file : P_Firefox_Caution&#46;icns<br/>
  <b>◦</b> icon-file : appIcon&#46;icns<br/>
  <b>◦</b> sh-script-file : pashua&#46;sh<br/>
  <b>◦</b> sh-script-file : script<br/>
  <b>◦</b> readme-file : Read me&#46;txt<br/>
  <b>◦</b> license-file : GPL-3.0_LICENSE_for_script&#46;txt<br/>
  <b>◦</b> license-file : MPL-1.1&#46;txt<br/>
  <b>◦</b> license-file : MPL-2.0_LICENSE_for_Firefox&#46;txt<br/>
  <b>◦</b> license-file : BSD-3-clause_LICENSE_for_Pashua&#46;txt<br/>
  <b>◦</b> license-file : BSD-3-clause_LICENSE_for_Platypus&#46;txt<br/>
  <b>◦</b> license-file : BSD-3-clause&#46;txt
</dd></dl>
</dd></dl>
</div><br/>

<div><a name="b-3"></a>B-3: Then you may use, these type of settings in Platypus 
 GUI interface<b>:</b>
<dl><dd>
 <b>◦</b> Script Type : Shell : /bin/sh<br/>
 <b>◦</b> Script Path : 
 <code>/System/Volumes/Data/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/script</code><br/>
 &#160;&#160;( above location’s shorter form is: 
 <code>"/Projects/Portable-Apps-OS-X-64/F/PortableFirefoxOSX64/script"</code> )<br/>
 <b>◦</b> Interface : Text Window<br/>
 <b>◦</b> Unselected options : Run with root privileges , Run in background , 
  Accept dropped items<br/>
 <b>◦</b> Selected/Check-Marked options : Remain running after execution<br/>
 <b>◦</b> App Name : Portable Firefox OSX64 (or what you want)<br/>
 <b>◦</b> Fill in other boxes: identifier, author, etc
</dd></dl>
</div><br/>

<a name="b-4"></a>B-4: Then tap/click/select/press the <code>“Create App”</code> 
 button.<br/><!-- “.” is &#46; -->
 It will create/generate a new <code>“Portable Firefox OSX64.app”</code> bundle, that is<br/>
 compatible with 64-only macOSX (Catalina or macOSX after it), and<br/>
 compatible with 64bit+32bit macOSX (Mojave or macOSX earlier of it)

<a name="b-5"></a>B-5: Run/execute/TEST it.
<div><a name="test"></a>You may OPTIONALLY do these:<dl><dd>
 <b>◦</b> Which “profile” folder is used by the running Firefox ?<dl><dd>
  Firefox > FF main menu > Help > Troubleshooting Information > Profile Folder: ...<br/>
  if above info row/line is not-showing a full-PATH of “profile” folder, 
  then press “Show in Finder” button</dd></dl></dd></dl></div>

<a name="Errors"></a>
<b>ERRORs/PROBLEMs:</b><br/>

If you have spotted an bug/error/fault, then let us know,<br/>
 create/report an issue under this project in GitHub.<br/>
 And during/after build, if you received/observed/found Error(s)<br/>
 please Write down what Error⒮ you’re getting,<br/>
 try to research & try to solve as much possible,<br/>
 and/then Let us know about your unsolved errors & Share your code changes<br/>
 either in <a href="http://www.FreeSMUG.org/forum/t-13404441/" target="_blank">FreeSMUG-forum</a> or 
 Create an <a href="https://github.com/atErik/Portable-Apps-OS-X-64/issues/new/choose">Issue</a> 
 here in GitHub, & submit info.<br/>
<br/>
If no errors, even then please share your final working code, your OS info, 
 etc (if you want to)<br/>
 either: by Forking/Cloning (this project) + Edit/Change & Test ‘script’ file 
 in your side/computer + Push your own (successful/working) code-changes inside 
 your own (this)-cloned-project first + then send a Pull-request to this project,<br/>
 or: by Sharing/pasting your code-changes, by using the create new “Issue” option 
 in GitHub under this project.<br/>
<br/>

<a name="HelpToBuild"></a>
<b>HELP TO BUILD:</b><br/>

Please help+contribute+collaborate+improve current codes to build these
(bash-shell) ‘script’ & (C/C++) tools, etc (so-that, these can be run/used 
by Platypus or tools, to run macOSX apps (i.e: `“Firefox.app”`) on (64-bit) 
macOSX from portable/external drive/storage⒮), or as a 
(second/third)/multi-instance of same-app.<br/>
Thanks in advance.
<p width="100%" align="center">Goto <a href="#intro">Top</a> or <a href="#index">Index</a></p>

## EXTRA-NOTES:

<table border="0" width="100%" cellspacing="0" cellpadding="0" align="center" class="UatErik70">
<tr><td border="1" width="100%"><a name="VerifyFileAuthenticity"></a><a name="Hash"></a><a name="Digest"></a><a name="CheckSum"></a> 
 In macOSX, Calculate & Compare hash/checksum/digest code (it is a very unique 
 identity code) of a file/bundle<b>:</b><br/>
 In macOSX in shell (“<code>Terminal</code>” utility) window, type command 
 (<code>shasum</code>) & press <code>space</code> key,<br/>
 then drag the <code>.dmg</code> file from <code>Finder</code>(file browser) 
 window & drop it into <code>Terminal</code> window<b>:</b><br/>
 The <code>shasum</code> tool by-default calculates the “SHA1” hash-code, 
 & <code>openssl</code> usage also shown<b>:</b>
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
To calculate “SHA256” hash-code, use <code>-a 256</code> option in 
 <code>shasum</code>, & <code>openssl</code> usage also shown<b>:</b>
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
<p width="100%" align="center">Goto <a href="#intro">Top</a> or <a href="#index">Index</a></p>
<br/>
