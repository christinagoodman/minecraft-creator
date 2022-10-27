---
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.TitleDisplayOptions Interface
description: Contents of the @minecraft/server.TitleDisplayOptions class.
---
# TitleDisplayOptions Interface
>[!IMPORTANT]
>These APIs are experimental as part of the Beta APIs experiment. As with all experiments, you may see changes in functionality in updated Minecraft versions. Check the Minecraft Changelog for details on any changes to Beta APIs. Where possible, this documentation reflects the latest updates to APIs in Minecraft beta versions.

> [!CAUTION]
> This interface is still in pre-release.  Its signature may change or it may be removed in future releases.

Contains additional options for displaying a title and optional subtitle.

## Properties

### **fadeInSeconds**
`fadeInSeconds: number;`

Fade-in time for the title and subtitle, in seconds.

Type: *number*

### **fadeOutSeconds**
`fadeOutSeconds: number;`

Fade-out time for the title and subtitle, in seconds.

Type: *number*

### **staySeconds**
`staySeconds: number;`

Amount of time for the title and subtitle to stay in place.

Type: *number*

### **subtitle**
`subtitle?: string;`

Optional subtitle text.

Type: *string*