---
title: "Opening the SSCP Connection2 | Microsoft Docs"
ms.custom: ""
ms.date: "11/30/2017"
ms.prod: "host-integration-server"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 6094a0f6-099e-48d4-9a1f-6739f76f45f6
caps.latest.revision: 3
---
# Opening the SSCP Connection
An application gains access to the system services control point (SSCP) session by opening an SSCP connection to the local node. To do this, an application sends an [Open(SSCP) Request](../HIS2010/open-sscp-request1.md) message to the local node, which responds with an [Open(SSCP) Response](../HIS2010/open-sscp-response2.md). The local node follows a positive **Open(SSCP) Response** with a [Status-Session](../HIS2010/status-session1.md) message reporting the current state of the SSCP session. (For more information, see [Using the SSCP Session](../HIS2010/sscp-session1.md).)  
  
 The following figure shows the message flow. For a figure showing a more detailed message flow, including locality, partner, index (LPI) values used during initialization of both the SSCP and primary logical unit (PLU) sessions, see [Opening the PLU Connection](../HIS2010/opening-the-plu-connection2.md).  
  
 ![](../core/media/his-32703c.gif "his_32703c")  
Message flow between a local node and an application  
  
## In This Section  
  
-   [LU Groups](../HIS2010/lu-groups2.md)  
  
-   [Resource Location for Open SSCP](../HIS2010/resource-location-for-open-sscp1.md)