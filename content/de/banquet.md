+++
title = "banquet"
description = "Banquet page"
layout = "banquet"
lang = "de"

felsenegg_room = "Felsenegg"
jaeger_room = "Jäger"
arven_room = "Arven"

per_day="pro Person"
banquet_rooms = "Räume"
banquet_title = "Gruppen"
banquet_heading = "Banketträume"
banquet_content = "Wir bieten Ihnen passende Räumlichkeiten für Ihren Anlass. Je nach Event können neben den folgenden Lokalitäten weitere Bereiche wie die Hauptterrasse oder das Restaurant einbezogen werden."

packages_heading = "Group Packages"
packages_content = """Dem Alltag entschweben und in luftiger Höhe sich verwöhnen lassen – das ist Felsenegg-Fondue. Die Luftseilbahn Adliswil-Felsenegg LAF und das Gasthaus Felsenegg halten für Sie ein nicht alltägliches Angebot bereit. Natürlich können Sie Ihren Anlass auch individuell gemäss unten stehenden Menu gestalten.

Reservationen unter: Sihltal Zürich Uetliberg Bahn SZU AG via email [szuextra@szu.ch](mailto:szuextra@szu.ch) oder Telefon 044 206 45 07
"""
group_packages = "Packages"
groups_menu = "Menu für Gruppen"

book_package = "Reservieren"

dinatoire_heading = "MOUNTAIN DINATOIRE"
dinatoire_content = "Mit kalten, warmen und süssen Häppchen gemischt - entspricht einem ausgiebigen Menü. Es ist ein situativer Genuss, von der Hand in den Mund, Verführung für das Auge und den Gaumen. Sie bietet Abwechslung und vermittelt Spass. Das Angebot variiert zwischen kalten und warmen Speisen sowie süssen Häppchen. Die Häppchen werden in kleinen Portionen auf dem Teller serviert, so dass Sie in wenigen Bissen gegessen werden können. "
dinatoire_items = [
"Unser beliebtes Käsefondue mit Hausbrot",
"Münchner Weisswürstchen mit bayrisch-süssem Senf und Laugenbrezn",
"Buntes Salatschüsseli",
"Fischknusperli im Teigmantel mit Sauce Tartar",
"Ofenkartoffel mit Sourcream",
"Bauernchnoblibrot belegt mit Speck und Tomaten, überbacken mit Käse",
"Bergjausen-Plättli - Eine Auswahl aus Trockenfleisch, Alp- und Weichkäse",
"Gebackene Zwiebelringli mit Kräuterdip",
"Mini Röschti mit Bündnerfleisch",
"Frische Fruchtspiessli",
"Kaiserschmarrn mir Zwetschgenkompott"
]

[[packages]]
id = "felsenegg"
name = "Käsefondue"
price = 74.00
includes = [
	"Gemeinsame Bergfahrt mit der Felseneggbahn auf 800 m, kurzer Fussmarsch zum Panorama-Restaurant Felsenegg (5 Minuten).",
	"Begrüssungs-Apero auf der Aussichtsterrasse mit einer Tasse heissem Glühwein und warmen Aperitifhäppchen.",
	"Als Vorspeise wird eine bunte Salatkomposition serviert.",
	"Käsefondue: Die beliebte Käsemischung des Gasthauses Felsenegg.",
	"Gemeinsame Talfahrt mit der Felseneggbahn (Extrafahrt) zurück nach Adliswil."
]

[[packages]]
id = "meat"
name = "Winzerfondue"
price = 95.00
includes = [
	"Gemeinsame Bergfahrt mit der Felseneggbahn auf 800 m, kurzer Fussmarsch zum Panorama-Restaurant Felsenegg (5 Minuten).",
	"Begrüssungs-Apero auf der Aussichtsterrasse mit einer Tasse heissem Glühwein und warmen Aperitifhäppchen.",
	"Als Vorspeise wird eine bunte Salatkomposition serviert.",
	"Fleischfondue nach Winzerart mit hauseigenem würzigem Rotweinsud: Kleingeschnittenes Schweizer Frischfleisch vom lokalen Metzger, Rind-, Kalbs-, Poulet- und Schweinefleisch. Rotweinsud: Bouillon mit Rotwein aus der Region verfeinert. Beilagen: Pommes Frites, Silberzwiebeli, Gürkli, Maiskölbchen, pikante Peppadew, Mini Champignon, eingelegte Knoblauchzehen. Saucen: Cocktail, Tartar, Knoblauchsauce, Curry und BBQ Sauce",
	"Gemeinsame Talfahrt mit der Felseneggbahn (Extrafahrt) zurück nach Adliswil."
]


