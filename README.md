# backup2ipfs

<b>Syntax:</b><br>
<b>backup2ipfs &lt;command&gt; (--secOFF)</b><br>
copies data recursive from <i>current</i> directory to ipfs<br><br>

*Be aware that ipfs is readable by anyone!!!*<br>
So just store public or encrypted data!<br><br>

<b>Commands:</b><br>
<b>*backup2ipfs copy</b><br>
-&gt; copy data to ipfs<br>
<br>
<b>*backup2ipfs move</b><br>
-&gt; move data to ipfs<br>
<br>
<b>*backup2ipfs rebuild</b><br>
-&gt; get data from ipfs<br>
<br>
<b>*backup2ipfs pin</b><br>
-&gt; exchange hashes for pinning (redundancy)<br>
This is a simple pin exchange service - you store ten pins from others - others store ten pins from you!<br>
You need to install <i>lftp</i>:<br>
<i>sudo apt install lftp</i><br>
<br>
<b>*backup2ipfs redundancy</b><br>
-&gt; calculate how often each hash from your list could be found in ipfs<br>
<br>
<br>
<br>
 for symbolic links ipfs need to be started with mount option!<br>
 ipfs daemon --mount &amp;
 
 <b>To store *non* gpg files set "--secOFF" with script start!</b>
