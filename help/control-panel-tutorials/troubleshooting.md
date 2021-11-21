---
title: Risoluzione dei problemi del Pannello di controllo Campaign
description: Scopri come risolvere i problemi del Pannello di controllo Campaign
feature: Control Panel
kt: 8520
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 0dca4676-2d5e-411b-9fdf-fbfd1081cb0e
source-git-commit: f7cb6c57d9cd6b00def9f0a4ccbcc94267f0d593
workflow-type: tm+mt
source-wordcount: '338'
ht-degree: 100%

---

# Risoluzione dei problemi del [!UICONTROL Pannello di controllo Campaign]

Scopri come risolvere i problemi del Pannello di controllo Campaign.

## Login e homepage

### Sintomo: impossibile accedere a Experience Cloud

**Come procedere:**
L’utente deve individuare il proprio ID organizzazione IMS (xxx). L’amministratore deve aggiungere l’utente al profilo di prodotto “Campaign-xxx-Admins” per ogni istanza che desidera gestire. Se l’utente è amministratore di tutte le istanze, deve comunque aggiungere se stesso come utente.

### Sintomo: i collegamenti nella home di Experience Cloud per accedere al [!UICONTROL Pannello di controllo Campaign] non vengono visualizzati per un utente

**Causa:**
Gli utenti non visualizzano i collegamenti finché non vengono aggiunti come utenti al profilo di prodotto _Campaign-xxx-Administrators/Admin_.

**Come procedere:**
L’amministratore deve aggiungere l’utente al profilo di prodotto _Campaign-xxx-Admins_ per ogni istanza che desidera gestire. Se l’utente è amministratore di tutte le istanze, deve comunque aggiungere se stesso come utente.

### Sintomo: un’istanza non è elencata nel [!UICONTROL Pannello di controllo Campaign]

**Causa:**
Probabilmente l’utente deve essere aggiunto come *utente* al Profilo di prodotto _Campaign-xxx-Administrators/Admin_ per l’istanza mancante

**Come procedere:**
L’amministratore deve aggiungere l’utente al profilo di prodotto _Campaign-xxx-Admins_ per ogni istanza che desidera gestire. Se l’utente è amministratore di tutte le istanze, deve comunque aggiungere se stesso come “utente”.

### Video utili

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Verificare Org ID IMS (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Come aggiungere un amministratore al profilo di prodotto in modo che possa utilizzare il [!UICONTROL Pannello di controllo Campaign] (01:03 min)*

### Documentazione utile

* [Scoprire il Pannello di controllo Campaign](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=it)
* [Gestione delle autorizzazioni di accesso al [!UICONTROL Pannello di controllo Campaign]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Stabilimento di una connessione al server SFTP (client o API)

La connessione ai server SFTP richiede:

* Aggiungere all’[!UICONTROL elenco Consentiti] l’indirizzo IP per la connessione al server SFTP
* Una coppia di chiavi privata/pubblica che deve essere registrata con Adobe Campaign
* Per connetterti direttamente al server SFTP, devi usare anche un software client SFTP.

### Documentazione utile {#helpful-docs}

* [Accesso al server SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
