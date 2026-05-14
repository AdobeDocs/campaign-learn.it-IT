---
title: Creare approvazioni e flussi di lavoro di convalida - Introduzione
description: Scopri come configurare diversi flussi di lavoro di convalida dell’approvazione.
feature: Workflows, Approvals
doc-type: feature video
activity: setup
team: TM
role: User
level: Intermediate
recommendations: noDisplay
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
TQID: https://experienceleague.adobe.com/nVZT-SWtytNyXrkbV-J7LWhR5-KHo601s0dE9yUiOaY
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
feature_v2:
  - id: a075b2c1-7748-4328-b7f6-343aa314616a
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
level_v2:
  - id: b5a62a22-46f7-4f0d-b151-3fc640bef588
source-git-commit: 1f6ccc9f0e59ce16a4e781d2d366cf0257b1c8aa
workflow-type: tm+mt
source-wordcount: 267
ht-degree: 89%

---

# Creare approvazioni e flussi di lavoro di convalida - Introduzione

Adobe Campaign offre agli esperti di marketing diverse opzioni per rivedere e fornire il contenuto da recapitare, il target della campagna, l’estrazione dei dati e le approvazioni del budget. Scopri come [gestire le approvazioni](/help/process-management/create-approvals-and-validation-workflows/manage-approvals.md).

## Prerequisito {#prerequisite}

Prima di abilitare i passaggi di approvazione, il team di marketing deve definire i singoli revisori:

* Il ruolo di revisore Adobe Campaign all’interno di un’attività di approvazione può essere un singolo revisore (Operatore) o un gruppo di revisori (ruolo Operatore).
* Per consentire agli sviluppatori di campagne di selezionare i revisori come approvatori in una campagna o una consegna, i revisori e i gruppi di revisori devono essere configurati in Adobe Campaign da un amministratore.

## Configurazione delle approvazioni {#configuring-approvals}

1. [Configurare le approvazioni per le campagne](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-campaigns.md):
Se uno stesso gruppo revisori si occupa di tutte le consegne nel flusso di lavoro della campagna, puoi applicare la funzionalità di approvazione impostando approvazioni e revisori a livello di campagna. Quando il flusso di lavoro viene eseguito, le attività di approvazione e i revisori vengono applicati a ogni sua attività di consegna.
2. [Configurare le approvazioni per le consegne](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-deliveries.md):
Puoi anche impostare le approvazioni a livello di consegna. Se i passaggi di approvazione e i revisori di una consegna differiscono da quelli della campagna, le impostazioni specifiche della consegna hanno la precedenza rispetto a quelle della campagna.
3. [Creare un processo di approvazione in un flusso di lavoro](/help/process-management/create-approvals-and-validation-workflows/create-approval-process-in-a-workflow.md):
L’attività di approvazione consente di creare un processo di approvazione all’interno di un flusso di lavoro. In questo modo, la logica di selezione del targeting può essere approvata prima dell’avvio della consegna stessa. Inoltre, se necessario, consente l’approvazione a più livelli all’interno del flusso di lavoro.

Per ulteriori informazioni, consulta la [documentazione](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=it).
