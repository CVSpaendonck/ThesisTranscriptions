### Interviewer

Eerst even om de achtergrond weer duidelijk te krijgen, want we hebben elkaar natuurlijk een tijdje geleden gezien. Wat het methode van mijn thesis is, is eigenlijk een Design Science probleem, daarna de doelen opstellen, daarna iets designen, demonstratie en evaluatie. Dat laatste stukje, daar zijn we nu beland, dus ook de laatste stukje is fijn dat het nog voor de vakantie kan van jou, want het scheelt mij natuurlijk ook. Om te herhalen met onderzoeksvragen en dat heb ik toen een beetje laten doorschemeren, maar dat was nog niet helemaal duidelijk. Hij staat hier heel lang opgeschreven, maar waar het eigenlijk op neerkomt is dat ik vanuit software variabiliteit, management, ideeën, approaches, methodologieën ben gaan kijken, hé, is dat niet iets wat we ook kunnen toepassen op manufacturing, dus vanuit echt die invalshoek ben ik gaan kijken, wat doen zij, wat kunnen zij. Literatuuronderzoek en hoe kan ik dat aanpassen, al dan niet toepassen op prodrive en in die zin iets groter manufacturing bedrijven. Het doel in design is een conceptualisatie maken van product van je management en configuraties systeem, dus gebaseerd op die SPL methodes. Dit zijn de vragen. Je hebt ze net al even gezien. Als je hier meteen iets ziet van hé leg me even uit, dan laat het vooral weten. Nou, uiteindelijk ben ik uitgekomen bij feature modelling. Ik weet niet of jij feature modelling ooit gezien hebt? Het is eigenlijk een methode om communiteit en variabiliteit in softwaresysteem te laten zien. Zij gebruiken het heel veel voor in eerste instantie voor loc, dus Lines of code die ze dan modulair kunnen opzetten en daarmee modulair zeg maar systeem van kunnen maken. Daar ben ik uitgekomen na eigenlijk een onderzoek naar wat is er allemaal nog meer? Ja, er zijn er nog meer. Er worden een aantal ook al dan niet gebruikt in onder andere bijvoorbeeld PTC Windchill voor inderdaad, software development. Feature modeling bleek een fit te zijn in mijn ogen en ook vanuit de literatuur met manufacturing, dus daar ben ik verder naar gaan kijken. Daarvan heb ik een eigen metamodel gemaakt, dus om zo'n feature model op te zetten aan de hand van je producten of en met de link naar productdata en op de manier die voor manufacturing goed kan zijn. Aan de ene kant zie je daar links dependencies, dus eigenlijk moet je het een beetje zien als een data, een entiteit model, zoals je ze ook wel ziet in bijvoorbeeld RSD van PLM. Je hebt features dat staan los van alle productdata, dus je hebt ook een nieuw systeem waarin je features aanmaakt. Daar kom ik straks op. Ik heb straks een kleine demonstratie waarin je features aanmaakt en die features die hebben dependencies aan elkaar, dus als jij een bepaalde feature kiest dan kan dat zijn dat hij in implicatie heeft voor een andere feature dus of hij wel of niet kan, of dat hij juist heel nodig.

### Manufacturing Engineer

Dan heb je het over features als onderdeel van een hardware product?

### Interviewer

Ja precies. Maar een feature kan ook een document zijn. Een feature kan ook equipment zijn. Een feature kan een bom zijn, een feature kan ook een component zijn. Er is een feature linkje eigenlijk aan data die al op zichzelf bestaat in het PLM PDM systeem, dus aan de ene kant heb je die link naar PDM / PLM en aan de andere kant heb je die de configuratie regels waarin je eigenlijk aangeeft. Dit kan wel met elkaar en dit kan niet met elkaar of dit heeft elkaar nodig. Het is een hele simpele methode. Je hoeft er niet veel voor te kennen. Het is vrij grafisch, maar het kan ook allemaal omgezet worden in tabellen, zodat je het ook op queryen. et cetera et cetera. Bijvoorbeeld, je hebt een auto, die is een engine car and comfort functions. Nou een engine dan moet je een keuze uit maken dat zijn alternatieven. Je kunt er geen twee hebben en wij comfort kunt comfort functions kun je bijvoorbeeld die zijn optioneel, maar je kunt ook kiezen om of airconditioning te hebben, of eigenlijk heel simpel. Wat je dan kan doen is je keuzes in gaan maken, maar dat is nog niet genoeg om te zeggen, hé, Dit is een feasible product, dit kunnen wij maken, Dit is logisch. Daarvoor zul je ook regels moeten toevoegen. Een elektrische auto kan niet en navigatie en airconditioning. Super simpel kun je dus ook omzetten in tabelletjes, zodat het mooi inzichtelijk wordt of beter inzichtelijk wordt. Wat je ook kunt doen en dat is is ook onderzocht. Is het modulair maken van dat soort dingen. Dus op het moment dat jij een navigatiesysteem hebt die bestaat uit, ja, daar heb je een feature model voor gecreëerd die heeft regels op zichzelf, dan kun je die ook hergebruiken in nieuwe feature modellen. Dus stel we maken nu een auto en dat is autotype 1 dan kun je daarvoor kiezen: Ik zet dat feature model eigenlijk in het feature model van de auto en dan heb ik meteen toegang tot die features set en ook die regels die daarbij. En wat je ook nog meteen kunt doen is regels bedenken die specifiek gelden voor dat ene type auto. Dus als jij een cabriolet hebt en je hebt een stationwagen en allebei een navigatiesysteem kun je zo'n feature moeten hergebruiken in allebei de auto's. Traceability, dus dat is eigenlijk het stukje enerzijds ga je linken aan PDM PLM of productdata, dus dat dat al bestaat daarvoor. Daardoor zorg je er ook voor dat een keuze van een feature ook meteen bepaalt hoe jouw product eruit gaat zien in je productstructuur, maar ook je document. Natuur en dat zijn twee slings dus die die Trees je eigenlijk naar productdata andere kant van het tracé is. Even kijken hoe eerst dit vertellen op het moment dat jij gaat Configureren ga jij ook keuzes maken tot elke feature gekozen is of juist uitgesloten is. Dus door een requir kun je bijvoorbeeld zeggen van hé, als die gekozen is moet die andere ook gekozen worden, dus dan kies je er een een exclude sluit de ander uit, dus op het moment dat dat allemaal gebeurd is. Heb je eigenlijk een configuratie en dan kun je door middel van al die Trees slings kun je eigenlijk die configuratie maken in in je pee m systeem. En die als zijnde een instantie opslaan om om daarna te met effect zilver te. Ik heb. Daarbij komt dat je een tussen aanhalingstekens, makkelijk en overzichtelijke manier hebt om te kijken. Welke feature zit nou, in welke variant? En dat kun je aan de ene kant doen nog een perspectief te pakken van hé, Ik heb mijn type één auto cabriolet. Die heeft allemaal een comfort functions daarvan. Variant A B hebben Navigation System met de software. Die is allebei snel is, maar de ene heeft een standaard computer aan de andere in een executive. Even kijken ja, dus op deze manier kun je eigenlijk inzicht krijgen van hè; welke feature set zit er in mijn type 1 auto? Anderzijds kun je dus ook kijken, mijn navigatiesysteem is dus een imposed / modular model en is gebruikt in meerdere feature modellen. In welke feature modellen zit hij nog meer? Je kan kijken, kan ik die in car type 1, maar ook car type twee dus op die manier kun je kijken, best wel als een impact analyse creëren. Als ik iets verander in mijn in dit geval configurable product navigatiesysteem, waar zit dat nog meer in en waar moet ik dan op letten. Voor zover vragen trouwens?

