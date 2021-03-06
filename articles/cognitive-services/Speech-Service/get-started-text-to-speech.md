---
title: 'Inicio rápido de la síntesis de voz: servicio de voz'
titleSuffix: Azure Cognitive Services
description: Aprenda a usar el SDK de voz para convertir texto a voz. En este inicio rápido, obtendrá información sobre la construcción de objetos y los patrones de diseño, los formatos de salida de audio admitidos, la CLI de voz y las opciones de configuración personalizadas de la síntesis de voz.
services: cognitive-services
author: trevorbye
manager: nitinme
ms.service: cognitive-services
ms.subservice: speech-service
ms.topic: quickstart
ms.date: 08/11/2020
ms.author: trbye
ms.custom: devx-track-python, devx-track-javascript
zone_pivot_groups: speech-full-stack
ms.openlocfilehash: e66da95bea0b03ddad1096b2b19751f73aaacbe0
ms.sourcegitcommit: c28fc1ec7d90f7e8b2e8775f5a250dd14a1622a6
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 08/13/2020
ms.locfileid: "88170169"
---
# <a name="get-started-with-speech-synthesis"></a>Introducción a la síntesis de voz

En este inicio rápido aprenderá patrones de diseño comunes para realizar la síntesis de texto a voz mediante el SDK de voz. Para empezar, puede realizar una configuración y síntesis básicas y, después, pasar a ejemplos más avanzados para el desarrollo de aplicaciones personalizadas, entre las que se incluyen:

* Obtención de respuestas como flujos de datos en memoria
* Personalización de la frecuencia de muestreo y la velocidad de bits de salida
* Envío de solicitudes de síntesis mediante SSML (lenguaje de marcado de síntesis de voz)
* Uso de voces neuronales

> [!TIP]
> Si quiere pasar directamente al código de ejemplo, consulte los [ejemplos del inicio rápido](https://github.com/Azure-Samples/cognitive-services-speech-sdk/tree/master/quickstart) en GitHub.

::: zone pivot="programming-language-csharp"
[!INCLUDE [C# Basics include](includes/how-to/text-to-speech-basics/text-to-speech-basics-csharp.md)]
::: zone-end

::: zone pivot="programming-language-cpp"
[!INCLUDE [C++ Basics include](includes/how-to/text-to-speech-basics/text-to-speech-basics-cpp.md)]
::: zone-end

::: zone pivot="programming-language-java"
[!INCLUDE [Java Basics include](includes/how-to/text-to-speech-basics/text-to-speech-basics-java.md)]
::: zone-end

::: zone pivot="programming-language-javascript"
[!INCLUDE [JavaScript Basics include](includes/how-to/text-to-speech-basics/text-to-speech-basics-javascript.md)]
::: zone-end

::: zone pivot="programming-language-python"
[!INCLUDE [Python Basics include](includes/how-to/text-to-speech-basics/text-to-speech-basics-python.md)]
::: zone-end

::: zone pivot="programming-language-spx"
[!INCLUDE [CLI include](includes/how-to/text-to-speech-basics/text-to-speech-basics-cli.md)]
::: zone-end

## <a name="next-steps"></a>Pasos siguientes

* [Introducción a Voz personalizada](how-to-custom-voice.md)
* [Mejora de síntesis con SSML](speech-synthesis-markup.md)
* Aprenda a usar [Long Audio API](long-audio-api.md) para ejemplos con mucho texto, como libros y artículos de prensa
* Consulte los [ejemplos del inicio rápido](https://github.com/Azure-Samples/cognitive-services-speech-sdk/tree/master/quickstart) en GitHub
