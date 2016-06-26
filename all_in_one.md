File Header (file_header.md): 




<!DOCTYPE html>
<html>

<head>

    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=0.7">
    <meta name="Keywords" content="apps,applications,Android,HTML,Web development,tutorials,programming,training,learning,examples,source code,colors,demos,tips,template,templates">
    <meta name="Description" content="A Table of Installed Applications">

    <title>The Enumeration Table of Installed Applications</title>

    <style>
        body {
            font-family: Calibri, "Lucida Sans", Helvetica, sans-serif;
        }
        
        li {
            padding: 7px;
        }
        
        table,
        th,
        td {
            border-collapse: collapse;
        }
        
        table#main {
            border: 1px solid black;
            padding: 30px;
        }
        
        table#main th {
            text-align: center;
            color: black;
            font-weight: bold;
            padding: 14px;
            background-color: white;
        }
        
        table#main td {
            text-align: center;
            color: black;
            font-weight: normal;
            padding: 14px;
        }
        
        table#main tr:nth-child(even) {
            background-color: white;
        }
        
        table#main tr:nth-child(odd) {
            background-color: #cccccc;
        }
        
        table.stats th {
            border: 0px solid black;
            background-color: white;
            color: black;
            text-align: left;
            width: 120px;
            padding: 2px;
        }
        
        table.stats td {
            border: 0px solid black;
            background-color: white;
            color: black;
            text-align: left;
        }
        
        .right_pane {
            text-align: right;
            font-size: 80%;
        }
        
        .filter-type {
            border-bottom: 0px dotted #343434;
        }
        
        .show_more {
            width: 95%;
            margin-bottom: 14px;
            overflow-y: scroll;
            border: none;
            visibility: visible;
        }
        
        #filter {
            display: none
        }
        
        #filter:checked + .show_more {
            visibility: visible;
        }
    </style>
</head>

<!-- Start content -->

<body>
    <h1 id="top" style="font-family: 'Gill Sans', sans-serif">
        Installed Apps</h1>
    <table class="stats">
        <tr>
            <th>Generated:</th>
            <td>${now}</td>
        </tr>
        <tr>
            <th>Total:</th>
            <td>${count} apps</td>
        </tr>
    </table>
    <p class="right_pane"><a href="#bottom">↓ Bottom ↓</a></p>
    <br>
    <p>To see the code in action, a real-time Online HTML Editor can be found at: <a href="http://htmledit.squarefree.com/">http://htmledit.squarefree.com/</a></p>
    <br>
    <br>
    <br>
    <br>
    <br>
    <table id="main" border="1px" cellpadding="14" style="width:99%">
        <caption><span style="font-family: 'Gill Sans', sans-serif; font-size:300%">The Enumeration Table of Installed Applications</span><br>
            <br>
            <br></caption>
        <thead>
            <tr>
                <th style="text-align:left">Name</th>
                <th>Comment</th>
                <th>Data Directory</th>
                <th>First Installed</th>
                <th>Last Updated</th>
                <th>Market ID</th>
                <th>Market Link</th>
                <th>Package Name</th>
                <th>Target SDK</th>
                <th>UID</th>
                <th>Tags</th>
                <th>Version</th>
                <th>Version Code</th>
                <th>www</th>
                <th>Search (Google)</th>
                <th>Google Store</th>
                <th>Search (DDG)</th>
                <th style="text-align:right">Name</th>
            </tr>
        </thead>
        <tbody>








