### Transcript

# Interviewer
Waar ik vandaag wil gebruiken is eigenlijk de evaluatie van wat ik gedaan heb. De afgelopen tijd en vooral ook jouw mening op een aantal criteria om te kijken of wat ik wat ik bedacht heb überhaupt iets is dat dat wij bij PT misschien kan leiden tot verbetering of in ieder geval gericht op de problemen die we die we gevalideerd en gevonden hebben binnen de cases. Het gaat er vooral om dat je je input geeft, vooral je feedback van wat wel kan dat niet kan. Waar jij problemen in ziet, waar jij verdere uitwerking in nodig acht en eigenlijk zo uitgebreid mogelijk, zodat ik daar de conclusies aan kan ophangen. Van hoe gaat werken of hoe het misschien zou kunnen werken. Snap je dat, Is dat duidelijk?

# Business Process Manager

Ja, ja, Ja zeker.

# Interviewer

Het om even terug te pakken, wat ik moest doen of wat het vanuit de TU gevraagd werd, was om een design Science project op te starten. Simpel gezegd een probleem daar sta je doelen aan vast, dan design je iets die dat demonstreer je of je implementeert het in dit geval kan implementatie niet direct, dus middels een demonstratie. Daar kom ik straks op terug. En uiteindelijk evalueer je met de stakeholders die verantwoordelijk zijn voor in ieder geval die verantwoordelijk zijn of hebben meegewerkt hebben aan en mijn onderzoeksvraag. Waar het eigenlijk op neerkomt, is dat ik gekeken heb naar een aantal variabiliteit management ideeën, approaches of methodologieën in software productlijnen en die proberen toe te passen op PT en in die zin manufacturing van producten en variabele producten vooral. Met als doel in conceptualisatie te maken van hoe zulk soort management methodes er misschien voor kunnen zorgen dat het bij PT of in ieder geval een concept kunnen maken van hoe je bij PT dan op die manier ook zou kunnen en of daar of dat zou werken, ja of of nee? Voor jou belangrijk, dit zijn de evaluatie criteria die onder andere uit de literatuur komen, maar ook te maken hebben met de problemen die ik gevonden heb in de cases gaat dan over de validity, efficiency, completeness, understandability and fit in the organisation. Daar kom ik straks nog op terug, dus die hoef je niet te onthouden, maar misschien wel goed dat je even gezien hebt om om zometeen commentaar te geven.

# Interviewer

En dan kunnen eigenlijk door naar naar het de artefact en de artefact is feature modeling. Feature modelling wordt veel gebruikt in software development, zeker een software development van productlijnen, maar omdat ze heel goed de communiteit maar ook de variabiliteit laten zien van in dit geval softwareproducten en ze maken daarin variabiliteit en expliciet onderdeel. En die halen ze naar boven en die proberen ze te managen. En daarbij ook nog te traceren, dus met traceren bedoel ik eigenlijk: je hebt een feature die implementeer je maar wat zit daaronder bij software is dat vaak loc, dus Lines of code of bepaalde modules aan code of bepaalde stukken software die anders geschreven zijn . In manufacturing wordt dat een part, een bom, equipment of iets anders aan productdata, dan komen we straks op terug. Daarvoor heb ik. Feature modelling en de daarbij horende ideeën proberen toe te passen en ook aan te passen voor applicatie op variabele producten binnen PT. Dit is daarvan het metamodel, dus het metamodel. Verder een hele, simpele grafische weergave. En eentje die die goed schaalt met het aantal features dat bijvoorbeeld kan zitten in een product. Nou ja, in PT eigenlijk een hele ja nogmaals simpele simpele weergave. Maar dat is niet alles wat je nodig hebt om variabele producten te configureren, want je hebt namelijk ook manieren nodig om jullie model te limiteren. Enerzijds is dat de keuzes te maken bij variabele features. Anderzijds is dat door constraints in te zetten die we al een keer besproken hebben. Om bepaalde features niet met elkaar of juist wel maar elkaar te linken, waardoor ze altijd samen of juist niet tegelijkertijd in hun product kunnen zitten. En daarbij wat vooral in mijn manufacturing voorkomt, is dat variabele producten gemaakt zijn van de variabele parts en daarvoor kun je feature modellen superimposen. Hierdoor kun je feature modellen elk hergebruiken in andere eindproducten, zodat je maar één keer op hoeft te zetten, waardoor je reuseability improved and redundancy zo min mogelijk hebt. Daarbij bijkomend voordeel is dat je ze individueel kunt managen, dus je hoeft niet per se complexe eindproducten in zijn totaliteit te managen in een feature model, maar je kan ze juist splitsen om ze apart te behandelen.

# Business Process Manager

Het is voor mij. Sommige plaatjes zijn een beetje vaag, maar.

Speaker 3

Oh, dat is niet de bedoeling.

# Business Process Manager

Op bijvoorbeeld comfort functions, ja oké. Dat is meer als het over teams gaat in ieder geval soms zo vaag.

# Interviewer

