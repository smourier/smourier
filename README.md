## Some of the projects you can find here:

#### .NET AOT publishing projects

* [DirectN AOT](https://github.com/smourier/DirectNAOT) - A DirectN (see below) AOT compatible version. Only for .NET Core 9 and beyond.
* [DirectN](https://github.com/smourier/DirectN) - Direct interop Code for .NET Framework, .NET Core and .NET 5+ : DXGI, WIC, DirectX 9 to 12, Direct2D, Direct Write, Direct Composition, Media Foundation, WASAPI, CodecAPI, GDI, Spatial Audio, DVD, Windows Media Player, UWP DXInterop, WinUI3, etc. This project is legacy, it should only be used if .NET Framework is a target.
* [ShellBat](https://github.com/smourier/ShellBat) - A modern Windows file explorer with file viewers, multi-instance workflows, terminal integration, search capabilities, and deep Windows Shell interoperability.
* [Wice](https://github.com/aelyo-softworks/Wice) - The "Windows Interface Composition Engine" is a .NET C# UI engine for creating Windows application, for .NET Framework and .NET Core, compatible with AOT publishing.
* [Wic .NET](https://github.com/smourier/WicNet) - .NET interop classes for WIC (Windows Imaging Component), Direct2D and DirectWrite. With .NET 10+ AOT publishing support.
* [WebView2 AOT](https://github.com/smourier/WebView2Aot) - WebView2 .NET AOT publishing compatible bindings independent from WinForms or WPF.
* [ActiveN](https://github.com/smourier/ActiveN) - A lightweight framework for building classic COM components and OLE/ActiveX controls in modern fully AOT-compatible .NET, with registration-ready deployment.
* [AOT Net Com Host](https://github.com/smourier/AotNetComHost) - A development-time "thunk" dll tool that enable COM support (registration, etc.) for not-yet published .NET AOT COM objects for easier debugging.
* [JS Runtime AOT](https://github.com/smourier/JsRuntimeAot) - A .NET9+ AOT compatible wrapper over the Microsoft "Chakra" JavaScript engine (aka JScript9.dll). => It's just one 2500 lines of C# file that allows you to run Javascript code from .NET.

#### Windows 11 Virtual Camera
* [VCam Sample](https://github.com/smourier/VCamSample) - A Windows 11 Virtual Camera sample code in C++.
* [VCam .NET Sample](https://github.com/smourier/VCamNetSample) - A Windows 11 Virtual Camera sample code. It's the C# version of VCamSample that uses DirectN for .NET Framework and DirectNAot for .NET Core.

#### .NET Library and Components (Property Grid, etc.)
* [SQLNado](https://github.com/smourier/SQLNado) - SQLNado (SQLite Not ADO) is a .NET lightweight bloat-free wrapper and object persistence framework based on SQLite.
* [WinUI3 PropertyGrid](https://github.com/smourier/WinPropertyGrid) - A WinUI3 property grid component.
* [Wpf PropertyGrid](https://github.com/smourier/WpfPropertyGrid) - A .NET Core 9+ WPF property grid that supports the newer ThemeMode XAML attribute.
* [Zero-Dep JSON](https://github.com/smourier/ZeroDepJson) - A .NET Json parser in one .cs file, with zero dependencies.
* [ProxyServer](https://github.com/smourier/ProxyServer) - A simple proxy server written in C#.
* [Sheet Reader](https://github.com/smourier/SheetReader) - A simple CSV, XLSX or JSON data sheet reader, and a WPF Sheet Control to display the tabular data.
* [Futese](https://github.com/smourier/Futese) - A simple in-memory persistable full text search engine in less than 1000 lines of C# code.

#### Sample code projects demonstrating something
* [Winforms Sandbox](https://github.com/smourier/WinformsSandbox) - A sample Windows Forms .NET app that hosts the real and only Windows Sandbox.
* [WinUI3 Windows](https://github.com/smourier/WinUI3Windows) - A WinUI3 application that opens another Xaml window running on another thread.
* [Win32 Shows WinUI3](https://github.com/smourier/Win32ShowsWinUI3) - A simple Win32 desktop classic application (in C++) that can show WinUI3 elements (in .NET C#).
* [WinUI3 Notify Icon](https://github.com/smourier/WinUI3NotifyIcon) - A WinUI3 application that has a notify icon in the system tray. Once the icon in the notification has been clicked, a full WinUI3's Window is displayed.
* [XPS & PDF Print Samples](https://github.com/smourier/XpsPrintSamples) - XPS and PDF file printing samples.
* [Example Widget Provider](https://github.com/smourier/ExampleWidgetProviderAot) - ExampleWidgetProvider project in .NET 10 AOT
* [Excel Out-Of-Process RDT Server](https://github.com/smourier/ExcelOutOfProcessRdtServer) - An Excel out-of-process Real-Time Data (RTD) server written in .NET Core.
* [Reg-free .NET COM](https://github.com/smourier/RefreeNetCom) - A .NET 10+ registry-free In-Process COM server.
* [Reg-free .NET COM Server](https://github.com/smourier/RegfreeNetComServer) - A .NET 10+ registry-free Out-Of-Process COM server that also demonstrates 32-64 bit communication.
* [Out-Of-Process COM Server](https://github.com/smourier/OutOfProcessCOMServer) - An ATL C++ Out-Of-Process COM server and clients (C++, .NET, VBscript) sample.
* [MF Decode H264](https://github.com/smourier/MFDecodeH264) - A C++ console application code that decodes an H264 raw file using Media Foundation's H.264 Video Decoder.

#### Tools
* [Doxie](https://github.com/smourier/Doxie) - A search engine, local to your machine, focused on source (or textual information) code (based on SQLNado and Lucene .NET).
* [App Settings Studio](https://github.com/smourier/AppSettingsStudio) - A GUI for centralizing .NET appsettings.json management. Provides a unified view to edit, validate, and apply changes across multiple projects and/or binaries, including WSL on Windows, with support for live updates.
* [Jump List Explorer](https://github.com/smourier/JumpListExplorer) - A (forensics) tool to view and remove Windows JumpLists.
* [Device Explorer](https://github.com/smourier/DeviceExplorer) - A tool that displays the hardware attached to a Windows computer, similar to Device Manager. It also shows Association EndPoints dynamically (Bluetooth endpoints, UPnP, etc.) and Bluetooth LE advertisements.
* [Trace Spy](https://github.com/smourier/TraceSpy) - TraceSpy is a pure .NET, 100% free and open source, alternative to the very popular SysInternals DebugView tool.
* [Traces To CSV](https://github.com/smourier/TracesToCsv) - An ASP.NET Core app that continuously digest traces sent from HTTP(S) clients and creates csv files from them.
* [Raw Input Reader](https://github.com/smourier/RawInputReader) - A tool to read raw input from mouse, keyboard, or other hid devices.
* [CSharp Merge](https://github.com/smourier/CSharpMerge) - A console utility to merge .cs source files from a directory into one unique .cs file. Uses Roslyn.
* [Time Zone Changer](https://github.com/smourier/TimeZoneChanger) - A .NET apphost that runs in a custom time zone. Useful for testing apps in different time zones w/o rebooting nor changing Windows time zone.
* [Time Traveler](https://github.com/smourier/TimeTraveler) - A tool that runs any .NET executable in a parallel world, where time is not the same.
* [Auto Close Folder](https://github.com/smourier/AutoCloseFolder) - A Visual Studio extension that automatically closes folders when the last document from it is closed.
* [Binding Redirect Generator](https://github.com/smourier/BindingRedirectGenerator) - A tool to generate binding redirects from assemblies in a given path (for .NET Framework).
* [Normalize Line Endings](https://github.com/smourier/NormalizeLineEndings) - A tool to normalize files line ending.
* [VIM 2 VHD](https://github.com/smourier/VIM2VHD) - Pure C# version of VIM2VHD.
* [PDF Text Mask](https://github.com/smourier/PdfTextMask) - A C# tool to mask (and destroy from original text) portions of text in a document.
* [D3D12 SDK Version Patcher](https://github.com/smourier/D3D12SDKVersionPatcher) - A tool that can patch a .exe file exports to enabled DirectX 12 Agility SDK versioning
