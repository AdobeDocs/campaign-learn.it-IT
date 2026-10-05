---
title: 'Guida introduttiva alle notifiche push per Android: introduzione'
description: Il presente tutorial illustra i passaggi necessari per l’invio di notifiche push da Adobe Campaign e la ricezione di tali notifiche all’interno dell’app Android™.
feature: Push
jira: KT-6438
doc-type: article
activity: setup
team: TM
role: Admin, Developer
level: Experienced
recommendations: noCatalog
exl-id: 91ff4bae-8598-4227-b4c9-4e436ce7400d
TQID: 'https://experienceleague.adobe.com/llhU9-u6ri1njd6wSTE1CTZTmYerQDz7-R2WY4ahWzs'
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
  - id: d0e9f0b2-1f2b-4134-9844-49cd4e950f27
    internal-label: Campaign v8
feature_v2:
  - id: a4671286-a59f-47e3-b97b-90627a1977d5
    internal-label: Communication channels
subfeature_v2:
  - id: a4657621-810c-498b-8a27-7ced9c176dda
    internal-label: Push notifications
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
  - id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
    internal-label: Developer
level_v2:
  - id: d378ca77-2da1-4f39-ad92-1917fe974a38
    internal-label: Experienced
topic_v2:
  - id: e0eb8757-182f-49f3-94a4-1587d16f5094
    internal-label: Personalization
source-git-commit: 369f9c3691b6326e521ebc9139aac1d2ee7c3ce2
workflow-type: tm+mt
source-wordcount: '331'
ht-degree: 100%
---
# Guida introduttiva alle notifiche push per Android: introduzione

Adobe Campaign ti consente di inviare notifiche [!DNL push] personalizzate e segmentate ai dispositivi mobili [!DNL iOS] e [!DNL Android™]. Questo tutorial illustra i passaggi necessari per inviare le notifiche [!DNL push] da Adobe Campaign a un’app [!DNL Android™].

## Prerequisiti

Prima di iniziare, è necessario disporre dei seguenti elementi:

1) **App mobile Android™**

   Questo tutorial non descrive i passaggi dettagliati necessari per configurare l’app mobile. È necessaria un’app mobile **[!DNL Android™]in cui è integrato [!DNL Campaign SDK]**.

   La descrizione dettagliata dei passaggi necessari è disponibile nella documentazione del prodotto:

   [Integrazione di Campaign SDK nell’app mobile](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=it)

2) Pacchetto **[!DNL Mobile App channel]installato**

   Il pacchetto [!DNL Mobile App channel] deve essere installato nell’istanza di [!DNL Campaign]. Il seguente video spiega come verificare se [!DNL Mobile App channel] è installato nell’istanza indicata e, in caso contrario, come installarlo.

>[!VIDEO](https://video.tv.adobe.com/v/340423?captions=ita&quality=12&learn=on){transcript=true}

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
