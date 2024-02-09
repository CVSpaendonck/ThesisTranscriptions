
### Interviewer
Het is eigenlijk goed om te de achtergrond van mijn onderzoek te weten. Wat ik doe is Design Science. Wat dat wat inhoud is een probleem waarna er doelen opgesteld worden, daarna design je iets en je gaat het dan demonstreren en evalueren. Dat laatste stukje daar is dit voor bedoeld, om met jou naar te kijken. Het is ook goed om te begrijpen dat ik het onderzoek gedaan heb vanuit een bepaald perspectief, software productlijnen, dus hoe ze in software omgaan met variabele software producten, om dat eigenlijk toe te passen op manufacturing, dus de manieren die ze daar gebruiken kunnen we die ook hier gebruiken. Dit is eigenlijk mijn onderzoeksvraag. Staat hier heel mooi op. Het doel daarvan was om een conceptualisatie te maken van een product variabiliteit management systeem met daaraan gekoppelde configuratie systeem gebaseerd op de SPL methodes. 
### Systems Developer
Wat maakt dat het precies design science? Daar kun je alles wel onder scheiden, toch?
### Interviewer
Ja, het is allemaal net hoe ze het noemen, en het is allemaal net wat anders. Het zijn juist ook een aantal stappen die je doorloopt om tot goed gestructureerd research te komen, zeg maar.
Gewoonlijk kan deze gebruikt worden voor information System Research, waar ik onder val.
### Systems Developer
Ja precies, dus Het is eigenlijk meer ja, oke, een onderzoeksmiddel?
### Interviewer
Ja precies een onderzoeksmiddel, de manier waarop je die doet. De onderstaande 5 dingen waar ik op geëvalueerd wil worden en hier boven zie je eigenlijk alle problemen die ik gevonden heb hier binnen PT.
### Systems Developer
Ja zo op die fiets. Ja ja die. Is dan ja oké ja.
### Interviewer
Dat betekent dat zij building blocks en producten die varianten van elkaar hebben, kunnen ze niet identificeren überhaupt en ze kunnen ze dan ook niet maintainen, dus ze kunnen überhaupt niet kijken van hé, zijn ze er en ze kunnen daarna ook niet zeggen van oké, deze is dat nu wel of deze is het niet meer.
### Systems Developer
En er zit geen tracing of niks tussen, niks dus 0.0. Dat geeft enige problemen die hier opgelost worden, en daar stappen we in precies dezelfde problemen.
### Interviewer
Dat is de tweede stukje issues worden dus niet geanalyseerd op ze allemaal, maar ook niet gesolved, zeg maar, ze worden niet opgelost bij allemaal. Ze krijgen dat ze onafhankelijk van elkaar bepaalde problemen oplossen, niet oplosse. Bijvoorveeld ook een werkinstructies gaat dat door en in requirements aanpassen.
### Systems Developer
Wat we dus nu van hebben, is dat je een stukje design werk uit handen genomen wordt, omdat het al gedaan is. Maar de rest? Alles daarachter ligt , weten we niet de vruchten van te plukken die je zou kunnen plukken. 
### Interviewer
Precies. En daarnaast willen ze dus een gestructureerde en systematische manier hebben om het een PLM op te slaan. Dat wordt nu gedaan door af en toe PN's uit te trekken om daar mapjes van te maken. Iedereen geeft daar zijn eigen ingeving aan. Ik Je hebt drie cases bekeken. Drie cases doen het totaal anders. Die 3 cases doen het totaal anders.
### Systems Developer
Ja nee, dat klopt. Er is absoluut geen manier waarop het opgelegd is of meegenomen is een design van PLM.
### Systems Developer
Elke Architect gaat daar op zijn eigen manier mee om, en ja, precies je krijgt wildgroei.
### Interviewer
Ja precies. Die wildgroei gaat alle kanten op. Ik heb er, Ik heb er na 3 gekeken om een om een keer te kijken van hé, wat doen ze nou allemaal? Hoe werkt dat nou en hoe kunnen we dat vertalen? Naar bijvoorbeeld software productlijnen. Als laatste willen ze een configurator. Dus mocht je inderdaad weten wat je allemaal wilt doen, kun je op een bepaalde manier een configuratie van de producten eigenlijk maken. 
Waar ik naar gekeken heb, is featuremodel. Ik weet niet of dat iets zegt?
### Systems Developer
Ik kan me er iets bij voorstellen als ik het hier al zo zie.
### Interviewer
Dit is het entity relationship diagram. Eigenlijk is het de metamodel van hoe je zo'n model op kan maken, hoe je een features wilt matches, hoe liggen de relaties? Eigenlijk is dit een datamodel zo. Uiteindelijk bleek dit het beste te werken, omdat het zowel communiteit laat zien als variabiliteit laat zien, maar ook de keuzes en de dependencies die je hebt binnen je product.
Binnen je building blocks of binnen je product kun je variabiliteit laten zien. Dus als jij een keuze maakt links in op een stukje van de variëteit betekent dat dat een ander stukje bijvoorbeeld ook gekozen moet worden.  
### Systems Developer
Dit soort dingen wil je echt zo simpel mogelijk. Het kan soms heel complex zijn om het heel simpel te maken.
### Interviewer
En daarbij komt dat het dus grafisch is. Als je een complex product hebt, dan wordt dat lastiger om te zien in tabellen en grafisch is het gewoon makkelijker. Zo zien ze er een beetje uit, in dit geval zie je dat er een keuze hebben gemaakt moet worden tussen diesel, petrol, Electric motor en aan de andere kant heb je die keuze, zeg maar mag je één van de twee kiezen of meerdere kiezen?  Dus mag je hier een of twee kiezen van comfort functies. Die zijn ook overigens allemaal optioneel,. 
### Systems Developer
Waarom dit model type, dus heb je het zelf zo bedacht. Is dit standaard?
### Interviewer
Dit wordt veel gebruikt binnen software. Het is een hele makkelijke en een best wel oude manier. Hij is simpel, hij is makkelijk in gebruik en je kunt hem uitbreiden, zoveel complexiteit als je nodig hebt. Dus dit zijn eigenlijk degene die ik gekozen heb voor mijn artefact, waar dit relatief de complexiteit van de producten binnen PT covert, maar hij kan nog 10 stappen complexer. Dependencies kun je eruit halen. Deze kun je omzetten zijn tools voor gemaakt om bijvoorbeeld een xml op te zetten, zodat je ze in xml in kan  importeren et cetera.
### Systems Developer
Ja, wat is het verschil tussen alternatieve or?
### Interviewer
Or is je mag er één of meerdere kiezen dan alternatief is. Je mag één van deze set kiezen.
### Systems Developer
Ah zo ja ja.
### Interviewer
Zo ziet het al een uit, dan kan je dependencies gaan creëren, dus in dit geval mocht jij navigatiesysteem en airconditioning allebei kiezen. Dan mag jij geen elektrische motor, maar kies jij een diesel, dan moet zij ook een navigatiesysteem hebben, dus op die manier kun je dat de dependencies heel netjes en mooi grafisch weergeven.
### Systems Developer
Ja ja.
### Interviewer
Mocht dat te complex worden of mocht je dat anders willen zien, kun je dat natuurlijk ook een tabel weergeven, omdat alleen keuzes maken binnen je variabiliteit niet per se feasible product genereert.
### Systems Developer
Nee exact, ja ja is duidelijk ja.
### Systems Developer
Je kunt er een elektromotor in doen, maar als je daar geen batterij doet, dan doet hij niets. Dus dat hoort erbij. Ja.
### Interviewer
Die dependencies hier, die creëren eigenlijk de feasible producten, aan de ene kant heb je dan dependencies? Aan de andere kant heb je juist traceability en dat is meer naar de producten en productdata. Wat je ook kunt doen, is het modulair opzetten van de featuremodellen, dus in dit geval heb je navigatiesysteem die zijn eigen feature model heeft. Je kunt die modulair beheren dus  modulair maken en dan implementeren in een ander feature. Dus super imposed heet.
### Systems Developer
Aha ja, dus je kunt blokken gebruiken om tot een bouwwerk te komen.
### Interviewer
Juist en dan is eigenlijk de variabiliteit van je auto is de variabiliteit van zichzelf plus alle modulaire modellen.
### Systems Developer
Nu kun je op basis van model. Die is makkelijk om te zetten in regels en dan kun je een invaliditeits check doen op mijn hele apparaat.
### Interviewer
Juist juist, kan het, werkt dit? Als ik deze keuze maak, is dat dan feasible. 
Als laatste de je  traceability, dus je moet die features je linken aan enerzijds de bom documenten componenten. Noem het maar op. Ik heb hem ingezet op echt het productconfiguratie stukje dus je product bom, documenten en alles wat daarbij hoort, maar er is mogelijkheid, omdat die variabiliteit dus losstaat van het managen van je productstructuur om, hem daarna te linken aan andere stukken binnen PT.
### Systems Developer
Ja, dat is goed om het te future proven zeg maar, ja, zeker.
### Interviewer
Configuratie werkt eigenlijk heel simpel, je maakt keuzes die moet feasible zijn aan de hand van de dependencies, die features link je dan op dat moment aan je bom je documenten waarin je dan een variant krijgt .
### Systems Developer
Kijk wat technisch kan er een hele hoop natuurlijk, dus als je puur kijkt naar wat is een valide en invalide configuratie, dan krijg je een hele lijst staan valide configuratie. Ik weet niet of je direct met het model mee wil nemen, maar in ieder geval een belangrijk interface daarin is de businesscase. Dus de strategie van het programma, zeg maar. Om bepaalde keuzes te maken, maken we een low, Middle High class een ding, apparaat of niet? De architect en engineer zijn natuurlijk een belangrijke stakeholder hierin, maar de business case eigenaar? Zeker ook ja, misschien wel het belangrijkste.
### Interviewer
Wat wel goed om te beseffen is je featuremodel modelleert je variabiliteit, losstaand van je productstructuur, dus je maakt hier inderdaad misschien wel de keuzes van je business case. Zo wil ik hem wel opzetten, maar alsnog moet je daarnaast een in PLM alle componenten klaar gaan zetten om hem eraan te linken.
Maar goed, dus zo ziet de configuratie eruit en wat je daaraan kan doen is eigenlijk aan die features kun je variabiliteit gaan zien, hè? Hoe zien mijn varianten binnen het type 1 eruit? Anderzijds zag je net dat je die die navigatiesysteem heb je gesuperimposed, dus die heb je gebruikt meerdere feature modellen, kun je hem eigenlijk een across the board kijken van hé ga ik iets veranderen in mijn software, waar moet ik dan nog meer naar kijken? Hoe en waar moet dat compatible mee zijn? Kan ik dat in een keer updaten?
### Systems Developer
Die twee heb je nodig voor de business case manager.
Waar ga ik focus op leggen In de upgrade in het te upgrade pad, zeg maar welke variant? En waar hebben we het meest profijt van? Als de high end iets doen, kan ik dat dan door laten druppelen naar de low end, trickle down technology?
### Interviewer
Precies ja dus hier kun je echt je impactanalyse gaan doen en in een snelle manier je overzicht creëren van hé, hoe zit dat nou en hoe werkt dat nou? 
### Systems Developer
Misschien ook nog wel een als je kijkt over trickle down. Je liet met verschillende productvarianten zien. Ik kan me voorstellen dat je in die configuratie een keuze maakt voor je ABC waarbij je in A en B en feature kan inzetten, zeg maar de high end features. Die wegens structuur beslissing is maar voor je variant C helemaal niet meer compatibel kunnen, volgens je model, misschien leuk om daar ook om dat inzicht naar boven te brengen. Nou bijvoorbeeld van een elektromotor en een dieselmotor, inderdaad, Je high end is elektro bijvoorbeeld. En nieuwe snufjes en features hebben we ontwikkeld voor je high end apparaten en daar kun je dan na verloop van tijd, zeg maar die techniek wat ouder wordt en er komen nog meer nieuwe snufjes op, kun je die weer door laten sijpelen naar B en eventueel je C maar naar B zal misschien nog gaan. Het is ook een elektro, maar C heb je een andere techniek gebruikt? Daar gaat dat model gaat fout zijn. Kan nuttig zijn om dat ook dat ook naar boven te brengen. Je inheritance zeg, maar van features, hoe gaat het over je productlijn heen. 
### Interviewer
Misschien dat je dat ook wel af kan sluiten met dus die dependencies. Maar jij bedoeld meer het inzicht creëren. 
### Systems Developer
Ik bedoel inderdaad dat dat je dat je daar in de toekomst in, ook weer die business case manager om het vast te stellen. Dat is een hele belangrijke. 
### Interviewer
Ik, ik zie het eigenlijk als een als een extensie van standaard PLM, dus je bouwt op PLM. Dat is het interface voor wat je eigenlijk doet is. Je gaat features aanmaken en dan link je spullen of dingen uit PLM aan dat die zijn gebaseerd op je PNs. Je geeft daar een naam aan en je creëert feature. Daarbij is best belangrijk om een rationaal toe te voegen. Dus je geeft aan niet per se voor degene die het feature model zelf maakt, want die heeft er veel kennis van of degene die de feature modellen maken. Maar misschien in de toekomst, bijvoorbeeld voor sales, dus iemand die er geen kennis van heeft, dat die ook vanuit dit featuremodel een product kan configureren, of iemand die later bij het team komt die kan zien, hè? Deze feature is daar en daarvoor en implementeren kan op in zo’n manier. Dit is de high end motor, die wil ik implementeren op het moment dat ik een high end apparaat ga maken, dus je wilt echt dat die rationaal daar ook voor gebruikt kan worden.
### Systems Developer
Ja ja absoluut ja, ja. 
### Interviewer
Al die features maak je aan op dezelfde manier en op het moment dat jij ze aanmaakt hebben ze nog geen relatie. Maar dan ga je zeggen, hè, die nano die ik heb, Ik wil dat dat alternatieven zijn van mekaar, dus die nano en die mini die zijn alternatief van elkaar, dus op het moment dat ik die IMX8 ga bouwen of configureren heb ik sowieso die building block feature nodig. Hij heeft ook DRAM nodig. Hij heeft ook zeker micro nodig en memory ook.
Daar mag hij kiezen uit een van deze twee, maar goed je kunt je voorstellen die mini of die nano die heeft bepaalde eisen aan Ram of aan micro.
### Systems Developer
Nou, precies ja, dan heb je minder nodig dan waarschijnlijk dan de mini.
### Interviewer
Hier zie je de zijkant, zie je ook wat die meeneemt, dus hij neemt sub-assamblies en componenten, maar ook documenten mee. Dat zijn sub-assamblies, die gewoon micro zijn bijvoorbeeld alleen documenten. Dat kunnen voorbeeld test documenten zijn, maar dus de tekstdocumenten in zijn algemeenheid. Goed op dat moment kun je dependencies gaan toevoegen? In dit geval mag en Q 1 8 micro microcontroller niet met 8 GB memory stick en in dit geval mag ik die 8 gigabyte, als 512 MB Ram ook gekozen wordt, dan moet bij memory, dan moet je een QL. 
### Systems Developer
Ja dit aspect mist nu ja, totaal compleet dus.
### Interviewer
Dat doen ze dus nu onder andere door titels in PLM aan te passen. 
### Systems Developer
Building blocks zijn ze serieus aan het oppakken zijn, maar dan moet je dit soort aspecten zeker meenemen. Daar hebben we het al heel lang over dat we het willen. Als we dat niet kunnen verkopen, zeg maar om goed in geïntegreerd te krijgen. Wat doen we dan nog met überhaupt?
### Interviewer
Je kunt het integreren in de productstructuur zelf zeg maar dus dat je gaat zeggen op refdes regels. Dit staat er los van, maar heeft juist  interfaces met de PLM, dat zijn twee verschillende tactieken.
### Systems Developer
Oh zo ja ja. Van die structuur, ja. Dat is juist beter. Die aspecten wil je onafhankelijk van elkaar houden, zodat wijzigingen in de een niet leidt tot een wijziging van anderen. Dat wil je het liefst zo min mogelijk openingen hebben juist. En wat hier uitkomt? Die heb je in PLM staan, die dingen die hieronder hebt staan. Die heb je in PLM hangen en ziet hoe dat samenhangt?.
Ja, ik wil de onafhankelijkheids zo groot mogelijk houden, ja.
### Interviewer
Je kunt hier op het moment dat je een geconfigureerd hebt, kun je een aanpassen op het moment dat je hem gereleased hebt. Dus je release staat voor een featuremodel. Zo ziet hij eruit. Dit zijn de linkjes naar PLM, dan kun je hem gaan configureren. Op het moment dat je dat gaat doen, kiest hij eigenlijk direct alle dingen die er sowieso in zitten. 
### Systems Developer
Werkt wel hoor als visualisatie.
### Interviewer
Dus je kiest ook meteen alle dingen die erin zitten. Nou super simpel, Je kunt gaan kiezen voor mini nano en hij ziet dan meteen hè. Het is nog geen volledige configuratie, want er zijn keuzes nog niet gemaakt. Je stopt je configuratie pas als alle keuzes of alle featureen opties gekozen zijn of juist uitgesloten zijn.
### Systems Developer
Misschien zou je dan, dit is een wip natuurlijk, maar die zaken waar je nog input van de user verwacht ook een kleurtje geven.
### Interviewer
Dat is een goede. 
### Systems Developer
Als het grijs ja, waar moet ik allemaal klikken?
### Interviewer
Ja, dus dat je dat je laat zien waar er keuzes nog gemaakt moet worden.
### Interviewer
Daarna ga je kijken van hé, Ik wil daar 512 en weer bij en Ik wil 8 gigabyte bij.
### Interviewer
En op die manier wil je eigenlijk die feasibility erin hebben. Dit zijn de opties en op die manier. werken die dependencies met elkaar en op het moment dat je hem dan gaat releasen, zie je wat erin zit. Zie je welke features daarbij zitten, wat je kunt hem met naam geven. Description, noem het maar op en dan kun je maar pushen in PLM, krijg je ook een lijst met alle varianten die ooit gemaakt zijn vanuit dit feature model en je kunt eens kijken hoe die eruit zien. Dit is echt de feature structuur en daar aan de PLM kant zit de productstructuur.
### Systems Developer
De bill of features, bof? 
### Interviewer
Dat is een eentje die het voornamelijk inzichtelijk krijgt is. Je kunt vanuit je bof kun je gaan kijken van hé hoe, hoe werk het nou, hoe zit het nou al die features geïmplementeerd in mijn?
### Systems Developer
Ja ja ja.
### Interviewer
Er zijn een aantal die zitten overal. Er zijn al een aantal zijn grijs, dat zijn gewoon zeg maar groepen aan opties. Een aantal zijn rood van hé, die gebruik ik helemaal niet. Waarom zitten die erin? Ik heb daar geen variant van, moet ik die nog supporten, moet ik die nog gebruiken? Je kunt hier zien. Hè, als ik iets ga aanpassen, dan moet ik daarop letten op deze en dan heeft dat zon effect.
### Systems Developer
Of misschien wordt die door heel veel varianten gebruikt, dus die is kritischer dan bijvoorbeeld anderen.
### Interviewer
Precies ja. En ga ik in aanpassing doen, waar zit inderdaad de meeste benefit waar kan ik het meeste halen.
### Systems Developer
Dat is interessant voor purchasing natuurlijk ook. Dus als je ziet dat we gebruiken de 4 Gbyte. Dan kan het handig zijn om in je keuze voor de variant juist diegene te pakken, waar we heel veel van gebruik maken. 
### Interviewer
Echt op variant. En dan ook je je marges en weet ik veel, wat kun je er allemaal aan afleiden. Dat is het eigenlijk en het zit het in elkaar, zo zie ik het een beetje voor me
Snap je het idee van feature modelling, zeg maar hoe dat centraal staat? Hoe dat los staat van PLM? Waarom dat los staat van PM? En hoe het werkt natuurlijk?
### Systems Developer
Ja. Ik denk wel ik, ik snap dat ook met name omdat ik er. zelf mee bezig ben geweest. Ik ben zelf met dat vraagstuk ook een beetje geworsteld heb. Mij duidelijk is welke problemen daarbij komen kijken. Zeker als het een en al gebaseerd is op deze presentatie, heeft dat misschien nog wat meer uitleg nodig, want tegen welke problemen loop ik nu op dit moment precies aan? Zeg maar wat meer, ja wat duidelijker. Ik denk dat we de oplossing die je gekozen hebt, die liggen er helemaal mee in line. Dat is zeker dus netjes. Uitleg van het concept waarom het nodig is zelf dat misschien een beetje beter.
### Systems Developer
Misschien een voorbeeld erbij, dat we nu in de praktijk hebben? Dus daar zijn veel voorbeelden. Te vinden volgens mij.
### Interviewer
Zeker, ja, ik heb ze mijn thesis echt wel benoemd. Misschien zijn ze hier niet zo duidelijk naar voren gekomen.
### Systems Developer
Misschien een leuke use case. Ik weet niet of je die ook allemaal tegen bent gekomen. Ik weet het rond die tijd van de corona eigenlijk, waren component shortages voor verschillende producten waarbij bepaalde componenten niet meer geleverd konden worden, dus daar was een alternatief voor in gebruik genomen. Dat is toen een jaar lang of twee jaar lang op zo gebruikt. En op een gegeven moment kwam iemand met het briljante idee om te kijken, ik heb dit component. Kunnen we dat misschien als alternatief voor het eerst component gebruiken, moest helemaal gekwalificeerd worden. Maar het bleek gewoon het originele component te zijn. Dus men gebruikt altijd a als a niet meer leverbaar is b wat werd in gebruikt en omdat dat dat hele proces is slecht gedocumenteerd, gecommuniceerd was. Dus op een gegeven moment kwam iemand a weer tegen, hè? Waarom gebruiken we eigenlijk die niet, maar die gebruikten we al is, Dat is het hele probleem.
Dat is een hele hoop effort en dingen in gedaan om alweer te kwalificeren, terwijl dat is verdorie in eerste instantie voor ontworpen.
### Interviewer
Het stukje alternatieve dat zit nog een laag hiernaast eigenlijk. Dus het klopt en het zit in het verlengde hiervan of parallel hieraan, Ik weet niet hoe je het moet noemen.
### Systems Developer
Wel goed te beseffen, zeg maar dat we de methode die je hier kiest afhankelijk van welke methode je kiest dat we wel of niet feasible gaat zijn ook om dat soort problemen te lossen. Dus dan is wel goed om alvast mee te doen ter voorbereiding van.
### Interviewer
Snap je het concept wel binnen PT, zeg maar hoe dit kan werken en hoe het probleem op kan lossen. Op welke manieren?
### Systems Developer
Ja zeker. Het verhoogt het inzicht op het probleem überhaupt. Welk probleem? Het laat de mogelijkheden en vooordelen binnen het probleem zien. Het geeft inzicht in inderdaad die mogelijkheden welke speelruimte heb ik überhaupt? Alleen al een centrale manier om dit soort problemen op te lossen gaat al helpen, dat zie je nu. Je hebt een wildgroei aan aan de oplossingen groeien. Er zitten ongetwijfeld hè? Dit is een best het huidige kunnen en onderzoek, zeg maar nu dit model ingestoken en gaat in de praktijk gaat dat weerbarstiger zijn. Die gaat tegen dingen aanlopen. Als je allemaal tegen dezelfde dingen binnen hetzelfde modellen aanloopt, leidt dat gewoon centraal tot verbetering van dit hele principe. Dat is alleen al een win, absoluut. En je ziet ja toepasbaarheid van het concept ja, je ziet met die programma's al. We hebben inmiddels hele productfamilies, daar gaan we helemaal niet serieus mee om, dus hoog tijd. Eigenlijk had dit in Place moeten zijn voordat we aan product families, gingen beginnen.
### Interviewer
Ja ja, want het idee van die product van jullie is, want SPL zeg maar ook als praktisch hetzelfde ziet. Je gaat van tevoren bedenken wat je gaat maken. Je creëert daar alle building blocks voor je, zet het allemaal klaar in PLM. Dat gebeurt nu en dan heb je dit soort functionaliteit nodig om daar goed mee om te gaan.
### Systems Developer
Dan baseer je die familie op basis van de strategie en nu is het meer op basis van: nou hè? Daar kunnen we best ook wel eens variant van maken. Dat is heel reactief en dat is inefficiënt.
### Interviewer
Dat is meer off the shelve gedachtegoed in PT zorgt ervoor dat je die productlijnen op gaat zetten en dit soort functionaliteiten nodig is.
### Systems Developer
Nou ja, het een kan niet zonder het ander, dus lopen we nu keihard tegenaan. Nou ja niet, want Het was inefficiënt. Dat is een van de redenen dat er nou flink gesneden wordt.
### Interviewer
Ja, zeker wel. Goed denk je dat het concept effectief die problemen aanpakt, denk je dat het de problemen goed oplost? Maar ook limitaties daaraan?
### Systems Developer
Wat je misschien nog meer mee moet nemen is een lijstje met eisen van de stakeholders. Voorkom dat je een big bang integratie moet doen, zeg maar, waarbij je pas op het moment dat het helemaal geïntegreerd en klaar is, dat mensen dan pas profijt gaan hebben, want Ik denk dat veel stakeholders zal blij zijn met überhaupt minimum viable. Als je kijkt eind van de rit heeft dan dit model probleem effectief aangepakt? Ik denk het wel, ziet er doordacht uit, zeg maar je komt ongetwijfeld nog issues tegen. Het is moeilijk koffiedik kijken. Maar de effectieve uitrol van het hele gebeuren, ik denk dat je dat goed mee moet nemen en kijken waar ligt je prioriteit, zodat mensen daar alvast mee aan de gang kunnen gaan. 
Ik denk een pilot project doe je voornamelijk om te zien of iets feasible is, een proof of concept dat moet je niet eens willen, dat moet je gewoon doen. Dat lijkt me een no brainer. Hadden we al lang gedaan moeten hebben. Ik zou het niet de scope beperken door de hoeveelheid projecten daarin bijvoorbeeld in werken hier gebruik van maken, maar eerder zeg maar gewoon wel alle projecten beschikbaar stellen, maar dan de featureer set laag houden. Dus dat je het heel breed inzet en dan langzaam opbouwt. 
Maar het pad dat je dan kiest, tot uiteindelijk het hele afmaken van het hele gebeuren, dat je het zo inzet, dat dat ook al ligt er maar een beperkte featureset dat men dan toch wel iets aan heeft.
### Interviewer
Maar goed, even kijken, mis je dingen in het concept ? Ook met je Achtergrond en bijvoorbeeld V systeem of bijvoorbeeld het linken naar requirements of iets dergelijks?
### Systems Developer
Ik denk wel dat het interessant is om te kijken, volgens mij dat variant management binnen polarion, , dat is hij super mee in lijn dus. Niet gezegd dat je dat nu meteen al mee moet nemen, zo niet wil je denk ik eerst dat het feature functie model beperken begrijpelijk. Maar maak het wel op zo'n manier dat je voorsorteert op de ook de integratie met die aspecten en als dat je weet welke features je hebt,  Als het goed is, moet je daar de RSD uit kunnen genereren.
### Interviewer
Dus dat je dat je op die manier samen werkt met polarion voor de requirements?
### Systems Developer
Als je de RSD hebt, dan voorziet polarion zelf in het linker richting design en testen zeg maar. Dus de link die hieruit komt en de RSD die moet je kunnen genereren.
### Interviewer
Het is daarin het linken, naar de requirements.
### Systems Developer
In principe kun je dat in polarion zelf zouden dat kunnen oplossen. Uiteindelijk heeft een klant de data sheet ook. Als je verschillende configuraties bij mekaar klikt, kun je daar dan ook een specificatie documenten van extraheren. Ja en die kun je gebruiken om je producten te verkopen richting die klant.
### Interviewer
Omd dit soort dingen in de toekomst toe te Laten, is mijn keuze ook gevallen op het niet integreren in PLM maar het aparte houden, want dan kun je dus die requirements specifiek linken, net zoals je eigenlijk naar PLM doet. Naar bepaalde features en dan naar een bepaalde feature keuze. 
### Systems Developer
Ja, precies, als je dat apart houdt.
### Interviewer
Is dat het grootste deel dat je misschien mist?
### Systems Developer
Nou ik, ik snap dat je dat er nu niet meegenomen hebt, dus ik mis het niet in die zin, maar het is wel iets in de toekomst is dat ook weer een no brainer. Uiteindelijk moet dat resulteren in je design requirements van een bepaalde configuratie, dus dan wil je ook inzichten hebben, kun je genereren hoef je eigenlijk helemaal geen werk meer te doen.
### Interviewer
In hoeverre past het binnen PT zoiets als dit? En dan die per se een functionaliteit maar meer in gebruik. Hoe gaan mensen het gebruiken? Denk je dat het kan werken binnen de context van de programma’s?
### Systems Developer
Absoluut, sowieso heel erg en momenteel helemaal in flux en wat men gewend is te doen en waar welke kant welke kant we op gaan. Ik denk als je het mij vraagt, het belangrijkste waar we wel scherp op moeten zijn is, zeg de verantwoordelijkheid die mensen daarin kunnen pakken, de vrijheid van het maken van keuzes daarin in design. Dit zit dat helemaal niet weg. Je kunt zelf je model opstellen, dus in principe kun je daar ook maar spelen. Je kunt het zelfs een moeilijke zo makkelijk maken voor jezelf als je wilt. Maar het biedt wel, je ondersteunt je faciliteert dat deel van het proces en dan dat doen we nu niet. Ja nogmaals, dat het allang gebeurt had moeten zijn. En dat is niet vanuit PT, zeg maar, onze mensen goed daarin ondersteund, dus is eigenlijk tegelijk zwemmen.
### Interviewer
Ja zowel het proces als de tooling die daarbij zit?
### Systems Developer
Ja ja. Dus past het bij PT ja, dat lijkt me wel. Ja, ik zou niet weten waarom niet.
Plus helemaal omdat we meer naar een echte product organisatie gaan, niet alleen een projectorganisatie gaan. We maken nu zelf het product, zelfs product lijnen.
### Interviewer
Dus je hebt dit ook nodig? Want op het moment dat jij een product In de markt gooit, wil je daar om hem verschillende markten te bedienen of juist verschillende customers te kunnen bedienen. Wil je daar varianten van hebben. Punt.
### Systems Developer
En dat wil je wel een professionele manier doen en op deze manier is er helemaal niets dat borgt dat je inderdaad connectors krijgt die helemaal niks doen, enzovoort weet je wel, dus dat is funest voor je voor je perceptie en de kwaliteiten. Dus dat als je die markt serieus wil nemen moet, moet je ja, dit heb je gewoon nodig.
### Systems Developer
Het is precies., en daarom was ik er ook mee bezig vanuit vanuit system development process. Oudsher kregen met een klant met een stel vragen en er was principe al impliciet duidelijk, zeg maar welk deel van de functionaliteiten de klant om vroeg in hardware of software ging landen. We hadden projectleider en hardware architect, software architect en afhankelijk van senioriteit van de architect, of welk domein de overhand had binnen een product was de hardware of de software architect de lead architect. Op basis daarvan werd die V doorgelopen en samengevoegd voila we hebben een product, maar Omdat.
Sinds een aantal jaren hebben ook het systeem development systeem niveau daarboven. Ja wat wij eigenlijk nog steeds maar beperkt doen, ik wil zeggen, we missen de concept stap. Dus we krijgen requirements vanuit de klant een bepaalde functionaliteit in te vullen. Daarin moet met de klant meegedacht worden. Bedoel je bedoel je dat? Zeg maar, dus dat zal nou goed hè? Dat is dan ook weer een vak apart. Maar voordat je naar de techniek springt, wil je daar eigenlijk een concept tussen zetten, dus oké, dit concept en dan gewoon niet in termen van techniek denken gewoon puur functioneel een functioneel blok diagram. Als ik dit vertaal in deze functieblokken dan voldoe ik functioneel aan die requirments en die stap wordt vaak overgeslagen. We stappen in één keer vanuit requirements naar bam de techniek. We gaan het op deze manier, met die microcontroller en dan gaat de software gaat dit doen en de hardware gaat dat doen. Dat beschrijven we op systeemniveau en daarna gaat hardware software mee aan de slag. Maar de vertaalslag van concept naar die techniek. Die mist nu nog. Welke concepten liggen daaronder, wat zijn de alternatieven?
### Interviewer
Bedoel je meer dat je dat je meteen eigenlijk de specifieke invulling ingaat met hoe je het welke microcontroller hoe je het in software wil gaan doen, of hoe? Hoe moet ik het zien?
### Systems Developer
Wat je nu ziet, et is zo evident voor de meeste architecten dat je bepaalde functionaliteit in software doet, dus die functionaliteit wordt direct met andere functies samengepakt. Zo in software gegooid zal ik maar zeggen, terwijl voor de functionaliteit aan het bepalen hoe de afhankelijkheid daarin is, wat is de onderhoudbaarheid van bepaalde zaken? Hoe kan ik dingen zoals je hier ook zag, gewoon modulair opbouwen, zodat je als er iets fout gaat dat dat de focus daarop kan leggen, ook voor issue management. Zeg maar beter isoleren en diagnostiek van je systeem,  doe je allemaal op functie niveau. Terwijl als je verschillende functies pakt en je weet nou, dat heeft allemaal een algoritme nodig om bepaalde uitvoer te doen op het moment dat je direct stapt naar het idee van ik moet op de microcontroller doen dan valt dat allemaal, blob in de blob software weg. Terwijl of je iets in hardware of software doet, dat doe je eigenlijk pas nadat je de functie bepaalt hebt.
### Interviewer
Want dan weet je wat er allemaal moet gebeuren en hoe het allemaal in verhouding staat met elkaar? Het is een beetje als feature modelling, maar dan op dat systeem niveau zeg maar ja, heel abstract en vrij abstract.
### Systems Developer
Dat is dus precies dat, ja. Het is de de aller abstracte variant van je design naar de klant requirements. Daar past dit heel goed bij. Straks moet de verantwoordelijkheid van met name de architect wordt. Die moet hier zeker in betrokken zijn. Logisch. Met de business case owner en de project manager en de planning een beetje de kosten enzovoort. Daar dat zit er natuurlijk ook bij, maar dit gaat hand in hand met de met het functionele concept en niet het technisch concept technisch concept komt daarna pas.
Dus dit past vanuit dat perspectief, het past binnen PT, maar het past ook, denk ik binnen  onze processen in de eerste stap en dan moeten we nog eerst stap tussen de systeemarchitectuur zetten, daar moet systeem concept neerzetten nog,  Daar de requirement elicitatie met de klant. Is dit stap twee. 
### Systems Developer
Dat is zelfs ook weer een iteratief proces, want afhankelijk van de strategie die gekozen is ga je andere klanten benaderen, met het product familie.
### Systems Developer
Ja en dus vanuit dat perspectief is ook nog eens omdat je een centrale methode hebt, biedt het ook een Centraal punt, een praatplaat om de verschillende disciplines over hetzelfde aspect te laten discussiëren. De business case owner, de de projectleider architect puur op op dit model.  Terwijl op dit moment is het zo dat in die business case owner heeft daar bepaalde perspectieven op, bepaalde ideeën op. De projectleider of de architect die de structuur in het PLM invullen, die lopen er op dat moment tegenaan, hebben daar ook bepaalde aannames bij. Die hoeven niet perse met elkaar te stoken. Omdat ze op andere tijden met een andere tool bezig zijn om diezelfde aspecten in te voeren. Als je dat centraal in één ding doet, dan heb je ook met zijn allen geen mismatch in de configuratie in.
Het is eigenlijk een single source of truth van je functie model. Dat moet de tool bieden. Als iemand het functie model heeft. 
En de product structuur, die leid je daarvan af. En niet andersom, dat bied ook nog meerwaarde, dat je gewoon een centraal ding hebt, dat is goed voor de communicatie.
### Interviewer
Om daar om je daar aan vast te houden.
### Systems Developer
Ja, dat klopt. 
### Interviewer
Super hartstikke bedankt dankjewel.