Body (body.md):








            <tr>
                <td style="text-align:left"><strong>${displayname}</strong></td>
                <td>${comment}</td>
                <td>${datadir}</td>
                <td>${firstinstalled}</td>
                <td>${lastupdated}</td>
                <td>${marketid}</td>
                <td>market://details?id=${packagename}</td>
                <td>${packagename}</td>
                <td>${targetsdk}</td>
                <td>${uid}</td>
                <td>${tags}</td>
                <td>${version}</td>
                <td>${versioncode}</td>
                <td><a href="${source}">Link</a></td>
                <td><a href="https://www.google.com/search?q=${packagename}">Search</a></td>
                <td><a href="https://play.google.com/store/apps/details?id=${packagename}">Store</a></td>
                <td><a href="https://duckduckgo.com/?q=${packagename}+%22${displayname}%22">DDG</a></td>
                <td style="text-align:right"><strong>${displayname}</strong></td>
            </tr>
        </tbody>








File Footer (file_footer.md):





  

  
    </table>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>
    <div class="right_pane"><a href="#bottom">↓ Bottom ↓</a>  |  <a href="#top">↑ Top ↑</a></div>
    <div style="margin-left:1em">
        <h3>'List My Apps' -Template (Table)</h3>
        <br>
        <p>To open this code with an Android device, for instance:</p>
        <ol>
            <li>Create a new template in '<a href="https://play.google.com/store/apps/details?id=de.onyxbits.listmyapps">List My Apps</a>' -app's Template Editor by clicking Options (three dots) → Template Editor → Add. [<a href="http://groovyandroid.com/wp-content/uploads/2013/10/List-My-Apps-select-all.png">Screenshot</a>]</li>
            <li>Type in a name for the template. [<a href="http://groovyandroid.com/wp-content/uploads/2013/10/List-My-Apps-Template-Editor.png">Screenshot</a>]</li>
            <li>Paste all the appropriate template data to 'List My Apps' and save the template. The most convenient template source is a separate file (such as <a href="http://pastebin.com/ADaRiDYq">http://pastebin.com/ADaRiDYq</a>), but a fairly working version of the template (without the template that would reside inside the template footer) can be found at the end of this file.
                <ul>
                    <li>The template code below is in three parts as described below:
                           <table style="border:0; margin-left:3em; margin-top:2em; margin-bottom:2em; text-align:left">
                               <tr>
                                   <th style="padding:12px">Template File Header:</th>
                                   <td style="padding:12px">"List header, may be blank"</td>
                                </tr>
                                <tr>
                                    <th style="padding:12px">Template Body:</th>
                                    <td style="padding:12px">"Item format, may not be blank"</td>
                                </tr>
                                <tr> 
                                    <th style="padding:12px">Template File Footer:</th>
                                    <td style="padding:12px">"List footer, may be blank"</td>
                                </tr>
                            </table>
                    </li>
                    <li>The footer section (under the header 'Template File Footer:') includes only a truncated version of the real footer section, which was used to create the underlying HTML-page.</li>
                    <li>In the header and footer sections of the template (under 'Template File Header:' and 'Template File Footer:' -headers below) every instance of [dollar_sign] has to be replaced with a single $ character (to repair the timestamp and count -variables to their correct form).</li>
                </ul>
            </li>
            <li>Go back to the 'List My Apps' -app's home screen and select the name that was created in Step 2 from the 'Copy/Share as:' -dropdown menu. Please also select the apps that you'd like to be included in the list. [<a href="http://groovyandroid.com/wp-content/uploads/2013/10/List-My-App-HTML-list.png">Screenshot</a>]</li>
            <li>'Run' the 'List My Apps' -app with the new template by copying the app data to Clipboard [Copy] (since direct sharing may not work, if a lot of applications has been installed).
                <ul>
                    <li>There seems to be some kind of a limit, how much data the Android Clipboard can contain. With verbose templates ~200 apps might be the upper limit, but with a simple template, the Android Clipboard clearly is capable of containing considerably more app data.</li>
                </ul>
            </li>
            <li>Open a HTML editor, such as <a href="https://play.google.com/store/apps/details?id=com.aor.droidedit">DroidEdit Free</a>.</li>
            <li>Paste the app data (source code generated by 'List My Apps' in Step 5) from Clipboard to the HTML editor.
                <ul>
                    <li>If nothing happens (no data is copied to a HTML editor), try selecting fewer apps in 'List My Apps' and go back to Step 5.</li>
                    <li>If "old data" gets copied to a HTML editor (i.e. "the data that was in the Clipboard before 'List My Apps' apps' 'Copy to Clipboard' -button was clicked"), try selecting fewer apps in 'List My Apps' and go back to Step 5.</li>
                </ul>
            </li>
            <li>Save the file as a HTML file, for example as 'Installed_Apps.html', for example in 'Home/Documents' folder (a filename without any spaces is recommended).</li>
            <li>Open the HTML file with an appropriate app, such as a browser by surfing directly to the file location, which could, for instance, be: <a href="file:///storage/emulated/0/Documents/Installed_Apps.html">file:///storage/emulated/0/Documents/Installed_Apps.html</a>
                <ul>
                    <li>In a browser the spaces in the filename can be replaced with %20 to make the link work. For more exotic filename characters, see <a href="http://www.w3schools.com/tags/ref_urlencode.asp">HTML URL Encoding Reference</a>.</li>
                </ul>
            </li>
            <li>Conversion from HTML to PDF might work with <a href="https://play.google.com/store/apps/details?id=org.mozilla.firefox">Firefox (for Android)</a> (Options (three dots) → Page → Save as PDF) or perhaps with the printing option in the default Android File Manager.
            </li>
        </ol>
    </div>

    <!-- End Instructions (INSTRUCTIONS), can be selected over when pasting -->

    <div style="margin-left:3em"><br>
        <h4>www</h4>
        <ul>
            <li>Template: <a href="http://pastebin.com/ADaRiDYq/">http://pastebin.com/ADaRiDYq/</a></li>
            <li><a href="https://play.google.com/store/apps/details?id=de.onyxbits.listmyapps">List My Apps</a> (Google Play)</li>
            <li><a href="http://www.onyxbits.de/listmyapps">List My Apps' homepage</a></li>
            <li><a href="http://forum.xda-developers.com/showthread.php?t=2460266">List My Apps' application thread</a> at xda-developers.com</li>
            <li><a href="https://play.google.com/store/apps/details?id=com.aor.droidedit">DroidEdit Free</a> (free code editor)</li>
            <li><a href="https://play.google.com/store/apps/details?id=jp.ne.shira.html.viewer">Local HTML Viewer</a></li>
            <li><a href="https://play.google.com/store/apps/details?id=org.mozilla.firefox">Firefox for Android</a></li>
            <li><a href="https://play.google.com/store/apps/details?id=com.h3r3t1c.app.droidpaste">DroidPaste for Pastebin</a></li>
        </ul>
        <br>
        <h4>Related scripts</h4>
        <ul>
            <li>List My Apps Template - List: <a href="http://pastebin.com/U4K39BRx">http://pastebin.com/U4K39BRx</a></li>
            <li>List My Apps Template - Pro: <a href="http://pastebin.com/kK646g16">http://pastebin.com/kK646g16</a></li>
            <li>List My Apps Template - Data: <a href="http://pastebin.com/NfEeHHf0">http://pastebin.com/NfEeHHf0</a></li>
            <li>List My Apps Template - XML plain: <a href="http://pastebin.com/YPFQnhPH">http://pastebin.com/YPFQnhPH</a></li>
            <li>List My Apps Template - XML style: <a href="http://pastebin.com/qQDKwSG0">http://pastebin.com/qQDKwSG0</a></li>
        </ul>
    </div>
    <br>
    <br>
    <br>
    <br>
    <br>
    <br>

    <!-- Start Template File Header (HEADER), can be selected over when pasting -->

    <label class="filter-type" for="filter"><strong>Template File Header:</strong></label>
    <div class="show_more">
        <input type="checkbox" id="filter">
        <pre>
&lt;!DOCTYPE html&gt;
&lt;html&gt;

&lt;head&gt;

    &lt;meta http-equiv=&quot;Content-Type&quot; content=&quot;text/html; charset=utf-8&quot;&gt;
    &lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=0.7&quot;&gt;
    &lt;meta name=&quot;Keywords&quot; content=&quot;apps,applications,Android,HTML,Web development,tutorials,programming,training,learning,examples,source code,colors,demos,tips,template,templates&quot;&gt;
    &lt;meta name=&quot;Description&quot; content=&quot;A Table of Installed Applications&quot;&gt;

    &lt;title&gt;The Enumeration Table of Installed Applications&lt;/title&gt;

    &lt;style&gt;
        body {
            font-family: Calibri, &quot;Lucida Sans&quot;, Helvetica, sans-serif;
        }
        
        li {
            padding: 7px;
        }
        
        table,
        th,
        td {
            border-collapse: collapse;
        }
        
        table#main {
            border: 1px solid black;
            padding: 30px;
        }
        
        table#main th {
            text-align: center;
            color: black;
            font-weight: bold;
            padding: 14px;
            background-color: white;
        }
        
        table#main td {
            text-align: center;
            color: black;
            font-weight: normal;
            padding: 14px;
        }
        
        table#main tr:nth-child(even) {
            background-color: white;
        }
        
        table#main tr:nth-child(odd) {
            background-color: #cccccc;
        }
        
        table.stats th {
            border: 0px solid black;
            background-color: white;
            color: black;
            text-align: left;
            width: 120px;
            padding: 2px;
        }
        
        table.stats td {
            border: 0px solid black;
            background-color: white;
            color: black;
            text-align: left;
        }
        
        .right_pane {
            text-align: right;
            font-size: 80%;
        }
        
        .filter-type {
            border-bottom: 0px dotted #343434;
        }
        
        .show_more {
            width: 95%;
            margin-bottom: 14px;
            overflow-y: scroll;
            border: none;
            visibility: visible;
        }
        
        #filter {
            display: none
        }
        
        #filter:checked + .show_more {
            visibility: visible;
        }
    &lt;/style&gt;
