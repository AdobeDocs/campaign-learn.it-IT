---
title: Creare approvazioni e flussi di lavoro di convalida - Introduzione
description: Scopri come configurare diversi flussi di lavoro di convalida dell’approvazione.
feature: Workflows, Approvals
doc-type: feature video
activity: setup
team: TM
role: User
level: Experienced
exl-id: fa4c2180-15bb-424b-a54e-c7d744385fb6
source-git-commit: d4959c9a0559aca0ccaa02816690ed586aa5e201
workflow-type: ht
source-wordcount: '262'
ht-degree: 100%

---

# Creare approvazioni e flussi di lavoro di convalida - Introduzione

Adobe Campaign offre agli esperti di marketing diverse opzioni per rivedere e fornire il contenuto da recapitare, il target della campagna, l’estrazione dei dati e le approvazioni del budget. Scopri come [gestire le approvazioni](/help/process-management/create-approvals-and-validation-workflows/manage-approvals.md).

## Prerequisito {#prerequisite}

Prima di abilitare i passaggi di approvazione, il team di marketing deve definire i singoli revisori:

* Il ruolo di revisore Adobe Campaign all’interno di un’attività di approvazione può essere un singolo revisore (Operatore) o un gruppo di revisori (ruolo Operatore).
* Per consentire agli sviluppatori di campagne di selezionare i revisori come approvatori in una campagna o una consegna, i revisori e i gruppi di revisori devono essere configurati in Adobe Campaign da un amministratore.

## Configurazione delle approvazioni {#configuring-approvals}

1. [Configurare le approvazioni per le campagne ](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-campaigns.md):
Se hai impostato gli stessi revisori per tutte le consegne nel flusso di lavoro della campagna, puoi applicare la funzionalità di approvazione impostando approvazioni e revisori a livello di campagna. Quando il flusso di lavoro viene eseguito, le attività di approvazione e i revisori vengono applicati a ogni sua attività di consegna.
2. [Configurare le approvazioni per le consegne](/help/process-management/create-approvals-and-validation-workflows/configure-approvals-for-deliveries.md): 
Puoi anche impostare le approvazioni a livello di consegna. Se i passaggi di approvazione e i revisori di una consegna differiscono da quelli della campagna, le impostazioni specifiche della consegna hanno la precedenza rispetto a quelle della campagna.
3. [Creare un processo di approvazione in un flusso di lavoro](/help/process-management/create-approvals-and-validation-workflows/create-approval-process-in-a-workflow.md): 
L’attività di approvazione consente di creare un processo di approvazione all’interno di un flusso di lavoro. In questo modo, la logica di selezione del targeting può essere approvata prima dell’avvio della consegna stessa. Inoltre, se necessario, consente l’approvazione a più livelli all’interno del flusso di lavoro.

Per ulteriori informazioni, consulta la [documentazione](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html?lang=it).
