---
title: Creare flussi di lavoro di convalida
description: Scopri come configurare diversi flussi di lavoro di convalida dell’approvazione.
feature: Workflows, Approvals
kt: 7991
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
source-git-commit: 02a6238163a7c8f887236e03b78673c57c836a45
workflow-type: tm+mt
source-wordcount: '263'
ht-degree: 100%

---

# Creare flussi di lavoro di convalida

Adobe Campaign offre agli esperti di marketing diverse opzioni per rivedere e fornire il contenuto da recapitare, il target della campagna, l’estrazione dei dati e le approvazioni del budget.

Questo tutorial spiega come configurare diversi flussi di lavoro per la convalida dell’approvazione.

## Prerequisito {#prerequisite}

Prima di abilitare i passaggi di approvazione, il team di marketing deve definire i singoli revisori:

* Il ruolo di revisore Adobe Campaign all’interno di un’attività di approvazione può essere un singolo revisore (Operatore) o un gruppo di revisori (ruolo Operatore).
* Per consentire agli sviluppatori di campagne di selezionare i revisori come approvatori in una campagna o una consegna, i revisori e i gruppi di revisori devono essere configurati in Adobe Campaign da un amministratore.

## Configurazione delle approvazioni per le campagne  {#configuring-approvals-for-campaigns}

Se uno stesso gruppo revisori si occupa di tutte le consegne nel flusso di lavoro della campagna, puoi applicare la funzionalità di approvazione impostando approvazioni e revisori a livello di campagna. Quando il flusso di lavoro viene eseguito, le attività di approvazione e i revisori vengono applicati a ogni sua attività di consegna.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Configurazione delle approvazioni per le consegne  {#configuring-approvals-for-deliveries}

Puoi anche impostare le approvazioni a livello di consegna. Se i passaggi di approvazione e i revisori di una consegna differiscono da quelli della campagna, le impostazioni specifiche della consegna hanno la precedenza rispetto a quelle della campagna.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Configurazione di un’attività di approvazione  {#configuring-an-approval-activity}

A differenza delle approvazioni per consegne o campagne, l’attività di approvazione consente di creare un processo di approvazione all’interno di un flusso di lavoro. In questo modo, la logica di selezione del targeting può essere approvata prima dell’avvio della consegna stessa. Inoltre, se necessario, consente l’approvazione a più livelli all’interno del flusso di lavoro.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

Per ulteriori informazioni, consulta la [documentazione sulle approvazioni](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=it)