&lt;/head&gt;

&lt;!-- Start content --&gt;

&lt;body&gt;
    &lt;h1 id=&quot;top&quot; style=&quot;font-family: 'Gill Sans', sans-serif&quot;&gt;
        Installed Apps&lt;/h1&gt;
    &lt;table class=&quot;stats&quot;&gt;
        &lt;tr&gt;
            &lt;th&gt;Generated:&lt;/th&gt;
            &lt;td&gt;[dollar_sign]{now}&lt;/td&gt;
        &lt;/tr&gt;
        &lt;tr&gt;
            &lt;th&gt;Total:&lt;/th&gt;
            &lt;td&gt;[dollar_sign]{count} apps&lt;/td&gt;
        &lt;/tr&gt;
    &lt;/table&gt;
    &lt;p class=&quot;right_pane&quot;&gt;&lt;a href=&quot;#bottom&quot;&gt;&#x2193; Bottom &#x2193;&lt;/a&gt;&lt;/p&gt;
    &lt;br&gt;
    &lt;p&gt;To see the code in action, a real-time Online HTML Editor can be found at: &lt;a href=&quot;http://htmledit.squarefree.com/&quot;&gt;http://htmledit.squarefree.com/&lt;/a&gt;&lt;/p&gt;
    &lt;br&gt;
    &lt;br&gt;
    &lt;br&gt;
    &lt;br&gt;
    &lt;br&gt;
    &lt;table id=&quot;main&quot; border=&quot;1px&quot; cellpadding=&quot;14&quot; style=&quot;width:99%&quot;&gt;
        &lt;caption&gt;&lt;span style=&quot;font-family: 'Gill Sans', sans-serif; font-size:300%&quot;&gt;The Enumeration Table of Installed Applications&lt;/span&gt;&lt;br&gt;
            &lt;br&gt;
            &lt;br&gt;&lt;/caption&gt;
        &lt;thead&gt;
            &lt;tr&gt;
                &lt;th style=&quot;text-align:left&quot;&gt;Name&lt;/th&gt;
                &lt;th&gt;Comment&lt;/th&gt;
                &lt;th&gt;Data Directory&lt;/th&gt;
                &lt;th&gt;First Installed&lt;/th&gt;
                &lt;th&gt;Last Updated&lt;/th&gt;
                &lt;th&gt;Market ID&lt;/th&gt;
                &lt;th&gt;Market Link&lt;/th&gt;
                &lt;th&gt;Package Name&lt;/th&gt;
                &lt;th&gt;Target SDK&lt;/th&gt;
                &lt;th&gt;UID&lt;/th&gt;
                &lt;th&gt;Tags&lt;/th&gt;
                &lt;th&gt;Version&lt;/th&gt;
                &lt;th&gt;Version Code&lt;/th&gt;
                &lt;th&gt;www&lt;/th&gt;
                &lt;th&gt;Search (Google)&lt;/th&gt;
                &lt;th&gt;Google Store&lt;/th&gt;
                &lt;th&gt;Search (DDG)&lt;/th&gt;
                &lt;th style=&quot;text-align:right&quot;&gt;Name&lt;/th&gt;
            &lt;/tr&gt;
        &lt;/thead&gt;
        &lt;tbody&gt;
        </pre>
    </div>

    <!-- End Template File Header (HEADER), can be selected over when pasting -->

    <!-- Start Template Body (BODY), can be selected over when pasting -->

    <label class="filter-type" for="filter"><strong>Template Body:</strong></label>
    <div class="show_more">
        <input type="checkbox" id="filter">
        <pre>
            &lt;tr&gt;
                &lt;td style=&quot;text-align:left&quot;&gt;&lt;strong&gt;${displayname}&lt;/strong&gt;&lt;/td&gt;
                &lt;td&gt;${comment}&lt;/td&gt;
                &lt;td&gt;${datadir}&lt;/td&gt;
                &lt;td&gt;${firstinstalled}&lt;/td&gt;
                &lt;td&gt;${lastupdated}&lt;/td&gt;
                &lt;td&gt;${marketid}&lt;/td&gt;
                &lt;td&gt;market://details?id=${packagename}&lt;/td&gt;
                &lt;td&gt;${packagename}&lt;/td&gt;
                &lt;td&gt;${targetsdk}&lt;/td&gt;
                &lt;td&gt;${uid}&lt;/td&gt;
                &lt;td&gt;${tags}&lt;/td&gt;
                &lt;td&gt;${version}&lt;/td&gt;
                &lt;td&gt;${versioncode}&lt;/td&gt;
                &lt;td&gt;&lt;a href=&quot;${source}&quot;&gt;Link&lt;/a&gt;&lt;/td&gt;
                &lt;td&gt;&lt;a href=&quot;https://www.google.com/search?q=${packagename}&quot;&gt;Search&lt;/a&gt;&lt;/td&gt;
                &lt;td&gt;&lt;a href=&quot;https://play.google.com/store/apps/details?id=${packagename}&quot;&gt;Store&lt;/a&gt;&lt;/td&gt;
                &lt;td&gt;&lt;a href=&quot;https://duckduckgo.com/?q=${packagename}+%22${displayname}%22&quot;&gt;DDG&lt;/a&gt;&lt;/td&gt;
                &lt;td style=&quot;text-align:right&quot;&gt;&lt;strong&gt;${displayname}&lt;/strong&gt;&lt;/td&gt;
            &lt;/tr&gt;
        </pre>
    </div>

    <!-- End Template Body (BODY), can be selected over when pasting -->

    <!-- Start Template File Footer (FOOTER), can be selected over when pasting -->

    <label class="filter-type" for="filter"><strong>Template File Footer:</strong></label>
    <div class="show_more">
        <input type="checkbox" id="filter">
        <pre>
        &lt;/tbody&gt;
    &lt;/table&gt;
    &lt;br&gt;
    &lt;br&gt;
    &lt;br&gt;
    &lt;br&gt;
    &lt;br&gt;
    &lt;br&gt;
    &lt;div class=&quot;right_pane&quot;&gt;&lt;a href=&quot;#bottom&quot;&gt;&#x2193; Bottom &#x2193;&lt;/a&gt;&#x2003;&#x2002;|&#x2002;&#x2003;&lt;a href=&quot;#top&quot;&gt;&#x2191; Top &#x2191;&lt;/a&gt;&lt;/div&gt;
    &lt;div style=&quot;margin-left:1em&quot;&gt;
        &lt;h3&gt;'List My Apps' -Template (Table)&lt;/h3&gt;
        &lt;br&gt;
        &lt;p&gt;To open this code with an Android device, for instance:&lt;/p&gt;
        &lt;ol&gt;
            &lt;li&gt;Create a new template in '&lt;a href=&quot;https://play.google.com/store/apps/details?id=de.onyxbits.listmyapps&quot;&gt;List My Apps&lt;/a&gt;' -app's Template Editor by clicking Options (three dots) &#x2192; Template Editor &#x2192; Add. [&lt;a href=&quot;http://groovyandroid.com/wp-content/uploads/2013/10/List-My-Apps-select-all.png&quot;&gt;Screenshot&lt;/a&gt;]&lt;/li&gt;
            &lt;li&gt;Type in a name for the template. [&lt;a href=&quot;http://groovyandroid.com/wp-content/uploads/2013/10/List-My-Apps-Template-Editor.png&quot;&gt;Screenshot&lt;/a&gt;]&lt;/li&gt;
            &lt;li&gt;Paste all the appropriate template data to 'List My Apps' and save the template. The most convenient template source is a separate file (such as &lt;a href=&quot;http://pastebin.com/ADaRiDYq&quot;&gt;http://pastebin.com/ADaRiDYq&lt;/a&gt;), but a fairly working version of the template (without the template that would reside inside the template footer) can be found at the end of this file.
                &lt;ul&gt;
                    &lt;li&gt;The template code below is in three parts as described below:
                           &lt;table style=&quot;border:0; margin-left:3em; margin-top:2em; margin-bottom:2em; text-align:left&quot;&gt;
                               &lt;tr&gt;
                                   &lt;th style=&quot;padding:12px&quot;&gt;Template File Header:&lt;/th&gt;
                                   &lt;td style=&quot;padding:12px&quot;&gt;&quot;List header, may be blank&quot;&lt;/td&gt;
                                &lt;/tr&gt;
                                &lt;tr&gt;
                                    &lt;th style=&quot;padding:12px&quot;&gt;Template Body:&lt;/th&gt;
                                    &lt;td style=&quot;padding:12px&quot;&gt;&quot;Item format, may not be blank&quot;&lt;/td&gt;
                                &lt;/tr&gt;
                                &lt;tr&gt; 
                                    &lt;th style=&quot;padding:12px&quot;&gt;Template File Footer:&lt;/th&gt;
                                    &lt;td style=&quot;padding:12px&quot;&gt;&quot;List footer, may be blank&quot;&lt;/td&gt;
                                &lt;/tr&gt;
                            &lt;/table&gt;
                    &lt;/li&gt;
                    &lt;li&gt;The footer section (under the header 'Template File Footer:') includes only a truncated version of the real footer section, which was used to create the underlying HTML-page.&lt;/li&gt;
                    &lt;li&gt;In the header and footer sections of the template (under 'Template File Header:' and 'Template File Footer:' -headers below) every instance of [dollar_sign] has to be replaced with a single $ character (to repair the timestamp and count -variables to their correct form).&lt;/li&gt;
                &lt;/ul&gt;
            &lt;/li&gt;
            &lt;li&gt;Go back to the 'List My Apps' -app's home screen and select the name that was created in Step 2 from the 'Copy/Share as:' -dropdown menu. Please also select the apps that you'd like to be included in the list. [&lt;a href=&quot;http://groovyandroid.com/wp-content/uploads/2013/10/List-My-App-HTML-list.png&quot;&gt;Screenshot&lt;/a&gt;]&lt;/li&gt;
            &lt;li&gt;'Run' the 'List My Apps' -app with the new template by copying the app data to Clipboard [Copy] (since direct sharing may not work, if a lot of applications has been installed).
                &lt;ul&gt;
                    &lt;li&gt;There seems to be some kind of a limit, how much data the Android Clipboard can contain. With verbose templates ~200 apps might be the upper limit, but with a simple template, the Android Clipboard clearly is capable of containing considerably more app data.&lt;/li&gt;
                &lt;/ul&gt;
            &lt;/li&gt;
            &lt;li&gt;Open a HTML editor, such as &lt;a href=&quot;https://play.google.com/store/apps/details?id=com.aor.droidedit&quot;&gt;DroidEdit Free&lt;/a&gt;.&lt;/li&gt;
            &lt;li&gt;Paste the app data (source code generated by 'List My Apps' in Step 5) from Clipboard to the HTML editor.
                &lt;ul&gt;
                    &lt;li&gt;If nothing happens (no data is copied to a HTML editor), try selecting fewer apps in 'List My Apps' and go back to Step 5.&lt;/li&gt;
                    &lt;li&gt;If &quot;old data&quot; gets copied to a HTML editor (i.e. &quot;the data that was in the Clipboard before 'List My Apps' apps' 'Copy to Clipboard' -button was clicked&quot;), try selecting fewer apps in 'List My Apps' and go back to Step 5.&lt;/li&gt;
                &lt;/ul&gt;
            &lt;/li&gt;
            &lt;li&gt;Save the file as a HTML file, for example as 'Installed_Apps.html', for example in 'Home/Documents' folder (a filename without any spaces is recommended).&lt;/li&gt;
            &lt;li&gt;Open the HTML file with an appropriate app, such as a browser by surfing directly to the file location, which could, for instance, be: &lt;a href=&quot;file:///storage/emulated/0/Documents/Installed_Apps.html&quot;&gt;file:///storage/emulated/0/Documents/Installed_Apps.html&lt;/a&gt;
                &lt;ul&gt;
                    &lt;li&gt;In a browser the spaces in the filename can be replaced with %20 to make the link work. For more exotic filename characters, see &lt;a href=&quot;http://www.w3schools.com/tags/ref_urlencode.asp&quot;&gt;HTML URL Encoding Reference&lt;/a&gt;.&lt;/li&gt;
                &lt;/ul&gt;
            &lt;/li&gt;
            &lt;li&gt;Conversion from HTML to PDF might work with &lt;a href=&quot;https://play.google.com/store/apps/details?id=org.mozilla.firefox&quot;&gt;Firefox (for Android)&lt;/a&gt; (Options (three dots) &#x2192; Page &#x2192; Save as PDF) or perhaps with the printing option in the default Android File Manager.
            &lt;/li&gt;
        &lt;/ol&gt;
    &lt;/div&gt;

    &lt;!-- End Instructions (INSTRUCTIONS), can be selected over when pasting --&gt;

    &lt;div style=&quot;margin-left:3em&quot;&gt;&lt;br&gt;
        &lt;h4&gt;www&lt;/h4&gt;
        &lt;ul&gt;
            &lt;li&gt;Template: &lt;a href=&quot;http://pastebin.com/ADaRiDYq/&quot;&gt;http://pastebin.com/ADaRiDYq/&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&quot;https://play.google.com/store/apps/details?id=de.onyxbits.listmyapps&quot;&gt;List My Apps&lt;/a&gt; (Google Play)&lt;/li&gt;
            &lt;li&gt;&lt;a href=&quot;http://www.onyxbits.de/listmyapps&quot;&gt;List My Apps' homepage&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&quot;http://forum.xda-developers.com/showthread.php?t=2460266&quot;&gt;List My Apps' application thread&lt;/a&gt; at xda-developers.com&lt;/li&gt;
            &lt;li&gt;&lt;a href=&quot;https://play.google.com/store/apps/details?id=com.aor.droidedit&quot;&gt;DroidEdit Free&lt;/a&gt; (free code editor)&lt;/li&gt;
            &lt;li&gt;&lt;a href=&quot;https://play.google.com/store/apps/details?id=jp.ne.shira.html.viewer&quot;&gt;Local HTML Viewer&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&quot;https://play.google.com/store/apps/details?id=org.mozilla.firefox&quot;&gt;Firefox for Android&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;&lt;a href=&quot;https://play.google.com/store/apps/details?id=com.h3r3t1c.app.droidpaste&quot;&gt;DroidPaste for Pastebin&lt;/a&gt;&lt;/li&gt;
        &lt;/ul&gt;
        &lt;br&gt;
        &lt;h4&gt;Related scripts&lt;/h4&gt;
        &lt;ul&gt;
            &lt;li&gt;List My Apps Template - List: &lt;a href=&quot;http://pastebin.com/U4K39BRx&quot;&gt;http://pastebin.com/U4K39BRx&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;List My Apps Template - Pro: &lt;a href=&quot;http://pastebin.com/kK646g16&quot;&gt;http://pastebin.com/kK646g16&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;List My Apps Template - Data: &lt;a href=&quot;http://pastebin.com/NfEeHHf0&quot;&gt;http://pastebin.com/NfEeHHf0&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;List My Apps Template - XML plain: &lt;a href=&quot;http://pastebin.com/YPFQnhPH&quot;&gt;http://pastebin.com/YPFQnhPH&lt;/a&gt;&lt;/li&gt;
            &lt;li&gt;List My Apps Template - XML style: &lt;a href=&quot;http://pastebin.com/qQDKwSG0&quot;&gt;http://pastebin.com/qQDKwSG0&lt;/a&gt;&lt;/li&gt;
        &lt;/ul&gt;
    &lt;/div&gt;
    &lt;br&gt;
    &lt;br&gt;
    &lt;br&gt;
    &lt;br&gt;
    &lt;br&gt;
    &lt;br&gt;
    &lt;br&gt;
    &lt;br&gt;
    &lt;br&gt;
    &lt;p class=&quot;right_pane&quot;&gt;&lt;a href=&quot;#top&quot;&gt;&#x2191; Top &#x2191;&lt;/a&gt;&lt;/p&gt;
    &lt;p&gt;[End of Line]&lt;/p&gt;
    &lt;table id=&quot;bottom&quot; class=&quot;stats&quot;&gt;
        &lt;tr&gt;
            &lt;th&gt;Generated:&lt;/th&gt;
            &lt;td&gt;[dollar_sign]{now}&lt;/td&gt;
        &lt;/tr&gt;
        &lt;tr&gt;
            &lt;th&gt;Total:&lt;/th&gt;
            &lt;td&gt;[dollar_sign]{count} apps&lt;/td&gt;
        &lt;/tr&gt;
    &lt;/table&gt;
&lt;/body&gt;

&lt;!-- End content --&gt;

&lt;/html&gt;
        </pre>
    </div>

    <!-- End Template File Footer (FOOTER), can be selected over when pasting -->

    <br>
    <br>
    <br>
    <p class="right_pane"><a href="#top">↑ Top ↑</a></p>
    <p>[End of Line]</p>
    <table id="bottom" class="stats">
        <tr>
            <th>Generated:</th>
            <td>${now}</td>
        </tr>
        <tr>
            <th>Total:</th>
            <td>${count} apps</td>
        </tr>
    </table>
</body>

<!-- End content -->

</html>