---
title: Tangenter
description: Med tangenter kan du inkludera variabelinformation i när du arbetar med DITA i AEM Guides
exl-id: cb64e094-fe6d-4a5e-8f0e-25ae58aaa2c6
source-git-commit: 67ba514616a0bf4449aeda035161d1caae0c3f50
workflow-type: tm+mt
source-wordcount: '585'
ht-degree: 0%

---

# Tangenter

Olika materialuppsättningar kan innehålla liknande information som behöver anpassas på vissa platser. Med tangenter kan du inkludera variabelinformation i när du arbetar med DITA.

Exempelfiler som du kan välja att använda för den här lektionen finns i filen [keys.zip](assets/keys.zip).

>[!VIDEO](https://video.tv.adobe.com/v/342756?quality=12&learn=on)

## Aktivera tangenter

1. Överför uppsättningen med exempelfiler.

   a. Läs in zip-filen.

   b. Uppdatera AEM.

   c. Välj den fil som ska extraheras.

   ![Välj postnummer](images/lesson-9/select-zip.png)

   d. Klicka på [!UICONTROL **Extrahera arkiv**] i det övre verktygsfältet.

   ![Verktygsfält](images/lesson-9/extract-archive.png)

   e. I dialogrutan väljer du den specifika platsen för filer som ska extraheras, till exempel en mapp som heter Tangenter.

   f. Klicka på [!UICONTROL **Nästa**].

   g. Hoppa över eventuella konflikter eftersom de inte finns för innehåll som aldrig har överförts tidigare.

   h. Välj [!UICONTROL **Extract**] längst upp till höger på skärmen.

1. När extraheringen är klar klickar du på [!UICONTROL **Gå till målmappen**].

   ![Bekräftelse](images/lesson-9/go-to-target.png)

## Lös nycklar till refererade värden

För att använda tangenter på rätt sätt måste användarinställningarna referera till en viss karta som rotkarta. I den här kartan finns en samling nycklar som grupperats tillsammans i en ämnesgrupp. När du öppnar kartan och avsnitten tolkas tangenterna till de värden som kartan refererar till.

1. Ange en rotkarta.

   a. Öppna en karta på tangentskärmen.

   b. Konfigurera användarinställningar.

   c. Klicka på ikonen [!UICONTROL **Användarinställningar**] i det övre verktygsfältet.

   ![Övre verktygsfält](images/lesson-9/author-view.png)

   d. Klicka på nyckelikonen för att ange en **rotkarta** som ska användas för att matcha nycklar.

   e. Markera kryssrutorna för eventuella Assets-filer.

   ![Assets-listruta](images/lesson-9/select-assets.png)

   f. Klicka på [!UICONTROL **Markera**].

   g. **Spara** användarinställningarna.

1. Navigera till **Kartvyn**.

1. Öppna den angivna kartan.

Tangenterna är lösta.

## Lägga till en ny nyckelruta manuellt

1. Öppna en karta med en angiven rotkarta.

1. Välj en tangent.

   ![Nyckellistruta](images/lesson-9/hybrid-key.png)

1. Infoga ett nytt nyckelord.

   a. Klicka på en giltig plats på kartan.

   b. Välj ikonen **Keydef** i det övre verktygsfältet.

   ![Verktygsfältet Nyckeldef](images/lesson-9/key-icon.png)

   c. Ange ett unikt värde för Tangenter som passar den definition du skapar i dialogrutan Infoga nyckelord.

   d. Klicka på [!UICONTROL **Infoga**].

1. Lägg till topicmeta i keydef.

   a. Klicka på ikonen [!UICONTROL **Infoga element**] i det övre verktygsfältet.

   ![Verktygsfältet Nyckeldef](images/lesson-9/add-icon.png)

   b. I dialogrutan Infoga element söker du efter och väljer &quot;topicmeta&quot;.

1. Lägg till nyckelord i ämnesmetan.

   a. Klicka på ikonen [!UICONTROL **Infoga element**] i det övre verktygsfältet.

   ![Verktygsfältet Nyckeldef](images/lesson-9/add-icon.png)

   b. Sök efter och välj nyckelord i dialogrutan Infoga element.

1. Lägg till ett nyckelord i ämnesmetan.

   a. Klicka på ikonen [!UICONTROL **Infoga element**] i det övre verktygsfältet.

   ![Verktygsfältet Nyckeldef](images/lesson-9/add-icon.png)

   b. Sök efter och välj nyckelord i dialogrutan **Infoga element**

1. Skriv värdet för nyckelordet i nyckelordet.

På kartan ska din nyckeldef nu se ut ungefär så här:

![Nyckelordet har slutförts](images/lesson-9/keydef.png)

## Konfigurera ett nyckelord som ett fragment

Kodavsnitt är små innehållsfragment som kan återanvändas i olika ämnen i dokumentationsprojektet. I stället för att generera varje nyckelord manuellt kan du konfigurera en enskild nyckeldef som ett fragment.

1. Markera ett nyckelelement på kartan.

1. Klicka på [!UICONTROL **Skapa fragment**] på snabbmenyn.

1. I dialogrutan Nytt kodfragment lägger du till en titel och en beskrivning.
Du kan också ta bort befintliga nycklar eller nyckelordsdefinitioner från innehållet.

1. Klicka på [!UICONTROL **Skapa**].

1. Välj **Kodavsnitt** på den vänstra panelen.

1. Dra och släpp det fragment du nyss skapade från fragmentpanelen på kartan.

1. Uppdatera nyckelordet efter behov med Content Properties.
När du sparar och uppdaterar den här uppsättningen nycklar är de tillgängliga för alla användare som har definierat en karta som innehåller samma rotkarta.