Oké, Traceability, zoals ik toen straks al zei, twee security software productlijnen wordt voornamelijk gedaan op bijvoorbeeld Lines of code of modules binnen code. Voor manufacturing is dat natuurlijk niet aan de hand en daarbij moet je ook je features tracen, dus je feature model staat apart, wordt apart onderhouden van je productdata. Die productdata zit nog steeds in je in je PDM of je PLM in dit geval, maar die haal je eigenlijk naar voren op het moment dat jij gaat configureren en die link je daarbij aan speciaal of aan de specifieke features die waar ze toepassing op hebben. En op het moment dat je dan gaat configureren, moet je keuzes maken per features totdat alle features alle features of uitgesloten zijn of juist gekozen zijn dat ze het zijn. Waarna hij met behulp van de Trace Links configuratie kan omzetten in de benodigde productdata. Daarna kun je de configuratie, zo gaan managen door een overzicht te hebben van de geïmplementeerde features. Dus niet per se de feature data, maar de juiste geïmplementeerde features en zeker je kijken van hoe een verandering in een feature of hoe een verandering in een variant impact heeft op alle andere varianten of hoe een verandering in configuratie model impact heeft op alle andere varianten. En, dat kun je dan doen vanuit een productlijn of juist vanuit een superimposed feature model, dus als jij hem in andere productlijnen hergebruikt, kun je specifiek zien voor zo'n feature model waarin die gebruikt wordt en daarbij komend welke onderdelen daarvan dan gebruikt worden In de verschillende features.

# Business Process Manager

Ja, dus de linkse is de productlijn en rechts is super imposed?

# Interviewer

Ja, klopt dus links kijk je nou echt vanuit hè? Dit is mijn productlijn. Welke features zitten er in de varianten van mijn productlijn en rechts kijk je veel meer: Ik heb een variabel feature model, dus een variabel part als ik het zo mag noemen. Het gaat erom dat je een onderdeel hebt van een groter product dat variabel is. En die kan natuurlijk in meerdere producten zitten en dan wil je eigenlijk zien: ga ik daar iets aan veranderen? Welke andere producten, maar ook andere productlijnen heeft dat dan impact op? En dan heb ik een kleine demonstratie voor gemaakt binnen binnen PT. Geen Tim kwaliteit maar ik heb mijn best gedaan.

# Business Process Manager

Ik ben benieuwd en ik geloof me, de mooigheid dat intereseert me niet als het maar werkt en duidelijk is.

# Interviewer

Heb je tot nu toe vragen opmerkingen of dingen waarvan je denkt; leg me dat even anders uit of beter uit.

# Business Process Manager

Nee, waar je net die vorige had. Die moest ik even twee keer denken, maar volgens mij snap ik die ook nu.

# Interviewer

Ik denk dat jij nu dit ziet. Wat we ook een keertje besproken hebben is dus dat je vanuit PLM door kan klikken naar een configurator en in dit geval zal dat dan zijn jouw configurator van features dus jouw feature configuror. Waarin je los los features kan toevoegen en daaraan koppelen en aan productdata. In dit geval zou dat bijvoorbeeld zijn: ik wil de BOM overnemen van een aantal productnummers. Ik wil het equipment overnemen van een ander productnummer of van hetzelfde productnummer. Ik wil een aantal documenten die behoren bij een productnummer erin hebben dus op het moment dat we dan geconfigureerd wordt in deze feature zit erin, dan zullen al deze dingen meegenomen worden in je configuratie. Die kun je dan een naam geven, dus de feature naam. Een description ook. En een rationale, dus eigenlijk waarom en op welk moment en op welk moment niet wordt deze feature meegenomen of zal deze feature meegenomen worden. Om te kijken wanneer moet ik deze nou selecteren? Zo kun je er eigenlijk heel veel toevoegen. Ik ga daar even iets sneller klikken doorheen. Als je een aantal features hebt kun je ze daarna aan elkaar gaan linken, dus dat werkt eigenlijk gewoon op basis van de grafische, maar ook de onderliggende definities van feature modelling, dus in dit geval kan ik zeggen, mijn nano is een alternatief van de IMX8, die kan ook opslaan. En mijn mini is ook een alternatief feature van de imx 8. Die kan ook ook opslaan en zo vorm je uiteindelijk skip ik eigenlijk een klein stukje naar voren een hele feature model oprichten, zoals ik ze net ook al liet zien met links, eigenlijk alle features die je ook kunt groeperen in bijvoorbeeld dit geval de DRAM options, dus dat je een groepje maakt waar welke bij hoorde makkelijk vindbaar, maar ook ja, ze horen bij elkaar, want het zijn allemaal dezelfde van een soort. Bijvoorbeeld in dit geval zijn het componenten.

# Business Process Manager

Nou kun je daar nog eens even die want die dram tenminste? Ik kan gewoon vragen stellen toch?

Als je die dram options opent, dan moet ik dat dus zien. Dan staan er daar dus 5, en die komen eigenlijk overeen met wat je dram binnen je mini is en dram binnen je nano is. # Interviewer Ja, dus links is eigenlijk je alle features die in dit model zitten, maar om niet een losse lijst te laten zijn en omdat vaak features overeenkomsten hebben, kun je daarvoor eigenlijk een groep van maken binnen je feature model zodat je ze en makkelijk kan vinden, maar ook dat het niet gewoon een vlakke lijst, dus.# Business Process ManagerJa, dus oke dat is duidelijk en dan moet ik het zo zien: Dit zijn al je componenten, toch?