[[packages]]
id = "raclette"
name = "Raclette"
price = 79.00
includes = [
	"Gemeinsame Bergfahrt mit der Felseneggbahn auf 800 m, kurzer Fussmarsch zum Panorama-Restaurant Felsenegg (5 Minute).",
	"Begrüssungs-Apero auf der Aussichtsterrasse mit einer Tasse heissem Glühwein und warmen Aperitifhäppchen.",
	"Als Vorspeise wird eine bunte Salatkomposition serviert.",
	"Raclette: mit Tischgrill zum Selberbrutzeln. Beilagen: Raclette-Kartoffeln, Silberzwiebeli, Gürkli, Maiskölbchen, separat.",
	"Gemeinsame Talfahrt mit der Felseneggbahn (Extrafahrt) zurück nach Adliswil."
]


[[restaurant_menu]]
id = "apero"
name = "Apero"

	[[restaurant_menu.items]]
	title = "Bergjausen-Platte"
	description = "Eine Auswahl aus Trockenfleisch, Alp- und Weichkäse Dazu Hausbrot, Silberzwiebeli, Gürkli und Maiskölbchen"
	price = 15.50

	[[restaurant_menu.items]]
	title = "Münchner Weisswürstchen"
	description = "mit bayrisch-süssem Senf und Laugenbrezn"
	price = 12.50
	
	[[restaurant_menu.items]]
	title = "Aperokomposition"
	description = "Stellen Sie sich Ihre eigene Aperokomposition" 
	description_items = [
		"Gemüse-Crostini - Toasbrot mit warmem Gemüse-Käse Aufstrich",
		"Bauernchnoblibrot mit Speck + Tomaten, überbacken mit Käse",
		"Hackfleischbällchen mit würziger Sauce",
		"Lachs-Brötli mit Mozzarella überbacken",
		"Bruschetta mit würzigen Kräutern",
		"Gebackene Zwiebelringli mit Kräuterdip",
		"Pangasius Fischknusperli mit Tartar Sauce",
		"Mini-Röschti mit Traube und Rohschinken"
	]

	[[restaurant_menu.items.prices]]
	price = 9.0
	description = "sorten"
	quantity = 2

	[[restaurant_menu.items.prices]]
	price = 12.50
	description = "sorten" 
	quantity = 3


[[restaurant_menu]]
id = "starter"
name = "Vorspeise"

	[[restaurant_menu.items]]
	title = "Bunt gemischter Saisonsalat"
	description = "Bunt gemischter Saisonsalat mit karamellisierter Baumnuss"
	price = 12.50

	[[restaurant_menu.items]]
	title = "Knackige Blattsalate"
	description = "Knackige Blattsalate mit Rohschinken und Sprinzmöckli"
	price = 14.50

	[[restaurant_menu.items]]
	title = "Schaumcremesuppe"
	description = "Schaumcremesuppe mit Zürcherriesling und Nussbrotcroutons"
	price = 12.50

	[[restaurant_menu.items]]
	title = "Hausgemachte Capuns"
	description = "3 Stück hausgemachte Capuns. In Mangoldblätter gewickeltes Päckchen aus Spätzliteig, angereichert mit klein geschnittenen Stückchen Salsiz, an einer Rahm–Käsesauce"
	price = 14.50

	[[restaurant_menu.items]]
	title = "Felseneggplättli"
	description = "Trockenfleisch, Speck und Schweizerkäse"
	price = 12.00

	[[restaurant_menu.items]]
	title = "Klare Bouillon"
	description = "Klare Bouillon mit buntem Gemüse Julienne"
	price = 11.00

	[[restaurant_menu.items]]
	title = "Gluschtige Spiessli"
	description = "Spiessli mit Rohschinken und Honigmelone"
	price = 13.00

