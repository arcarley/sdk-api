---
UID: NN:dxgi1_6.IDXGIFactory7
title: IDXGIFactory7 (dxgi1_6.h)
description: This interface enables registration for notifications to detect adapter enumeration state changes.
helpviewer_keywords: ["IDXGIFactory7","IDXGIFactory7 interface [DXGI]","IDXGIFactory7 interface [DXGI]","described","direct3ddxgi.idxgifactory7","dxgi1_6/IDXGIFactory7"]
old-location: direct3ddxgi\idxgifactory7.htm
tech.root: direct3ddxgi
ms.assetid: 6E6B4E7F-F835-4FB9-9147-3659402EFCBB
ms.date: 12/05/2018
ms.keywords: IDXGIFactory7, IDXGIFactory7 interface [DXGI], IDXGIFactory7 interface [DXGI],described, direct3ddxgi.idxgifactory7, dxgi1_6/IDXGIFactory7
req.header: dxgi1_6.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows 10, version 1809 [desktop apps only]
req.target-min-winversvr: Windows Server, version 1709 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Dxgi.lib
req.dll: 
req.irql: 
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: RS5, 19H1
f1_keywords:
 - IDXGIFactory7
 - dxgi1_6/IDXGIFactory7
dev_langs:
 - c++
topic_type:
 - APIRef
 - kbSyntax
api_type:
 - COM
api_location:
 - dxgi.lib
 - dxgi.dll
api_name:
 - IDXGIFactory7
---

# IDXGIFactory7 interface


## -description

This interface enables registration for notifications to detect adapter enumeration state changes.

## -inheritance

The <b xmlns:loc="http://microsoft.com/wdcml/l10n">IDXGIFactory7</b> interface inherits from <a href="/windows/desktop/api/dxgi1_6/nn-dxgi1_6-idxgifactory6">IDXGIFactory6</a>. <b>IDXGIFactory7</b> also has these types of members:
<ul>
<li><a href="https://docs.microsoft.com/">Methods</a></li>
</ul>

## -members

The <b>IDXGIFactory7</b> interface has these methods.
<table class="members" id="memberListMethods">
<tr>
<th align="left" width="37%">Method</th>
<th align="left" width="63%">Description</th>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://msdn.microsoft.com/en-us/library/Mt832836(v=VS.85).aspx">RegisterAdaptersChangedEvent</a>
</td>
<td align="left" width="63%">
Registers to receive notification of changes whenever the adapter enumeration state changes.

</td>
</tr>
<tr data="declared;">
<td align="left" width="37%">
<a href="https://msdn.microsoft.com/en-us/library/Mt832837(v=VS.85).aspx">UnregisterAdaptersChangedEvent</a>
</td>
<td align="left" width="63%">
Unregisters  an event to stop receiving notifications when the adapter enumeration state changes.

</td>
</tr>
</table>