# Interviewer

Ja, dus het dingetje wat erachter staat, is eigenlijk zoals in het begin, zeg, maar voeg je dus een product toe. Daarmee dus Bill of Materials, documenten of iets dergelijks en hier staat eigenlijk bij IMX8, die heeft en zowel subassamblies dus de bom. En componenten en bij de rest idem dito, dus je ziet dat bijvoorbeeld bij DRAM dat hij alleen componenten overneemt.# Business Process Manager

En en nou snap ik hem dus niet want naar boven heeft die dram alleen maar documenten en die dram options alleen maar componenten. Maar ik had dan eigenlijk verwacht dat bij mijn dram daarboven ook componenten zouden staan.

# Interviewer

Ja in principe kan dat, dus stel alle dram had dezelfde ik zeg maar even iets dezelfde slot gehad die die ook mee moet nemen en dat is ook een component. Dan heeft dram dus alle ook componenten, maar de optie specifiek, zeg maar het componentje dram 1 gigabyte. Dat is een apart component en dat zeg maar is het in het model.

# Business Process Manager

Oh, zo ja j. Ja, want als ik, Als ik jou vraag om memory options of micro options open te zetten, dan zal dat niet gaan in de demo, gok ik? Maar bijvoorbeeld voor mijn beeld bij memory options had gestaan 4, 8, gigabyte ja 16 gigabyte 64 gigabyte. En bij micro options zie en die is dan die derde, maar waarom heb je dan je hebt geen dingetje gemaakt voor tussen mini en nano bijvoorbeeld. Dat zijn eigenlijk ook weer twee opties of zie ik het dan verkeerd?

# Interviewer

Dat zijn twee alternatieven, maar dat zijn in principe ook opties. Je hoeft ze niet te groeperen, dus in principe had links en vlakke lijst kunnen staan om met een hele grote alles achter elkaar. Maar om het overzichtelijk te houden, kun je die opties wel als het ware groeperen en omdat in dit geval zowel bij de mini kant als de Nano kantoor dus opties zijn voor dram. Maar die zijn niet per se hetzelfde. Dan is het logisch om ze te groeperen.

# Business Process Manager

Ja, want je gaat toch wel even vanuit dat, pak even goed voorbeeld. De 8 gigabyte memory. Ja, dat zijn er 5. Nou ja, die 8 gigabyte memory die is wel hetzelfde bij links en rechts. En dan ga je er eigenlijk ook vanuit dat dat hetzelfde component is, zie die dan twee keer terugkomen of is laat je die dan gewoon een keer zien?

# Interviewer

Nee, Dat is 1 feature zeg maar, dus je feature kunt je op zich wel herhalen, net zoals dram memory en micro. Die zie je aan allebei de kanten staan. Maar het kan ook zijn, stel het is een andere 8 gigabyte. Dat kan in principe. Dan heb je een andere feature nodig die anders gekoppeld is en een ander component.

# Business Process Manager

Ja dus, dan zou je hem wel twee keer zien. Ja, dan zie je hem twee keer allemaal. Maar dan hoop je dat je hem wel een iets duidelijker naam kan geven. Ja dan ben ik mee, ga door.

# Interviewer

Wat je daarna kan doen is constraints toevoegen. Dus welke mogen wel en welke mogen niet met elkaar. In dit geval kunnen we er bijvoorbeeld voor kiezen dat de Quad 1.8 Ghz processor niet samen mag met de 8 gigabyte. En hetzelfde kunnen we doen voor requirements. In dit geval worden die ook weergegeven in een tabelvorm, dus dat je makkelijk kan zien,. He de 512 megabyte en de 8 gigabyte moet samengaan met een Quad Light van 1.6 Ghz. Op deze manier kun je hem ook helemaal opbouwen tot jij de hele feature model hebt en op het moment dat je dat hebt kun je aanpassen. Je kunt bijvoorbeeld zeggen, hé, ik wil nog een ander componentje toevoegen. Of Ik wil nog een extra componentje toevoegen, maar op het moment dat zo een configuratie eigenlijk gereleased wordt, staat hij vast werkt in principe hetzelfde als een part.

# Business Process Manager

Ja precies, hij valt gewoon onder die releases, dan heb je deze features zorgen er dan bij met die dependencies. Ja en dit is eigenlijk gewoon een extra tabje bij wijze van bij PLM net als je bom et cetera, heb je je feature model. Ja bijvoorbeeld die componenten die je nou allemaal selecteert, die je feature model, die komen dan wel weer terug in je component lijst, toch?

# Interviewer

In je configuratie, bedoel je of?

# Business Process Manager

