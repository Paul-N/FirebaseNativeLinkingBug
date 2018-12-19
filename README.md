# Upd 19 Dec 2018:
Now it's possible to build this project, all you need is to add 
```
            var foo = Firebase.Core.Configuration.SharedInstance;
```
See https://github.com/xamarin/GoogleApisForiOSComponents/issues/158#issuecomment-448682798
# FirebaseNativeLinkingBug
Repo for demo Native Linking bug while using Firebase

See packages.config:
```
<packages>
  <package id="Xamarin.Build.Download" version="0.4.11" targetFramework="xamarinios10" />
  <package id="Xamarin.Firebase.iOS.Analytics" version="5.1.4" targetFramework="xamarinios10" />
  <package id="Xamarin.Firebase.iOS.CloudMessaging" version="3.1.2" targetFramework="xamarinios10" />
  <package id="Xamarin.Firebase.iOS.Core" version="5.1.3" targetFramework="xamarinios10" />
  <package id="Xamarin.Firebase.iOS.Crashlytics" version="3.10.9" targetFramework="xamarinios10" />
  <package id="Xamarin.Firebase.iOS.InstanceID" version="3.2.1" targetFramework="xamarinios10" />
</packages>
```

This repo is almost default iOS project, created by Visual Studio for Mac. The only change is the set of nuget packages (see above). 

# This project CAN NOT be built in this environment:

Visual Studio Community 2017 for Mac
Version 7.7 (build 1868)
Installation UUID: be401d1b-e028-4720-bba5-f4766cba7973
	GTK+ 2.24.23 (Raleigh theme)
	Xamarin.Mac 4.4.1.178 (master / eeaeb7e6)

	Package version: 516000221

Mono Framework MDK
Runtime:
	Mono 5.16.0.221 (2018-06/b63e5378e38) (64-bit)
	Package version: 516000221

NuGet
Version: 4.7.0.5148

.NET Core
Runtime: /usr/local/share/dotnet/dotnet
Runtime Versions:
	2.1.2
	2.1.1
	2.0.5
SDK: /usr/local/share/dotnet/sdk/2.1.302/Sdks
SDK Versions:
	2.1.302
	2.1.301
	2.1.4
MSBuild SDKs: /Library/Frameworks/Mono.framework/Versions/5.16.0/lib/mono/msbuild/15.0/bin/Sdks

Xamarin.Profiler
Version: 1.6.4
Location: /Applications/Xamarin Profiler.app/Contents/MacOS/Xamarin Profiler

Apple Developer Tools
Xcode 10.1 (14460.46)
Build 10B61

Xamarin.Mac
Version: 5.2.1.11 (Visual Studio Community)
Hash: 5ef73d34
Branch: 
Build date: 2018-11-21 00:03:25-0500

Xamarin.iOS
Version: 12.2.1.11 (Visual Studio Community)
Hash: 5ef73d34
Branch: d15-9
Build date: 2018-11-21 00:03:24-0500

Build Information
Release ID: 707001868
Git revision: 8bcdfa96d67c8c88dc45728cc968a2f84b55322f
Build date: 2018-11-22 12:19:29+00
Build branch: release-7.7
Xamarin extensions: d66dbedcda237cd9b546abfecfeecafba6f8e3cb

Operating System
Mac OS X 10.14.1
Darwin 18.2.0 Darwin Kernel Version 18.2.0
    Fri Oct  5 19:40:55 PDT 2018
    root:xnu-4903.221.2~1/RELEASE_X86_64 x86_64

Enabled user installed extensions
MvvmCross Template pack 2.0.1
FileNesting 0.1.1
MSBuild Editor 2.1.0
NuGet Package Explorer 0.2
Open With 0.1
NuGet Package Management Extensions 0.13
Prism Template Studio and Developer Toolkit 2.2.0.434
Prism QuickStart TemplatePack 1.5.0

