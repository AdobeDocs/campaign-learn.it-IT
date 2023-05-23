---
title: Creare consegne e-mail ricorrenti e continuative
description: Scopri come impostare una consegna ricorrente e continua e le differenze tra i due approcci.
feature: Workflows
kt: 7982
thumbnail: 342637.jpg
doc-type: feature video
activity: use
team: TM
role: User
level: Beginner
exl-id: 469aecd7-4774-42c6-b07f-82792dfdc9c2
source-git-commit: b1b8d8a99a551239c445fb588cbd126b66a53c9b
workflow-type: tm+mt
source-wordcount: '232'
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

>[!VIDEO](https://video.tv.adobe.com/v/342638?quality=12&learn=on)

## Come impostare una consegna continua {#how-to-set-up-a-continuous-delivery}

Questo video mostra come configurare una consegna continua con una query incrementale.

>[!VIDEO](https://video.tv.adobe.com/v/342637?quality=12&learn=on)
