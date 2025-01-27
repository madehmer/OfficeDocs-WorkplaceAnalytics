---

title: Differential privacy in Viva Insights  
description: Learn about how Microsoft Viva Insights uses Differential Privacy technology for data analysis
author: madehmer
ms.author: v-mideh
ms.topic: conceptual
ms.localizationpriority: medium 
ms.prod: wpa
ms.collection: M365-analytics
manager: scott.ruble
audience: Admin
---

# Differential privacy

Microsoft Viva Insights is serious about protecting individual privacy. Privacy can always be guaranteed if no information is revealed, which is not very useful. Similarly, making all information available can lead to high-fidelity metrics that compromise individual privacy.

Differential privacy offers a balance between providing useful information and protecting individual privacy. Viva Insights uses methods from world-class researchers to apply differential privacy. By introducing slight variations to the data, it protects privacy while simultaneously maintaining accuracy. The methods are more sophisticated than this simple description, with numerous options toward balancing fidelity and privacy. For more details, see [Differential Privacy for Everyone](https://download.microsoft.com/download/D/1/F/D1F0DFF5-8BA9-4BDF-8924-7816932F6825/Differential_Privacy_for_Everyone.pdf).

The first application of differential privacy in Viva Insights is within [Manager and leader insights](../use/pm-home.md). These insights enable managers to understand how the people in their team are doing and to learn how to drive change by using aggregated collaboration data.

No matter how the metrics are presented or used in Viva Insights, no individual activity or metric can ever be discerned. The individual activity can never be established with certainty, and no manager or team-leader can conclude with confidence anything specific about any individual.

See [Differential privacy](https://www.microsoft.com/ai/ai-lab-differential-privacy) to learn more about how Microsoft AI is helping to define and use it.
