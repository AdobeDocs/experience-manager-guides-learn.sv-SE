---
title: Mappprofiler
description: Skapa och använda mappprofiler för AEM Guides
exl-id: 5a0daa68-51ae-42d0-8320-6e8bdb1fe545
source-git-commit: 67ba514616a0bf4449aeda035161d1caae0c3f50
workflow-type: tm+mt
source-wordcount: '914'
ht-degree: 0%

---

# Mappprofiler

AEM ger snabb åtkomst till konfigurationsverktygen. Genom att anpassa mappprofiler kan olika avdelningar eller produkter ha unika mallar, redigeringsmiljöer, villkorsstyrda attributprofiler, kodfragment eller till och med Web Editor-konfigurationer.

Exempelfiler som du kan välja att använda för den här lektionen finns i filen [folderprofiles.zip](assets/folderprofiles.zip).

>[!VIDEO](https://video.tv.adobe.com/v/342758?quality=12&learn=on)

## Åtkomst till mappprofiler

Konfigurationer hanteras med hjälp av ikonen Mappprofiler.

1. Klicka på ikonen [!UICONTROL **Verktyg**] på navigeringsskärmen.

   ![Verktygsikon](images/reuse/tools-icon.png)

1. Välj **Stödlinjer** på den vänstra panelen.

1. Klicka på panelen [!UICONTROL **Mappprofiler**].

   ![Mappprofiler](images/reuse/folder-profiles-tile.png)

1. Välj önskad profil. Välj till exempel **Global profil**, som är standardprofil.

   ![Global profil](images/lesson-3/global-profile-tile.png)

## Redigera villkorsattribut i den globala profilen

När du har öppnat den globala profilen kan du redigera dess konfiguration. Inställningarna för global profil tillämpas på alla användare om inget annat anges.

1. Välj fliken **Villkorliga attribut** i den globala profilen.

1. Klicka på [!UICONTROL **Redigera**] i skärmens övre vänstra hörn.

   ![Villkorliga attribut](images/lesson-3/edit-conditional-attributes.png)

1. Klicka på [!UICONTROL **Lägg till**].

1. Fyll i fälten **Namn**, **Värde** och **Etikett** för det nya villkoret.

   ![nytt villkor](images/lesson-3/new-condition.png)

1. Klicka på [!UICONTROL **Spara**] längst upp till vänster på skärmen.
Det nya villkoret är nu tillgängligt för alla användare. Du kan markera den på panelen Innehållsegenskaper och tillämpa den på innehåll efter behov.

## Skapa en ny mappprofil

Förutom den globala standardprofilen kan du skapa egna anpassade profiler.

1. Klicka på ikonen [!UICONTROL **Verktyg**] på navigeringsskärmen.

   ![Verktygsikon](images/reuse/tools-icon.png)

1. Välj **Stödlinjer** på den vänstra panelen.

1. Klicka på panelen [!UICONTROL **Mappprofiler**].

   ![Mappprofiler](images/reuse/folder-profiles-tile.png)

1. Klicka på [!UICONTROL **Skapa**].

1. I dialogrutan Skapa mappprofil.

   a. Namnge profilen.

   b. Ange en sökväg.

   c. Klicka på [!UICONTROL **Skapa**].

   ![Skapa mappprofil](images/lesson-3/create-folder-profile.png)

En ruta med det nya profilnamnet visas på sidan Mappprofiler.

## Lägga till administrativa användare från fliken Allmänt

Administrativa användare har behörighet att uppdatera villkorsattribut, redigeringsmallar och utdatainställningar för mappprofilen.

1. Klicka på rutan för att öppna den önskade mappprofilen.

   ![Redigera mappprofil](images/lesson-3/edit-folder-profile.png)

1. Välj fliken **Allmänt**.

1. Klicka på [!UICONTROL **Redigera**] längst upp till vänster på skärmen.

1. Under Administratörsanvändare väljer du en användare i listrutan eller skriver ett användarnamn.

1. Klicka på [!UICONTROL **Lägg till**].

   Du kan lägga till flera administratörsanvändare om det behövs.

   ![Lägg till administratör](images/lesson-3/add-admin.png)

1. Klicka på [!UICONTROL **Spara**] i skärmens övre högra hörn när alla användare har lagts till.

Administrativa användare har nu tilldelats den här profilen.

## Lägg till en ny målgrupp på fliken Villkorsattribut

När du har öppnat den globala profilen kan du redigera dess konfiguration. Inställningarna för global profil tillämpas på alla användare om inget annat anges.

1. Välj fliken **Villkorliga attribut** i den önskade mappprofilen.

1. Klicka på [!UICONTROL **Redigera**] i skärmens övre vänstra hörn.

   ![Redigera villkorsattribut ](images/lesson-3/edit-conditional-attributes-2.png)

1. Klicka på [!UICONTROL **Lägg till**].

1. Fyll i fälten **Namn**, **Värde** och **Etikett** för det nya villkoret.

   Om du klickar på plustecknet [!UICONTROL **Plus**] kan du lägga till ytterligare värde- och etikettpar för det namngivna attributet.

   ![Lägg till villkor](images/lesson-3/add-conditions.png)

1. Klicka på [!UICONTROL **Spara**] längst upp till vänster på skärmen.

De nya villkorsattributen har lagts till i den här profilen.

## Välj en mall och en karta på fliken Redigeringsmallar

AEM Guides innehåller färdiga mallar och kartor. Du kan begränsa dem till vissa författare. Som standard lagras mallarna på Assets-platsen i en DITA-mallmapp.

1. Välj fliken Redigeringsmallar i den önskade mappprofilen.

1. Klicka på Redigera i skärmens övre vänstra hörn.

1. Lägg till en kartmall.

   a. I listrutan **Kartmallar** väljer du ett alternativ från de tillgängliga kartorna.

   b. Klicka på [!UICONTROL **Lägg till**].

   ![Kartmallar](images/lesson-3/map-templates.png)

1. Lägg till en ämnesmall.

   a. I listrutan **Ämnesmallar** väljer du ett alternativ bland de tillgängliga mallarna.

   ![Ämnesmallar](images/lesson-3/topic-templates.png)

1. Klicka på [!UICONTROL **Lägg till**].

1. Lägg till ytterligare ämnesmallar efter behov.

1. När du är klar klickar du på [!UICONTROL **Spara**] längst upp till vänster på skärmen.

De nya redigeringsmallarna har lagts till i den här profilen.

## Ta bort förinställningar som inte är nödvändiga på fliken Utdatförinställningar

Du kan konfigurera varje förinställning för utdata baserat på mappprofilen. Utdatainställningar som inte behövs bör tas bort.

1. Gå till önskad mappprofil och välj fliken **Utdataförinställningar**.

1. Markera kryssrutorna för de förinställningar som inte är obligatoriska på den vänstra panelen.

   ![Ta bort förinställningar](images/lesson-3/delete-presets.png)

1. Klicka på [!UICONTROL **Ta bort förinställning**] i skärmens övre vänstra hörn.

1. Klicka på [!UICONTROL **Ta bort**] i dialogrutan Ta bort förinställning.

   ![Ta bort](images/lesson-3/delete.png)

Nu är de enda utdataförinställningarna som visas de som kommer att användas.

## Överföra ett fragment från fliken Konfiguration i XML-redigeraren

1. Välj fliken **XML-redigerarkonfiguration** i den önskade mappprofilen.

1. Klicka på [!UICONTROL **Överför**] under XML-redigeringsfragment.

   ![Överför fragment](images/lesson-3/upload-snippet.png)

1. Navigera till ett tidigare skapat kodfragment.

1. Klicka på [!UICONTROL **Öppna**].

1. Klicka på [!UICONTROL **Spara**] längst upp till vänster på skärmen.

Du har ändrat redigeringskonfigurationen så att den innehåller kodfragment.

## Ange mappprofilen i databasen

I redigeraren ser du resultatet av de ändringar du har gjort i mappprofilerna.

1. Navigera till **Databasvy**.

1. Klicka på mappen för det innehåll du vill arbeta med.

1. Klicka på ikonen [!UICONTROL **Användarinställningar**] i det övre verktygsfältet.

   ![Användarinställningar](images/lesson-3/hr-user-prefs.png)

1. Välj önskad mappprofil i listrutan i dialogrutan Användarinställningar.

   ![Välj användarinställningar](images/lesson-3/select-user-pref.png)

1. Klicka på [!UICONTROL **Spara**].

Du har använt mappprofilen på ditt innehåll. När du skapar ett nytt DITA-avsnitt visas nu en begränsad lista med ämnestyper som baseras på mappprofilen. Målgruppsvillkoret innehåller de globala inställningarna samt de som är specifika för mappprofilen. I fragmentfilen som du överförde skapades en uppsättning med standardfragment att välja bland. På kartkontrollpanelen visas de begränsade utdataförinställningarna.
