# IT Hit WebDAV Server Sample with Microsoft SQL Back-End for ASP.NET Core
This sample is a WebDAV server with Microsoft SQL back-end that runs on IT Hit WebDAV Server Engine for .NET.

It stores all data in Microsoft SQL database and can run on ASP.NET Core on Windows, OS X and Linux. The sample keeps documents, folders structure, locks and custom properties in SQL tables.

It provides a sample web page listing content of your WebDAV server with Edit button, demonstrating how you can open a document for editing directly from a web page and save back to server without download/upload steps.

To list documents, navigate folders structure and open documents for editing this sample utilizes IT Hit WebDAV Ajax Library. It is also covered with WebDAV Ajax integration tests provided with WebDAV Ajax Library so you can test your modifications.

Additionally it demonstrates Ajax File Browser that you can use to manage documents, open for editing and perform advanced upload operations such as pause and resume upload, drag-and-drop as well as restore broken uploads.

To install IT Hit WebDAV Server Sample with Microsoft SQL Back-End for ASP.NET Core, run the following command in the [Package Manager Console](https://docs.microsoft.com/en-us/nuget/tools/package-manager-console):


```shell
Install-Package WebDAVServer.SqlStorage
```

## Author

**IT Hit, Ltd**

## Copyright

Copyright 2017 IT Hit, Ltd
