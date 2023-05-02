---
title: Adressgranskningskommentarer
description: Lär dig hur du hanterar granskningskommentarer
source-git-commit: 7cd719921e68ac1763d09d9665d912e3697e5849
workflow-type: tm+mt
source-wordcount: '935'
ht-degree: 0%

---


# Adressgranskningskommentarer {#id2056B0X0KBI}

Som författare kan du adressera kommentarer i ett ämne med hjälp av webbredigeraren. I följande avsnitt beskrivs hur du redigerar kommentarer i Web Editor.

En författare kan adressera kommentarer i ett dokument från Web Editor. Visuella indikatorer visas som anger om kommentarer som infogats, tagits bort eller markerats. Även kommentarstypen anges längst upp i varje kommentarspost.

>[!NOTE]
>
> När du adresserar granskningskommentarer \(för ett aktivt granskningsdokument\) ska du se till att du inte öppnar ämnet i granskningen på flera flikar med full taggvy aktiverat, inte växla mellan redigeringsläget och källvyn.

![](images/comments-page-web-editor_cs.png)

I webbredigeringsläget innehåller den högra panelen ikonerna Granska och Spårade ändringar. Granskningspanelen visar alla kommentarer som granskarna har gjort i dokumentet. På panelen Spårade ändringar visas status för alla infogade och borttagna kommentarer i dokumentet.

- **A**: Välj ett granskningsprojekt om du vill se granskningskommentarerna. Om ditt ämne har delats för granskning i flera granskningsåtgärder visas de uppgifter som listas i den här listrutan.

   När du väljer en granskningsuppgift i listan kan du se kommentarer som gjorts av granskarna i den uppgiften. Du kan adressera granskningskommentarerna separat i uppgifter, vilket innebär att alla uppdateringar av en kommentar bara är synliga för granskarna av den aktuella uppgiften.

- **B:** Varje **Granska projekt** skapas på en viss version av dokumentet. The **Granskningsversion** visar den version som är associerad med det valda granskningsprojektet. På så sätt kan du hålla reda på vilken version du har delat för granskning.

- **C**: Om du har uppdaterat ämnet efter att du har startat granskningen återgår arbetskopian till den version som delats för granskning genom att klicka på ikonen Återställ ämne till granskningsversion. Det gör det enklare för dig att lägga in granskningsfeedback direkt i den version som delats för granskning. När du har tagit med feedback kan du spara ändringarna i den återskapade versionen eller skapa en ny version av ämnet. Om du väljer att skapa en ny revision av ditt ämne skapas en ny gren av den ämnesversion som delats för granskning. Om du till exempel har delat en version `1.2` för ett ämne som ska granskas medan den aktuella redigeringsversionen är `1.3`kan du använda den här ikonen för att växla tillbaka till version `1.2` för att lägga in granskningskommentarer. Om du väljer att skapa en ny revision efter att ha infogat ändringar i versionen `1.2`, sedan en ny gren med version `1.2.0` skapas för ämnet.

   När du har infogat feedback på en granskning vill du vanligtvis sammanfoga ändringar från den senaste versionen av avsnittet. Om du vill göra det använder du [Sammanfoga](web-editor-features.md#id205DF04E0HS) för att få alla uppdateringar som gjorts efter att ämnet delats för granskning.

- **D**: Öppna sida vid sida-vyn för att visa den kommenterade versionen av ämnet. Som du ser på skärmbilden ovan är avsnittet längst till vänster den senaste versionen av ämnet där du kan göra ändringar. Nästa avsnitt är den kommenterade versionen av ämnet. När du navigerar mellan kommentarer i ämnet ändras sidvyn och den versionen av ämnet som kommentaren gjordes om visas. Alla kommentarer på kommentarpanelen är länkade till motsvarande text i det här avsnittet. Den hjälper dig att identifiera kommenterad text. Kommentarerna visas i den ordning som de kommenteras i dokumentet.

   Versionsnumret visas högst upp i sidvyn. Om du klickar på den här ikonen igen döljs den kommenterade versionen av ämnet.

- E: Importera infogade och borttagna \(eller Genomstruken\) kommentarer direkt i ämnet. När du har klickat på ikonen Importera visas alla textinmatningar och -borttagningar i arbetskopian av avsnittet. Nu finns det två sätt att godkänna eller avslå kommentarer.

   Om du vill infoga den föreslagna ändringen \(infoga eller ta bort\) en i taget högerklickar du bara på kommentaren i innehållet och väljer Acceptera ändring eller Ignorera ändring. Beroende på vad du väljer godkänns eller avvisas kommentaren. Om det finns en godtagen kommentar läggs innehållet till i innehållet. och om det avvisas tas det bort från innehållet. Statusen för kommentaren ändras också på granskningspanelen.

   ![](images/import-comment-accept-web-editor_cs.png)

   Du kan också använda granskningsfunktionen på den högra panelen för att godkänna eller avvisa kommentarer. Om du klickar på en kommentar markeras kommentaren i dokumentet.

   ![](images/changes-tab_cs.png)

   >[!IMPORTANT]
   >
   > Funktionen för att importera kommentarer fungerar bara på de dokument som inte har ändrats sedan de delades för granskning. Om du har ändrat något efter att du skickat dokumentet för granskning får du ett varningsmeddelande till **Tvinga import** kommentarer i dokumentet. Om du gör det förlorar du dock alla uppdateringar som du har gjort i dokumentet. The **Tvinga import** visas även om dokumentet har skapats utanför och sedan delats för granskning. Du kan importera kommentarerna.

   När du accepterar eller avvisar en kommentar tas den bort från listan Spårade ändringar. Detta fungerar också som en indikator på hur många kommentarer som behöver tas upp i dokumentet.

- **F**: Hämta alla bilagor som är tillgängliga i granskningsavsnittet på menyn Fler alternativ.
- **G**: Sök efter text i kommentarer.
- **H**: Acceptera eller avvisa en kommentar.

- **I**: Använd ett filter på kommentarerna. Du kan filtrera om du vill se kommentarer baserat på granskningstyp \(all, markerad, borttagen, infogad eller anteckningsbar), granskningsstatus \(all, godkänd, avvisad eller ingen\), granskare \(alla eller vissa granskare\)\) eller ämnesversioner.


**Överordnat ämne:**[ Granska ämnen och kartor](review.md)
