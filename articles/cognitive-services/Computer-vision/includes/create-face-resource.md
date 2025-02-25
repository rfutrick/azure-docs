---
title: Container support
titleSuffix: Azure Cognitive Services
services: cognitive-services
author: aahill
manager: nitinme
ms.service: cognitive-services
ms.topic: include 
ms.date: 7/5/2019
ms.author: aahi
---

## Create a Face resource

1. Sign into the [Azure portal](https://portal.azure.com)
1. Select [Create **Face**](https://portal.azure.com/#create/Microsoft.CognitiveServicesFace) resource
1. Enter all required settings:

    |Setting|Value|
    |--|--|
    |Name|Desired name (2-64 characters)|
    |Subscription|Select appropriate subscription|
    |Location|Select any nearby and available location|
    |Pricing Tier|`F0` - the minimal pricing tier|
    |Resource Group|Select an available resource group|

1. Select **Create** and wait for the resource to be created. After it's created, navigate to the resource page
1. Collect configured `endpoint` and an API key:

    |Resource Tab in Portal|Setting|Value|
    |--|--|--|
    |**Overview**|Endpoint|Copy the endpoint. It looks similar to `https://face.cognitiveservices.azure.com/face/v1.0`|
    |**Keys**|API Key|Copy one of the two keys. It's a 32 alphanumeric-character string with no spaces or dashes, `xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx`.|
