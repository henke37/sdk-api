---
UID: NE:winuser.__unnamed_enum_2
tech.root: inputdev
title: TOOLTIP_DISMISS_FLAGS
ms.date: 06/17/2022
targetos: Windows
description: 
prerelease: false
req.construct-type: enumeration
req.ddi-compliance: 
req.header: winuser.h
req.include-header: 
req.kmdf-ver: 
req.max-support: 
req.target-min-winverclnt: Windows 11 Build 22621
req.target-min-winversvr: 
req.target-type: Windows
req.typenames: 
req.umdf-ver: 
topic_type:
 - apiref
api_type:
 - HeaderDef
api_location:
 - winuser.h
api_name:
 - TOOLTIP_DISMISS_FLAGS
f1_keywords:
 - TOOLTIP_DISMISS_FLAGS
 - winuser/TOOLTIP_DISMISS_FLAGS
dev_langs:
 - c++
helpviewer_keywords:
 - __unnamed_enum_2
---

## -description

Defines constants that indicate whether a window is registered or unregistered to receive tooltip dismiss notifications.

## -enum-fields

### -field TDF_REGISTER

The window is registered to receive tooltip dismiss notifications.

### -field TDF_UNREGISTER

The window is unregistered from receiving tooltip dismiss notifications.

## -remarks

This enumeration is used by the [RegisterForTooltipDismissNotification](nf-winuser-registerfortooltipdismissnotification.md) function.

## -see-also

[RegisterForTooltipDismissNotification](nf-winuser-registerfortooltipdismissnotification.md), [Tooltip](/windows/win32/controls/tooltip-control-reference)
