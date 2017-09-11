A tool to minify Javascript and CSS webresource for MS Dynamics CRM
-------------------------------------------------------------------

>**Import solution: ** Download solution from repository and import to your organization
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
 - minifyjs: Turn on minify function for javascript file
 - minifycss:  Turn on minify function for css file
 - prefix: only run the function for those files which have one of prefixes in configuration
