

Projekta uzdevums
Projekta uzdevums ir veikt 2 funkcijas: pirmā no tām ir nolasīt noteiktas grāmats nodaļas tekstu un saglabāt to. Programma nolasa un ieraksta teksta failā nodaļu, kādai grāmatai no mājaslapas royalroad.com, kurai ir iedots links uz šo nodaļu. Otra funkcija programmai ir webscrapot noteiktu grāmatu sēriju ar nosaukumu "Practical Guide to Evil", visas 7 grāmatas, un saglabāt šo grāmatu nodaļas teksta failā. Kā arī programma saglabā katru nodaļu kopā ar tās nosaukumu un grāmatas nummuru linked listā.

Python bibliotēkas
Programmā tiek izmantotas requests bibliotēk, lai varētu iegūt informāciju no vairākām mājaslapām, kā arī tiek izmantota beautifulsoup4 bibliotēka, lai vārētu izvēlēties specifisku informāciju no tā, kas tiek iegūts no šīm mājaslapām.

Datu struktūras
Programmā tiek izveidot datu struktūra LinkedList. Šajā LinkedListā var pievienot objektus, kas sastāv no grāmatas nummura, nodaļas nosasukuma, un paša nodaļas teksta. Vēl ir arī print funkcija, lai izprintētu visus LinkedLista objektus, kas eksistē priekš testēšanas.

Programmatūras izmantošana.
Palaižot programmu tā consolē piedāvā izmantot vienu no divām funkcijām: nodaļa vai grāmata. Ja izvēlas un ieraksta consolē nodaļu, tad programma pieprasīs royalroam.com mājaslapas linku uz kādas grāmatas nodaļu. Pēc linka ievadīšanas programma pieprasa nosaukumu failam, kurā saglabās nodaļas tekstu no dotā linka. Kad tas tiek consolē ievadīts, programma izveidos failu ar doto nosaukumu, webscrapos nodaļas tekstu un saglabās to šajā failā. Ja jau eksistē fails ar doto nosaukumu, tad programma izvadīs paziņojumu, ka šāds fails jau eksistē un beigs darbību.
Ja tiek izvēlēta funkcija ar nosaukumu grāmatas, tad programma pārbaudīs vai jau ir izveidots fails izmantojot šo funkciju un ja ir, tad izvadīs paziņojumu un beigs darbību.