### Manufacturing Engineer

Nee, dit is allemaal duidelijk.

### Interviewer

Om het wat ja wat inbeelden te maken, heb ik een een klein modelletje of een demonstratie laten zien. Dus eigenlijk werk je gewoon vanuit vanuit PLM met een link naar een configurator module. Dat kan hier een tabje zijn. Dat kan iets anders zijn, maar het is een PN dat gemaakt is voor configurable variabele producten waaraan dus een configurator gekoppeld is. In mijn mening moet dat niet bij elk product zijn. Ik denk dat dat iets is dat je aan uit kan zetten of op een bepaalde manier moet inregelen. Wil je daar toegang tot hebben. Nou, dan kom je eigenlijk in dit scherm waarin je aan de ene kant je feature model kan aanmaken. Aan de andere kant, je dependency ziet en linksboven zie je varianten. Op die manier kun je features gaan toevoegen en dan kun je hem eigenlijk linken. Dan kun je hem goed zien en dan kun je eigenlijk gaan linken aan de productdata die al bestaat. Dat doe je aan de hand van van je PNs. Je zegt ik wil de bil of material opnemen of meenemen van dit PN. Die heb ik al klaargezet als een building block. Die wil ik in zijn geheel meenemen.

### Manufacturing Engineer

Dus dit is een feature?

### Interviewer

Feature ja, Dit is een feature. Je bent eigenlijk een feature aan het opbouwen. Ik wil nog eentje meenemen. Ik wil de documenten meenemen van hetzelfde PN, want dat is mijn building blok. Maar ik wilde documenten meenemen en of ik documenten meenemen. Die feature geef je naam een descriptie on, maar ook belangrijk is om hem een rationaal mee te geven, dus dat je meegeven van deze feature staat hiervoor. Dus bijvoorbeeld deze building block en je moet hem gebruiken op dit moment als je dit wil implementeren, zodat niet alleen de mensen die je de feature model opgezet hebben, het snappen, maar ook de mensen die het daarna bijvoorbeeld gebruiken. Laten we zeggen in sales aan de voorkant of bijvoorbeeld of aan service aan de achterkant.

### Manufacturing Engineer

Ja, Natuurlijk.

Dus nou heb je voor dit product gekozen dat er deze twee bill of material features in zitten en die documenten en die equipment? Ja, dat is een feature. Ja, Misschien kom je er nog op terug, Maar het eerste wat mij zo eventjes naar boven komt, is dat eigenlijk elke PNs binnen een bill of material kan uiteindelijk een feature zijn.

Dus stel je dan dit model voor dat je al van tevoren weet welke groepen van bill of materiaal items je eigenlijk bij elkaar wil benoemen tot een feature of?

### Interviewer

Hoe bedoel je precies?

### Manufacturing Engineer

Want nou ja. Op PCBS heb je bijvoorbeeld als je over de varianten gaat van producten die wij maken, dan heb je eigenlijk een PCB plank. Daar zitten heel veel componenten op en dan zitten er op die PCB plank zit er een aantal componenten die de variant bepalen, dus bijvoorbeeld een snellere proces over langzamere processor en maar dat die processor is een refdes of een bom item instance, wat we dan noemen binnen die Bill of materials dus. Nou lijkt het erop alsof je dan die processor die snel of die lange processor dat je die als een losse feature je hier wil hebben, dus dat je dan eigenlijk alleen maar bill of material waar alleen maar een processor in gaat zitten en een bill of material waar alle andere zaken in zit. Zo bedoel je het dan op te zetten?

### Interviewer

Ik denk dat dit het voorbeeld is wat ik met de IMX8 wil laten zien, dat is in principe zo'n voorbeeld. Maar hoe ik het eigenlijk bedoel is als je een building block klaar zet en je neemt de bill of Material over, dan neem je eigenlijk de volledige assembled Bill of Materials over die dat PN op dat moment heeft. zeg maar dat 12 Cijferige PN heeft, dus je neemt ook de instances over, dus ook de refdessen die er allemaal op zit. Op het moment dat je een component toevoegt, voeg je eigenlijk ook een bill of materiaal van een component en dat is het component zelf, die heeft geen instance, dus die feature zul je een instance mee moeten geven. En op het moment dat jij een keuze moet mag gaan maken tussen twee features, dus als het alternatief zijn voor mekaar, dan mogen die dezelfde instances hebben.

### Manufacturing Engineer

Ja dat snap.

### Interviewer

Als je niet uitsluit, dan moeten die verschillende instances.

### Manufacturing Engineer

Dat moet vanuit het product zelf al ja, misschien komen er straks op.

Ik vraag me af of je nu. Eis je nu al vooraf als je begint met het maken van een product dat je eigenlijk al.. Hoe weet ik welke componenten er onder dezelfde bom vallen? Want eigenlijk heb je nu gezegd, van je definieert nu een feature enje kunt in een later stadium kun je niet meer zeggen, Oh, wacht even deze feature, die bestaat eigenlijk uit 10 componenten waarvan ik dacht dat die allemaal van toepassing zijn voor of een snelle processor of een langzame processor. Maar nou kom ik erachter van ja, wacht even maar een snelle processor hebben we ook nog met een combinatie met memory te maken, dus eigenlijk die die die groep van componenten die ik eerst bepaald had om die horen bij elkaar als een de feature dat zijn eigenlijk twee features.

### Interviewer

Dan moet je die eigenlijk hier uithalen.

### Manufacturing Engineer

Dus ja, precies, die moet je eruit kunnen halen.

### Interviewer

Je feature model valt absoluut onder version management. Dus jouw configuratie en de instances die je eruit maakt die leidde terug naar een bepaalde versie van jouw feature mode. Dat feature model heeft een structuur en in die structuur heb je gegeven een feature heeft al deze componenten Als je die gaat aanpassen, dan moet je ook een nieuwe release doen van je feature model waarin je dus nieuwe instances van producten gaat doen.

### Manufacturing Engineer

Ja, dat snap ik.

Je hebt eigenlijk twee uitersten aan granulariteit, je zegt van Ik heb de complete bom is een feature, dan heb je helemaal niks, heb je geen mogelijkheden. Of je kunt het andere uiterste is van elke refdes deze is een aparte feature. In jouw tool moet je eigenlijk, dus Ik had.

Ik had hier niet de features van Bill of Material verwacht, maar eigenlijk dat je de refdes aanklikt ontzettend veel, maar goed.

### Interviewer