Nee, ja, Dit is je configuratie, maar Als ik nou de PN weer zou openen PLM, jou eerste start van je screenshot. Ja, eigenlijk zou je hier een tabje ergens krijgen met features, toch of configuratie? En ja, want ik verwacht eigenlijk dat je hier gewoon onder dit PN. Bijvoorbeeld configurator. Neem onder op begint te bouwn, of waar dan ook logisch is. Ja mijn vraag is meer, die componenten die je dan geselecteerd hebt. Als ik dan hier die configuratie zie? Dan verwacht ik dat ik die hier ook weer terugzie. Die componenten die erbij horen en ook in die sub assemblees, of wil je hier nog een boom bouwen of dat niet meer?

# Interviewer

In principe, kijk hoe ik het voor me zie, is dat ze dat je bijvoorbeeld een building block en die zet je als het ware klaar. In PDM/PLM. dus Je kunt in die zin ervoor kiezen om dit PN, dat is gewoon een normaal PN is, en die heeft een Bill of Materials en op het moment dat je die selecteert. Neem je eigenlijk in je configuratie, neem je die hele bill of Materials over. Dus die PN die bestaat ergens een PLM, waar dat maakt in principe niet uit.

# Business Process Manager

Nee, ik oke snap hem.

# Interviewer

Dus in die zin kun je er voor kiezen om inderdaad bij die configurator te zeggen, hé, alles wat ik hierin gebruik gooi ik daar meteen in een lijst onderin. Of, ik wil ze ergens anders een PLM opzetten en ze dan hier gaan gebruiken in het feature model.

# Interviewer

Goed, dan kun je dan voor gaan kiezen om om een configuratie te maken en dat kan aan de ene kant door te gaan klikken. Dus je zet een filter aan en je zegt: Ik wil een IMX 8 enwil daarin een nano en daar zie je dus eigenlijk meteen dit zijn nog mijn opties. Dit kan wel, dit kan niet of Ik wil hem niet, dan gaat ie de andere kant op. In dit geval en zo kun je de keuzes ook verder uitbouwen, dus ik wil 512 megabyte dram, Ik wil 1 8 gigabyte Memory en dan zegt hij ook meteen al; dus dan moet jij ook de QL 1.6 kiezen. En zo kun je ook speels tussen aanhalingstekens gaan kijken wat betekenen nou keuzes die ik wil maken in mijn variabel product. Zonder hem daadwerkelijk the publishen of te releasen. Maar op het moment dat je dat wel gedaan hebt, kun je hem in het systeem zetten en dan laat je eigenlijk zien. Welke included features erin zitten, welke bill of Materials, dus waar die die dingen oppakt of op meeneemt opneemt de documenten, de equipment en de discription en de titel zeg maar van. Van jouw product en Als je je publish dan staat die een PLM\PDM onder het PN zeg maar waar de configurator in zit.

# Business Process Manager

Gedefinieert.

# Interviewer

Als je dat gedaan hebt, kun je eigenlijk gaan kijken naar, hoe ziet dat er dan uit en hoe ziet mijn features eruit en waarom worden die gebruikt. Dat kun je dus doen in je productlijn. En dan zie je dus dat er 4 verschillende en varianten zijn, namelijk deze, die hebben allemaal de titel. Maar die kan ook heel anders zijn. Die kan ook variant A variant B. Of ik zeg maar even iets Signify ASML noem maar op, dus in die zin kun je dan eenzelfde product voor verschillende klanten hebben. Ligt er maar net aan wie het wil. Hier zie je dan eigenlijk hè? Ik heb twee verschillende mini’s twee verschillende Nano 's allemaal hebben ze Dram, memorie en Micro, dat staat vast. Maar ik zie ook dat mijn 4 gigabyte eigenlijk nergens gebruikt wordt die die zit wel in het model. Net zoals die andere twee en zo kun jij ook gaan kijken van hé, Als ik nou iets verander in mijn Mini's, welke veranderen dan ook mee of moet ik dan ook vervangen?

# Business Process Manager

Ah ja dit is wel vet. Dit hebben we echt nodig.

# Interviewer

Dat is een beetje hoe ik het voor me zie. Dan komen we nu op, wat vind je hier nou van en dan met name, antwoord alsjeblieft zo uitgebreid mogelijk en ook al je vragen en bedenkingen et cetera et cetera, aan de hand van deze eigenlijk aan de hand van deze vragen.

# Business Process Manager

Ja, Ik heb natuurlijk al best wel een verhaal gesteld, hè, ondertussen.

# Interviewer

Dat is eens.

# Business Process Manager

Dus lost het concept de juiste problemen op en hoe goed doet hij dat? Ja. Natuurlijk is het voor mij lastig om nu in een keer allemaal te zien, want dan zou je echt meerdere cases, zou ik ze allemaal door moeten lopen of zou echt allemaal opgelost worden. Maar volgens mij cover je hiermee, los je de juiste problemen op ja. Of daar alles perse in zit? Ik weet niet of elke case die wij hebben hier 100% gedekt door gaat zijn. Maar ik denk wel dat wij genoeg dekken. Met de vragen die ze hebben. Ja en hoe goed het hij dan? Dus ja, ik, Ik gok dus het overgrote deel dus meer dan 90-95% sowieso. Nou, wat betekent dat? Ik denk dat hij in veel gevallen zelfs meer kan dan dat nodig gaat zijn om het zo maar te zeggen. Dat het in veel gevallen nog simpeler zijn dan wij net lieten zien of dat jij net als voorbeeld paktte. Ja, kunnen we dat toch wel even kort terug naar die superimposed? Met zon variabele variant. Ja, deze snapte ik niet helemaal.

