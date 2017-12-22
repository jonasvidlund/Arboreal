# Arboreal

Startup-företaget Arboreal behöver en ny hemsida för sin affärsidé. jag har då fått i uppdrag att skapa denna sida.
Krav för sidan var bl.a  att använda semantisk HTML för att strukturera upp innehållet och att huvudsakligen använda sig av flexbox.

output från valideringen:
* Document checking completed. No errors or warnings to show.
* Gratulerar! Inga fel har hittats


FEEDBACK 

Den feedback jag fick av Tommy:

1 - Finns en `link` i head i ditt HTML dokumment som inte leder någonstans. Denna ger en error i consollen när man inspekterar.

2 - En intressant lösning på informationen under 'Pricing', fint kopplat med CSS för att styla men skulle man inte kunna använda ett `table` och fortfarande få samma resultat? Skulle kräva mindre arbete?

3 - Genom att styla `p`, `h1`, `label` taggarna etc. har du hållit specificity i CSS låg vilket är bra och gör det lätt att senare skriva över om man skulle behöva. Men jag skulle nog överväga att skapa speciella klasser för olika element som ofta återkommer, jag syftar främst på title under varje sektion. Detta skulle vara för att få mer kontroll på stilarna, speciellt om mer information skulle behövas läggas till på sidan i framtiden.

4 - Hittade har några klasser i din HTML som jag inte kan hitta i din CSS. `.missionItem`, `.art1`, `.art2`, `.art3` och `.labels.

5 - Hittade ett par enstaka pixel värden på några ställen för att ändra margin och padding, de skulle man kanske kunna göra om till em eller rem?

6 - På min skärm ligger texten under 'Mission' på en enda rad förutom ett par ord, en max bredd tror jag skulle göra sig bra där för att få det att se lite stiligare ut men även för att göra det lättare att läsa.

7 - Innehållet under 'Pricing' skulle behöva lite mer luft (padding eller margin) 	för att göra det lättare att läsa, mycket information på en liten yta.


ÅTERGÄRDER

1. Länken är borttagen

2. Blev inte som jag ville vid första inlämningen. klurade inte ut hur det skulle gå till. Så till denna inlämning gjorde jag en lösning som fungerade bra med flex.

3. Har nu skapat klasse till headers. 

4. Tog bort classer som jag hade glömt fanns kvar.

5. Har nu bara pixelvärden på boxshadow och border-radius, tycker det blir enklare så.

6. Har tryckt ihop texten lite mer så den känns fylligare.

7. Bytte ju som sagt ut hela den sektionen.

övrigt. Har ändrat lite smått här och där på sånt som jag ville förbättra. tex färger osv.


RESPONSIVITET OCH MEDIAQUERIES

Jag designade min sida först så att det skulle se bra ut på en ganska liten men ändå vanlig mobilskärm som tex galaxy s5 med pixelbredden 360px. Därefter valde jag att sätta en breakpoint vid 769px då det är ett vanligt tablet format.
Samtidigt tyckte jag att vid denna pixelbredd behövdes en ändring på min navbar för att utnyttja sidans bredd mer.
Sista breakpointen valde jag att ha vid 1025px eftersom värdet är direkt efter apples stora ipadpro. plus att jag här ville utnyttja hela sidans bredd med alla mina kolumner och navbar.


RESPONSIVE PATTERN

Jag tycker min sida är mest lik Responsive UI Examples därför att där har dom också vissa fasta divar som wrappar under varandra när utrymmet kräver.








