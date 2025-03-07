---
title: "Define a New Trunk"
ms.reviewer: 
ms.author: serdars
author: SerdarSoysal
manager: serdars
ms.date: 11/17/2018
audience: ITPro
ms.topic: article
f1.keywords:
- CSH
ms.custom:
- ms.lync.tb.AddTrunkPage
ms.prod: skype-for-business-itpro
ms.localizationpriority: medium
ms.assetid: e5d97b27-5ae8-41e0-8ee9-0c3f6d5dd123
description: "You define a new session initiation protocol (SIP) trunk by providing the following information:"
---

# Define a New Trunk

You define a new session initiation protocol (SIP) trunk by providing the following information:

- **Trunk name**: unique name in your topology that will identify this trunk

- **Associated PSTN Gateway**: select a deployed and configured PSTN gateway in your deployment from the list

- **Listening port for the IP/PSTN gateway**: port that the IP-PBX or PSTN gateway will listen on. Must be unique from all other trunk listening ports configured in your deployment

- **SIP Transport Protocol**: select from the list either TCP or TLS

- **Associated Mediation Server**: select from the list a Mediation Server that is deployed and configured in your deployment

- **Associated Mediation Server port**: set the port value equal to the TCP or TLS port value of the Mediation Server that this SIP trunk will use

## See also

[M:N trunk in Skype for Business Server 2015](../../plan-your-deployment/enterprise-voice-solution/m-n-trunk.md)

[How do I implement SIP trunking?](/previous-versions/office/lync-server-2013/lync-server-2013-how-do-i-implement-sip-trunking)