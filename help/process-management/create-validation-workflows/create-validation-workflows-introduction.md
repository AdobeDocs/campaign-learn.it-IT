---
title: Creare flussi di lavoro di convalida - Introduzione
description: Scopri come configurare diversi flussi di lavoro di convalida dell’approvazione.
feature: Workflows, Approvals
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
source-git-commit: f25e3e7553d23aacf96c0f05e1ad78ee783192ff
workflow-type: tm+mt
source-wordcount: '260'
ht-degree: 66%

---

# Creare flussi di lavoro di convalida - Introduzione

Adobe Campaign offre agli esperti di marketing diverse opzioni per rivedere e fornire il contenuto da recapitare, il target della campagna, l’estrazione dei dati e le approvazioni del budget.

## Prerequisito {#prerequisite}

Prima di abilitare i passaggi di approvazione, il team di marketing deve definire i singoli revisori:

* Il ruolo di revisore Adobe Campaign all’interno di un’attività di approvazione può essere un singolo revisore (Operatore) o un gruppo di revisori (ruolo Operatore).
* Per consentire agli sviluppatori di campagne di selezionare i revisori come approvatori in una campagna o una consegna, i revisori e i gruppi di revisori devono essere configurati in Adobe Campaign da un amministratore.

## Configurazione delle approvazioni {#configuring-approvals}

Campaign offre tre diversi livelli di approvazione:

1. [Configurare le approvazioni per le campagne](/help/process-management/create-validation-workflows/configure-approvals-for-campaigns.md): Se disponi dello stesso set di revisori per tutte le consegne nel flusso di lavoro della campagna, applica la funzionalità di approvazione della campagna impostando approvazioni e revisori a livello di campagna. Quando il flusso di lavoro viene eseguito, le attività di approvazione e i revisori vengono applicati a ogni sua attività di consegna.
2. [Configurare le approvazioni per le consegne](/help/process-management/create-validation-workflows/configure-approvals-for-deliveries.md): Puoi anche impostare le approvazioni a livello di consegna. Se i passaggi di approvazione e i revisori di una consegna differiscono da quelli della campagna, le impostazioni specifiche della consegna hanno la precedenza rispetto a quelle della campagna.
3. [Creare un processo di approvazione in un flusso di lavoro](/help/process-management/create-validation-workflows/create-approval-process-in-a-workflow.md): L’attività di approvazione consente di creare un processo di approvazione all’interno di un flusso di lavoro. In questo modo, la logica di selezione del targeting può essere approvata prima dell’avvio della consegna stessa. Inoltre, se necessario, consente l’approvazione a più livelli all’interno del flusso di lavoro.

Per ulteriori informazioni, consulta la [documentazione](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=it).