Om dat te voorkomen denk ik, inderdaad wat je zegt, je hebt het allergrootste is dat je eigenlijk? Ja, je hebt gigantische lijsten met dit is een feature en dit is de andere feature.

### Manufacturing Engineer

Ja misschien wel.

### Interviewer

Maar dat doen ze nu ook. Ze maken nu al building blocks. Die zetten ze al klaar in PDM of PLM. Als het ware en eigenlijk moet je een beetje zien van een feature is een soort building blok, dus je creëert eigenlijk meerdere features en daar hang je allerlei verschillende dingen onder, daar maak je een bouwblokjes van. Op die manier link je ze dus als alternatief het ware aan als alternatief voor een nano linkjes ze aan jouw product. Dus je maakt meerdere van die features. Dat kan 1 component zijn en dan heb je het dus over een refdes die je invult of niet invult of anders moet invullen, maar het kan ook een hele lijst zijn, dus een IMX8 is gewoon een hele lijst van laten we zeggen, 900 componentes of een aantal 100 componentes die op een PCB zitten.

### Manufacturing Engineer

Ja precies. Je kunt dan geen meer, als je als je deze definitie heeft gemaakt van die IMX8. Dan kun je niet meer in een later stadium binnen die IMX8 een nieuwe feature definiëren, waardoor je weer een andere variant krijgt.

### Interviewer

Heb je het dan over ik wil die IMX8 opsplitsen in twee delen? 

### Manufacturing Engineer

Daar komt er wel op neer ja.Want dat het dat in ieder geval de meest logische use cases die hebben, want als ze beginnen met een product, dan weet je vaak nog niet welke variant je wil maken, want vaak is het in in de hardware mogelijk om veel meer varianten te maken dan waar de klant behoefte aan hebt. We gaan niet al beginnen met zeg maar van oké, we kunnen al deze varianten maken, hè? Je begint met van oké, we denken alleen maar dat we een snelle en langzame processor nodig hebben. Maar vervolgens zegt de klant van ja, wacht even die snelle die langzaam processen. Die hebben nu allebei een terabyte aan geheugen, Maar ik wil die snelle processor wil ik de keuze maken tussen een terabyte of 4 Terra. Ja en die andere, wil ik dat dus niet doen.

### Interviewer

Ik ga hem even doorklikken. Je kunt hier splitsen, dus je kunt eindelijk gaan zeggen, hè, ik ben erachter gekomen, je hebt een imx8m en je hebt een imx8m plus. Die hebben volgens mij ook. Dan haal je of dan zorg je eigenlijk voor dat net zoals bij Mini Nano dat je hier ook een keuze moet maken en daar hang je dan eigenlijk hele grote lijst hetzelfde aan e alles wat anders is, hang je daar dan anders aan?

### Manufacturing Engineer

Precies ja.

### Interviewer

Ik ga hem even heel stuk verder klikken, dan zie je een beetje hoe ik het op wil bouwen, dus je hebt een deIMX 8. Die heeft een Ram, micro controller en een memory. En op het moment dat jij net aangaf van hé, Ik wil 4gb sessie hierbij 64, maar ik wil ook nog de 128 dan vroeg je die hier, dan is dat in principe een componentje, dan voeg je hieruit toe van memory als optie.

### Manufacturing Engineer

Ja ja ja.

### Interviewer

Het enige wat je hoeft te doen, dus je maakt ook een nieuwe feature aan en die hang je onder memory dus op dat moment dat je moet kiezen en memory moet erin zitten tussen een memory module heb je nu ineens ook de keus om daar een nieuwe 128.

### Manufacturing Engineer

Ja, maar dat is niet maar wat ik bedoelde, want in dit geval is het is het heel erg triviaal, want je hebt al een aantal varianten binnen die feature. Wat met name interesseert is, hoe ga je daarmee om straks? Als je nog geen feature hebt gedefinieerd en je komt erachter van, hé, wacht even, deze commonality moet ik op gaan splitsen, dus in dit geval die mini, die moet ik in een keer op gaan splitsen tussen een mini met weet ik veel, een connector en een mini met twee usb connectoren. Noem maar even. 

### Interviewer

Wat je dan in dit geval wat je dan zou doen, heb je die feature en wat je daaruit haalt is de connectoren. Die trek je er dan uit. Je moet zien is alles dat moet zeg maar alles wat niet gesplitst is communal.

### Manufacturing Engineer

Ja precies, Je moet het wel uittrekken, ja. Ja precies.

### Interviewer

En alles dat je daar naar onder uitsplitsen, kun je nog steeds verder uitsplitsen. Dan op het moment dat je die communality wil die eigenlijk zo hoog mogelijk in het in de tree hebben. Omdat dan bepaalt, dan zie je heel goed. Van oké, dit is communality en dit dus variabel. En als ik hier een veranderingen maak, dan betekent dat, dat op die al die dingen effect heeft. Veranderingen kun je alleen doen als die nog niet gereleased is. Dus je hebt een released versie van de configurator van een feature model.

### Manufacturing Engineer

Ja ja. Is dat zo, dus stel nu hè dat ik deze configuratie heb met die mini hier. Ik maak daar een variant van, dus die is gereleased. En vervolgens wil ik in een later stadium kom ik er in een keer achter van. Oké, We willen die mini, willen we een onderverdelen in een mini met een USB poort aan de mini met twee usb poorten moet je USB poort, moet je uit die mini trekken hè? Je moet daar een nieuwe feature van maken, maar die variant die we al gereleased hadden die de mini had met die nog oude twee poort die moet die moet dus geupdate worden, dus dat die zorgt dat die wijst naar de juiste features, want je wil wel dat die wijst uiteindelijk de laatste versie van de feature, want stel dat ik die feature van de toekomst update omdat er replacement moet komen voor dat voor die USB poort. Moet je ook in die ook al in de released variant moet die aangepast worden, dus je moet ook met terugwerkende kracht, zeg maar. Het opsplitsen van features moet je ook aan de bestaande set van varianten moet je die ook zeg maar aanpassen.

Dus die oude variant die wees voorheen alleen maar naar mini, maar als je deze opgesplitst heeft, dan wijst hij naar mini met de variant met een usb connector gaan.

### Interviewer

Dus eigenlijk wil je zeggen dat als jij op het moment dat jij hem dus opsplitst en je verandert hem, wil jij eigenlijk dat die update naar de laatste versie van die configuratie? Of in die feature model?

### Manufacturing Engineer

Alle gereleaset de varianten. Die moeten dan gebruik maken van de nieuwe gedefinieerde feature set. Ja, dat is heel essentieel. Anders breek je namelijk daar jouw onderhoudbaarheid en compatibility, wan is wat je niet wil.

### Interviewer

Want in mijn ogen linkt die eigenlijk naar het naar het feature model waar die mee gemaakt is.

### Manufacturing Engineer