# Interviewer

Dit kun je vergelijken met die IMX8 dus dat dat daar maak je een model van en dat feature model kan gebruikt worden in andere.

# Business Process Manager

Ja, zelfs in andere feature modellen toch?

# Interviewer

Juist ja, andere variabele producten. Dat kan eigenlijk op twee manieren gebeuren, dus enerzijds kan jij een volledig geconfigureerde, dus die wat we net hadden.

# Business Process Manager

Ja die ene die je uitgetekend hebt met alles wat groen is?

# Interviewer

Yes. Je kunt hem aan de ene kant dus een hele geconfigureerde kun je zeggen hè? Deze configuratie van die variabele beelding blok, die kan ik in mijn feature model doen, dus dan link je hem eigenlijk na de volledig geconfigureerde building blok. Maar wat je ook kan doen is dus jouw volledige feature model, dus jouw hele variabele product in het feature model van een andere variabele product stoppen. En dan neem je eigenlijk alle keuzes die mogelijk gemaakt kunnen worden mee in je nieuwe variabele product dus in het andere feature model.

# Business Process Manager

Ja dan snap ik die. En dan is het enige wat ik niet scherp heb is of… Want je gaat hier exclude zijn requires naar die andere toelinken, ja, die zit er eigenlijk allemaal in of je daar geen tegenstrijdigheden kan maken en als dat wel kan, want dat kan volgens mij. Dan moeten we natuurlijk softwarematig dicht houden. Dat als jij requires toevoegt dat je niet eens toevoegt die eigenlijk tegenstrijdig is, met iets waar je al uitgemaakt.

# Interviewer

Wat het wel is, is dat je maakt die requires die door je modellen heen gaan specifiek voor dat product. Dus in die zin moet je dan alsnog gaan nadenken? Dit zijn de de require and excludes binnen mijn aparte kleine feature model en deze binnen mijn grote feature model. Die heeft er ook nog op zichzelf staand, maar die heeft er dus ook nog in samenwerking met het andere feature model.

# Business Process Manager

Oke, dat snap ik, Het is mij meer dat je een excluded of een requires toevoegt. Je moet daar sowieso binnen een eigen feature model ook al dicht gaan houden. Ik kan niet een require doen en een exclude op dezelfde lijn. Ik zeg maar iets of een driehoeksverhouding creëren.

# Interviewer

Nee precies, dus je kan niet inderdaad hebben dat iets iets anders require die zichzelf exclude zeg maar of die dan andere ja.

# Business Process Manager

Ja nee, je kan zo een paar of daar kun je driehoeksverhouding, maar je kan ook over 10 schijven heen. Kan het zijn dat hij dat je eigenlijk iets creëert, wat niet kan?

# Business Process Manager

Even voor de zekerheid. Executive requires fast. Stel voor fast exclude standard and standards Required executive, dan ga je nat toch?

# Interviewer

Ja, maar dat kan niet executive doen, want dat zijn alternatieven.

# Business Process Manager

Oh ja nou requires slow. Weet even niet hoe ik hem nou dicht krijg, Maar dat is misschien net geen goed voorbeeld dan.

# Interviewer

Even kijken als diesel Navigation system require zoals nu. Maar hij exclude software en computer. Dat kan bijvoorbeeld niet.

# Interviewer

Maar dat, dat zul je ook binnen een feature model dicht gaan houden. En wat je dan gaat krijgen is dat je hem niet kunt configureren. Hij heeft hem wel nodig? Maar hij kan hem niet selecten.

# Business Process Manager

Nee, maar het is voor mensen natuurlijk als ze er fouten maken of iets? Hoe moeilijk makkelijk kunnen wij dat voor hun aangeven, Maar dat is detail. Ja, ze moeten gewoon goed nadenken en als je het zo tekent, maak je het natuurlijk ook wel heel snel, heel erg visueel.

# Interviewer

Inderdaad, wat je zegt die afhankelijkheden dan interpreteren is ontzettend lastig.

# Business Process Manager

Ja oke. Even terug naar de laatste slide. Hoe goed doet hij dat? Ja, Dat is goed, ik kan niet inschatten of het overal is, maar ik gok in veel gevallen zelfs dat het te goed doet. Ja dat teveel functionaliteit in zit die niet altijd nodig is. Maar we hebben die cases wel, dus hij doet ja, ja. Is concept compleet. Ja, dat is voor mij een beetje hetzelfde als de vorige vraag, maar ja, ik denk dat die vrij compleet is.

# Interviewer

Mis je nog dingen? Had je had je andere dingen verwacht die er wel in meegenomen zouden moeten worden in jouw ogen?

# Business Process Manager

Nee, we hebben deze al zo aangetikt van hoe ziet er dat uit? Ik heb nog een dingetje wat ik niet helemaal zeker weet, is hoe het stukje rond refdessen zou werken.

# Interviewer