[[restaurant_menu]]
id = "main"
name = "Hauptgerichte"

	
	[[restaurant_menu.items]]
	title = "Geschnetzeltes Kalbfleisch"
	description = "Geschnetzeltes Kalbfleisch nach Zürcher Art mit knuspriger Butterröschti"
	price = 38.00

	[[restaurant_menu.items]]
	title = "Roastbeef"
	description = "Roastbeef mit sämiger Sauce Bernaise serviert mit Kartoffelgratin und Gartengemüse"
	price = 39.00

	[[restaurant_menu.items]]
	title = "Schweinefilet"
	description = "Schweinefilet an Cognac Senfsauce im Ofen gegart mit Rösticroquetten und Gartengemüse"
	price = 38.00

	[[restaurant_menu.items]]
	title = "Kalbs-Piccata"
	description = "Kalbs-Piccata Milanese Der Klassiker aus Italien dazu Vialone-Risotto und Gartengemüse"
	price = 35.00

	[[restaurant_menu.items]]
	title = "Hausgemachter Hackbraten"
	description = "Hausgemachter Hackbraten mit Kartoffelpüree und Marktgemüse"
	price = 33.00

	[[restaurant_menu.items]]
	title = "Kalbsschnitzeli"
	description = "Kalbsschnitzeli an gluschtiger Feigenschaumsauce serviert mit Butternüdeli und Gartengemüse"
	price = 38.00

	[[restaurant_menu.items]]
	title = "Hausgemachter Rindsfilet"
	description = "Fackelspiess gluschtig mariniert aus fein geschnittenem Rindsfilet mit Ofenkartoffel und Sauerrahm, Maiskolben zum „gnagä“"
	price = 39.50

	[[restaurant_menu.items]]
	title = "Tessiner-Braten"
	description = "Schweinshals mit Speck umwickelt Kartoffelgratin und Gemüse als Beilage"
	price = 36.50

	[[restaurant_menu.items]]
	title = "Raclette"
	description = "Zum selber bruzzeln. Mit Kartoffeln, Silberzwiebeli, Gürkli und Maiskölbchen"
	price = 39.00

	[[restaurant_menu.items]]
	title = "Fleischfondue nach Winzerart"
	description = "mit hauseigenem Rotweinsud. Die tolle Alternative mit dem besonderen Geschmack. Kleingeschnittenes Schweizer Frischfleisch vom lokalen Metzger Schweine-, Poulet-, Kalb- und Rindfleisch. Der Rotweinsud wird aus Bouillon zubereitet und mit Rotwein aus der Region und Gartengemüse verfeinert. Beilagen: Kartoffelkringel, Reis, Silberzwiebeli, Gürkli, Maiskölbchen, pikante Peppadew, Minichampignon, eingelegte Knoblauchzehen Saucen: Cocktail, Tartar, Knoblauch, Curry und scharfe Barbecue Sauce"
	price = 55.00


[[restaurant_menu]]
id = "desert"
name = "Dessert"

	[[restaurant_menu.items]]
	title = "Emmentaler-Merinques"
	description = "Emmentaler-Merinques mit Rahm und Eis"
	price = 12.00

	[[restaurant_menu.items]]
	title = "Frischer Fruchtsalat"
	description = "Frischer Fruchtsalat mit Rahm"
	price = 12.50

	[[restaurant_menu.items]]
	title = "Kaiserschmarrn"
	description = "Kaiserschmarrn mit Zwetschgenkompott"
	price = 14.50

	[[restaurant_menu.items]]
	title = "Hausgemacht Apfelstrudel"
	description = "Apfelstrudel mit Vanillesauce oder einer Kugel Vanilleeis"
	price = 14.50

	[[restaurant_menu.items]]
	title = "Kürbiskernenparfait"
	description = "Kürbiskernenparfait mit Baileysschaum"
	price = 14.50

	[[restaurant_menu.items]]
	title = "Palatschinken mit Vanilleeis"
	description = "Palatschinken mit Vanilleeis, warmer Schoggisauce und Rahm"
	price = 13.50

	[[restaurant_menu.items]]
	title = "Gebrannte Creme"
	description = "Gebrannte Creme mit Rahm"
	price = 11.00

	[[restaurant_menu.items]]
	title = "Süssmostcreme"
	description = "Süssmostcreme mit Rahm"
	price = 11.00
	

