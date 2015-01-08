
<h3>Force Download Using PHP</h3>

 <h4>Features</h4>
 <p>Customizable allowed file types for download <br />
Predefined mime type settings for following extensions: zip, pdf, doc, xls, ppt, exe, gif, png, jpg, mp3, wav, mpeg, mpg, mpe, mov, avi<br />
Hotlinking protection<br />
Script can log downloads in plain text file. Log file includes: IP, date/time, filename. Can turn this feature on/off.<br />
Automatic mime type detection (if Mimetype or Fileinfo extension installed on the server)<br />
avoid direct files downloads (hide real file paths)<br /></p>
 
 
 <h4>Installation Guide</h4> 
 
 1. Search this code <br />
 <blockquote>define('BASE_DIR','Your Download Folder Directory');</blockquote>

 2. Change 'Your Download Folder Directory' to you download folder directory.
 3. Test the code.<br />
 <blockquote>Use following syntax for downloads: download.php?f=FileName
</blockquote>
 4. Done
