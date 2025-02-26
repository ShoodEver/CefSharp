[![CefSharp Logo](logo.png)](https://cefsharp.github.io/ "CefSharp - Embedded Chromium for .NET")

[![Build status](https://ci.appveyor.com/api/projects/status/9g4mcuqruc283g66/branch/master?svg=true)](https://ci.appveyor.com/project/cefsharp/cefsharp/branch/master)
[![CefSharp.WinForms](https://img.shields.io/nuget/v/CefSharp.WinForms.svg?style=flat&label=WinForms)](https://www.nuget.org/packages/CefSharp.WinForms/)
[![CefSharp.Wpf](https://img.shields.io/nuget/v/CefSharp.Wpf.svg?style=flat&label=Wpf)](https://www.nuget.org/packages/CefSharp.Wpf/)
[![CefSharp.Wpf.HwndHost](https://img.shields.io/nuget/v/CefSharp.Wpf.HwndHost.svg?style=flat&label=Wpf.HwndHost)](https://www.nuget.org/packages/CefSharp.Wpf.HwndHost/)
[![CefSharp.OffScreen](https://img.shields.io/nuget/v/CefSharp.OffScreen.svg?style=flat&label=OffScreen)](https://www.nuget.org/packages/CefSharp.OffScreen/)

Got a quick question? [Discussions](https://github.com/cefsharp/CefSharp/discussions) here on `GitHub` is the preferred place to ask!

[CefSharp](https://cefsharp.github.io/) lets you embed Chromium in .NET apps. It is a lightweight .NET wrapper around the [Chromium Embedded Framework (CEF)](https://bitbucket.org/chromiumembedded/cef) by Marshall A. Greenblatt. About 30% of the bindings are written in C++/CLI with the majority of code here is C#. It can be used from C# or VB, or any other CLR language. CefSharp provides both WPF and WinForms web browser control implementations.

CefSharp is [BSD](https://opensource.org/licenses/BSD-3-Clause "BSD License") licensed, so it can be used in both proprietary and free/open source applications. For the full details, see the [LICENSE](LICENSE) file. 

If you like and use CefSharp please consider signing up for a small monthly donation, even $25 can help tremendously. See [Financial Support](Readme.md#Financial-Support) for more details.

## Releases

Stable binaries are released on NuGet, and contain everything you need to embed Chromium in your .Net/CLR application. For usage see the [Quick Start](https://github.com/cefsharp/CefSharp/wiki/Quick-Start) guide or checkout [CefSharp.MinimalExample](https://github.com/cefsharp/CefSharp.MinimalExample/) project for basic demos using the CefSharp NuGet packages.

- [CefSharp.WinForms](https://www.nuget.org/packages/CefSharp.WinForms/)
- [CefSharp.Wpf](https://www.nuget.org/packages/CefSharp.Wpf/)
- [CefSharp.OffScreen](https://www.nuget.org/packages/CefSharp.OffScreen/)
- [CefSharp.Wpf.HwndHost](https://github.com/cefsharp/CefSharp.Wpf.HwndHost/) (A [HwndHost](https://docs.microsoft.com/en-us/dotnet/api/system.windows.interop.hwndhost) based WPF implementation, similar to hosting the WinForms version in WPF, supports data binding, airspace issues apply).

## Documentation

* See the [CefSharp.Wpf.Example](https://github.com/cefsharp/CefSharp/tree/master/CefSharp.Wpf.Example) or [CefSharp.WinForms.Example](https://github.com/cefsharp/CefSharp/tree/master/CefSharp.WinForms.Example) projects for example web browsers built with CefSharp. They demo most of the available features.
* See the [CefSharp.MinimalExample](https://github.com/cefsharp/CefSharp.MinimalExample/) project for a basic demo of using the CefSharp NuGet packages.
* See the [General Usage Guide](https://github.com/cefsharp/CefSharp/wiki/General-Usage) in help getting started/dealing with common scenarios.
* See the [Wiki](https://github.com/cefsharp/CefSharp/wiki) for work-in-progress documentation
* See the [FAQ](https://github.com/cefsharp/CefSharp/wiki/Frequently-asked-questions) for help with common issues
* Upgrading from an earlier version of CefSharp? See the [ChangeLog](https://github.com/cefsharp/CefSharp/wiki/ChangeLog) for breaking changes and upgrade tips.
* [CefSharp API](https://cefsharp.github.io/api/) generated from the source code comments.

## Contact

Please keep the `Issue Tracker` for **Bugs** only please! Before submitting a `PR` please read [CONTRIBUTING](https://github.com/cefsharp/CefSharp/blob/master/CONTRIBUTING.md).

- [CefSharp Discussions](https://github.com/cefsharp/CefSharp/discussions) is generally where `CefSharp` specific questions should be asked, please search before posting, thanks!
- [Stackoverflow](https://stackoverflow.com/questions/tagged/cefsharp) is where generic html/javascript/C# questions can be asked.
- [Chromium Embedded Framework(CEF) Forum](https://magpcss.org/ceforum/viewforum.php?f=18)

## Branches & Forks

This is the `official` CefSharp fork, as maintained by the CefSharp community. You can also view [the entire network of public forks/branches](https://github.com/cefsharp/CefSharp/network).

Development is done in the `master` branch. New features are preferably added in feature branches, if the changes are more than trivial. New `PR's` should be targeted against `master`.

When a new release is imminent a `release` branch is created. We try to avoid making public facing `API` changes in `release` branches (Adding new features is fine, just not breaking changes).

### Releases

**CI Builds**<br/>
Every commit on `master` produces a `Nuget` package. Use at your own risk!


- [![MyGet Pre Release](https://img.shields.io/myget/cefsharp/v/CefSharp.WinForms.svg?style=flat&label=WinForms)](https://www.myget.org/feed/cefsharp/package/nuget/CefSharp.WinForms)
- [![MyGet Pre Release](https://img.shields.io/myget/cefsharp/v/CefSharp.Wpf.svg?style=flat&label=Wpf)](https://www.myget.org/feed/cefsharp/package/nuget/CefSharp.Wpf)
- [![MyGet Pre Release](https://img.shields.io/myget/cefsharp/v/CefSharp.OffScreen.svg?style=flat&label=OffScreen)](https://www.myget.org/feed/cefsharp/package/nuget/CefSharp.OffScreen)

**Pre-release**<br>

- [![CefSharp.WinForms](http://img.shields.io/nuget/vpre/CefSharp.WinForms.svg?style=flat&label=CefSharp.WinForms)](http://www.nuget.org/packages/CefSharp.WinForms/)
- [![CefSharp.Wpf](http://img.shields.io/nuget/vpre/CefSharp.Wpf.svg?style=flat&label=CefSharp.Wpf)](http://www.nuget.org/packages/CefSharp.Wpf/)
- [![CefSharp.OffScreen](http://img.shields.io/nuget/vpre/CefSharp.OffScreen.svg?style=flat&label=CefSharp.OffScreen)](http://www.nuget.org/packages/CefSharp.OffScreen/)

- [![CefSharp.WinForms.NETCore](http://img.shields.io/nuget/vpre/CefSharp.WinForms.NETCore.svg?style=flat&label=CefSharp.WinForms.NETCore)](http://www.nuget.org/packages/CefSharp.WinForms.NETCore/)
- [![CefSharp.Wpf.NETCore](http://img.shields.io/nuget/vpre/CefSharp.Wpf.NETCore.svg?style=flat&label=CefSharp.Wpf.NETCore)](http://www.nuget.org/packages/CefSharp.Wpf.NETCore/)
- [![CefSharp.OffScreen.NETCore](http://img.shields.io/nuget/vpre/CefSharp.OffScreen.NETCore.svg?style=flat&label=CefSharp.OffScreen.NETCore)](http://www.nuget.org/packages/CefSharp.OffScreen.NETCore/)

**Stable**<br>
- [![CefSharp.WinForms](http://img.shields.io/nuget/v/CefSharp.WinForms.svg?style=flat&label=CefSharp.WinForms)](http://www.nuget.org/packages/CefSharp.WinForms/)
- [![CefSharp.Wpf](http://img.shields.io/nuget/v/CefSharp.Wpf.svg?style=flat&label=CefSharp.Wpf)](http://www.nuget.org/packages/CefSharp.Wpf/)
- [![CefSharp.OffScreen](http://img.shields.io/nuget/v/CefSharp.OffScreen.svg?style=flat&label=CefSharp.OffScreen)](http://www.nuget.org/packages/CefSharp.OffScreen/)

- [![CefSharp.WinForms.NETCore](http://img.shields.io/nuget/v/CefSharp.WinForms.NETCore.svg?style=flat&label=CefSharp.WinForms.NETCore)](http://www.nuget.org/packages/CefSharp.WinForms.NETCore/)
- [![CefSharp.Wpf.NETCore](http://img.shields.io/nuget/v/CefSharp.Wpf.NETCore.svg?style=flat&label=CefSharp.Wpf.NETCore)](http://www.nuget.org/packages/CefSharp.Wpf.NETCore/)
- [![CefSharp.OffScreen.NETCore](http://img.shields.io/nuget/v/CefSharp.OffScreen.NETCore.svg?style=flat&label=CefSharp.OffScreen.NETCore)](http://www.nuget.org/packages/CefSharp.OffScreen.NETCore/)

### Release Branches

With each release a new branch is created, for example the `92.0.260` release corresponds to the [cefsharp/92](https://github.com/cefsharp/CefSharp/tree/cefsharp/92) branch.
If you're new to `CefSharp` and are downloading the source to check it out, please use a **Release** branch.

**&ast;** VC++ 2019 is required starting with version 93<br/>
**&ast;&ast;** For .Net Core Packages .Net Core 3.1/.Net 5.0 is required. 

| Branch                                                               | CEF Version  | VC++ Version | .Net Version | Status |
|----------------------------------------------------------------------|------|-------|---------|-----------------|
| [master](https://github.com/cefsharp/CefSharp/)                      | 4692 | 2019* | 4.5.2** | Development     |
| [cefsharp/97](https://github.com/cefsharp/CefSharp/tree/cefsharp/97) | 4692 | 2019* | 4.5.2** | **Release**     |
| [cefsharp/96](https://github.com/cefsharp/CefSharp/tree/cefsharp/96) | 4664 | 2019* | 4.5.2** | Unsupported     |
| [cefsharp/95](https://github.com/cefsharp/CefSharp/tree/cefsharp/95) | 4638 | 2019* | 4.5.2** | Unsupported     |
| [cefsharp/94](https://github.com/cefsharp/CefSharp/tree/cefsharp/94) | 4606 | 2019* | 4.5.2** | Unsupported     |
| [cefsharp/93](https://github.com/cefsharp/CefSharp/tree/cefsharp/93) | 4577 | 2019* | 4.5.2** | Unsupported     |
| [cefsharp/92](https://github.com/cefsharp/CefSharp/tree/cefsharp/92) | 4515 | 2015* | 4.5.2** | Unsupported     |
| [cefsharp/91](https://github.com/cefsharp/CefSharp/tree/cefsharp/91) | 4472 | 2015* | 4.5.2** | Unsupported     |
| [cefsharp/90](https://github.com/cefsharp/CefSharp/tree/cefsharp/90) | 4430 | 2015* | 4.5.2** | Unsupported     |
| [cefsharp/89](https://github.com/cefsharp/CefSharp/tree/cefsharp/89) | 4389 | 2015* | 4.5.2** | Unsupported     |
| [cefsharp/88](https://github.com/cefsharp/CefSharp/tree/cefsharp/88) | 4324 | 2015* | 4.5.2** | Unsupported     |
| [cefsharp/87](https://github.com/cefsharp/CefSharp/tree/cefsharp/87) | 4280 | 2015* | 4.5.2** | Unsupported     |
| [cefsharp/86](https://github.com/cefsharp/CefSharp/tree/cefsharp/86) | 4240 | 2015  | 4.5.2   | Unsupported     |
| [cefsharp/85](https://github.com/cefsharp/CefSharp/tree/cefsharp/85) | 4183 | 2015  | 4.5.2   | Unsupported     |
| [cefsharp/84](https://github.com/cefsharp/CefSharp/tree/cefsharp/84) | 4147 | 2015  | 4.5.2   | Unsupported     |
| [cefsharp/83](https://github.com/cefsharp/CefSharp/tree/cefsharp/83) | 4103 | 2015  | 4.5.2   | Unsupported     |
| [cefsharp/81](https://github.com/cefsharp/CefSharp/tree/cefsharp/81) | 4044 | 2015  | 4.5.2   | Unsupported     |
| [cefsharp/79](https://github.com/cefsharp/CefSharp/tree/cefsharp/79) | 3945 | 2015  | 4.5.2   | Unsupported     |
| [cefsharp/77](https://github.com/cefsharp/CefSharp/tree/cefsharp/77) | 3865 | 2015  | 4.5.2   | Unsupported     |
| [cefsharp/75](https://github.com/cefsharp/CefSharp/tree/cefsharp/75) | 3770 | 2015  | 4.5.2   | Unsupported     |
| [cefsharp/73](https://github.com/cefsharp/CefSharp/tree/cefsharp/73) | 3683 | 2015  | 4.5.2   | Unsupported     |
| [cefsharp/71](https://github.com/cefsharp/CefSharp/tree/cefsharp/71) | 3578 | 2015  | 4.5.2   | Unsupported     |
| [cefsharp/69](https://github.com/cefsharp/CefSharp/tree/cefsharp/69) | 3497 | 2015  | 4.5.2   | Unsupported     |
| [cefsharp/67](https://github.com/cefsharp/CefSharp/tree/cefsharp/67) | 3396 | 2015  | 4.5.2   | Unsupported     |
| [cefsharp/65](https://github.com/cefsharp/CefSharp/tree/cefsharp/65) | 3325 | 2015  | 4.5.2   | Unsupported     |
| [cefsharp/63](https://github.com/cefsharp/CefSharp/tree/cefsharp/63) | 3239 | 2013  | 4.5.2   | Unsupported     |
| [cefsharp/62](https://github.com/cefsharp/CefSharp/tree/cefsharp/62) | 3202 | 2013  | 4.5.2   | Unsupported     |
| [cefsharp/57](https://github.com/cefsharp/CefSharp/tree/cefsharp/57) | 2987 | 2013  | 4.5.2   | Unsupported     |
| [cefsharp/55](https://github.com/cefsharp/CefSharp/tree/cefsharp/55) | 2883 | 2013  | 4.5.2   | Unsupported     |
| [cefsharp/53](https://github.com/cefsharp/CefSharp/tree/cefsharp/53) | 2785 | 2013  | 4.5.2   | Unsupported     |
| [cefsharp/51](https://github.com/cefsharp/CefSharp/tree/cefsharp/51) | 2704 | 2013  | 4.5.2   | Unsupported     |
| [cefsharp/49](https://github.com/cefsharp/CefSharp/tree/cefsharp/49) | 2623 | 2013  | 4.0     | Unsupported     |
| [cefsharp/47](https://github.com/cefsharp/CefSharp/tree/cefsharp/47) | 2526 | 2013  | 4.0     | Unsupported     |
| [cefsharp/45](https://github.com/cefsharp/CefSharp/tree/cefsharp/45) | 2454 | 2013  | 4.0     | Unsupported     |
| [cefsharp/43](https://github.com/cefsharp/CefSharp/tree/cefsharp/43) | 2357 | 2012  | 4.0     | Unsupported     |
| [cefsharp/41](https://github.com/cefsharp/CefSharp/tree/cefsharp/41) | 2272 | 2012  | 4.0     | Unsupported     |
| [cefsharp/39](https://github.com/cefsharp/CefSharp/tree/cefsharp/39) | 2171 | 2012  | 4.0     | Unsupported     |
| [cefsharp/37](https://github.com/cefsharp/CefSharp/tree/cefsharp/37) | 2062 | 2012  | 4.0     | Unsupported     |

**&ast;** VC++ 2019 is required starting with version 93<br/>
**&ast;&ast;** For .Net Core Packages .Net Core 3.1/.Net 5.0 is required. 

## Financial Support

To continue developing/supporting the project I (@amaitland) am asking for financial contributions. Donations of any size are greatly appreciated!

One-Time or Recurring contributions can be made through [GitHub Sponsors](https://github.com/sponsors/amaitland) it only takes a GitHub account and a credit card.  I can also take contributions through [PayPal](https://paypal.me/AlexMaitland).

Now that I (@amaitland) am a stay at home dad your contributions are the only reason I'm allowed to continue working on the project. Without continued funding the time I currently spend on the project will have to be put into finding other paid work.

## Links

- [CefGlue](https://gitlab.com/xiliumhq/chromiumembedded/cefglue): An alternative .NET CEF wrapper built using P/Invoke.
- [CEF Bitbucket Project](https://bitbucket.org/chromiumembedded/cef/overview) : The official CEF issue tracker
- [CEF Forum](http://magpcss.org/ceforum/) : The official CEF Forum
- [CEF API Docs](http://magpcss.org/ceforum/apidocs3/index-all.html) : Well worth a read if you are implementing a new feature
- [CefSharp API Doc](http://cefsharp.github.io/api/)

## Projects using CefSharp
- [HtmlView](https://github.com/ramon-mendes/HtmlView) : Visual Studio extension bringing CefSharp for showing HTML pages inside VS.
- [SharpBrowser](https://github.com/sharpbrowser/SharpBrowser) : The fastest web browser for C# with tabbed browsing and HTML5/CSS3.
- [Chromely CefSharp](https://github.com/chromelyapps/CefSharp) : Build HTML Desktop Apps on .NET/.NET Core 3/.NET 5 using native GUI, HTML5/CSS.
