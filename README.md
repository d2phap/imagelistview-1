ImageListView is a .NET control for displaying a list of image files. It looks and operates similar to the standard ListView control. Image thumbnails are loaded asynchronously with a separate background thread.

ImageListView requires .NET framework 3.5 to take advantage of the Windows Imaging Component. It is possible to recompile ImageListView to [target .NET 2.0](https://github.com/oozcitak/imagelistview/wiki/WICSupport) without Windows Imaging Component.

# Features #
  * Asynchronously loaded image thumbnails
  * [Custom renderers](https://github.com/oozcitak/imagelistview/wiki/ImageListViewRenderer)
  * [Thumbnails, Gallery, Pane and Details view modes](https://github.com/oozcitak/imagelistview/wiki/ViewModes)
  * Ability to extract embedded thumbnails
  * Drag&drop support
  * Works with .NET 3.5
  * Optionally works with [.NET 2.0](https://github.com/oozcitak/imagelistview/wiki/WICSupport) and [Mono 2.6](https://github.com/oozcitak/imagelistview/wiki/MonoSupport)

![ImageListView](https://github.com/oozcitak/imagelistview/blob/wiki/ImageListView.thumbnails.jpg)

# Installation #

If you are using [NuGet](https://nuget.org/) you can install the assembly with:

`PM> Install-Package ImageListView`
