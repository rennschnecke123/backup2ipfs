# backup2ipfs

<b>Syntax:</b><br>
backup2ipfs &lt;command&gt; (--secOFF)<br>
copies data recursive from <i>current</i> directory to ipfs<br><br>

*Be aware that ipfs is readable by anyone!!!*<br>
So just store public or encrypted data!<br><br>

<b>Commands:</b><br>
*backup2ipfs copy<br>
-&gt; copy data to ipfs<br>
<br>
*backup2ipfs move<br>
-&gt; move data to ipfs<br>
<br>
*backup2ipfs rebuild<br>
-&gt; get data from ipfs<br>
<br>
*backup2ipfs pin<br>
-&gt; pin data to local ipfs server<br>
This is a simple pin exchange service - you store ten pins from others - others store ten pins from you!<br>
You need to install <i>lftp</i>:<br>
<i>sudo apt install lftp</i>
<br>
<br>
 for symbolic links ipfs need to be started with mount option!<br>
 ipfs daemon --mount &amp;
 
 <b>To store *non* gpg files set "--secOFF" with script start!</b>