Ja, maar dan oké, dat kan, maar als je dan die Usb Connector update omdat, hij is absoluut en je moet een nieuwe connector hebben, dan moet je hem dus updaten in de nieuwe featuret set waarin die mini is opgesplitst in 1 usb connector, en usb connector, twee. Je moet hem ook nog updaten In de feature waarbij die niet zo, dus dat wil je niet. Je sleept continu die historie mee als jij nieuwe features definieert en dat moet ook denk ik, want anders heeft het geen zin meer anders dan je afscheid aan het nemen van jouw voorheen gedefinieerde varianten, want die kun je daar niet meer updaten.

### Interviewer

Ja precies.

### Manufacturing Engineer

Dat is het moeilijke denk ik zon varianten model groeit. Als je een variant model vooraf kan opzetten zoals die auto en je denkt er van tevoren over na. Ik wil u groene auto een blauwe auto en mijn sportstoelen, meer niet. Als je er van tevoren over nadenkt en je definieert al die al die features, dan is het relatief makkelijk. Maar het probleem is nou juist als je gaandeweg de jaren op een gegeven moment denkt van ja, wacht even, we gaan voortborduren op dit product portfolio en we gaan nieuwe varianten creëren, dus we moeten nu Features opsplitsen, dan moeten al die oude varianten die moeten her gedefinieerd worden. Die moet in één keer nieuwe f eature definitie , maar die moeten qua functionaliteiten 100% hetzelfde zijn. Alleen, ze moeten wel een update krijgen. Wat ja naar welke feature en welke variant van de features zijn wijzen?

### Interviewer

De 64 gigabyte kan niet meer wat gebeurt dan, want dan kan je hem niet meer een op een tussen aanhalingstekens linken naar een oud feature model.

### Manufacturing Engineer

Ja, maar dan krijg je gewoon het op obselesence proces wat je dan ingaat? En dan kun je dat product sowieso niet meer maken, dus dat product met die gedefinieerde variant en die featureset.

Die moet dan sowieso geupdate worden, want die ene feature niet bestaat gewoon niet meer. Het featuren model moet nog wel compleet blijven, alleen kom je dan uiteindelijk achter als je helemaal afdaalt van hè deze feature, die is niet meer leverbaar, dus ik mag die die link die bestaat nog wel, maar dan kom je op een op een dood spoor en dan moet je zeggen van oké die 64 megabyte gigabyte variant, die kan niet meer leveren, dan moet die feature of dan moet die variant in een verwijzen naar die 128 gigabyte, dus het model moet je gewoon updaten. Alleen je kunt dat product met dat model niet meer releasen, dus dan moet je eerst een nieuwe feature toegewezen krijgen.

### Interviewer

Ja precies.

### Manufacturing Engineer

Dus ja,ik denk dat het dynamisch update van het model. Dat is het lastige, denk ik van het verhaal.

### Interviewer

Klopt en dat klopt zeker. Het komt al eigenlijk alles wat ik gekeken heb, komt uit software productlijnen en dat is het inderdaad. Zij benoemen ook heel vaak: hoe ga ik nou van tevoren, bijvoorbeeld op het denken wat communaal is en wat variabele? Dat is een heel groot deel van van die approaches en ik snap daarmee met je bedoelt.

### Manufacturing Engineer

Ja, ja, en dat wil je idealiter ook, maar de praktijk is veel weerbarstiger.

### Interviewer

Tegenwoordig met een aantal of de of the shelf producten en met catalogussen gebeurt dit wel meer binnen PT.

### Manufacturing Engineer

Nou ja klopt en het heeft er met name mee te maken hoe een project ingestoken wordt en IMX is een mooi voorbeeld, want die is van tevoren al ingestoken met het idee van: we willen hier een building block van maken en we willen al een bepaalde hoeveelheid varianten maken, dus daar is aan het begin al over nagedacht welke varianten allemaal krijgen, dus welke features daar eruit moeten worden getrokken. Maar ook daar kun je niet voorkomen dat er gaandeweg dat er nieuwe features ontstaan, want er wordt meer memory gemaakt. Er wordt op een gegeven moment wat ik net zeg. We dachten voorheen dat er altijd twee USB poorten gaan maken, maar we willen nu toch een USB poorten en twee USB poorten gaan uitleveren en wat nog veel lastiger is, is dat eigenlijk idealiter voor PT, maar dat is een natte droom. Je moet anders vertellen. Je weet dat we nu binnen PT eigenlijk geen varianten beheer hebben, niet op de op de manier zoals we willen, dus we creëren eigenlijk elke keer kopieën en ik moet al die kopieën gaan bijhouden. Als bij een common element moeten aanpassen, moeten al die kopieën al die varianten moeten altijd dat dat probleem aanpakken, dus ook als er een component obsolete wordt, moeten we dan al die varianten aanpakken. Het zou heel mooi zijn als wij nu nieuwe variant systemen hebben en dat wil ik zeggen, oké, denk er van tevoren goed over na. Dit is de featureset en gaan met de banaan, maar eigenlijk is het ultieme is dat wij een bestaan product set kunnen pakken. Van oké, we hebben van deze productset hebben we 5 kopieën, dus 5 varianten en die tool. Die moet dus eigenlijk al die varianten gaan analyseren en dan zeggen, oké, maar dit is de communality en dit zijn de features. Dat is uiteindelijk wat je wil bereiken.

### Interviewer

En nog eentje verder zou zijn dus: ik zie dat ze overal hetzelfde zijn. Ik update mijn feature model. Daar zitten twee andere componentes in, ik druk op update en alle 5 worden ze geupdate als het kan en als ze ach misschien accepteren dat dat moet in ieder geval dat. Dat het op die manier werkt. Ik kom er ook zo op. Als je dit hebt, dus je hebt je feature mee opgebouwd kun je dus die dependencies gaan op opstellen, dus in dit geval heeft een quad 1 punt 8 heeft 8 gigabyte aan memory nodig. Anderzijds heeft een 5 12 Ik denk dat allemaal wel voor zich spreekt. En op het moment dat jij zeg maar je featuret nou echt gereleased hebt, kun jij gaan kiezen, dus gaan configureren en in eerste instantie is dat gewoon configuratie door te zeggen hé, ik wil gaan configureren en dan kiest hij meteen alles wat community heeft. Dus alles wat sowieso moet. In dit geval kun je nog kiezen uit een mini en nano en de rest. Dan ga je rustig kiezen. Een mini sluit meteen de nano uit een nano en sluit meteen de mini uit. Als je dan zegt hé ik wil 512 met 1.8 gigabyte memory. Dat die zegt: let op, dan moet jij dus deze kiezen, want dat staat erin en op het moment dat ik hier de actie gebruikt kan kiezen. Ik heb nog geen ram gekozen, dan zegt hij, hè, let op je mag 1.8 Quad sowieso niet kiezen, dus op die manier heb je aan de ene kant heb je de regels binnen je feature model van dit mag niet samen en aan de andere kant linkt hij dus naar de data die eigenlijk gewoon opgeslagen in een in in PDM PLM. Dus het bezit geen data. Ik denk dat dat belangrijk is van het idee. Het enige wat het doet is een manier geven om een configuratie te doen en om die varianten te managen en inzicht te krijgen.

### Manufacturing Engineer