Ik die vind heel lastig, moet ik eerlijk toegeven. Dat is ook echt waar waarmee ik gewoon In de knoei kom af en toe, want op het moment dat jij een bom overneemt in principe zitten daar de refdessen in. Dus als jij een PN hebt en hij heeft een boom staan, dan heb je daar je refdessen in zitten. Echter als jij een component toevoegt op PN, dus je PN doet en je hebt daar een component van. Dan zit daar geen refdes aan vast in principe. Wat je zou kunnen doen, is die als optie bij een feature geven, dus bijvoorbeeld als een feature alleen bestaat uit een component, dan kun jij die feature ook nog een refdes meegeven.

# Business Process Manager

Nee, je zegt, componenten hebben in principe geen refdes, dus bij schemas ga je daar wel nat toch?

# Interviewer

Als je aan een feature een component toevoegt, dan moet je er ook een Request aan toevoegen.

# Business Process Manager

Ja ga eens terug naar de plaatjes terug naar het plaatje gaat.

# Interviewer

Welke bedoel je?

# Business Process Manager

Of de of de applicatie die je had, maakt niet heel veel uit welke je pakt? In ieder geval ergens eentje waar we hem zien. Als ik nu op Mini componenten toevoeg. Dan verwacht je refdessen op? Maar in principe kan nano ook componenten hebben. Maar de refdessen. En aangezien je daar een keuze mag maken, mogen die allemaal hetzelfde zijn. En zo, kun je toch door je model heen als je. Dan dram hebt. Die kan component hebben met de refdes. Die mogen niet hetzelfde zijn als In de mini. En niet hetzelfde zijn als een IMX 8 m, maar die moeten wel hetzelfde zijn als aan de andere kant. Ja, de rest als memorie, micro en alles binnen nano. En Als je dan kiest? Ja en ook op de laagste niveau kun. Je nog een keer zo doen? En, Als je dan kiest voor? Oh wacht je kiest hier wel een dram, memory en een micro, die zijn niet hetzelfde als tussen mini en nano. Sorry, die haalde ik net door elkaar.

Als ik een refdes toevoeg in dram, dan mag die niet terugkomen in memory of een micro.

# Interviewer

Nee precies, want die zitten er allemaal in, dus die zitten er sowieso in eigenlijk. Je mag refdessen hergebruiken bij alles dat je in een bepaalde keuze uitsluit. Dus als jij met een bepaalde keuze iets uitsluit, zouden die in theorie dezelfde refdessen mogen hebben.

# Business Process Manager

Ja, want dit tekeningetje voor mij, ik snap niet helemaal hoe ik nou kan lezen als ik dit zag. Ik had verwacht dat dram memory micro uitsluit, want dat doen wij mini en nano ook.

# Interviewer

Nee, dat zeg Maar dat lijntje dat daaronder zit.

# Business Process Manager

Dat is het verschil. Ja, ja, is die kan dan de een of de andere?

# Interviewer

Kan een heel even twee seconden terughalen. Je hebt and, dus dat zijn gewoon lijntjes.

# Business Process Manager

En alternative.

# Business Process Manager

Optioneel mandatory. Die miste ik hier in dat lijntje? Ja, dat is duidelijk. Aan de hand daarvan kun je bepalen wat je, maar volgens mij kun je dan toch aan de hand daarvan bepalen welke refdessen hetzelfde mogen zijn. Welke niet, kun je er ook meenemen?

Maar waarom zou je het niet toestaan dat je hier toevoegt en een redes geeft, want je kan hier ook zeggen, Waarom mag ik geen subassambly, niet toevoegen. Ik wil eigenlijk de subassambly nu wel gebruiken, en dan zou ik hem ook een refdes moeten geven?

# Interviewer

Ja, in principe ook. Dus dan zou je eigenlijk willen uitbreiden dat je niet per se de hele bom meeneemt, maar juist echt dat je hier je productconfiguratie in gaat doen.

# Business Process Manager

Ja. Ik zie niet helemaal waarom dat mis zou gaan.

# Interviewer

Maar dat dat gedeelte van het de configurator zie ik voor ogen dat dat eigenlijk volledig een PLM/PDM zit.

# Business Process Manager

Ik snap wel, je bedoelt.

Ja, ik zit er wel mee als je het doet zoals jij het zegt, ben ik er bang, welke versie neem ik dan mee? Van het PN en zet je die vast in die product configurator.

# Interviewer

In principe kan dat nog steeds op PN niveau en 12 cijferig PN. Omdat die function of form fit function compatible zijn. Dus dan zou je in die zin vrij hem kunnen upgraden, naar andere minor versions of patch versions.

# Business Process Manager

Dus je zegt eigenlijk hetzelfde niet, oké? Ik snap hem.

Bij dit stukje. Ja, ik snap hem. Ik vind hem wel lastig om te beoordelen of het 100% gaat werken op dit moment.

# Interviewer

Ik heb hier gewoon niet direct een goede oplossing voor, Omdat elke oplossing waar je waar ik aan denk, bijvoorbeeld in dat wat jij zegt hier alle refdessen invoeren, maar dan heb je dat in PLM niet meer, dus dan dan ga je hier je hele productconfiguratie in doen. En, dat lijkt me geen goed plan. Omdat je dat stuk, denk ik heel erg een PLM wil houden, anders ga je alle variabele producten producten configuratie met alle refdessen en alles hierin doen en in alle andere producten in je PLM en ik zie dit meer als een extensie als een losstaand stukje waar je eigenlijk alleen maar linkjes trekt tussen de configurator of de variant management en je PLM systeem.

