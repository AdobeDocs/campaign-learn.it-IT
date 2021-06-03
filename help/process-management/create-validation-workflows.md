---
title: Creazione di flussi di lavoro di convalida
description: Scopri come configurare diversi flussi di lavoro di convalida dell’approvazione.
feature: Flussi di lavoro, approvazioni
kt: 7991
doc-type: feature video
activity: setup
team: TM
role: Business Practitioner
level: Experienced
source-git-commit: f6bb16306773a4b6ff7aa390a514e9b31fe047d6
workflow-type: tm+mt
source-wordcount: '265'
ht-degree: 0%

---


# Creazione di flussi di lavoro di convalida

Adobe Campaign offre diverse opzioni agli esperti di marketing per rivedere e fornire il contenuto di consegna, il target della campagna, l’estrazione dei dati e le approvazioni del budget.

Questa esercitazione spiega come configurare diversi flussi di lavoro di convalida dell&#39;approvazione.

## Prerequisito {#prerequisite}

Prima di abilitare i passaggi di approvazione, il team marketing deve definire i singoli revisori:

* Il ruolo di revisore Adobe Campaign all&#39;interno di un&#39;attività di approvazione può essere un singolo revisore (Operatore) o un gruppo di revisori (ruolo Operatore).
* Per consentire agli sviluppatori di campagne di selezionare i revisori come approvatori in una campagna o una consegna, i revisori e i gruppi di revisori devono essere configurati in Adobe Campaign da un amministratore.

## Configurazione delle approvazioni per le campagne {#configuring-approvals-for-campaigns}

Se disponi dello stesso set di revisori per tutte le consegne nel flusso di lavoro della campagna, applica la funzionalità di approvazione della campagna impostando approvazioni e revisori a livello di campagna. Le attività di approvazione e i revisori vengono inviati a ogni attività di consegna del flusso di lavoro una volta eseguito il flusso di lavoro.

>[!VIDEO](https://video.tv.adobe.com/v/25175?quality=12)

## Configurazione delle approvazioni per le consegne {#configuring-approvals-for-deliveries}

Puoi anche impostare le approvazioni a livello di consegna. Se i passaggi di approvazione della consegna e i revisori differiscono dai passaggi di approvazione della campagna e dai revisori, le impostazioni di consegna sovrascrivono le impostazioni della campagna.

>[!VIDEO](https://video.tv.adobe.com/v/25176?quality=12)

## Configurazione di un’attività di approvazione {#configuring-an-approval-activity}

A differenza delle approvazioni di consegna o campagna, l’attività di approvazione consente di creare un processo di approvazione all’interno di un flusso di lavoro. In questo modo, la logica di selezione del targeting può essere approvata prima dell’avvio della consegna. Inoltre, consente l’approvazione a più livelli all’interno del flusso di lavoro, se necessario.

>[!VIDEO](https://video.tv.adobe.com/v/25174?quality=12)

Per ulteriori informazioni, consulta la [documentazione di approvazione](https://experienceleague.adobe.com/docs/campaign-classic/using/automating-with-workflows/flow-control-activities/approval.html)