Ja eigenlijk die rules toe te passen en jouw configuratie vast te leggen. Zon model spreekt heel erg tot de verbeelding spreekt en ook een complex product relatief makkelijk laat lijken. Het lijkt op een gegeven moment een leuke uitdaging om het grafisch weer te geven, wat wel heel erg krachtig is overigens.

### Interviewer

Juist precies ja ik en Leon hadden het er ook even over; implementatie hiervan een tweede, maar goed.

### Manufacturing Engineer

Nou, volgens mij doet windchill en zo doe dit volgens mij met tabellen, maar dat weet ik niet zeker.

### Interviewer

In principe kan alles omgezet worden in tabel zeg maar deze regels en zijn tabellen feature modellen kunnen omgezet worden in tabellen, dus je kunt het ook heel niet grafisch, maar juist omdat het inzicht geeft en ik moet eerlijk toegeven, je hebt gelijk als een product echt complex wordt, dan krijg je een gigantisch feature model waar je dan voor kan kiezen is om dat dus weer modulair te maken. Dus hoe straks te zien in; je hebt een klein stukje en daar maak je een feature model van. Daar zet je alles van op die update je en dat gebruik je in.

### Interviewer

Dan kun je hem publishen dus vanuit een gereleased versie van de feature model, dus dan krijg je een overzicht, kun je met naam geven. description, je ziet wat er allemaal in zit. Overigens zie je hier ook welke featureen wat bezit, dus deze su- assemblies, componenten en documenten, deze alleen documenten, die is alleen componenten, etcetera, etcetera eigenlijk. Krijg je een inzicht van hé, dit is wat je wil gaan releasen. En dan publish je hem en dan krijg je hier links eigenlijk een overzicht van dit zijn allemaal varianten die gemaakt zijn met dit feature model en dan gaan kijken. In mijn Q 1 6 zitten deze features allemaal en die ziet er zo op deze manier uit visueel. anderzijds als je dan gaat kijken van hé, hoe ziet nou mijn hele productlijn eruit of hoe ziet nou eigenlijk allemaal varianten eruit? Krijg je eigenlijk een overzicht van dit zijn mijn features, dit zijn varianten. Mocht je dan natuurlijk meer hebben, kun je ervoor kiezen om ons allemaal te laten zien of gedeelte. Ik denk dat allemaal een beetje implementatie is. IMX8 hebben ze allemaal, dus die feature hebben ze allemaal. Ik heb twee Mini's, twee nanos, dram, memory, micro hebben ze allemaal, dus dat zijn al die documenten. Maar ik gebruik mijn 4gb, gebruik ik überhaupt niet en aan de andere kant mijn inderdaad mijn Q1.8 ook helemaal niet. Moet ik hem nog gebruiken? Moet ik hem nog ondersteunen? Moet ik dan nog iets voor gaan doen? Dus op die manier kun je heel erg inzicht krijgen en ook de impactanalyse. Als ik een bestand verander in mijn in mijn Dram, mijn test. Moet dat voor alle varianten gebeuren, dus op deze manier kun je vanuit die dat feature model aan de hand van je features bepalen hoe een update impact heeft op al jouw klanten of varianten.

### Manufacturing Engineer

Ja precies.

Waarom maak je nou deze rode rood? Omdat hij geen enkele groen heeft?

### Interviewer

Ja. Die anderen zijn grijs, omdat het eigenlijk een over een verzameling ging?

### Manufacturing Engineer

Er is een uitgevouwd? Ja, precies.

### Interviewer

Dat is hoe ik het nu voor me zie, of in ieder geval welke relatie er is een literatuur is. Ben ik ermee eens ingegeven door natuurlijk software en productlijnen en daar ideeën van. Maar ik denk dat het ideeën zijn die tot op zekere hoogte en met goede uitwerking ook relevant kunnen zijn voor hier.

### Manufacturing Engineer

Ja, ik denk dat zeker. Dit geeft een mooi overzicht welke varianten er bestaan en wat daarin zit. Maar ja, ik vind wat je net al zegt van dit is, zeg maar een soort configurator waar je naartoe moet en ik weet niet of je verhaal nog verder gaat? Dat is dus waarschijnlijk ook buiten jouw scope. Ik ben nog heel erg benieuwd, ga eens een paar stappen terug waar je op gegeven moment de feature.

### Interviewer

Dit bedoel je ongeveer, of?

### Manufacturing Engineer

Ja hier deze zeg maar, als je deze dan genereert feature of een variant configureert en dan genereren moet ik even kijken, dan krijg je een moment dat je die boom gaat samenstellen.

Ja, en als je nou hier zeg, maar een stapje verder gaat en je genereert dan ja, precies je kiest wat dingen.

### Interviewer

Denken te doen zo?

### Manufacturing Engineer

Ja ja, het bom als je klikt. Je en open, ja, dus, dus hier heb je eigenlijk aangegeven dat, ik weet niet of dat een voorbeeldje is of direct map op dit verhaal. Ik had eigenlijk verwacht dat je in ieder geval zoveel boms hier hebt als je features hebt.

### Interviewer

Nee, dat hoeft niet, want een feature kan ook bestaan uit alleen maar documenten of alleen maar componenten.

### Manufacturing Engineer

Ja oké, maar in dit in dit geval zijn het allemaal elektronische onderdelen, dus ik zou je verwachten dat je zoveel boms krijgt.

Hoe gaat het dan? Waar we het net over hebben gehad hebben, stel dat je zo'n nano uiteindelijk gaat opsplitsen dan die nano was voorheen een bom, dus je bestaat in PLM daar was een bom met een PN. Maar hoe willen we dat dan uiteindelijk gaan ondersteunen dat als we dat gaan opsplitsen dat dat ene PN in in PLM moet dan opgesplitst worden, dat wordt opgebroken in twee nieuwe ofzo? Want je moet het uiteindelijk eigenlijk moet je dit gaan mappen op de hoe het in PLM staat. In PLM heb je eigenlijk gewoon. Je hebt een PN en daar vallen gewoon alle componenten onder.

### Interviewer

Ja en in plaats van om dan een een volledig ander PN aan te maken die alles hetzelfde heeft, behalve het twee dingetjes, haal je daar eigenlijk de variabiliteit uit.

### Manufacturing Engineer

Ja precies.

### Interviewer

En maak je, in dit geval zou dat dan zijna je hem dus echt gaat opsplitsen, maak je daar twee PNs van eentje die dus de variabiliteit heeft aan de ene kant aan de andere kant en dan link je die direct weer.

### Manufacturing Engineer

Maar dan had ik hier geen PNS verwacht. Ik had hier een soort, ja, hoe moet het nou zeggen? Want in PN binnen PT is altijd een fysiek component of een lijst van fysieke vast gedefinieerde componenten, afgezien van alternatieven waar we het in het waar we het over gehad hebben. Is dat in principe als je een PN hebt, is dit gewoon 100%, zeker de bom. Als je dit nu gaat, gaat mappen op die op structuur. Dan krijg je een product, maar het product is eigenlijk een variant en onder die variant hangen dus je zegt nu eigenlijk verschillende boms? Daar hangen de verschillende groepjes van componenten, maar dat groepje, dat is niet een PN, dat is tenminste de oude definitie van het woord, want dat is die kan namelijk veranderen, want als je op gegeven moment een feature gaat opsplitsen, dan is dat ene groepje is in één keer van ja wacht even maar nou, nou hebben we twee nieuwe groepjes gemaakt, klopt dus.

