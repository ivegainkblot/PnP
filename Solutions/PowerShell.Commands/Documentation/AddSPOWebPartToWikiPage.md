#Add-SPOWebPartToWikiPage
*Topic automatically generated on: 2015-04-02*

Adds a webpart to a wiki page in a specified table row and column
##Syntax
```powershell
Add-SPOWebPartToWikiPage -Xml [<String>] -PageUrl [<String>] -Row [<Int32>] -Column [<Int32>] [-AddSpace [<SwitchParameter>]] [-Web [<WebPipeBind>]]
```
&nbsp;

```powershell
Add-SPOWebPartToWikiPage -Path [<String>] -PageUrl [<String>] -Row [<Int32>] -Column [<Int32>] [-AddSpace [<SwitchParameter>]] [-Web [<WebPipeBind>]]
```
&nbsp;

##Parameters
Parameter|Type|Required|Description
---------|----|--------|-----------
AddSpace|SwitchParameter|False|
Column|Int32|True|
PageUrl|String|True|
Path|String|True|
Row|Int32|True|
Web|WebPipeBind|False|The web to apply the command to. Leave empty to use the current web.
Xml|String|True|
