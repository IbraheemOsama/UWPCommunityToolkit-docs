---
permalink: /en-US/helpers/visualtreeextensions.htm
title: VisualTreeExtensions utility
description: VisualTreeExtensions defines a collection of extensions methods for UI
keywords: windows, app, toolkit, UWP, helpers, visual tree
layout: api
search.product: eADQiWindows 10XVcnh
lang: en-us
---

# VisualTreeExtensions

The **VisualTreeExtensions** provides a collection of extensions methods for UI.

## Example

{% highlight csharp %}

	// Find descendant control using its name
	var control = uiElement.FindDescendantByName("mytextbox");

	// Find first descendant control of a specified type
	control = uiElement.FindDescendant<ListView>();

	// Find first ascendant control of a specified type
	control = uiElement.FindAscendant<ListView>();

	// Find first visual ascendant control of a specified type
	control = uiElement.FindVisualAscendant<ScrollViewer>();

{% endhighlight %}

## Requirements (Windows 10 Device Family)

| [Device family](http://go.microsoft.com/fwlink/p/?LinkID=526370) | Universal, 10.0.10586.0 or higher |
| Namespace | Microsoft.Toolkit.Uwp |

## API

* [VisualTreeExtensions source code](https://github.com/Microsoft/UWPCommunityToolkit/blob/master/Microsoft.Toolkit.Uwp.UI/Extensions/VisualTreeExtensions.cs)
* [VisualTreeExtensions API documentation]({{site.baseurl}}/{{page.lang}}/api/Microsoft_Toolkit_Uwp_UI_VisualTreeExtensions.htm)

