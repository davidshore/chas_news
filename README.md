# Gruppuppgift: Bygg en nyhetssida med Next.js

I det här gruppprojektet ska ni tillsammans skapa en nyhetssida med hjälp av Next.js. Uppgiften kommer att ge er praktik i att hantera globalt state med Redux eller Context API, ge er erfarenhet av att hämta och visa data från ett externt API, och implementera funktionalitet för att bokmärka artiklar.

### Projektöversikt

Er nyhetssida ska inkludera:

- En **huvudsida** som visar huvudnyheter.
- **Kategorisidor** för olika nyhetstyper såsom sport, internationella nyheter osv. Dessa sidor ska vara tillgängliga genom navigeringslänkar på er webbplats.
- Individuella **artikelsidor** som presenterar innehållet i en nyhetsartikel när en användare klickar på en artikelöversikt. Tyvärr ger inte nyhetsapier tillgång till hela texten av artikeln, så ni får nöja er med det som finns.
- Möjligheten att **bokmärka artiklar**, vilka sedan ska vara tillgängliga på en sida för **sparade artiklar**.

### Tekniska Krav

1. **Next.js**: Ert projekt ska byggas med Next.js för att dra nytta av dess server-side rendering och filbaserade routing.
2. **Global state**: Använd Redux Toolkit eller Context API för att hantera global state. Detta använder ni för att hantera bokmärkta artiklar.
3. **Externt API**: Hämta nyheter från [https://newsdata.io/](https://newsdata.io/) eller ett annat nyhets-API efter eget val. Ni får kopiera svar och spara dem som JSON-filer för att undvika att överskrida gränsen för API:ets gratisversion med 200 förfrågningar per dag.
4. **GitHub-repo**: Arbeta tillsammans med hjälp av ett gemensamt GitHub-repo. Se till att alla medlemmar har åtkomst och bidrar till kodbasen.

### Frivilliga Funktioner (Extra Uppgifter)

- Implementera en layout med två kolumner på huvud- och kategorisidorna, där den högra, smalare kolumnen t.ex. innehåller textlänkar till de senaste nyhetsartiklarna.
- Lägg till ett flöde av ytterligare artiklar längst ner på varje enskild artikelsida för att uppmuntra till ytterligare läsning.
- Använd local storage för att spara och hämta användarens bokmärkta artiklar. Se till att bokmärkena är tillgängliga även efter att webbläsaren har stängts och öppnats igen.
- Använd er av en scrape-funktion för att hämta hela arikelns innehåll från länken till den riktiga artikeln på internet.

### Inlämning av Projektet

- **Deadline**: Ert projekt ska presenteras för klassen **tisdagen den 27:e februari**.
- **Presentation**: Var beredd att visa upp er webbplats, framhäva de funktioner ni har implementerat och diskutera eventuella utmaningar ni stött på och hur ni övervunnit dem. Det behövs ingen powerpoint.

### Komma Igång

1. **Sätt upp ert Next.js-projekt**: Initiera ert projekt med `npx create-next-app`.
2. **Installera Redux Toolkit eller inte**: Beroende på ert val för global state, installera nödvändiga paket.
3. **Planera strukturen på sidan**: Besluta vilka kategorier ni vill inkludera, hur ni ska strukturera era sidor och komponenter, och hur bokmärkningsfunktionaliteten ska implementeras.
4. **API-integration**: Registrera er för en API-nyckel på [https://newsdata.io/](https://newsdata.io/) och bekanta er med deras dokumentation för att förstå hur ni hämtar nyhetsartiklar.
5. **Samarbete**: Se till att alla teammedlemmar är bekanta med Git- och GitHub-arbetsflöden. Comitta och pusha regelbundet ert arbete så att era merge conflikts inte blir för omfattande.
