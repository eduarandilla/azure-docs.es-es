---
author: DCtheGeek
ms.service: azure-policy
ms.topic: include
ms.date: 07/10/2020
ms.author: dacoulte
ms.custom: generated
ms.openlocfilehash: 345cc8d5c1bc362973c8fae0e1c5605faf6e6e2d
ms.sourcegitcommit: 0b2367b4a9171cac4a706ae9f516e108e25db30c
ms.translationtype: HT
ms.contentlocale: es-ES
ms.lasthandoff: 07/11/2020
ms.locfileid: "86277361"
---
|Nombre<br /><sub>(Azure Portal)</sub> |Descripción |Efectos |Versión<br /><sub>(GitHub)</sub> |
|---|---|---|---|
|[Azure Backup debe estar habilitado para Virtual Machines.](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2Fproviders%2FMicrosoft.Authorization%2FpolicyDefinitions%2F013e242c-8828-4970-87b3-ab247555486d) |Esta directiva ayuda a auditar si el servicio Azure Backup está habilitado para todas las máquinas virtuales. Azure Backup es una solución rentable de copia de seguridad con un clic que simplifica la recuperación de datos y es más fácil de habilitar que otros servicios de copia de seguridad en la nube. |AuditIfNotExists, Disabled |[1.0.0](https://github.com/Azure/azure-policy/blob/master/built-in-policies/policyDefinitions/Backup/VirtualMachines_EnableAzureBackup_Audit.json) |
|[Configure copias de seguridad de las VM de una ubicación en un almacén central existente en la misma ubicación.](https://portal.azure.com/#blade/Microsoft_Azure_Policy/PolicyDetailBlade/definitionId/%2Fproviders%2FMicrosoft.Authorization%2FpolicyDefinitions%2F09ce66bc-1220-4153-8104-e3f51c936913) |Esta directiva configura la protección de Azure Backup en máquinas virtuales de una ubicación determinada en un almacén central existente en la misma ubicación. Solo se aplica a las máquinas virtuales que aún no están configuradas para la copia de seguridad. Se recomienda que esta directiva no se asigne a más de 200 máquinas virtuales. Si la directiva está asignada a más de 200 máquinas virtuales, puede ocurrir que la copia de seguridad se desencadene unas horas después de la programación definida. Esta directiva se mejorará para admitir más imágenes de máquina virtual. |deployIfNotExists, auditIfNotExists, disabled |[1.0.0](https://github.com/Azure/azure-policy/blob/master/built-in-policies/policyDefinitions/Backup/VirtualMachineBackup_Backup_DeployIfNotExists.json) |
