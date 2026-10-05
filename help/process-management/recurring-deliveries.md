---
title: Creare consegne e-mail ricorrenti e continuative
description: Scopri come impostare una consegna ricorrente e continua e le differenze tra i due approcci.
feature: Workflows
jira: KT-7982
thumbnail: 342637.jpg
doc-type: feature video
activity: use
team: TM
role: User
level: Intermediate
exl-id: 469aecd7-4774-42c6-b07f-82792dfdc9c2
TQID: 'https://experienceleague.adobe.com/pdYTRO3rBq3BdS-WUGcx3POKjD6V4lH1dco4W9L6FwM'
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
  - id: d0e9f0b2-1f2b-4134-9844-49cd4e950f27
    internal-label: Campaign v8
feature_v2:
  - id: a658c786-869b-4194-a780-2594d663adda
    internal-label: Data management
subfeature_v2:
  - id: fcb46c0f-76e1-48bc-9dd0-fcf9d97526cf
    internal-label: Workflows
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
    internal-label: Intermediate
source-git-commit: 369f9c3691b6326e521ebc9139aac1d2ee7c3ce2
workflow-type: tm+mt
source-wordcount: '233'
ht-degree: 100%
---
# Creare consegne e-mail ricorrenti e continuative

Questo tutorial spiega come impostare una consegna ricorrente e continua, e le differenze tra i due approcci.

## Tracciamento continuo e ricorrente delle consegne {#recurring-and-continuous-delivery-tracking}

Le consegne ricorrenti e continue differiscono nel modo in cui vengono gestiti i dati di contatto:

* La **consegna continua** consente di aggiungere nuovi destinatari a una consegna esistente ed evita di dover crearne una nuova ogni volta che viene aggiunto un destinatario. Puoi aggiornare il contenuto creativo direttamente nel flusso di lavoro della campagna, e il modello viene aggiornato nella cartella delle risorse del modello di consegna.

  Una consegna continua crea una SINGOLA consegna e relativi registri di consegna (broadLog); a ogni esecuzione vengono aggiunti i registri di tracciamento che fanno riferimento a tale consegna.

![Consegna continua](/help/assets/delivery_continuous.jpg)

* Una **consegna ricorrente** crea un’istanza di consegna ogni volta che viene eseguita. Ad esempio, se il flusso di lavoro è pianificato per essere eseguito una volta alla settimana, in un anno si otterranno 52 consegne. Significa anche che i log ampi e quelli di tracciamento sono separati per istanza di consegna.

![Consegna ricorrente](/help/assets/delivery_recurring.jpg)

## Come impostare una consegna ricorrente {#how-to-set-up-a-recurring-delivery}

Il video spiega come configurare una consegna ricorrente e un’attività di pianificazione.

>[!VIDEO](https://video.tv.adobe.com/v/342638?quality=12&learn=on){transcript=true}

## Come impostare una consegna continua {#how-to-set-up-a-continuous-delivery}

Questo video mostra come configurare una consegna continua con una query incrementale.

>[!VIDEO](https://video.tv.adobe.com/v/342637?quality=12&learn=on){transcript=true}
