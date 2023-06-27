---
title: Konfigurera anpassad ämnesmall för DITA
description: Lär dig hur du konfigurerar en anpassad ämnesmall för DITA
source-git-commit: 4f15166b1b250578f07e223b0260aacf402224be
workflow-type: tm+mt
source-wordcount: '354'
ht-degree: 0%

---


# Konfigurera anpassad ämnesmall för DITA {#id16A7G0O02TD}

AEM Guides innehåller följande ämnesmallar för DITA:

- Ämne

- Uppgift

- Koncept

- Referens

- Ordlista

- Felsökning

- Tom


Du kan använda någon av de här mallarna för att skapa ämnesmallar utifrån dina redigeringskrav. Den tomma DITA-mallen innehåller inga strukturer eller element som de andra mallarna. Du kan använda mallen Tom som bas om mallen är mycket anpassad och inte baseras på några vanliga ämnesmallar i DITA.

Om du vill anpassa en ämnesmall för DITA och använda den för redigering måste du utföra följande tre huvudåtgärder:

1. *\(Valfritt\)* [Konfigurera anpassad sökväg till DITA-mallmapp](#id191LCF0095Z)

1. [Skapa en anpassad redigeringsmall](conf-folder-level.md#id1917D0EG0HJ)

1. Lägg till en anpassad mall i den globala profilen eller mappnivåprofilen enligt anvisningarna i [Konfigurera redigeringsmallar](conf-folder-level.md#id1889D0IL0Y4) section


## Konfigurera anpassad sökväg till DITA-mallmapp {#id191LCF0095Z}

I AEM Guides kan du konfigurera en mapp för lagring av dina anpassade DITA-kartor och mallar. Som standard lagras mallfilerna i följande mapp i DAM:

`/content/dam/dita-templates/`

Om du vill hantera ämne- och mappningsmallfiler finns det dedikerade mappar för att lagra ämne- och mappmallar. Som standard lagras alla ämnesmallar under `/content/dam/dita-templates/topics`

mapp. Alla mappningsmallar lagras under `/content/dam/dita-templates/maps` mapp.

Som administratör kan du välja att skapa anpassade mappnings- eller ämnesmallar i standardmappen eller skapa en egen mapp där du kan lagra egna mallar. Om du tänker använda standardmappen kan du hoppa över den här processen.

Använd instruktionerna i [Konfigurationsåsidosättningar](download-install-additional-config-override.md#) för att skapa konfigurationsfilen. Ange följande \(egenskap\)-information i konfigurationsfilen för att konfigurera en mapp för dina anpassade DITA-ämnesmallar:

>[!IMPORTANT]
>
> Du kan hoppa över den här processen om du vill använda standardmappen för att lagra egna mallar.

| PID | Egenskapsnyckel | Egenskapsvärde |
|---|------------|--------------|
| `com.adobe.fmdita.config.ConfigManager` | `topic.templates` | Ange en plats där du vill lagra anpassade mallar.<br> Om den angivna platsen finns i DAM kopieras alla standardmallar för kartor och ämnen till den mappen. Om platsen inte finns skapas mappen med alla standardmallar för mappningar och ämnen. |

**Överordnat ämne:**[ Konfigurera ämne- och mappningsmallar](conf-template-tags.md)
