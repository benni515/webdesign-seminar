Breytur, lykkjur og flæði
=========================

Breytur
_______

Breytur eru hlutir sem geyma upplýsingar, tildæmis texta eða tölu og margt fleirra. Til að nota breytu kallar maður í nafn hennar og fær þá upplýsingar sem breytan geymir. Þú munt alltaf nota breytur, án þeirra væri mjög erfitt að skrifa kóða. Svo getur maður notað breytur á hrikalega marga hætti.

**Breytu Dæmi**

.. code-block:: Javascript
	
	var tala = 5;
	var texti = "32";
	var Sannyrði = false;

var "Nafn breytu" = "Gildi breytunnar";

Hérna fyrir ofan erum við með þrár breytur, til að skilgreina breytu í Javascript skrifar maður "var" svo nafn breytunar og hvað hún geymir. Fyrsta breytan í dæminu fyrir ofan geymir tölu eða int á ensku og þarf ekkert meir en að skrifa töluna sem hún geymir. Önnur breytan geymir texta eða string á ensku og til að segja breytuni að þetta sé texti geriru einfaldar gæsalappir í kringum textan eða tvöfaldar gæsalappir. Þriðja breytan geymir Sannyrði eða Bool á ensku, Sannyrði er annaðhvort true eða false og er mjög nothæf tengund af breytu. Breytur geta líka geymt marga hluti í einu og helling af öðrum hlutum sem við munum fara betur í á eftir.

Tölu Reikningar
_______________

Reikningur er mjög einfaldur hlutur í Javascript. Forritunartungumálið Javascript er mjög sveiganlegt meðan við önnur túngumál og leyfir mikið. Skellum okkur beint í dæmi.

.. code-block:: Javascript

	var plus = 5 + 5; // breytan geymir töluna 10
	var minus = 5 - 3; // breytan geymir töluna 2
	var sinnum = 5 * 5; // breytan geymir töluna 25
	var deiling = 25 / 5; // breytan geymir töluna 5
	var afgangur = 20 % 9; // breytan afgangur geymir afganginn á 20 / 9 sem er 2

Hérna erum við komin með fimm breytur, þið hafið notað flest þessi merki áður fyrir utan kannski "%" sem er modulus á ensku. Það er notað til að finna afgang á deilingu. Þú getur líka reiknað með breytum. Eins og er sýnt hér í dæminu fyrir neðan.

.. code-block:: Javascript

	//skilgreind breyta sem geymir tölunar 5
	var tala = 5; 
	//Allir þessir reikningar myndu virka einsog í dæminu fyrir ofan
	var plus = tala + tala; // breytan geymir töluna 10
	var minus = tala - tala; // breytan geymir töluna 0
	var sinnum = tala * tala; // breytan geymir töluna 25
	var deiling = tala / tala; // breytan geymir töluna 1
	var afgangur = tala % tala; // breytan geymir 0 því enginn afgangur er á deilingunni 5 deilt með 5

.. todo::
    
    Strengja vinnsla til að sýna strengja vinnslu

if, else if, else
_________________

if, else if og else eru skipanir sem þú notar til að tékka hvort eitthvað sé satt eða ósatt. Flæði þessara skipana er mjög einfalt, ef þú gerir if setningu geturu gert else if eða else skipun eftirá þannig ef fyrsta if setninginn skilar satt þá munu hinar ekki keyra og koll af kolli. Og ef fyrsta skilar ósatt mun næsta keyrast þangað til eitthver skipun skilar satt. Ef allar skipanirnar skila ósatt er hægt að setja else skipun sem mun alltaf keyra ef hinar skila allar ósatt.

.. code-block:: Javascript
	
	var tala = 3
	if(tala == 1) {
		alert("talan er 1");
	} else if (tala == 2) {
		alert("talan er 2");
	} else if (tala == 3) {
		alert("talan er 3");
	} else {
		alert("talan er ekki 1, 2 eða 3");
	}

Hérna í dæminu fyrir ofan köllum við í skipunina if. Eftir að við köllum á skipunina if gerum við sviga og inn í hann skilirðin. Svo slaufu sviga og inn í 
þá það sem mun gerast ef skilirðin eru rétt.

**Hérna eru dæmi um vennslavirki/skilirði**

*"=="* -Ef hlutirnir eru jafnir

*"!="* -Ef hlutirnir eru ekki jafnir

*"==="* -Ef hlutirnir eru jafnir og sama breytu týpa

*"<"* -Ef fyrsti hluturinn er minni en seinni hluturinn

*">"* -Ef fyrsti hluturinn er stærri en seinni hluturinn

*"<="* -Ef fyrsti hluturinn er minni eða jafnt og seinni hluturinn

*">="* -Ef fyrsti hluturinn er stærri eða jafnt og seinni hluturinn