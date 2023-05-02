---
title: Använd etiketter
description: Lär dig hur du använder etiketter
source-git-commit: 331871308035441f047b1ed588215b586daf3d28
workflow-type: tm+mt
source-wordcount: '365'
ht-degree: 0%

---


# Använd etiketter {#id164JBG0M0T1}

Med AEM stödlinjer kan du lägga till etiketter i olika versioner av en fil. Du kan använda dessa etiketter för att ange vilken version du vill ta med i en baslinje för publicering. Mer information om hur du använder etiketter för att skapa en baslinje finns i [Arbeta med baslinje](generate-output-use-baseline-for-publishing.md#).

Om du till exempel vill använda *version 1.0* om ett ämne i *release 1.0* och *version 1.1* för samma ämne i *release 2.0* kan du lägga till *release 1.0* etikett på *version 1.0* och *release 2.0* etikett på *version 1.1*.

När du har lagt till etiketterna kan du skapa en baslinje och ange vilken version av ämnet som ska inkluderas för publicering med den baslinjen. Om du vill se vilken version som ska inkluderas eller exkluderas i en baslinje kan du använda alternativet Versionshistorik.

## Lägg till en etikett

Utför följande steg för att lägga till en etikett i ditt ämne:

1. Välj ett ämne i resursgränssnittet
1. Klicka på den vänstra ikonen för att välja rälsväljare och välj **Versionshistorik**.
1. Klicka på en version där du vill lägga till en etikett i Tidigare versioner.

1. Ange en etikett för den valda versionen och tryck på Retur. Till exempel: *2.6 Utgåva*.

   >[!NOTE]
   >
   > Du kan inte lägga till samma etikett till olika versioner av ett ämne. Du kan dock lägga till flera etiketter till samma version av ett ämne.

   Etiketterna visas i versionshistoriken för det valda ämnet. På följande skärmbild visas etiketterna *x.x-release* och *Användarhandbok* läggs till i den markerade versionen av ämnet.


![](images/labels.png)

>[!NOTE]
>
> Med hjälp av en baslinje kan du lägga till en etikett till flera ämnen. Mer information om hur du lägger till etiketter med baslinjen finns i [Lägga till etiketter i en baslinje](generate-output-use-baseline-for-publishing.md#id184KD0T305Z).

## Ta bort en etikett

Så här tar du bort en etikett:

1. I resursgränssnittet väljer du ett ämne som har en etikett tillagd.
1. Klicka på den vänstra ikonen för att välja rälsväljare och välj **Versionshistorik**.

   I versionshistoriken ser du alla versioner av ett ämne och tillhörande etiketter. Följande bild visar ett exempel på olika versioner av ett ämne och en version har etiketter tillagda.

   ![](images/labels.png)

1. Klicka på knappen Ta bort \(**X**\) om du vill ta bort etiketten.

   ![](images/delete-labels.png)


**Överordnat ämne:**[ Arbeta med webbredigeraren](web-editor.md)
