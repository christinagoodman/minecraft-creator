---
author: jakeshirley
ms.author: jashir
ms.prod: gaming
title: minecraft/server.ItemUseEvent Class
description: Contents of the @minecraft/server.ItemUseEvent class.
---
# ItemUseEvent Class
>[!IMPORTANT]
>These APIs are experimental as part of the Beta APIs experiment. As with all experiments, you may see changes in functionality in updated Minecraft versions. Check the Minecraft Changelog for details on any changes to Beta APIs. Where possible, this documentation reflects the latest updates to APIs in Minecraft beta versions.

> [!CAUTION]
> This class is still in pre-release.  Its signature may change or it may be removed in future releases.

Contains information related to an item being used.

## Properties

### **item**
`item: ItemStack;`

The impacted item stack that is being used.

Type: [*ItemStack*](ItemStack.md)

### **source**
`read-only source: Entity;`

Returns the source entity that triggered this item event.

Type: [*Entity*](Entity.md)

