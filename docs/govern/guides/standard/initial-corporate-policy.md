---
title: 'Standard enterprise governance: Initial corporate policy'
description: Use the Cloud Adoption Framework for Azure to define initial standard governance position, early-stage risks, initial policy statements, and early enforcement processes.
author: BrianBlanchard
ms.author: brblanch
ms.date: 09/05/2019
ms.topic: conceptual
ms.service: cloud-adoption-framework
ms.subservice: govern
ms.custom: internal
---

# Standard enterprise governance guide: Initial corporate policy behind the governance strategy

The following corporate policy defines an initial governance position, which is the starting point for this guide. This article defines early-stage risks, initial policy statements, and early processes to enforce policy statements.

> [!NOTE]
> The corporate policy is not a technical document, but it drives many technical decisions. The governance MVP described in the [overview](./index.md) ultimately derives from this policy. Before implementing a governance MVP, your organization should develop a corporate policy based on your own objectives and business risks.

## Cloud governance team

In this narrative, the cloud governance team is comprised of two systems administrators who have recognized the need for governance. Over the next several months, they will inherit the job of cleaning up the governance of the company's cloud presence, earning them the title of *cloud custodians*. In subsequent iterations, this title will likely change.

[!INCLUDE [business-risk](../../../../includes/business-risks.md)]

## Tolerance indicators

The current tolerance for risk is high and the appetite for investing in cloud governance is low. As such, the tolerance indicators act as an early warning system to trigger more investment of time and energy. If and when the following indicators are observed, you should iteratively improve the governance strategy.

- **Cost management:** The scale of deployment exceeds predetermined limits on number of resources or monthly cost.
- **Security baseline:** Inclusion of protected data in defined cloud adoption plans.
- **Resource consistency:** Inclusion of any mission-critical applications in defined cloud adoption plans.

[!INCLUDE [policy-statements](../../../../includes/policy-statements.md)]

## Next steps

This corporate policy prepares the cloud governance team to implement the governance MVP, which will be the foundation for adoption. The next step is to implement this MVP.

> [!div class="nextstepaction"]
> [Best practices explained](./prescriptive-guidance.md)
