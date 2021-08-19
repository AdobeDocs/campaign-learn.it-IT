---
title: Risoluzione dei problemi del Pannello di controllo Campaign
description: Scopri come risolvere i problemi del Pannello di controllo Campaign
feature: Pannello di controllo Campaign
kt: 8520
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
source-git-commit: f8ed9264e592f4adf070a517049e3d36fc3112d5
workflow-type: tm+mt
source-wordcount: '340'
ht-degree: 19%

---

# Risoluzione dei problemi [!UICONTROL Pannello di controllo Campaign]

Scopri come risolvere i problemi del Pannello di controllo Campaign.

## Login e homepage

### Sintomo: Impossibile accedere all&#39;Experience Cloud

**Come procedere:**
l’utente deve individuare il proprio ID organizzazione IMS (xxx). L’amministratore deve aggiungere l’utente al profilo di prodotto &quot;Campaign-xxx-Admins&quot; per ogni istanza da gestire. Se l’utente è amministratore di tutte le istanze, deve aggiungere se stesso come utente.

### Sintomo: I collegamenti nella home dell&#39;Experience Cloud per accedere a [!UICONTROL Pannello di controllo Campaign] non vengono visualizzati per un utente

**Causa:**
gli utenti non visualizzano i collegamenti finché non vengono aggiunti come utenti al profilo di prodotto  _Campaign-xxx-Administrators/Admin_.

**Come procedere:**
l’amministratore deve aggiungere l’utente al profilo di prodotto  _Campaign-xxx-_  Adminsper ogni istanza da gestire. Se l’utente è amministratore di tutte le istanze, deve aggiungere se stesso come utente.

### Sintomo: Un&#39;istanza non è elencata nel [!UICONTROL Pannello di controllo Campaign]

**Causa:**
probabilmente l’utente deve essere aggiunto come  ** utenteProfilo di prodotto  _Campaign-xxx-Administrators/_ Adminper l’istanza mancante

**Come procedere:**
l’amministratore deve aggiungere l’utente al profilo di prodotto  _Campaign-xxx-_  Adminsper ogni istanza da gestire. Se l’utente è amministratore di tutte le istanze, deve aggiungersi come &quot;utenti&quot;.

### Video utili

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*Check IMS Org ID (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Come aggiungere un amministratore agli amministratori del profilo di prodotto per poter utilizzare il  [!UICONTROL Pannello di controllo Campaign]  (01:03 min)*

### Documentazione utile

* [Scoprire il Pannello di controllo Campaign](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=it)
* [Gestione delle autorizzazioni al  [!UICONTROL Pannello di controllo Campaign]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Stabilimento di una connessione al server SFTP (client o API)

La connessione ai server SFTP richiede:

* [!UICONTROL Consenti ] l’elenco dell’indirizzo IP da cui ti connetti al server SFTP
* Coppia di chiavi privata/pubblica che deve essere registrata con Adobe Campaign
* Per connettersi direttamente al server SFTP, è necessario anche il software client SFTP

### Documentazione utile {#helpful-docs}

* [Accesso al server SFTP](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
