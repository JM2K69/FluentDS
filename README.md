![Logo](https://s3.wasabisys.com/datacdn/dl/FluentDS.svg)

# Fluent Design System for .NET 5
WPF Class Library forked from FluentUI.Core then optimized, updated, rebuilt and repackaged for .NET 5.0.2

### Preview Image
![PreviewImage](https://raw.githubusercontent.com/adospace/fluent-ui-xaml/master/gallery.gif)

---

### Version 1.0.0 | Release Date: April 5, 2021
* Changes from the original repo:
  * Removed WinForms library
  * Removed .NET Core Examples project
  * Removed .NET Framework library
  * Removed .NET Framework Examples project
* New to this repo
  * Added support for .NET 5
  * Added an icon to more easily differentiate this specific library
  * Imported code (XAML and otherwise) for all Components and Styles into the same namespace as the rest of the project
  * Replaced all instances of "FluentUI" and "Fabric" namespaces, classes, etc., with "FluentDS" (all items now are in the same namespace.)

---

## Getting Started
Add using statements:
```csharp
using FluentDS;
using FluentDS.Styles; //Optional
using FluentDS.Converters; //Optional
```

In MainWindow.cs, inherit FluentWindow
```csharp
public partial class MainWindow : FluentWindow
{
    public MainWindow()
    {
        InitializeComponent();
    }
}
```
        
---

### Credits
* This library is essentially a direct fork of the original [FluentUI.Core](https://github.com/adospace/fluent-ui-xaml) by [adospace](https://github.com/adospace/) 
* Originally released under the MIT license (this release is, too.) 
* Thank you to **Icons8.com** for the new icon

**License:** MIT (as per the original author, credited above.)
