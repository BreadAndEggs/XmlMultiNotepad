## Install XML Notepad

There are thee ways to install XML Notepad.

First you must install [.NET Framework version 4.8](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48).

Then the most convenient is to install it directly from the web browser using the ClickOnce installer:

<div>
<a href="https://lovettsoftwarestorage.blob.core.windows.net/downloads/XmlNotepad/XmlNotepad.application"
   class="btn btn-primary mt-20 mr-30" target="_blank">ClickOnce® installer</a>
<br/>
<br/>
</div>

If you need something that installs offline for machines that have no network or are isolated from the internet then use
the standalone installer:

<div>
<a href="https://lovettsoftwarestorage.blob.core.windows.net/downloads/XmlNotepad/XmlNotepadSetup.zip"
   class="btn btn-primary mt-20 mr-30" target="_blank">Standalone installer</a>
<br/>
<br/>
</div>

Just download the zip file, copy it to the machine you want to install it on, unzip the file on that machine and run
`XmlNotepadSetup.msi`.

And lastly, you can also use `winget` to install XML Notepad:

<a href="https://winget.run/pkg/Microsoft/XMLNotepad" class="btn btn-primary mt-20 mr-30" target="_blank">winget
   installer</a>

Or use this command line if you have the [winget cli](https://github.com/microsoft/winget-cli) installed:

```shell
winget install XmlNotepad
```

<div>
<a href="https://docs.microsoft.com/en-us/DeployOffice/webview2-install"
   class="btn btn-primary mt-20 mr-30" target="_blank"> webview2</a>
<br/>
<br/>
</div>

WebView2 is an optional component that you can install from Microsoft. XML Notepad will use this component as the HTML
rendering engine behind the [XSLT Output tab](help/xslt.md). WebView2 provides a significant performance boost on large
XSLT outputs.

See [XML Notepad File Association](help/fileassociation.md).