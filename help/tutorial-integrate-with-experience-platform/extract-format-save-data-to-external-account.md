---
title: 'Creare un flusso di lavoro di esportazione - Parte 2: Estrarre, formattare e salvare dati in un account esterno'
description: In questa seconda parte del tutorial Creare un flusso di lavoro di esportazione, imparerai a formattare i dati per l’esportazione e a salvarli in un account esterno.
feature: Data Import/Export, Workflows
kt: 8160
thumbnail: 336391.jpg
doc-type: feature video
activity: setup
team: TM
role: Admin
level: Beginner, Experienced
exl-id: ac29b75c-a838-4183-8ec5-034281290725
source-git-commit: b1b8d8a99a551239c445fb588cbd126b66a53c9b
workflow-type: ht
source-wordcount: '0'
ht-degree: 100%

---

# Creare un flusso di lavoro di esportazione (parte 2): Estrarre, formattare e salvare dati in un account esterno

In questa seconda parte del tutorial Creare un flusso di lavoro di esportazione, imparerai a formattare i dati per l’esportazione e a salvarli in un account esterno.

>[!VIDEO](https://video.tv.adobe.com/v/336391?quality=12&learn=on)

## Assets

JavaScript: Data di salvataggio

```java
 logInfo("=====================")
 logInfo("Starting Execution...")

 optionName = vars.OPTION_NAME;
 logInfo("optionName: " + optionName);
 logInfo("NEXT Run Date: " + vars.nextRunTime);
 
 //Make sure we have valid values before saving for next run
 if (vars.nextRunTime == null || optionName == null){

   logInfo("Unable to find non-null values for optionName/nextRunTime! Throwing Error.")
   throw new Error('Unable to find non-null values for optionName/nextRunTime!  Ending Execution.');

 } else {

   // Save the nextRunTime to the database to establish starting point for next run.
   setOption(optionName, vars.nextRunTime);
   logInfo("Date Saved. [" + optionName + "] = [" + vars.lastRunTime + "]")

 }

 logInfo("Finished Execution.") 
 logInfo("===================")
```
