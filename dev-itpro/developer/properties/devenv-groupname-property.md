---
title: "GroupName Property"
description: "If the entitlement type is ConcurrentUserServicePlan, the GroupName determines which AAD group that users with this entitlement should be members of."
ms.author: solsen
ms.custom: na
ms.date: 10/25/2023
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: reference
author: SusanneWindfeldPedersen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)
# GroupName Property
> **Version**: _Available or changed with runtime version 7.0._

If the entitlement type is ConcurrentUserServicePlan, the GroupName determines which AAD group that users with this entitlement should be members of.

## Applies to
-   Entitlement

[//]: # (IMPORTANT: END>DO_NOT_EDIT)

## Remarks

[!INCLUDE[azure-ad-to-microsoft-entra-id](~/../shared-content/shared/azure-ad-to-microsoft-entra-id.md)]

> [!NOTE]  
> In the current version of [!INCLUDE [prod_short](../../includes/prod_short.md)] entitlements can only be included with Microsoft apps (enforced by the AppSource cop rules and the technical validation checks that we run for the apps submitted to AppSource). These objects will become available for the ISV apps when we introduce ability to monetize AppSource apps in one of our future releases. For more information, see [Entitlement Object](../devenv-entitlement-object.md).

## See Also

[Get Started with AL](../devenv-get-started.md)  
[Developing Extensions](../devenv-dev-overview.md)  
[Entitlement Object](../devenv-entitlement-object.md)  