# Business Process Manager

Qua implementatie is, dat is sowieso makkelijker. Ook denk ik. Vind het alleen moeilijk inschatten of dat ook beter en logischer is voor een gebruiker. Want volgens mij gaat het allebei, denk ik. Vind je het alleen niet waar ik als gebruiker fijner zou vinden. Dat ik het hier allemaal door elkaar heen wil hebben, omdat ik dan een plek heb om het te doen en. Dan is het duidelijk. Of juist los. Zodat het een extra feature is. Ja, dan klinkt er raar features maar features, Maar extra functionaliteit in PLM is die waar je de rest gewoon hergebruikt en alleen losse zoals je zegt, lijntjes kan gaan trekken.

# Interviewer

Precies, en dat laatste is wat ik dus meer voor me zie als een goede of een eerste manier van implementeren.

# Business Process Manager

Goed duidelijk, welke vraag waren we. Ja Refdessen hebben we daar net behandeld, voor de rest heb ik daar niks. Is het concept van het artefact duidelijk?

# Interviewer

Begrijpelijk, zeg maar is het idee hierachter duidelijk en hoe het je problemen die er zijn oplost?

# Business Process Manager

Ja ja ja 100%.

# Interviewer

En is de toepassing, dus hoe ik het voor me zie inderdaad eigenlijk net een beetje besproken heb dus dat de toepassing is echt als extensie met met de linkjes naar PDM/PLM.

# Business Process Manager

Allemaal duidelijk.

# Interviewer

En als laatste past het binnen het PT? Denk je dat het toevoeging is en en zo ja, als het een toevoeging is. Hoe zou jij dan de vervolgstappen voor bijvoorbeeld het implementatie van zo'n systeem als dit In de toekomst zien? Laten we zeggen, half jaar tot een jaar.

# Business Process Manager

Ik denk dat we nog een paar dingen wil hebben. Wat ik net zei, met de Refdessen en of je het lostrekt als een eerste feature, of dat je meteen toch doet wat ik net voorstel dat je het samen pakt. Dat zal van de gebruikers afhangen en dat vind ik moeilijk inschatten, want ik ben zelf geen eindgebruiker. Ja, voor mij is dit. Hoe ga ik dat goed zeggen, een duidelijk toepasbaar concept waar we dan gewoon de verdere mockups zou je moeten werken in PLM om te kijken of het duidelijk kunnen krijgen voor gebruiker? En als we dan een stapjes doorlopen, of het of ja, of het ook echt allemaal in detail klopt. En nu lijkt het voor mij lijkt het te kloppen. Maar die acties zou ik dan ook door willen gaan met ja Robert en een de mensen die het ook echt technisch zouden moeten maken. Of het haalbaar is om het zo te maken? Haalbaar is het waarschijnlijk altijd de vraag is, hoe werk je dat kost?

# Interviewer

Ja, dat klopt.

# Business Process Manager

Ja, als jij meer op papier krijgt, dan moeten we hem met software ook erin krijgen. In principe kan er in software alles, zeggen we altijd. Ik vind hem hij lijkt complex misschien, maar ergens vind ik hem ook wel heel simpel. Als je die die jij net leit zien, dat plaatje met denk slide 5. Linkse stuk, dat is alles wat je moet snappen. Ja, dat maakt het gewoon, ja? Allemaal technische Mensen. Nou ja, dan toch, als het dan grafisch is, dan helpt dat wel heel snel. Heel duidelijk van wat wel wat niet. Ja die legenda die moet je er een begin bij hebben, maar als die eenmaal is hoofd kent om dan lees je hier gewoon doorheen.

Jij zegt dat product, feature. In principe die lijntjes die eronder staan, dat is niet dat die twee optional en die mandatory die bij de producten horen en dat pijltje en ding bij de features horen, wel?

# Interviewer

Alles moet je apart zien, dit is een product. Dit is een feature en die lijntjes die zijn optimaal mandatory etc.

# Business Process Manager

Ja, dat was voor mij hier nog wel even als ik die las., dat zou ik daardoor misschien verwacht worden.

# Interviewer

Zal ik even aanpassen.

# Business Process Manager

Voor jou hier het product, de configuratie. En de meeste bedrijven waar ik ben geweest sinds het zoniet, dan is het product wel echt instantie.

# Interviewer

Ja, het is derivation configuration of instance inderdaad. Dat zijn de 3 meest gebruikte. Ik denk dat misschien wel goed is. Om te veranderen.

# Business Process Manager

Naming things.

Speaker 3

Dat is onderdeel van de brainstorm elke dinsdag.

# Business Process Manager

Dat is het moeilijkste van software maken definities, naamgeving.

# Interviewer

Het moet heel strak en heel duidelijk zijn. Misschien ook een goede voor mij om een keer door mijn artefact in ieder geval concept heen te lopen om te kijken of dat allemaal duidelijk is of ik dat niet ergens beter moet gaan neerzetten.

