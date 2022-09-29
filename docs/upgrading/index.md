---
title: "Upgrading from Xamarin to .NET"
description: "All Xamarin applications can upgrade to .NET starting with .NET 6"
ms.date: 10/01/2022
---

# Upgrade overview

Xamarin projects can run on .NET 6 and newer after completing some upgrade steps. These guides describe the most common steps required to run your existing code on .NET.

* All projects DO need to become "SDK Style"
* Projects do NOT need to be rewritten
* Multi-project solutions do NOT need to become "single project"

## [Xamarin.Android, Xamarin.iOS, Xamarin.Mac](xamarin-projects.md)

These SDKs are all supported in .NET 6, and Xamarin projects have an upgrade path. Very little needs to change, making these projects among the easier to upgrade.

## [Xamarin.Forms](forms-projects.md)

Xamarin.Forms solutions include Xamarin.Android, Xamarin.iOS, and often UWP and Tizen projects. A few additional steps are required to upgrade to .NET as compared to Xamarin.Android and Xamarin.iOS alone.

### See also

* [Custom renderers in .NET MAUI](using-custom-renderers.md)
* [Default value changes](defaults.md)
* [Layout changes](layout-reference.md)
* [Troubleshooting guide](troubleshooting.md)