### Interviewer

Nee klopt ja.

### Manufacturing Engineer

Ik denk dat dit verhaal wel kan werken, maar dan moet je niet praten over bill of material , maar Je moet je praten over bill of materiaal subgroepen of iets dergelijks.

### Interviewer

Eigenlijk moet je het zien als een beetje een building block en een building block wordt nu gecreëerd door een PN aan te maken en daar een bom onder te hangen. Dat heb ik proberen aan te houden omdat dat letterlijk, stel je zou dit nu willen doen, kan je dit tussen aanhalingstekens direct implementeren op de bestaande structuur.

### Manufacturing EngineerMisschien kan het ook wel zo hoor.

### InterviewerToekomst zul je inderdaad toe moeten naar een soort waarin je eigenlijk in plaats van een part heeft een PN hebt, heb je eigenlijk een feature groep en in die feature, wat je dan doet, en dat is misschien toekomstmuziek, het liefste zou je hier ook je volledige configuratie in doen? Dus dat je zegt, Hé, mijn memory zijn deze PNs hebben deze refdes en als je die kiest, kies je dit deze refdes met deze PN. En, die staat hoeft helemaal niet PLM als aparte PN.

### Manufacturing Engineer

Want nu zit ik mezelf, spreek ik mezelf tegen. Kijk in in PLM hebben we nu ook PNS voor bijvoorbeeld een groepje documenten. Ja, dat doen we ook en we gebruiken PNS voor virtuele subassamblies, omdat we daar alle building blocks bijvoorbeeld onder hangen is. Dan is alleen maar een folder geworden, maar goed, omdat die structuur zo werkt. Dus in dat opzicht kun je nog steeds dit doen. Dat is de grote moeilijkheid, zit hem straks in de communicatie tussen deze tool en PLM, zeg maar Als je nieuwe variant creëert, dan moet je eigenlijk die structuur opbouwen in PLM. En ook de andere kant op waar we het net over hebben gehad. Als jij bepaalde structuren niet in PLM of sorry bepaalde varianten al gedefinieerd in het PLM. Wil je eigenlijk met deze tool analyseren en die wil je daarmee op gaan bouwen? Oké, we hebben nu deze varianten, willen we dan die structuur in PLM hem ombouwen, zodat die matcht met hoe je het hier definieert of zeg je van nee, we laten het staan zoals het was en we doen elke keer als wij nieuwe variant gaan creëren, analyseren we die huidige structuur, trekken we daar de communalities uit, maken we nieuwe structuur en we exploiteren eigenlijk de complete variant structuur als een compleet nieuw PN, dan blijven we eigenlijk de oude zooi houden in PLM, maar dat hebben we alleen maar het overzicht via deze tool.

### Interviewer

Misschien voor legacy en voor de oude PNs dat dat misschien het beste werken Als je het kunt analyseren en kunt zeggen, hé, ik heb het geanalyseerd. Dit zijn je varianten. Dat betekent dat mijn feature model er zo uit gaat zien met dit common. Dit zijn keuzes.

### Manufacturing Engineer

Of je gaat zien migreren, dat kan. Je moet altijd kunnen migreren, want als je nieuwe variant creëert, dan doe je eigenlijk precies hetzelfde. Waar we net over hebben hadden, hè? Stel, je hebt in PLM heb jij 3 varianten en we gaan nu die die nano gaan we opsplitsen in twee features. Wat ga je dan doen met de huidige PN In PLM? Want je zou kunnen zeggen van die raak ik niet aan, want op zich die bom is nog steeds compleet, maar als je dan vervolgens een update gaat maken in een van die nieuwe features, dus die ene usb connector moet vervangen worden, dan moet je er wel iets gaan doen. Dus ga je, dan ga je dan twee zaken bijhouden. Je gaat hem updaten in de varianten die nog steeds wijzen naar de oude feature waarin die nieuws opgesplitst. En je gaat hem ook updaten in de nieuwe, dan heb je hetzelfde probleem, hè, dan moet je weer in twee verschillende dingen updaten, ja dus en daar zit hem nou juist de moeilijkheid. Het is geen onoverkomelijk probleem, maar het is wel een keuze van ga je de oude troep conformeren en eigenlijk migreren naar een nieuwe structuur en ga je nieuwe structuur netjes maken en handelen. Of wil je daar continu zeg maar ja, allebei kunnen behandelen?

### Interviewer

Ja, ik vind dit ook heel moeilijk, want ik heb hier een hele lange tijd op gepiekerd en gekeken van wat wil je nou doen, hoe kan je dit doen ook goed doen?

### Manufacturing Engineer

Dat is ook lastig hoor.

### Interviewer

Het liefste wat je zou willen is in PLM de mogelijkheid hebben inderdaad om in plaats van een PN een groep aan te maken.

### Manufacturing Engineer

Dat kunnen we vrij makkelijk maken en dan kan inderdaad deze tool kan op gegeven moment componenten gaan groeperen en dat wil eigenlijk zeggen, jouw hele boom verandert helemaal niks aan. Het enige wat je doet is componentes groeperen en als we op hetzelfde level blijven, dan denk ik dat je ook geen problemen hebt. Maar ik kan me voorstellen, maar dat is eventjes een gevoel op dit moment. Ik kan me voorstellen dat je ook nog zelf componenten van niveau moet verwisselen en dan ga je natuurlijk wel een gevaarlijk moment krijgen. Dat je in een subassambly er in moet hangen of juist naar boven wil trekken van om jouw varianten te ondersteunen.

### Interviewer
Maar in die zin als je dan iets aanpast, dan kun je ook kijken naar, in welke feature komt hij dan terecht of in welke feature zou hij dan terecht moeten komen? Dus als jij hier twee nieuwe features onder mini aan moet maken, dan moet jij bedenken hè? Deze features die ga ik splitsen omdat dit en dit anders is. Dat betekent dat ik in PLM mijn mini moet aanpassen, daar moeten die twee dingen uitgehaald worden en die moeten op een nieuwe manier in PLM komen. Als je dan apart twee PNS aanmaakt, die kunnen willekeurig een PLM staan. Die hebben dan gewoon een productnummer en dan link je die feature gewoon direct weer aan dat productnummer. En dan zeg jij hè, neem deze bom of neem dit component of de document maakt allemaal niet zoveel uit. Neem deze over in die feature.

### Manufacturing Engineer

