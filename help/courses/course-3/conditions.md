---
title: Villkor
description: Arbeta med villkor i AEM
exl-id: 2cb670d9-1a22-47c6-8409-52d1d526010a
source-git-commit: 67ba514616a0bf4449aeda035161d1caae0c3f50
workflow-type: tm+mt
source-wordcount: '497'
ht-degree: 0%

---

# Villkor

I DITA styrs villkoren ofta av attribut som Product, Platform och Audience. Dessa kan också ha specifika värden tilldelade. Användarna kan styra allt detta via Mappprofiler.

Exempelfiler som du kan välja att använda för den här lektionen finns i filen [conditions.zip](assets/conditions.zip).

>[!VIDEO](https://video.tv.adobe.com/v/342755?quality=12&learn=on)

## Tilldela villkor till en mappprofil

1. Markera rutan **Mappprofiler**.

1. Klicka på [!UICONTROL **Villkorliga attribut**].

1. Klicka på [!UICONTROL **Redigera**] i profilens övre vänstra hörn.

1. Klicka på [!UICONTROL **Lägg till**].

   ![Villkor i mappprofiler](images/lesson-13/add-name.png)

1. Fyll i obligatoriska fält.

   - Namnet ska motsvara ett attribut som används för profilering.

   - Värdet är den exakta posten som kommer att användas i DITA-kodkällan.

   - Etiketten är det ord som visas av användaren som anger attribut.

1. Klicka på [!UICONTROL **Spara**].

>[!NOTE]
>
>Obs! Att konfigurera en global profil kan vara ett tidigt och effektivt sätt att styra användningen av attribut och värden för att följa en konsekvent formatguide.

## Tilldela attribut till element

Om ingen anpassad mappprofil har tilldelats ett koncept kan du tilldela attribut till specifika element, t.ex. stycken.

1. I **databasvyn** klickar du på elementet som du vill arbeta med för att markera det.

1. Klicka på listrutan [!UICONTROL **Attribut**] i panelen **Innehållsegenskaper**.

1. Välj det attribut du vill tilldela.

1. Lägg till ett **värde**.

Kopplingen attribut och värde tilldelas nu till det valda elementet.

## Tilldela attribut- och värdepar med villkor

På villkorspanelen kan du styra tilldelningen av attribut- och värdepar.

1. Ändra **användarinställningarna**.

   a. Klicka på ikonen Användarinställningar.

   ![Ikon för användarinställningar](images/lesson-13/user-prefs-icon.png)

   b. Fyll i de obligatoriska fälten i dialogrutan **Användarinställningar**. Till exempel:

   ![Användarinställningar](images/lesson-13/user-preferences.png)

   c. Klicka på [!UICONTROL **Spara**].

1. Expandera listrutorna för Audience och Platform från villkorspanelen. Observera att de tillgängliga villkoren är mappprofilspecifika.

1. Dra och släpp ett villkor till önskat element för att tilldela det.

## Tilldela ett ämnesschema

Ämnesscheman är en specialiserad form av diamap och refereras av en karta. Ämnesscheman används för att definiera taxonomier. De ger kontroll över tillgängliga värden.

1. Navigera till **databasvyn**.

1. Välj en karta som refererar till objektschemat. I det här exemplet används kartan _Design och Layout_.

   ![Användarinställningar](images/lesson-13/subject-scheme-map.png)

1. Konfigurera användarinställningar.

   a. Klicka på ikonen [!UICONTROL **Användarinställningar**] .

   ![Användarinställningar](images/lesson-13/user-prefs-icon-2.png)

   b. Fyll i fälten i dialogrutan **Användarinställningar**.

   c. Klicka på mappsymbolen bredvid fältet Bassökväg för att välja sökvägen till önskad fil.

   d. Klicka på [!UICONTROL **Markera**].

   e. Klicka på nyckelsymbolen bredvid fältet **Rotschema** för att ange en sökväg.

   >[!IMPORTANT]
   >
   >Viktigt: Den markerade rotkartan måste vara den karta som innehåller ämnesschemat.

   ![Användarinställningar](images/lesson-13/user-preferences-2.png)

   f. Begränsa de visade resurserna genom att markera den eller de mappar som du vill använda.

   g. Klicka på [!UICONTROL **Markera**].

   h. Klicka på [!UICONTROL **Spara**].

Ämnesschemat har nu tilldelats.

## Visa ämnesschemat från villkorspanelen

1. Navigera till **Redigeringsinställningar**.

1. Välj fliken **Villkor**.

1. Markera rutan **Visa ämnesschema på panelen Villkor**
