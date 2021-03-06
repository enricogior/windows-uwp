---
title: Submit packages to Windows Package Manager
description: You can use Windows Package Manager as a distribution channel for software packages containing your applications.
ms.date: 04/29/2020
ms.topic: overview
ms.localizationpriority: medium
---

# Submit packages to Windows Package Manager

[!INCLUDE [preview-note](../../includes/package-manager-preview.md)]

If you're an Independent Software Vendor (ISV), you can use Windows Package Manager as a distribution channel for software packages containing your applications. Windows Package Manager currently supports installers in the following formats: MSIX, MSI, and EXE.

To submit software packages to Windows Package Manager, follow these steps:

1. [Create a package manifest that provides information about your application](manifest.md). Manifests are YAML files that follow the Windows Package Manager schema.
2. [Submit your manifest to the Windows Package Manager repository](repository.md). This is an open source repository on GitHub that contains a collection of manifests that the **winget** tool can access.

## Related topics

* [Use the winget tool](../winget/index.md)
* [Create your package manifest](manifest.md)
* [Submit your manifest to the repository](repository.md)
