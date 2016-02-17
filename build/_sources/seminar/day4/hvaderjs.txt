Hvað er Javascript?
===================

Javascript er forritunartungumál, það er oftast notað með vefsíðum. Fólk hefur gert allskyns hluti með Javascript, einsog leiki, veföpp, en er oftast notað fyrir effects á síðum. Þú notar Javascript til að breyta hlutum á síðum, færa þá, fela þá, stækka þá og helling af öðrum hlutum. Flest allar síður sem eru til nota Javascript, enda er það eitt af vinsælustu forritunartungumálum heimsins. Það er mjög einfalt að nota Javascript með vefsíðum.

.. code-block:: html

	<!DOCTYPE html>
	<html>
		<head>
			<title> Koder </title>
		</head>
		<body>
			<script>
			 //Hérna myndiru skrifa Javascript Kóða
			</script>
		</body>
	</html>

Ef þú ætlar að skrifa Javascript kóða á sömu skrá og þú skrifaðir vefsíðuna þína verðuru að seigja að það. Þá notar maður script tagið. Það er líka til mun þæginlegri aðferð, með því að hafa sér skrá fyrir Javascript kóðann og tengja hann svo við síðuna, einsog við gerðum með css. Svo skrifar maður bara beint Javascript kóða í hana. Þegar þú býrð til Javascript skrá vistaru hana með .js eftir nafninu á skránni.

.. code-block:: html

	<!DOCTYPE html>
	<html>
		<head>
			<title> Koder </title>
		</head>
		<body>
			<script type="text/javascript" src="js/javascript.js"></script>
		</body>
	</html>

Hérna erum við búnir að tengja við Javascript skrá, kannski takiðið eftir því að maður bendir ekki alveg eins á skrár og í css, þar er notað href en með Javascript notaru src.
Svo seigjum við tegundina á skránni með type, en það er valkostur.

Þegar þú ert að nota script tagið til þess að benda á Javascript skrá máttu hafa hana í head eða body. En ekki á báðum.