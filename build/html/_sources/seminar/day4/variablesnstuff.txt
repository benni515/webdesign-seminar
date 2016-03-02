Breytur, lykkjur og flæði
=========================

Hvað er ;
_________

Semíkomma eða Semicolon á Ensku, er notað til að seigja forritunar þýðaranum, eða þá tölvunni hvenær lína endar. Þegar þú skilgreinir breytu, kallar í verkfæri eða reiknar og margt fleirra setur maður alltaf semíkommu eftir á. Þegar þú býrð til aðferð sjálfur þarftu tildæmis ekki að setja semíkommu, þetta lærist allt með tímanum, en er minna vandamál.

Hvernig væri hægt að skrifa kóða

.. code-block:: Javascript

	//Hérna veit talvan hvenær hver lína endar og leyfir þetta því
	//Þetta er samt ekki flottur kóði
	var tala = 5; tala += 5; tala = tala + tala * 2; console.log(tala);

	//Venjulega myndi hann vera svona
	var tala = 5;
	tala += 5;
	tala = tala + tala * 2;
	console.log(tala);


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

**Verkefni 1**

Prufiði að búa til nokkrar breytur með texta, tölu og sannyrði. Nefnið þau viðeigandi.

Tölu Reikningar
_______________

Reikningur er mjög einfaldur hlutur í Javascript. Skellum okkur beint í dæmi.

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

Það er líka hægt að nota breytur til að reikna með. Hérna fyrir ofan skilgreinum við breytu með gildið 5 og notum hana til að reikna og geymum svo útkomuna í aðrari breytu.

.. code-block:: Javascript

	//Styttri leiðir
	var tala = 5;
	tala = tala + 1; //Geymir sjálfan sig plús ein
	tala++; //Þæginlegri aðferð til að bæta einum við
	tala += 20; //Bætir 20 við breytuna tala
	//Þetta er hægt með öll önnur merki þegar reiknað er starfræði í Javascript
	//Takið eftir að það er = fyrir aftan þannig breytan tala mun geyma útkomuna
	tala -= 20; 
	tala *= 5; 
	tala /= 5; 
	tala %= 2; 

Hérna fyrir ofan eru sýndar nokkrar styttri leiðir til að reikna og vinna með tölur í Javascript. Þetta eru flest allt betri leiðir til að skrifa kóðan þinn því þá styttist hann og verður lesanlegri.

Útskrift tölu

.. code-block:: Javascript

	var tala1 = 20;
	var tala2 = 30;
	console.log(tala1 + tala2); //skrifar út summu talnanna
	console.log((5 * 5) + 25 - (5*5));

**Verkefni 1**

Búðu til tvær tölu breytur og skrifaðu út margfeldi þeirra

**Verkefni 2**

Búðu til þrjár tölu breytur, geymdu summu þeirra í breytu af nafninu heild. Skrifaðu svo út gildi breytunnar heild.

**Verkefni 3**

Búðu til tvær tölu breytur með gildinn 274 og 29. Skrifaðu út afganginn af deilingunni 274/29.

Strengja vinnsla
________________

Strengja vinnsla er ekki flókin í byrjun en getur orðið það fljótt. Til að líma tvo strengi saman geriru einfaldlega + merki á milli. Í flestum túngumálum gæti maður ekki plúsað saman streng og tölu en því Javascript er mjög sveiganlegt túngumál geturu gert það. Þá verður talan bara einfaldlega strengur.

Með console.log() skipuninni geturu skrifað út strengi og tölur, og getur líka sameinað þá inní verkfærinu sjálfu.

Dæmi um Strengja vinnslu

.. code-block:: Javascript

	//Allt þetta skrifar út það sama bara á mismunandi hátt

	console.log("Ég er " + 15 + " ára gamall");

	var texti1 = "Ég er ";
	var texti2 = " ára gamall";
	var aldur = "15";
	console.log(texti1 + aldur + texti2);

	var heild = texti1 + aldur + texti2;
	console.log(heild)

**Verkefni 1**

Búðu til strengja breytu sem geymir gildið "Halló heimur!", skrifaðu gildi breytunnar svo út.

**Verkefni 2**

Búðu til tvær strengja breytur og eina tölu breytu. Fyrsta strengja breytan inniheldur "Ég á afmæli ". Seinni strengja breytann inniheldur mánuðinum sem þú á afmæli á. Tölu breytan geymir dagin sem þú átt afmæli. Sameinaðu allar þessar breytur í fjórðu breytuna og skrifaðu svo gildi hennar út.


if, else if, else
_________________

if, else if og else eru skipanir sem þú notar til að tékka hvort eitthvað sé satt eða ósatt. Flæði þessara skipana er mjög einfalt, ef þú gerir if setningu geturu gert else if eða else skipun eftirá þannig ef fyrsta if setninginn skilar satt þá munu hinar ekki keyra og koll af kolli. Og ef fyrsta skilar ósatt mun næsta keyrast þangað til eitthver skipun skilar satt. Ef allar skipanirnar skila ósatt er hægt að setja else skipun sem mun alltaf keyra ef hinar skila allar ósatt.

Dæmi um if, else if og else skipanir

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

Hérna í dæminu fyrir ofan köllum við í skipunina if. Eftir að við köllum á skipunina if gerum við sviga og inn í hann skilirðin. Svo slaufu sviga og inn í þá það sem mun gerast ef skilirðin eru rétt. Þegar þú notar þessar skipanir þarftu ekki að setja semíkommu, nema innan í skipununni sjálfri.

**Hérna eru dæmi um vennslavirki/skilirði**

*"=="* -Ef hlutirnir eru jafnir

*"!="* -Ef hlutirnir eru ekki jafnir

*"==="* -Ef hlutirnir eru jafnir og sama breytu týpa

*"<"* -Ef fyrsti hluturinn er minni en seinni hluturinn

*">"* -Ef fyrsti hluturinn er stærri en seinni hluturinn

*"<="* -Ef fyrsti hluturinn er minni eða jafnt og seinni hluturinn

*">="* -Ef fyrsti hluturinn er stærri eða jafnt og seinni hluturinn

Dæmi um aðra vennslavirkna

.. code-block:: Javascript
	
	var tala1 = 5;
	var tala2 = 20;
	var Sannyrði = false;
	var strengur = "Hello";
	if(strengur == "Hello"){
		//Mun keyrast
	}
	if(!Sannyrði){
		//Mun keyrast
		//Ef þú setur ! fyrir framan breytu með Sannyrði þíðir það ef hann er false
	}
	if(tala1 == "5") {
		//Keyrist því þetta er sama gildi
	}
	if(tala1 === "5") {
		//Keyrist ekki því það hefur ekki sömu breytutýpu
	}
	if(tala1 < tala2) {
		//Keyrist því tala2 er stærri en tala1
	}

**Verkefni 1**

**Verkefni 2**

**Verkefni 3**