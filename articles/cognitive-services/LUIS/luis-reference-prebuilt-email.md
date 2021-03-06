---
title: Referencia de correo electrónico de entidades precompiladas de LUIS
titleSuffix: Azure Cognitive Services
description: Este artículo contiene información acerca de la entidad precompilada de correo electrónico en Language Understanding (LUIS).
services: cognitive-services
author: diberry
manager: nitinme
ms.custom: seodec18
ms.service: cognitive-services
ms.subservice: language-understanding
ms.topic: reference
ms.date: 09/27/2019
ms.author: diberry
ms.openlocfilehash: f7aa2a341a82d30f7022af49e626a3cd358854b7
ms.sourcegitcommit: 2ec4b3d0bad7dc0071400c2a2264399e4fe34897
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 03/28/2020
ms.locfileid: "78273480"
---
# <a name="email-prebuilt-entity-for-a-luis-app"></a>Entidad precompilada Email para una aplicación de LUIS
La extracción de correo electrónico incluye la dirección de correo electrónico completa de un mensaje. Dado que esta entidad ya está entrenada, no se necesita agregar expresiones de ejemplo que contengan el correo electrónico en las intenciones de la aplicación. La entidad de correo electrónico se admite solamente en la referencia cultural `en-us`.

## <a name="resolution-for-prebuilt-email"></a>Resolución del correo electrónico precompilado

La consulta devuelve los siguientes objetos de entidad:

`please send the information to patti@contoso.com`

#### <a name="v3-response"></a>[Respuesta de V3](#tab/V3)

El siguiente JSON es con el parámetro `verbose` establecido en `false`:

```json
"entities": {
    "email": [
        "patti@contoso.com"
    ]
}
```
#### <a name="v3-verbose-response"></a>[Respuesta detallada de V3](#tab/V3-verbose)

El siguiente JSON es con el parámetro `verbose` establecido en `true`:

```json
"entities": {
    "email": [
        "patti@contoso.com"
    ],
    "$instance": {
        "email": [
            {
                "type": "builtin.email",
                "text": "patti@contoso.com",
                "startIndex": 31,
                "length": 17,
                "modelTypeId": 2,
                "modelType": "Prebuilt Entity Extractor",
                "recognitionSources": [
                    "model"
                ]
            }
        ]
    }
}
```
#### <a name="v2-response"></a>[Respuesta de V2](#tab/V2)

En el siguiente ejemplo, se muestra la resolución de la entidad **builtin.email**.

```json
"entities": [
    {
        "entity": "patti@contoso.com",
        "type": "builtin.email",
        "startIndex": 31,
        "endIndex": 55,
        "resolution": {
        "value": "patti@contoso.com"
        }
    }
]
```
* * *

## <a name="next-steps"></a>Pasos siguientes

Más información acerca del [punto de conexión de predicción de V3](luis-migration-api-v3.md).

Obtenga información acerca de las entidades de [número](luis-reference-prebuilt-number.md), [ordinal](luis-reference-prebuilt-ordinal.md) y [porcentaje](luis-reference-prebuilt-percentage.md).