Of je laat de structuur en PLM voor wat die is en je moet met die tool elke keer In de bestaande structuur je nieuwe varianten definiëren. Dus dan blijf je in PLM gewoon 5 kopieën hebben voor elke variant een kopie. Alleen het managen van die 5 kopieën, dat doe je op een andere manier, maar dat wil zeggen dat je elke feature in PLM via deze tool moet laten lopen, want als je op gegeven in een building blok iets wil aanpassen, maar dat building block bestaat nog niet in PLM. Dat is daar nog zeg dat component zit in al die 5 varianten. Ja, hoe ga je dat dan managen? Dan moet je deze tool dat allemaal laten managen en voor de producten waar het dan niet zo is. Daar doe je het dan in PLM, dan ben je eigenlijk je hele tool hele PLM, hierin opnieuw aan het bouwen.

Als je er ineens uit standaard product een nieuwe variant bijkrijg, ja, dan moet je in één keer om. Dan moet je structuur gaan passen, dus het is wel heel belangrijk dat je die grens en die keuze tussen een traditioneel product, wat maar een variant heeft en meerdere varianten dat dat die grens niet zo hard is.

Dat is heel moeilijk en ik heb ook nog geen idee over hoe je dat moet doen. Dat is de hele uitdaging. Dat is de crux.

### Interviewer

Daar precies heb ik ook niet 1 2 3 een antwoord op.

### Manufacturing Engineer

Ik weet eerlijk gezegd niet hoe andere tools dat doen, hoor met die varianten maar ja. Als je die keuze makkelijk maakt en je zegt van oké. Je moet gewoon altijd varianten opbouwen in PLM met behulp van deze tool en dan moet je gewoon bestaande producten als je daar varianten van wil maken, dan moet je de structuur van die bestaande producten moet je gewoon modificeren. Dat kan die tool voor jou doen of die kan je helpen. Dan denk ik dat je wel dat je veel Dichterbij komt.

### Interviewer

Het doel is om de tool leading moet zijn voor het moment dat je een variabel product hebt. Dus zeg maar, de manier waarop je die features aanmaakt moet eigenlijk bepalen hoe jij je structures in PLM aan moet gaan maken of moet veranderen.

### Manufacturing Engineer

We zeggen net dat je als je die nano weer opsplitst en je wil de twee features van maken, dan moet je dus in een bestaande bom van die varianten. Die varianten zijn nog niet uitgewerkt, dus we hebben eigenlijk twee varianten, maar die nano zit erin dus die willen wel opsplitsen. Dan moeten we die die componenten in die bom die behoren bij die nano, die moet je eigenlijk groeperen en die moet er eigenlijk als een module onder gaan hangen. Maar voordat je dat doet, zijn die componenten in al die boms zijn nog steeds. Die hangen nog steeds onder de module Nano en vervolgens moet je in die module nano, moet je die twee groepjes componenten gaan opsplitsen, dan moet je weer een module voor maken van een feature dan een usb connector, twee usb connectoren. Ik denk dat het niet onderuit komt en op zich hoeft het ook geen probleem te zijn, want Je kunt natuurlijk in PLM van die Nano heb een release natuurlijk en die is bevroren, dus een oude release gaat, dan zie je ook. In deze release was er nog geen keuze tussen een of twee usb connectoren en een nieuwe release het er wel. Alleen in nieuwe release verander je eigenlijk alleen je structuur maar de netto bom de platgeslagen bom is nog 100% hetzelfde. Het enige wat je gedaan hebt is eigenlijk die bestaande hebt je gesplitst.

### Interviewer

Maar het product dat daaronder zit is identiek. 

### Manufacturing Engineer

Ja, alleen we hebben nu in PLM het probleem dat we dus die modules maken door daar een PN tussen te hangen en ja op zich zou dat ook wel kunnen. Dan moet je daar een pn tussen hangen, ja.

### Interviewer

Ik moet deze vragen nog even nalopen en moet ze gesteld hebben. Is Featureen modeling duidelijk en begrijpelijk. 

### Manufacturing Engineer

Ja, zeker oké, ja,.

### Interviewer

Snap je de toepassing van het concept binnen PT zoals in hoe ik het gedemonstreerd heb en hoe het zou kunnen werken? 

### Manufacturing Engineer

Ja absoluut voor de problemen binnen PT, maar het grote deel wat ik mis en ik begrijp dat ik een beetje buiten die context is. Inderdaad, van hoe gaan we dat nou straks op PLM mappen en dat is een heel belangrijk stuk. Wat dat linken betekent, daar gaat het juist echt om.

### Interviewer

Dat precies, en dat is een van de belangrijkste dingen is van zoiets als dit implementeren.

### Manufacturing Engineer

Nou ja, anders kun je niet beginnen met implementeren voordat je dat duidelijk hebt, heeft geen zin om hier aan te beginnen. Je kunt je route niet afmaken.

Ik denk dat het oplosbaar is, maar het is echt een heel lastig ding en i denk dat je ook daarvoor heel veel kennis nodig en misschien heb je inmiddels wel van hoe wij PLM of hoe wij Orion gebruiken, en hoe onze structuur in elkaar zit en wat voor mogelijkheden we hebben om daar vanaf te wijken. En er komt nog een extra moeilijkheid bij met dat hele variant verhaal, want ik had het hier met jou ook over gehad. Alternatieven. Want dat is eigenlijk ook een soort extra dimensie. Wat er dan ook bij gaat komen en dat dat lijkt een beetje varianten, maar het bijt elkaar ook wel een beetje.

### Interviewer

Wat je in principe zou kunnen doen, is dan meteen ook een alternatief aan een feature hangen dus als een lijst krijgt binnen die feature, bijvoorbeeld. Dus in die zin kan het een stukje hetzelfde afdekken.

### Manufacturing Engineer

Ik denk dat het wel afgedekt wordt, want het idee met alternatieven is dat wij op refdes niveau dus niet op component niveau, maar op product refdes niveau dat we daar alternatief onder gaan hangen en in principe eindigt jouw verhaaltje bij een refdes. Je hoeft niet dieper te gaan, dus dat dat komt er eigenlijk gewoon nog een keer onder te hangen. En dan zou het moeten werken, maar dat is wel iets wat ik hier goed nagedacht moet worden als dit concept helemaal uitgewerkt is, tot aan implementatie of iets dergelijks in PLM ja.

### Interviewer

Dat zou nog een volgende stap zijn?

### Manufacturing Engineer

Dus zit er dus nog een addertje onder het gras. Op het moment dat wij in product gaan maken of eigenlijk bestellen. Want Het is nog steeds niet duidelijk wanneer wij die alternatief willen platslaan. Doen we dat op moment dat we gaan inkopen of doen we dat moment dat we de productie starten? Het is zeer waarschijnlijk dat we het willen doen op het moment dat we gaan inkopen. Want dan moeten we natuurlijk weten welke alternatieven we inkopen. Goedkoper wel niet goedkoper, bijvoorbeeld beschikbaarheid. Je zou kunnen zeggen,je kunt het later doen, maar ja, dan ga je dan ga je misschien de verkeerde alternatieven gebruiken die helemaal niet bedoeld waren voor dit product, maar voor een ander product. Dus het lijkt vrij logisch dat je die bom bevriest of de alternatieve bevriest op het moment dat je gaat inkopen en daar hebben we op dit moment ook nog helemaal geen. Hoe zeg je dat concept? Ja, geen definitie voor. We hebben nog helemaal geen bevroren bom met alternatieve, want bij ons is namelijk het PN is de bevroren bom, maar dan gaan we dus eigenlijk nog een laag dieper, dus we krijgen een PN met daar bovenop een bevroren set van de alternatieve mogelijkheden die daarin zitten. Nu is het PN eigenlijk 100 Procent als deze bom geen twijfel mogen. Maar straks gaat het PN gaat zich bijvoorbeeld zijn dat is deze bom met deze alternatieve hier.

