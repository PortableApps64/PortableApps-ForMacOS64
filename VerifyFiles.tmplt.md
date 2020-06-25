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
