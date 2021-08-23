<h1>Wordpress All In One Migration Plugin version 6.77</h1>

<p>People mainly use this version or below this version for changing file size when you have to import large file.</p>
<h4>Its default upload file size is: 512mb</h4>
<br>
Steps to change upload file size in wordpress:
<ol>
  <li>Go to plugins.</li>
  <li>click Add new.</li>
  <li>click Upload.</li>
  <li>Upload this zip file All-In-One-Wp-Migration-6.77.zip</li>  
  <li>Now go to Plugins => Editor and select All-in-One WP Migration. Once the plugin is loaded in the editor, click on the constants.php file from the right side</li>
  <li>Now its time to edit the code to increase Upload size limit. find this in the file and you will see Max File Size text.<br><br>
    <i>
      // =================<br>
      // = Max File Size =<br>
      // =================<br>
      define( 'AI1WM_MAX_FILE_SIZE', 536870912 * 20 ); <br><br>
      </i>
    You need to add 536870912 * 20 from bellow to change the upload size limit. You can change <i>20</i> to whatever u want. The higher the number the more upload size.</li>
  <li>Now you must click on Update button to save above actions.</li>
    <li>Now go back to import and you will see file upload size is changed.</li>
  </ol>
