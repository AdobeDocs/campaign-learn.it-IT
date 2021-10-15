---
title: 'Creare un flusso di lavoro di esportazione - Parte 1: Trovare la data dell’ultima modifica per un elenco di destinatari'
description: In questa prima parte dell’esercitazione Creare un flusso di lavoro di esportazione, scopri come creare un flusso di lavoro con cui trovare la data dell’ultima modifica per un elenco di destinatari creati da un segmento di Experience Platform.
feature: Data Import/Export, Workflows
kt: 8162
thumbnail: 336387.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
exl-id: 6fd70eea-3be7-4589-a608-05b0a8de93a6
source-git-commit: 85a32e0415c02ccfff9a22021ed77872ad726bf7
workflow-type: ht
source-wordcount: '120'
ht-degree: 100%

---

# Creare un flusso di lavoro di esportazione - Parte 1: Trovare la data dell’ultima modifica per un elenco di destinatari

In questa prima parte dell’esercitazione Creare un flusso di lavoro di esportazione, scopri come creare un flusso di lavoro con cui trovare la data dell’ultima modifica per un elenco di destinatari creati da un segmento di Experience Platform.

>[!VIDEO](https://video.tv.adobe.com/v/336387?quality=12)

## Assets

JavaScript per stabilire intervalli di date:

```java
 var DEFAULT_LOOKBACK_DAYS = 90;
 vars.OPTION_NAME = "BroadLog_CaptureTime";

 logInfo("=====================");
 logInfo("Starting Execution...");

 // Establish the last and next RunTimes
 var lastRunTime = getOption(vars.OPTION_NAME);
 var nextRunTime = getCurrentDate();

 //To reset and run through DEFAULT_LOOKBACK, uncomment the following line.
 //lastRunTime = null;

 logInfo("NEXT Run Date Set: [" + nextRunTime + "]");
 logInfo("LAST Run Date Retrieved (" + lastRunTime + ")");

 //Check for null so we can default the lastRunTime using the DEFAULT_LOOKBACK 
 if (lastRunTime == null || lastRunTime == "null" || lastRunTime == "") {

   logInfo("Empty Date Retrieved, setting to default lookback (-" + DEFAULT_LOOKBACK_DAYS + " days)");
   lastRunTime = new Date();
   lastRunTime.setDate(nextRunTime.getDate() - DEFAULT_LOOKBACK_DAYS);
   logInfo("LAST Run Date Set: [" + lastRunTime + "]");

 } 

 //Persist values through execution of this instance of the workflow.
 vars.lastRunTime = lastRunTime;
 vars.nextRunTime = nextRunTime;

 logInfo("Finished Execution.");
 logInfo("===================");
```

## Video successivo

[Creare un flusso di lavoro di esportazione - Parte 2: Estrarre, formattare e salvare dati in un account esterno](extract-format-save-data-to-external-account.md)
