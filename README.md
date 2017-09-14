A tool to minify Javascript and CSS webresource for MS Dynamics CRM
-------------------------------------------------------------------

>**This tool is based on AjaxMin library ([link here](http://ajaxmin.codeplex.com/))**

>**Import solution:** Download solution from repository and import to your organization.

>**Configuration:** Open your Plug-in Registration Tool to connect to your organization. Under create and update steps of **CRMPluginMinify.MinifyWebResource** plugin, check the unsecure configuration like below:
>
```xml
<configuration>
<enable>true</enable>
<minifyjs>true</minifyjs>
<minifycss>true</minifycss>
<prefix>new_;dev_;min_</prefix>
</configuration>
```
> 
 - enable: Turn on the minify function
 - minifyjs: Turn on minify function for javascript file (.js)
 - minifycss:  Turn on minify function for css file (.css)
 - prefix: only run the function for those files which have one of prefixes in configuration (separate by ';')

**Original JS file:**

![enter image description here](https://11p2pg.bn1301.livefilestore.com/y4mxOTGwiHkHEx4xZGUf4YdNFKHTW0PwmLCIgG4qfTZH8nah6unfQ1RcQfVrrTsPGVsnkrP2RKJnxbxWsJ6vNZ0_l389i4013ueRzo0chtsXMjv7i09T_C87MZViHhN97zc8Es4wJwYZwsqbKQBPIYys9FbO7EPYmNAALFjnt3pTEf4b7kTNROK9chkUiQG3pCEzmSmzXL_mnJ2q4xwseXAfQ?width=660&height=578&cropmode=none)

**Minified JS file:**

![enter image description here](https://dutfgw.bn1301.livefilestore.com/y4mheXNCjKeuTi_4pulnsisg9OJ7hy4Un5I-ZLTSr-uiOv78sOic3gWsveD50tAk544L4WPTYG_cav99tQcesboSisJFBKIGVxT0QwrDZYL09N0lVnBDdRkQrJUQrCzRFazmFqqEXt2Pf7vM-7NI3I6Cmsi3h4pvjCK2-2YyDvQWQ6vN3BSj85DrNJ87fAjaqLEcC7l_s03bSug6nLepwC3WQ?width=660&height=220&cropmode=none)

