## List My Apps Template - Table

<table>
   <tr>
      <td><strong>OS:</strong></td>
      <td>Android</td>
   </tr>
   <tr>
      <td><strong>Type:</strong></td>
      <td>A template for an Android app called '<a href="https://play.google.com/store/apps/details?id=de.onyxbits.listmyapps">List My Apps</a>'</td>
   </tr>
   <tr>
      <td><strong>Language:</strong></td>
      <td>mostly HTML (with extra variables)</td>
   </tr>
   <tr>
      <td><strong>Description:</th>
      <td>This template (when run in an Android app called 'List My Apps') creates a HTML list (in table format) of the apps installed on the device.</td>
   </tr>
   <tr>
      <td><strong>Homepage:</strong></td>
      <td><a href="https://github.com/auberginehill/list-my-apps-template-table">https://github.com/auberginehill/list-my-apps-template-table</a></td>
   </tr>
   <tr>
      <td><strong>Version:</strong></td>
      <td>1.1</td>
   </tr>
   <tr>
      <td><strong>Sources:</strong></td>
      <td>Emojis: <a href="https://api.github.com/emojis">https://api.github.com/emojis</a></td>
   </tr>
</table>



#### Remarks

<table>
    <tr>
        <th><img class="emoji" title="remarks" alt="remarks" height="100%" width="100%" align="absmiddle" src="https://assets-cdn.github.com/images/icons/emoji/unicode/26a0.png"></th>
        <td>
            <ul>
                <li>List My Apps custom templates consist of three fields ("List header", "Item format" and "List footer"). The template code in this project is divided into three parts, which correspond the fields found in List My Apps' Template Editor as described below:<br><br></li>
                <ul>
                    <table>
                        <tr>
                            <td><strong>Filename</strong></td>
                            <td><strong>Field in List My Apps' Template Editor</strong></td>
                        </tr>
                        <tr>
                            <td><a href="https://github.com/auberginehill/list-my-apps-template-table/blob/master/file_header.md">file_header.md</a></td>
                            <td>"List header, may be blank"</td>
                        </tr>
                        <tr>
                            <td><a href="https://github.com/auberginehill/list-my-apps-template-table/blob/master/body.md">body.md</a></td>
                            <td>"Item format, may not be blank"</td>
                        </tr>
                        <tr>
                            <td><a href="https://github.com/auberginehill/list-my-apps-template-table/blob/master/file_footer.md">file_footer.md</a></td>
                            <td>"List footer, may be blank"</td>
                        </tr>
                        <tr>
                            <td><a href="https://github.com/auberginehill/list-my-apps-template-table/blob/master/all_in_one.md">all_in_one.md</a></td>
                            <td>Contains all the above mentioned three parts in one file.</td>
                        </tr>
                    </table>
                </ul>
                <li>After a HTML-file has been created, the template included in the bottom of that file is limited. If that
                    limited template of the created HTML-file is to be used as a template in 'List My Apps' -app:<br><br>
                    <ul>
                        <li>All instances of [dollar_sign] need to be changed with $</li>
                        <li>File Footer ends before [End Of Line].</li>
                    </ul>
                    <br></li>
                <li>However, if the template code has been copied from this project (i.e.
                    <a href="https://github.com/auberginehill/list-my-apps-template-table">https://github.com/auberginehill/list-my-apps-template-table</a>) [dollar_sign] strings should be left as they are.</li>
            </ul>
        </td>
    </tr>
</table>



#### Tutorial

<p>To open this code with an Android device, for instance:</p>

<table>
    <tr>
        <th><img class="emoji" title="tutorial" alt="tutorial" height="100%" width="100%" align="absmiddle" src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4d6.png"></th>
        <td>
            <ol>
                <p>
                    <li>Create a new template in '<a href="https://play.google.com/store/apps/details?id=de.onyxbits.listmyapps">List My Apps</a>'
                        -app's Template Editor by clicking Options (three dots) → Template Editor → Add. [<a href="http://groovyandroid.com/wp-content/uploads/2013/10/List-My-Apps-select-all.png">Screenshot</a>]</li>
                </p>
                <p>
                    <li>Type in a name for the template.<br><br>
                       <ol>
                          <img class="screenshot" title="screenshot" alt="screenshot" height="70%" width="70%" align="absmiddle" src="https://github.com/auberginehill/list-my-apps-template-table/blob/master/list_my_apps_-_template_editor.png">
                       </ol>
                    </li>
                </p>
                <p>
                    <li>Paste all the appropriate template data (the three sections as specified below) to 'List My Apps' and
                        save the template.<br><br>
                        <ol>
                            <table>
                                <tr>
                                    <td><strong>Filename</strong></td>
                                    <td><strong>Field in List My Apps' Template Editor</strong></td>
                                </tr>
                                <tr>
                                    <td><a href="https://github.com/auberginehill/list-my-apps-template-table/blob/master/file_header.md">file_header.md</a></td>
                                    <td>"List header, may be blank"</td>
                                </tr>
                                <tr>
                                    <td><a href="https://github.com/auberginehill/list-my-apps-template-table/blob/master/body.md">body.md</a></td>
                                    <td>"Item format, may not be blank"</td>
                                </tr>
                                <tr>
                                    <td><a href="https://github.com/auberginehill/list-my-apps-template-table/blob/master/file_footer.md">file_footer.md</a></td>
                                    <td>"List footer, may be blank"</td>
                                </tr>
                                <tr>
                                    <td><a href="https://github.com/auberginehill/list-my-apps-template-table/blob/master/all_in_one.md">all_in_one.md</a></td>
                                    <td>Contains all the above mentioned three parts in one file.</td>
                                </tr>
                            </table>
                        </ol>
                    </li>
                </p>
                <p>
                    <li>Go back to the 'List My Apps' -app's home screen and select the name that was created in Step 2 from
                        the 'Copy/Share as:' -dropdown menu. Please also select the apps that you'd like to be included in
                        the list. [<a href="http://groovyandroid.com/wp-content/uploads/2013/10/List-My-App-HTML-list.png">Screenshot</a>]</li>
                </p>
                <p>
                    <li>'Run' the 'List My Apps' -app with the new template by copying the app data to Clipboard \[Copy\] (since direct sharing may not work, if a lot of applications has been installed).
                        <ul>
                            <li>There seems to be some kind of a limit, how much data the Android Clipboard can contain. With
                                verbose templates ~200 apps might be the upper limit, but with a simple template, the Android
                                Clipboard clearly is capable of containing considerably more app data.</li>
                        </ul>
                    </li>
                </p>
                <p>
                    <li>Open a HTML editor, such as <a href="https://play.google.com/store/apps/details?id=com.aor.droidedit">DroidEdit Free</a>.</li>
                </p>
                <p>
                    <li>Paste the app data (source code generated by 'List My Apps' in Step 5) from Clipboard to the HTML editor.
                        <ul>
                            <li>If nothing happens (no data is pasted to a HTML editor after a few seconds), try selecting fewer
                                apps in 'List My Apps' and go back to Step 5.</li>
                            <ul>
                                <li>Depending on the hardware some lagging may occur when trying to paste, say ~10000 lines of
                                    code, in an Android device.</li>
                            </ul>
                            <li>If "old data" gets pasted to a HTML editor (i.e. "the data that was in the Clipboard before List My Apps' 'Copy to Clipboard' -button was clicked"), try selecting fewer apps in 'List My Apps' and go back to Step 5.
                            </li>
                        </ul>
                        </li>
                </p>
                <p>
                    <li>Save the file as a HTML file, for example as 'Installed_Apps.html', for example in 'Home/Documents' folder (a filename without any spaces is recommended).</li>
                </p>
                <p>
                    <li>Open the HTML-file with an appropriate app, such as a browser by surfing directly to the file location, which could, for instance, be: <a href="file:///storage/emulated/0/Documents/Installed_Apps.html">file:///storage/emulated/0/Documents/Installed_Apps.html</a>
                        <ul>
                            <li>In a browser the spaces in the filename can be replaced with %20 to make the link work. For more
                                exotic filename characters, see <a href="http://www.w3schools.com/tags/ref_urlencode.asp">HTML URL Encoding Reference</a>.</li>
                        </ul>
                        </li>
                </p>
                <p>
                    <li>Conversion from HTML to PDF might work with <a href="https://play.google.com/store/apps/details?id=org.mozilla.firefox">Firefox (for Android)</a>                        (Options (three dots) → Page → Save as PDF) or perhaps with the printing option in the default Android
                        File Manager.</li>
                </p>
            </ol>
        </td>
    </tr>
</table>











1. Create a new template in [List My Apps](https://play.google.com/store/apps/details?id=de.onyxbits.listmyapps)' -app's Template Editor by clicking Options (three dots) → Template Editor → Add. [[Screenshot](http://groovyandroid.com/wp-content/uploads/2013/10/List-My-Apps-select-all.png)]

2. Type in a name for the template.
   ![screenshot](https://github.com/auberginehill/list-my-apps-template-table/blob/master/list_my_apps_-_template_editor.png "screenshot")

3. Paste all the appropriate template data (the three sections as specified below) to 'List My Apps' and save the template.

   |  Filename                          |  Field in List My Apps' Template Editor                     |
   |  -------------                     |  -------------                                              |
   |  [file_header.md](file_header.md)  |  "List header, may be blank"                                |
   |  [body.md](body.md)                |  "Item format, may not be blank"                            |
   |  [file_footer.md](file_footer.md)  |  "List footer, may be blank"                                |
   |  [all_in_one.md](all_in_one.md)    |  Contains all the above mentioned three parts in one file.  |

4. Go back to the 'List My Apps' -app's home screen and select the name that was created in Step 2 from the 'Copy/Share as:' -dropdown menu. Please also select the apps that you'd like to be included in the list. [[Screenshot](http://groovyandroid.com/wp-content/uploads/2013/10/List-My-App-HTML-list.png)]

5. 'Run' the 'List My Apps' -app with the new template by copying the app data to Clipboard \[Copy\] (since direct sharing may not work, if a lot of applications has been installed).
   - There seems to be some kind of a limit, how much data the Android Clipboard can contain. With verbose templates ~200 apps might be the upper limit, but with a simple template, the Android Clipboard clearly is capable of containing considerably more app data.

6. Open a HTML editor, such as [DroidEdit Free](https://play.google.com/store/apps/details?id=com.aor.droidedit).

7. Paste the app data (source code generated by 'List My Apps' in Step 5) from Clipboard to the HTML editor.
   - If nothing happens (no data is pasted to a HTML editor after a few seconds), try selecting fewer apps in 'List My Apps' and go back to Step 5.
      - Depending on the hardware some lagging may occur when trying to paste, say ~10000 lines of code, in an Android device.
   - If "old data" gets pasted to a HTML editor (i.e. "the data that was in the Clipboard before List My Apps' 'Copy to Clipboard' -button was clicked"), try selecting fewer apps in 'List My Apps' and go back to Step 5.

8. Save the file as a HTML file, for example as 'Installed_Apps.html', for example in 'Home/Documents' folder (a filename without any spaces is recommended).

9. Open the HTML-file with an appropriate app, such as a browser by surfing directly to the file location, which could, for instance, be: file:///storage/emulated/0/Documents/Installed_Apps.html
   - In a browser the spaces in the filename can be replaced with %20 to make the link work. For more exotic filename characters, see [HTML URL Encoding Reference](http://www.w3schools.com/tags/ref_urlencode.asp).

10. Conversion from HTML to PDF might work with [Firefox (for Android)](https://play.google.com/store/apps/details?id=org.mozilla.firefox) (Options (three dots) &rarr; Page &rarr; Save as PDF) or perhaps with the printing option in the default Android File Manager.
   
   <table>
      <tr>
        <th><img class="emoji" title="bulb" alt="bulb" height="60%" width="60%" align="absmiddle" src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f4a1.png"></th>
        <th>Tip:</th>
        <td>To see the code (<a href="https://github.com/auberginehill/list-my-apps-template-table/blob/master/all_in_one.md">all_in_one.md</a>) in action, a real-time Online HTML Editor can be found at: <a href="http://htmledit.squarefree.com/">http://htmledit.squarefree.com/</a></td>
      </tr>
   </table>



#### Contributing

<p>Find a bug? Have a feature request? Here is how you can contribute to this project:</p>

 <table>
   <tr>
      <th><img class="emoji" title="contributing" alt="contributing" height="28px" width="28px" align="absmiddle" src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f33f.png"></th>
      <td><strong>Bugs:</strong></td>
      <td><a href="https://github.com/auberginehill/list-my-apps-template-table/issues">Submit bugs</a> and help us verify fixes.</td>
   </tr> 
   <tr>
      <td rowspan="4"></td>
      <td><strong>Feature Requests:</strong></td>
      <td>Feature request can be submitted by <a href="https://github.com/auberginehill/list-my-apps-template-table/issues">creating an Issue</a>.</td>
   </tr> 
   <tr>
      <td><strong>Edit Source Files:</strong></td>
      <td><a href="https://github.com/auberginehill/list-my-apps-template-table/pulls">Submit pull requests</a> for bug fixes and features and discuss existing proposals.</td>
   </tr>
   <tr>
      <td><strong>Testing:</strong></td>
      <td>Download a template from this repo and try it out in <a href="https://play.google.com/store/apps/details?id=de.onyxbits.listmyapps">List My Apps</a>.</td>
   </tr> 
   <tr>
      <td><strong>Download:</strong></td>
      <td>For instance, <a href="https://github.com/auberginehill/list-my-apps-template-table/blob/master/all_in_one.md">all_in_one.md</a></td>
   </tr> 
 </table>   



#### www

<table>
    <tr>
        <th><img class="emoji" title="www" alt="www" height="28px" width="28px" align="absmiddle" src="https://assets-cdn.github.com/images/icons/emoji/unicode/1f310.png"></th>
        <td><a href="https://github.com/auberginehill/list-my-apps-template-table">Template Homepage</a></td>
    </tr>
    <tr>
        <td rowspan="6"></td>
        <td><a href="https://play.google.com/store/apps/details?id=de.onyxbits.listmyapps">List My Apps</a> (Google Play)</td>
    </tr>
    <tr>
        <td><a href="http://www.onyxbits.de/listmyapps">List My Apps' homepage</a></td>
    </tr>
    <tr>
        <td><a href="http://forum.xda-developers.com/showthread.php?t=2460266">List My Apps' application thread] at xda-developers.com</td>
   </tr> 
   <tr>
      <td><a href="https://play.google.com/store/apps/details?id=com.aor.droidedit">DroidEdit Free</a> (free code editor)</td>
    </tr>
    <tr>
        <td><a href="https://play.google.com/store/apps/details?id=jp.ne.shira.html.viewer">Local HTML Viewer</a></td>
    </tr>
    <tr>
        <td><a href="https://play.google.com/store/apps/details?id=org.mozilla.firefox">Firefox for Android</a></td>
    </tr>
</table>



#### Related scripts

 <table>
    <tr>
        <th><img class="emoji" title="www" alt="www" height="28px" width="28px" align="absmiddle" src="https://assets-cdn.github.com/images/icons/emoji/unicode/0023-20e3.png"></th>
        <td><a href="https://github.com/auberginehill/list-my-apps-template-list">List My Apps Template - List</a></td>
    </tr>
    <tr>
        <td rowspan="4"></td>
        <td><a href="https://github.com/auberginehill/list-my-apps-template-pro">List My Apps Template - Pro</a></td>
    </tr>
    <tr>
        <td><a href="https://github.com/auberginehill/list-my-apps-template-data">List My Apps Template - Data</a></td>
    </tr>
    <tr>
        <td><a href="https://github.com/auberginehill/list-my-apps-template-xml-plain">List My Apps Template - XML plain</a></td>
    </tr>
    <tr>
        <td><a href="https://github.com/auberginehill/list-my-apps-template-xml-style">List My Apps Template - XML style</a></td>
    </tr>
</table>  