### Interviewer

Dus je hebt ook een een lijst daarnaast lopen die je ook bevriest en die kun je dus los onafhankelijk bevriezen om nieuwe alternatieven toe te voegen, een verandering te maken die goedgekeurd zijn om hem dan weer te bevriezen?.

### Manufacturing Engineer

We gaan vroeger was een bom PN was onze laagste niveau. We gaan er eigenlijk nog een niveautje lager. Ja, wat eigenlijk het product niet verandert hè? Dus we hebben op bom PN niveau hebben we op gegeven moment releases waarbij het product wel veranderd list releases waar een product. eigenlijk niet verandert, en straks hebben we patches waarbij een product helemaal niet veranderd. Maar daaronder krijgen we dus nog eens een keer de laag van alternatieven. We hebben deze set van alternatieven gekozen op deze set van alternatief gekomen, wat ook niet het product beïnvloedt, dus die moeten ook door elkaar heen geproduceerd worden. En dat niveau hebben we op dit moment nog niet.

Ik denk dat jij zeg maar zit op het laagje van PN bom zit, dus ik denk dat die andere laag er ook bij jou gewoon onder past maar. Ik durf niet helemaal zeker te zeggen of er nooit een ja, een of ander conflict ontstaat.

### Interviewer

Even kijken, pakt het concept effectief de relevante problemen aan en hoeveel slaagt het daarin? Dus wat erop neerkomt er zijn aantal problemen, maintainability change en product management building block management PLM hoe, hoe gaan we die structuur daarin aanbrengen? Het configureren van producten. Denk je dat deze tool of dit idee of concept daar een goede oplossing voor bied.

### Manufacturing Engineer

Zeker wel met wel een aandachtspuntje. In jouw voorstel nog wat extra focus kan leggen op dat je op gegeven moment zo'n features moet opsplitsen, want dat is eigenlijk wat we heel veel gaan krijgen. Het is belangrijk dat daar duidelijk is dat die tool daar ook mee om kan gaan, dus dat je gaandeweg een feature moet opsplitsen en dat je die oude varianten die je al gemaakt hebt dat die dus in een keer moeten gaan wijzen naar een gesplitste feature op een of andere manier een beetje de maintainability van die feature modellen. Maar dat is ook direct de varianten die eraan gelinkt zijn. Uitbreiden van feature modellen en de opsplitsen van features en dan maintainability van de varianten die al daarvoor gedefinieerd zijn. Dat is een belangrijk punt.

### Interviewer

Denk je dat het concept volledig is? Bevat het alle elementen die jij noodzakelijk acht te zijn?

### Manufacturing Engineer

Ja, We hebben het over gehad, hè. Een beetje de feature maintenance en en de link naar PLM.

### Interviewer

Denk je dat dit cases het gros van de cases binnen PT kan aanpakken, denk je dat de cases buiten vallen, wat voor keuzes vallen er buiten denken, wat voor cases vallen er binnen? Heb je daar een een idee van?

### Manufacturing Engineer

Moeilijk te zeggen. Maar het concept is nu zo algemeen dat ik eigenlijk niet lan zeggen. Ja, nou ja, ik als dit goed geïmplementeerd wordt, dan denk ik dat het alle cases vangt ja. Het is niet voor niks dat we tot nu toe nog steeds geen goede variant management hebben, want voorheen maakten we er eigenlijk weinig gebruik van. We krijgen nu wel steeds meer, omdat we natuurlijk zelf eigen producten gaan maken en dan wil je gewoon toe grijpen op een bestaand design en dan wil je nieuwe variant van maken om dan weer effectief te kunnen verkopen aan een nieuw klant of markt.

Dan krijg je het probleem: als ik nou iets moest gaan updaten. Ja, dan wil ik het in één ding aanpassen, zodat al die varianten die we voor iedereen gemaakt hebben, dat die allemaal geupdate worden. Zo is probleem eigenlijk ontstaan. Ik denk dat de complexiteit van onze varianten als je dat vergelijkt met bijvoorbeeld een auto, dat wij zo makkelijker hebben. Nou maar ja, de dus ik denk dat wij misschien nog wel relatief weinig vragen van hoe complex de varianten zijn dus waar we het straks over hebben gehad. De grafische weergave van varianten. Ik denk dat het reuze meevalt, want je kunt al heel snel wat jij net zei op een gegeven moment afdalen in bijvoorbeeld als je een rek hebt, dan heb je het over een module, dan ga je alleen maar hebben over de variant binnen die module en die niveaus boven dat praten we over de varianten van de modules. Je hebt dan als het goed is geen relatie tussen die module en kan dan ook dezelfde moment ook de varianten binnen de module beheren . Ik zou niet weten waarom dat niet zou werken, dat kun je losknippen van elkaar. Dus ik denk dat dat heel erg meevalt. Dan denk ik dat je al vrij snel alle denkbare variant problemen kan vangen hiermee ja.

### Interviewer

Oké duidelijk. Fijn laatste vraag, is het concept geschikt voor verdere implementatie? Binnen de context PT? Hoe zie jij zoiets voor je? Als we dit verder gaan uitwerken, laten we zeggen, we beginnen nu. Wat doen we dan?

### Manufacturing Engineer

Je noemt nu implementatie. Nee, Dat is niet geschikt, want die andere dingen moeten dus goed uitgewerkt worden. Met name die link naar PLM, dus dat dat zie ik meer als een als een voortgang van wat je nu aan het doen bent. En dan met de focus op dat heel duidelijk uitgelegd wordt hoe die hoe die relatie ontstaat en hoe die moet samenwerken met PM en welke aanpassingen in PLM nodig zijn, dat hoort er natuurlijk ook bij. Pas als dat helemaal duidelijk is, dan kun je natuurlijk gaan praten over misschien eerst een proof of concept om te kijken van: je kunt niet alles op papier bedenken, dus op gegeven moet je gewoon hands om. Moet je gewoon een pilotproject starten. Hopen dat dan de aanpassingen PLM niet te complex zijn, want anders hang je daar weer natuurlijk. Maar ja, dat dit in de toekomst moet gaan gebeuren. Ja, dat weet je. Dat staat bij ons ook als toekomst op de PLM roadmap.

Implementatie nee, nog lang niet, Maar ik denk dat dit een hele goeie aanzet is om hier inderdaad, ja, om tot een compleet plan te komen en door te itereren.

### Interviewer

Goed, Dat was hem dan. Ik voorzien van heel veel informatie die ik kan gebruiken. Harstikke bedankt!
