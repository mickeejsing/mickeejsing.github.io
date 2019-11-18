---
layout: post
title:  "Klar för inlämning"
categories: Skola
comments: true
type: image
image: jagoblommor.jpg
---

**What do you think of pre-compiling your CSS?**

Jag har nu byggt en webbplats med hjälp av SASS. Jag tycker att det har varit väldigt smidigt att använda SASS, men ovant. Jag har bland annat använt mig av nesting, vilket har varit effektivt för att påverka flera element samtidigt. Jag har också använt mig av varabler. Det har varit väldigt effektivt för att återanvända t.ex. vanligt förekommande typsnitt, färger osv. Ytterligare tekniker jag har testat är mixins och operatorer.

**Pros and cons?**

Fördelen är att det går snabbare att skriva CSS med hjälp av SASS, på grund av nesting, mixins, variabler och så vidare. Då variabler möjliggör återanvändning blir koden även kortare och mer intuitiv att skriva.

Nackdelen är att det kräver lite inlärningstid. Dessutom har CSS utvecklats väldigt mycket och tillåter idag användning av variabler. Språken börjar därför likna varandra.

**What do you think of static site generators?**

Jag tycker att det har varit spännande att använda. Det är väldigt smidigt att skapa en enkel webbplats, då samtliga delar (både funktionallitet och design) kan återanvändas från det valda temat. I mitt fall Minima. Jag tycker att det har varit aningen komplext att sätta sig in i mappstrukturen och hur samtliga filer samverkar. Men det har klarnat under arbetsprocessen. Väldigt roligt att arbeta med!

**What type of projects are they suitable for?**

Jag skulle säga att det är lämpligt för projekt där tidsramen är stram. T.ex. kampanjer, bloggar, eller kanske till och med hi-fi-prototyper. 

**What is robots.txt and how have you configure it for your site?**

Det är en textfil som är till för sökrobottar, crawlers. Crawlers genomsöker internet för att indexera material för sökmotorer. Jag har ställt in robots.txt för att tillåta alla former av sökrobottar. Jag har även gjort så att dem inte har tillgång till mappen bilder.  

**What is humans.txt and how have you configure it for your site?**

Det är en fil som förklarar vilka som har skapat sidan och vilka som har utgjort ett stöd i skapandet av webbplatsen. Jag har angett mina kontaktuppgifter i humans.txt. Jag har ytterligare tackat webbplatsen Unslash.com, som har möjliggjort nedladdning av royaltyfria bilder.

**How did you implements comments to blog posts?**

Jag har använt mig av Disqus. 

**What is Open Graph and how do you make use of it?**

Open Graph möjliggör visualisering av webbplatsen, då den delas genom att uppvisa t.ex. titel, datum, url, beskrivning och så vidare. Då länken postas på t.ex. Facebook blir det tydligt vad webbsidan innehåller.

Jag använde den för att visa beskrivning, bild, url och typ. Informationen skiljer beroende på vilken url som kopieras, då respektive fil innehåller Front Matter. Front matter möjliggör beskrivning av respektive sida. 