# Business Process Manager

Nee maar, ik vind dit goeie input. Waar onze software Engineers mee slag zou moeten kunnen gaan. En ja, We moeten UI dan nog designen. En, hun zullen echt een model en je hebt eigenlijk een groot gedeelte van de modellering al gedaan. Maar ze moeten hem nog wel linken aan ons versie beheer. En het model waar het dan allemaal bestaat, dus dat moet nog wel die linkjes moeten dan nog wel denk ik vooral een stukje versiebeheer. En Refdes stuk.

# Interviewer

Ja, en zeg maar, Dit is zoals het hier staat ik het het link to product data stukje. Ik vind het en daar ben ik, kan ik best wel eerlijk zijn. Ik vind dit een beetje de makkelijke manier om mezelf er vanaf te maken. Om te zeggen, hé, ik link het aan product data. Alleen ik moet eerlijk toegeven, geen enkele andere manier zag om dit vanuit bijvoorbeeld de RSD van PLM te linken aan de specifieke datamodellen die daarin staan.

# Business Process Manager

Ja, want eigenlijk wat ik voorstel was dat het product data dan weghaalt en meteen: Link to bom equipment en documenten doet. Maar dan kom je dus bij het Refdes verhaal et cetera uit, hoe de stand houdt is ook maar de vraag. Hier maak je inderdaad. Het is een makkelijkere variant eigenlijk. Je hebt gelijk. En zo zouden we wel kunnen beginnen. Ik denk ook niet dat dat inderdaad een probleem is, want dan heb je wel een werkend model en hij doet het. Als je naderhand een slag dieper wilt. Ik denk niet dat het dan in een keer heel anders wordt.

# Interviewer

Nee, want het enige wat je verandert is dat linkje zeg maar naar PDM Beelen en hoe dat eruit ziet.

# Business Process Manager

Ja, want ik vraag me nou hierin wel bijvoorbeeld af, wat is dan de versie van jou feature ten opzichte van de versie van je productdata? En dan zei je al, dat doen ik gewoon op PN niveau 12 cijfers en minors neem ik gewoon mee. Maar jouw feature op zich moet ook een versie weer hebben, toch?

# Interviewer

In principe niet. Denk ik, Waarom? Omdat als jij een een feature model maakt als het ware, dan maak jij een configuratie van een feature model. En, die heeft bepaalde features, die zou je wel releasen. Ja, op dat moment dat je die dan veranderd, krijg je daar een nieuwe working version van. Daar kan je van alles aanpassen. En op het moment dat je die dan weer released, dan release eigenlijk de volledige feature model, weer in één keer. En alle producten, bijvoorbeeld die dat feature model gebruiken. Die linken nog steeds naar de oudere, maar die kunnen bijvoorbeeld ook weer upgraden. Zeg maar naar de nieuwe versie.

# Business Process Manager

Ja, dus hebben ze toch een, dus hebben we feature modellen toch versiebeheer.

# Interviewer

Ja feature modellen ja, features zelf Nee. Ik, ik dacht dat je features zelf bedoelde?

# Business Process Manager

Oh nee, ik had toch een feature model. Ik bedoelde met hier het feature bedoel ik eigenlijk de hele boom, samen.

# Interviewer

Absoluut, ja absoluut moet de diverse controle hebben.

# Business Process Manager

Ja en het enige wat wij doen als we dat in twee staps raket van maken, dan slopen we een stukje weg. Want die doe je in een keer de boom en alles eronder. Je zou bijna kunnen zeggen dat ze dat we het allebei kunnen ondersteunen.

# Interviewer

Als we dit gaan implementeren, hoe ziet dan het komende? Stel we mogen nu gaan implementeren. Hoe ziet het komende halfjaar eruit?

# Business Process Manager

Aan Tim geven voor UI/UX. Brainstormen en als die mockups et cetera er zijn. Die vragen die ik nog had waarschijnlijk beantwoorden. Ik weet niet of het een andere zijn van andere mensen. Ik kan zo snel niet verzinnen. En anders maken. Ja, ik zie niet heel veel meer en het is een grote feature maar nou ook weer niet dat ik denk zo extreem.

Daar zou je dan kunnen starten? Nou ja, jij weet qua planning staat hij dan als we deze willen, hebben we eigenlijk gepland voor start 2025. Voor mij is het dan niet heel veel meer. Aan onze kant en dan laat ik het even zeggen, de functionele kant. Kan ik niet heel veel zeggen dat we meer input moeten leveren aan het softwareteam om het te maken dan? Dit is al eigenlijk al twee stappen verder, want je doet eigenlijk al een deel wat hun normaal doen, dus een model erbij verzinnen wat we voor ons zou werken, geen twee stappen in maar 10 stappen verder.

# Interviewer

Oké, nee, dat is duidelijk dan. Dan denk ik dat dat hem is.

# Business Process Manager

Is goed, dan ga ik snel naar buiten.

# Interviewer

Helemaal goed, succes Lyon.

# Business Process Manager

Jij bedankt jij ook succes met het laatste stuk jij.
