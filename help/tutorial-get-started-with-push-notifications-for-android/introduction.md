---
title: 'Guida introduttiva alle notifiche push per Android: introduzione'
description: Il presente tutorial illustra i passaggi necessari per l’invio di notifiche push da Adobe Campaign e la ricezione di tali notifiche all’interno dell’app Android™.
feature: Push
kt: 6438
doc-type: article
activity: setup
team: TM
role: Admin, Developer
level: Experienced
exl-id: 91ff4bae-8598-4227-b4c9-4e436ce7400d
source-git-commit: 02a6238163a7c8f887236e03b78673c57c836a45
workflow-type: tm+mt
source-wordcount: '318'
ht-degree: 100%

---

# Guida introduttiva alle notifiche push per Android: introduzione

Adobe Campaign ti consente di inviare notifiche [!DNL push] personalizzate e segmentate ai dispositivi mobili [!DNL iOS] e [!DNL Android™]. Questo tutorial illustra i passaggi necessari per inviare le notifiche [!DNL push] da Adobe Campaign a un’app [!DNL Android™].

## Prerequisiti

Prima di iniziare, è necessario disporre dei seguenti elementi:

1) **App mobile Android™**

   Questo tutorial non descrive i passaggi dettagliati necessari per configurare l’app mobile. È necessaria un’app mobile **[!DNL Android™]in cui è integrato [!DNL Campaign SDK]**.

   La descrizione dettagliata dei passaggi necessari è disponibile nella documentazione del prodotto:

   [Integrazione dell’SDK Campaign nell’app mobile](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=it)

2) Pacchetto **[!DNL Mobile App channel]installato**

   Il pacchetto [!DNL Mobile App channel] deve essere installato nell’istanza di [!DNL Campaign]. Il seguente video spiega come verificare se [!DNL Mobile App channel] è installato nell’istanza indicata e, in caso contrario, come installarlo.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Panoramica del tutorial

L’obiettivo è quello di inviare una notifica [!DNL push] promozionale personalizzata agli abbonati dell’app mobile [!DNL Neotrip] per [!DNL Android™]. L’app [!DNL Neotrip] è configurata con [!DNL Campaign SDK] e [!DNL Mobile App channel] attivato sull’istanza di [!DNL Campaign].

Sono necessari i seguenti passaggi di configurazione:

### Passaggio 1: estendere lo schema di iscrizione all’app per personalizzare le notifiche [!DNL push]

Per personalizzare la notifica [!DNL push], devi prima [estendere lo schema di abbonamento dell’app](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md). Questo consente al sistema di memorizzare i valori di personalizzazione ricevuti dall’app quando l’utente si abbona al servizio.

### Passaggio 2: configurare il servizio Android™ e creare l’app mobile in Campaign

Successivamente, devi [configurare il servizio Android™ e creare l’app mobile in Campaign](/help/tutorial-get-started-with-push-notifications-for-android/configure-an-android-service-in-campaign.md). In questo passaggio, l’app [!DNL Neotrip] viene definita come destinazione della notifica push.

### Passaggio 3: configurare e inviare la notifica push

Ora la notifica push è pronta per essere [configurata e inviata](/help/tutorial-get-started-with-push-notifications-for-android/configure-and-send-push-notifications.md).

## Inizia l’esercitazione

Passaggio 1: [estendere lo schema di iscrizione all’app](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)
