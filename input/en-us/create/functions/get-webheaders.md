﻿---
Order: 170
xref: get-webheaders
Title: Get-WebHeaders
Description: Information on Get-WebHeaders function
RedirectFrom:
  - docs/helpers-get-web-headers
  - docs/helpersgetwebheaders
---

# Get-WebHeaders

<!-- This documentation is automatically generated from https://github.com/chocolatey/choco/blob/master/src/chocolatey.resources/helpers/functions/Get-WebHeaders.ps1 using https://github.com/chocolatey/choco/blob/master/GenerateDocs.ps1. Contributions are welcome at the original location(s). -->

Gets the request/response headers for a url.

## Syntax

~~~powershell
Get-WebHeaders `
  [-Url <String>] `
  [-UserAgent <String>] `
  [-IgnoredArguments <Object[]>] [<CommonParameters>]
~~~

## Description

This is a low-level function that is used by Chocolatey to get the
headers for a request/response to better help when getting and
validating internet resources.


## Aliases

None

## Inputs

None

## Outputs

None

## Parameters

###  -Url [&lt;String&gt;]
This is the url to get a request/response from.

Property               | Value
---------------------- | -----
Aliases                | 
Required?              | false
Position?              | 1
Default Value          | 
Accept Pipeline Input? | false
 
###  -UserAgent [&lt;String&gt;]
The user agent to use as part of the request. Defaults to 'chocolatey
command line'.

Property               | Value
---------------------- | -----------------------
Aliases                | 
Required?              | false
Position?              | 2
Default Value          | chocolatey command line
Accept Pipeline Input? | false
 
###  -IgnoredArguments [&lt;Object[]&gt;]
Allows splatting with arguments that do not apply. Do not use directly.

Property               | Value
---------------------- | -----
Aliases                | 
Required?              | false
Position?              | named
Default Value          | 
Accept Pipeline Input? | false
 
### &lt;CommonParameters&gt;

This cmdlet supports the common parameters: -Verbose, -Debug, -ErrorAction, -ErrorVariable, -OutBuffer, and -OutVariable. For more information, see `about_CommonParameters` http://go.microsoft.com/fwlink/p/?LinkID=113216 .


## Links

 * [Get-ChocolateyWebFile](xref:get-chocolateywebfile)
 * [Get-WebFileName](xref:get-webfilename)
 * [Get-WebFile](xref:get-webfile)


[Function Reference](xref:powershell-reference)

> :choco-info: **NOTE**
>
> This documentation has been automatically generated from `Import-Module "$env:ChocolateyInstall\helpers\chocolateyInstaller.psm1" -Force; Get-Help Get-WebHeaders -Full`.

View the source for [Get-WebHeaders](https://github.com/chocolatey/choco/blob/master/src/chocolatey.resources/helpers/functions/Get-WebHeaders.ps1)
