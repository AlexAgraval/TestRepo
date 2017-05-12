# WebDAV Server Examples, C#
IT Hit WebDAV Server Engine is provided with several WebDAV server C# examples that demonstrate how to build a WebDAV server with SQL back-end or with file system storage. You can adapt these samples to utilize almost any back-end storage including storing data via CMS/DMS/CRM API, Azure or Amazon API. The provided examples run in ASP.NET/IIS or HttpListener.

By default WebDAV Server Examples are installed to the following folder:

```shell
C:\Users\<UserName>\Documents\IT Hit\WebDAV Server Engine\vX.X.X\Samples\
```

Note that these WebDAV Examples were generated automatically by the WebDAV wizards for Visual Studio and there is no any difference between code you get from wizard and these examples. In most cases using [WebDAV Wizards for Visual Studio](https://www.webdavsystem.com/server/documentation/vs_wizards/) is more convenient and straightforward solution comparing to configuring the example.

## ASP.NET Core WebDAV Server with File System Storage Example
A cross-platform Class 2 WebDAV server that runs on ASP.NET Core on Windows, Mac OS X and Linux. It stores locks and custom properties in file system Extended Attributes in case of OS X and Linux or in NTFS Alternate Data Streams in case of Windows. This example is a fully-functional WebDAV server that can be used to open, edit and save Microsoft Office documents directly to server, without download/upload steps. [More...](https://www.webdavsystem.com/server/server_examples/cross_platform_asp_net_core_file_system/)

## ASP.NET Core WebDAV Server with Microsoft SQL Storage Example
A cross-platform Class 2 WebDAV server that runs on ASP.NET Core on Windows, Mac OS X and Linux. It stores all data including locks, file content and custom properties in Microsoft SQL Server database. This example is a fully-functional WebDAV server that can be used to open, edit and save Microsoft Office documents directly to server, without download/upload steps. [More...](https://www.webdavsystem.com/server/server_examples/cross_platform_asp_net_core_sql/)
