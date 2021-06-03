---
title: 'Guida introduttiva alle notifiche push per Android: introduzione'
description: Questo tutorial illustra i passaggi necessari per l’invio di notifiche push da Adobe Campaign e per la ricezione di tali notifiche nell’app Android™.
feature: Push
kt: 6438
doc-type: article
activity: setup
team: TM
role: Administrator, Developer
level: Experienced
source-git-commit: 39bed2fe5fbe19101a9684b29d73f61026ad77b2
workflow-type: tm+mt
source-wordcount: '318'
ht-degree: 41%

---

# Guida introduttiva alle notifiche push per Android: introduzione

Adobe Campaign ti consente di inviare notifiche [!DNL push] personalizzate e segmentate ai dispositivi mobili [!DNL iOS] e [!DNL Android™]. Questa esercitazione descrive i passaggi necessari per inviare notifiche [!DNL push] da Adobe Campaign a un&#39;app [!DNL Android™].

## Prerequisiti

Prima di iniziare, è necessario disporre dei seguenti elementi:

1) **Applicazione mobile Android™**

   Questo tutorial non descrive i passaggi dettagliati necessari per configurare l’applicazione mobile. È necessaria un&#39;applicazione mobile **[!DNL Android™]con [!DNL Campaign SDK] integrata**.

   La descrizione dettagliata dei passaggi necessari è disponibile nella documentazione del prodotto:

   [Integrazione dell’SDK Campaign nell’app mobile](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=it)

2) Pacchetto **[!DNL Mobile App channel]installato**

   Il pacchetto [!DNL Mobile App channel] deve essere installato nell&#39;istanza [!DNL Campaign]. Il seguente video spiega come verificare se [!DNL Mobile App channel] è installato nell’istanza indicata e, in caso contrario, come installarlo.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Panoramica del tutorial

L&#39;obiettivo è quello di inviare una notifica promozionale personalizzata [!DNL push] agli abbonati dell&#39; [!DNL Neotrip] [!DNL Android™] app mobile. L&#39;app [!DNL Neotrip] è configurata con [!DNL Campaign SDK] e il [!DNL Mobile App channel] viene attivato sull&#39;istanza [!DNL Campaign].

Sono necessari i seguenti passaggi di configurazione:

### Passaggio 1: estendere lo schema di iscrizione all’app per personalizzare le notifiche [!DNL push]

Per personalizzare la notifica [!DNL push], devi prima [estendere lo schema di sottoscrizione dell&#39;app](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md). Questo consente al sistema di memorizzare i valori di personalizzazione ricevuti dall’app quando l’utente si abbona al servizio.

### Passaggio 2: Configurare il servizio Android™ e creare l’app mobile in Campaign

Successivamente, [il servizio Android™ deve essere configurato e l&#39;applicazione mobile creata in Campaign](/help/tutorial-get-started-with-push-notifications-for-android/configure-an-android-service-in-campaign.md). In questo passaggio, l’ [!DNL Neotrip] app è definita come destinazione della notifica push.

### Passaggio 3: configurare e inviare la notifica push

Ora la notifica push è pronta per essere [configurata e inviata](/help/tutorial-get-started-with-push-notifications-for-android/configure-and-send-push-notifications.md).

## Inizia l’esercitazione

Passaggio 1: [estendere lo schema di iscrizione all’app](/help/tutorial-get-started-with-push-notifications-for-android/extend-the-app-subscription-schema.md)