[[restaurant_menu]]
id = "wine"
name = "Weine"

	[[restaurant_menu.wine_categories]]
		name = "White wines"
		[[restaurant_menu.wine_categories.items]]
		title = "Zürcher Riesling"
		description = " “Dä vo da”, Riesling – Silvaner Jürg Saxer, Neftenbach"
			[[restaurant_menu.wine_categories.items.prices]]
			price = 8.00
			quantity = 10
			[[restaurant_menu.wine_categories.items.prices]]
			price = 13.50
			quantity = 20
			[[restaurant_menu.wine_categories.items.prices]]
			price = 18.50
			quantity = 30
			[[restaurant_menu.wine_categories.items.prices]]
			price = 25.50
			quantity = 50

		[[restaurant_menu.wine_categories.items]]
		title = "Fechy AOC, Le Terroir"
		description = "Chasselas Hammel, Rolle"
			[[restaurant_menu.wine_categories.items.prices]]
			price = 8.00
			quantity = 10
			[[restaurant_menu.wine_categories.items.prices]]
			price = 14.00
			quantity = 20
			[[restaurant_menu.wine_categories.items.prices]]
			price = 19.50
			quantity = 30
			[[restaurant_menu.wine_categories.items.prices]]
			price = 26.50
			quantity = 50

		[[restaurant_menu.wine_categories.items]]
		title = "Fechy AOC, Le Terroir"
		description = "Chasselas Imesch Vins, Sierre"
			[[restaurant_menu.wine_categories.items.prices]]
			price = 8.50
			quantity = 10
			[[restaurant_menu.wine_categories.items.prices]]
			price = 13.50
			quantity = 20
			[[restaurant_menu.wine_categories.items.prices]]
			price = 18.50
			quantity = 30
			[[restaurant_menu.wine_categories.items.prices]]
			price = 25.50
			quantity = 50

		[[restaurant_menu.wine_categories.items]]
		title = "Petite Arvine du Valais"
		description = "AOC Jacques Germanier, Petite Arvine Ein sehr sortentypischer Wein – lebhaft, kräftig und fruchtig Schweiz"
			[[restaurant_menu.wine_categories.items.prices]]
			price = 47.00
			quantity = 75

		[[restaurant_menu.wine_categories.items]]
		title = "Fendant Etoile"
		description = "AOC Jacques Germanier Valais, Chasselas Prickelnd und spritzig, ein knackiger Fendant Schweiz"
			[[restaurant_menu.wine_categories.items.prices]]
			price = 35.00
			quantity = 75
			

		[[restaurant_menu.wine_categories.items]]
		title = "Eleganzia"
		description = "AOC Gebrüder Nauer Bremgarten Chardonnay – Pinot gris – Sauvignon blanc - Gewürztraminer Aromatisch mit einem Hauch vonApfel und Zitronen Schweiz"
			[[restaurant_menu.wine_categories.items.prices]]
			price = 54.50
			quantity = 75
			

	[[restaurant_menu.wine_categories]]
		name = "Red wines"
		[[restaurant_menu.wine_categories.items]]
		title = "Merlot del Ticino, Runchet"
		description = ""
			[[restaurant_menu.wine_categories.items.prices]]
			price = 8.50
			quantity = 10
			[[restaurant_menu.wine_categories.items.prices]]
			price = 13.50
			quantity = 20
			[[restaurant_menu.wine_categories.items.prices]]
			price = 18.50
			quantity = 30
			[[restaurant_menu.wine_categories.items.prices]]
			price = 25.50
			quantity = 50

		[[restaurant_menu.wine_categories.items]]
		title = "Carlo Tamborini, Lamone"
		description = ""
			[[restaurant_menu.wine_categories.items.prices]]
			price = 8.50
			quantity = 10
			[[restaurant_menu.wine_categories.items.prices]]
			price = 13.50
			quantity = 20
			[[restaurant_menu.wine_categories.items.prices]]
			price = 18.50
			quantity = 30
			[[restaurant_menu.wine_categories.items.prices]]
			price = 25.50
			quantity = 50

		[[restaurant_menu.wine_categories.items]]
		title = "Soñador, Tempranillo"
		description = "Vino de la Tierra de Castilla Finca Loranque Kräftiges purpurrot, breit abgestützte Aromatik Spanien"
			[[restaurant_menu.wine_categories.items.prices]]
			price = 8.50
			quantity = 10
			[[restaurant_menu.wine_categories.items.prices]]
			price = 15.50
			quantity = 20
			[[restaurant_menu.wine_categories.items.prices]]
			price = 20.50
			quantity = 30
			[[restaurant_menu.wine_categories.items.prices]]
			price = 29.50
			quantity = 50

		[[restaurant_menu.wine_categories.items]]
		title = "Barbarossa, Ripasso"
		description = "Veneto Valpolicella Superiore DOC Reife Beerenaromatik mit etwas Gewürz, geschmeidige Struktur Italien"
			[[restaurant_menu.wine_categories.items.prices]]
			price = 9.00
			quantity = 10
			[[restaurant_menu.wine_categories.items.prices]]
			price = 16.50
			quantity = 20
			[[restaurant_menu.wine_categories.items.prices]]
			price = 22.00
			quantity = 30
			[[restaurant_menu.wine_categories.items.prices]]
			price = 32.00
			quantity = 50

		[[restaurant_menu.wine_categories.items]]
		title = "Sepp Moser"
		description = "Weingut Hedwighof, Apetlon Neusiedlersee Zweigelt Ein eleganter Wein mit feinem Fruchtcharme und langem Ausklang Österreich"
			[[restaurant_menu.wine_categories.items.prices]]
			price = 49.50
			quantity = 75

		[[restaurant_menu.wine_categories.items]]
		title = "Primitivo Puglia"
		description = "IGT Luccarelli, Farnese, Terre di Sava Primitivo Ein vollmundiger Wein, weich und ausgewogen, leicht zu trinken Italien"
			[[restaurant_menu.wine_categories.items.prices]]
			price = 53.00
			quantity = 75

		[[restaurant_menu.wine_categories.items]]
		title = "Nobler Blauer"
		description = "Jürg Saxer’s, Neftenbach Barrique, Pinot Noir Reiffruchtige Note sowie einen gehaltvollen und komplexen Körper Schweiz"
			[[restaurant_menu.wine_categories.items.prices]]
			price = 54.00
			quantity = 75

		[[restaurant_menu.wine_categories.items]]
		title = "Domingo"
		description = "Vino de la Tierra de Castilla Finca Loranque, Bargas Tempranillo – Cabernet Sauvignon Vollmundiger, fruchtiger und sehr abgerundeter Wein Spanien"
			[[restaurant_menu.wine_categories.items.prices]]
			price = 49.50
			quantity = 75


	[[restaurant_menu.wine_categories]]
		name = "Rose"
		[[restaurant_menu.wine_categories.items]]
		title = "Oeil de perdrix, Pinot Noir"
		description = ""
			[[restaurant_menu.wine_categories.items.prices]]
			price = 8.00
			quantity = 10
			[[restaurant_menu.wine_categories.items.prices]]
			price = 13.50
			quantity = 20
			[[restaurant_menu.wine_categories.items.prices]]
			price = 18.50
			quantity = 30
			[[restaurant_menu.wine_categories.items.prices]]
			price = 25.50
			quantity = 50

		[[restaurant_menu.wine_categories.items]]
		title = "Jürg Saxer, Neftenbach"
		description = ""
			[[restaurant_menu.wine_categories.items.prices]]
			price = 8.00
			quantity = 10
			[[restaurant_menu.wine_categories.items.prices]]
			price = 13.50
			quantity = 20
			[[restaurant_menu.wine_categories.items.prices]]
			price = 18.50
			quantity = 30
			[[restaurant_menu.wine_categories.items.prices]]
			price = 25.50
			quantity = 50

	[[restaurant_menu.wine_categories]]
		name = "Proseco"
		[[restaurant_menu.wine_categories.items]]
		title = "Nino Franco Brut"
		description = "DOC di Valdobbiadene Leichter Körper bei eleganter Struktur, feine Perlage bei lebhafter Säure Italien"
			[[restaurant_menu.wine_categories.items.prices]]
			price = 11.00
			quantity = 10
			[[restaurant_menu.wine_categories.items.prices]]
			price = 53.00
			quantity = 75

+++