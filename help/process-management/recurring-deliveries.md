---
title: Come impostare campagne e-mail ricorrenti e continue
description: Scopri come impostare una consegna ricorrente e continua e comprendere le differenze tra i due approcci.
feature: Flussi di lavoro
kt: 7982
doc-type: feature video
activity: use
team: TM
role: Business Practitioner
level: Beginner
source-git-commit: 7609aa35dba225a05c8f5e3d3f75f4b6023772a0
workflow-type: tm+mt
source-wordcount: '239'
ht-degree: 6%

---


# Come impostare campagne e-mail ricorrenti e continue

Questa esercitazione spiega come impostare una consegna ricorrente e continua e le differenze tra i due approcci.

## Tracciamento continuo e ricorrente delle consegne {#recurring-and-continuous-delivery-tracking}

Le consegne ricorrenti e continue differiscono nel modo in cui vengono gestiti i dati di contatto:

* La **consegna continua** consente di aggiungere nuovi destinatari a una consegna esistente e di evitare di dover creare una consegna ogni volta che viene aggiunto un nuovo destinatario. Puoi aggiornare il contenuto creativo direttamente nel flusso di lavoro della campagna e il modello viene aggiornato nella cartella delle risorse del modello di consegna.

   Una consegna continua crea un singolo log di consegna e consegna (wideLog) e i log di tracciamento, che fanno riferimento a tale consegna, vengono aggiunti ogni volta che viene eseguito.

![Consegna continua](/help/assets/delivery_continuous.jpg)

* Una **consegna ricorrente** crea un&#39;istanza di consegna ogni volta che viene eseguita. Ad esempio, se il flusso di lavoro è pianificato per essere eseguito una volta alla settimana, si otterranno 52 consegne dopo un anno. Significa anche che i log ampi e i log di tracciamento sono separati per istanza di consegna.

![Consegna ricorrente](/help/assets/delivery_recurring.jpg)

## Come impostare una consegna ricorrente {#how-to-set-up-a-recurring-delivery}

Il video spiega come configurare una consegna ricorrente e un’attività di pianificazione.

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## Come impostare una consegna continua {#how-to-set-up-a-continuous-delivery}

Questo video mostra come configurare una consegna continua con una query incrementale.

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)