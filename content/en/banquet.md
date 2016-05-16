+++
title = "banquet"
description = "Banquet page"
layout = "banquet"
lang = "en"

felsenegg_room = "Felsenegg"
jaeger_room = "Jaeger"
arven_room =  "Arven"

per_day = "per person"
banquet_rooms = "Rooms"
banquet_title = "Groups"
banquet_heading = "BANQUET ROOMS"
banquet_content = "We offer a several different areas and rooms on our premises to cater for your event. Depending on the event you can choose from the following rooms and locations. "

packages_heading = "Group Packages"
packages_content = """We cater for group events from 10 to 80 people. In conjuction with our partner Cable Car Adliswil-Felsenegg LAF, we offer a selection of all inclusive packages. We also offer tailor made group reservations from our group menu. All menus can be adjusted according to vegitarian or allergy requirements.    

For reservations please contact Sihltal Zürich Uetliberg Bahn SZU AG via email at [szuextra@szu.ch](mailto:szuextra@szu.ch) or phone 044 206 45 07
"""
group_packages = "Packages"
groups_menu = "Groups Menu"

book_package = "Book"

dinatoire_heading = "MOUNTAIN DINATOIRE"
dinatoire_content = "A large variety of cold, warm and sweet snacks. The appetizers are served in small portions so that they can be eaten in a few bites. "

dinatoire_items = [
"Cheese fondue",
"Traditional white sausage from Munich with sweet mustard",
"Seasonal mixed salad",
"Crispy battered Pangasius fish with tartar sauce",
"Baked potato with sour cream",
"Sliced garlic bread with bacon and tomatoes, topped with melted cheese",
"Dried cured meats, bacon, Swiss cheese, pickles and bread on the side",
"Crispy onion rings with herb dip",
"Mini potato röschti with dried cured veal",
"Fresh fruit skewers",
"Kaiserschmarrn is one of Austria’s best known desserts. Caramelized pancake served with stewed plums"
]

[[packages]]
id = "felsenegg"
name = "Cheese Fondue"
price = 74.00
includes = [
	"Group ascent by the Felsenegg cable car to 800 m.  This is followed by a short walk to the panoramic restaurant Felsenegg (5 minutes).",
	"Welcome drink on the terrace of either a cup of hot mulled wine or white wine and a warm canapés. The canapés are available with or without meat. Non alcoholic drinks are available as an alternative to wine.",
	"As a starter, a colourful mixed salad is served.",
	"Cheese Fondue: The popular house mixed cheese fondue.",
	"Group descent with the Felsenegg cable at the arranged time to return back to Adliswil."
]

[[packages]]
id = "meat"
name = "Meat fondue Winzerart "
price = 95.00
includes = [
	"Group ascent by the Felsenegg cable car to 800 m.  This is followed by a short walk to the panoramic restaurant Felsenegg (5 minutes).",
	"Welcome drink on the terrace of either a cup of hot mulled wine or white wine and a warm canapés. The canapés are available with or without meat. Non alcoholic drinks are available as an alternative to wine.",
	"As a starter, a colourful mixed salad is served.",
	"Meat fondue Winzerart homemade with red wine with an exciting special taste. Small slices of Swiss fresh meat from the local butcher, veal, beef, chicken and pork and the specially prepared red wine bouillon. Served with: Fries, silverskin pickled onions, baby gurkins, baby sweetecorns, mini mushrooms and garlic. Sauces: cocktail, tartar, garlic, curry and spicy barbecue sauce.",
	"Group descent with the Felsenegg cable at the arranged time to return back to Adliswil."
]


[[packages]]
id = "raclette"
name = "Raclette"
price = 79.00
includes = [
	"Group ascent by the Felsenegg cable car to 800 m.  This is followed by a short walk to the panoramic restaurant Felsenegg (5 minutes).",
	"Welcome drink on the terrace of either a cup of hot mulled wine or white wine and a warm canapés. The canapés are available with or without meat. Non alcoholic drinks are available as an alternative to wine.",
	"As a starter, a colourful mixed salad is served.",
	"Raclette: the fun way to melt cheese",
	"Group descent with the Felsenegg cable at the arranged time to return back to Adliswil."
]

[[restaurant_menu]]
id = "apero"
name = "Apero"

	[[restaurant_menu.items]]
	title = "Dried cured meats"
	description = "Dried cured meats, bacon, Swiss cheese, pickles and bread on the side"
	price = 15.50

	[[restaurant_menu.items]]
	title = "White sausage from Munich"
	description = "Traditionally served with sweet mustard"
	price = 12.50


	[[restaurant_menu.items]]
	title = "Aperitif compilation"
	description = "Choose your aperitif compilation from a selection of: "
	description_items = [
		"Meatballs with BBQ sauce",
		"Baked mini toasts with salmon and mozarella",
		"Bruschetta with aromatic herbs",
		"Homemade garlic bread with bacon and tomatoes topped with melted cheese",
		"Onion rings with herb dip",
		"Crispy battered Pangasius fish with tartar sauce",
		"Mini-Röschti with grapes and dried cured veal",
		"Vegetable-crostini, mini toasts with warm vegetable-cheese spread",		
	]
	[[restaurant_menu.items.prices]]
	price = 9.0
	description = "types"
	quantity = 2

	[[restaurant_menu.items.prices]]
	price = 12.50
	description = "types" 
	quantity = 3


[[restaurant_menu]]
id = "starter"
name = "Starters"

	[[restaurant_menu.items]]
	title = "Seasonal mixed salad"
	description = "Seasonal mixed salad with caramelised walnut"
	price = 12.50

	[[restaurant_menu.items]]
	title = "Green garden salad"
	description = "Green garden salad with cured meat and cheese pieces"
	price = 14.50

	[[restaurant_menu.items]]
	title = "Creamy soup"
	description = "Creamy soup made out of Riesling from the hills of Zürich, with nut bread croutons"
	price = 12.50

	[[restaurant_menu.items]]
	title = "Swiss specialty Capuns"
	description = "Pasta and bacon filling wrapped in Swiss chard leaves topped with creamy cheese sauce"
	price = 14.50

	[[restaurant_menu.items]]
	title = "Felsenegg plate"
	description = "Dried cured meats, bacon and Swiss cheese"
	price = 12.00

	[[restaurant_menu.items]]
	title = "Bouillon with colorful vegetable"
	description = ""
	price = 11.00

	[[restaurant_menu.items]]
	title = "Sliced garlic bread"
	description = "Skewer with smoked ham and honeydew melon"
	price = 13.00

[[restaurant_menu]]
id = "main"
name = "Mains"

	
	[[restaurant_menu.items]]
	title = "Geschnetzeltes Zurich style"
	description = "strips of veal in a cream and mushroom sauce potato röschti on the side"
	price = 38.00

	[[restaurant_menu.items]]
	title = "Roastbeef"
	description = "Served with sauce bernaise, potato gratin and vegetables"
	price = 39.00

	[[restaurant_menu.items]]
	title = "Filet of pork"
	description = "Served with a sauce made out of cognac and mustard, croquettes and vegetables on the side"
	price = 38.00

	[[restaurant_menu.items]]
	title = "Veal Escalope’s"
	description = "Piccata Italien style. Escalope’s in an egg-parmesan-coat with mushrooms and pieces of ham in tomato sauce served with risotto and vegetables"
	price = 35.00

	[[restaurant_menu.items]]
	title = "Homemade meat loaf"
	description = "Served with mashed potatoes and vegetables"
	price = 33.00

	[[restaurant_menu.items]]
	title = "Veal cutlets"
	description = "Veal cutlets with a creamy sauce made out of figs, thin noodles and vegetables"
	price = 38.00

	[[restaurant_menu.items]]
	title = "Spiced beef filet skewer"
	description = "Served with baked potato, sour cream and corn on the cob"
	price = 39.50

	[[restaurant_menu.items]]
	title = "Lean pork neck wrapped in bacon"
	description = "Served with potato gratin and vegetables"
	price = 36.50

	[[restaurant_menu.items]]
	title = "Raclette"
	description = "The fun way to melt cheese"
	price = 39.00

	[[restaurant_menu.items]]
	title = "Meat Fondue Winzerart"
	description = "homemade with our specialty red wine bouillon for an exciting taste. Small slices of Swiss veal, beef, chicken and pork all sourced from the local butcher. Served with fries, silver skin pickled onions, baby gherkin, baby sweet corn, miniature mushrooms and garlic. Sauces include cocktail, tartar, garlic, curry and spicy barbecue."
	price = 55.00


[[restaurant_menu]]
id = "desert"
name = "Desert"

	[[restaurant_menu.items]]
	title = "Meringue with ice cream"
	description = "Served with whipped cream"
	price = 12.00

	[[restaurant_menu.items]]
	title = "Fresh fruit salad"
	description = ""
	price = 12.50

	[[restaurant_menu.items]]
	title = "Light caramelized pancake"
	description = "Served with with plums in syrup"
	price = 14.50

	[[restaurant_menu.items]]
	title = "Homemade apple strudel"
	description = "Served with vanilla sauce or vanilla ice cream"
	price = 14.50

	[[restaurant_menu.items]]
	title = "Pumpkin seed parfait"
	description = "Served with baileys cream"
	price = 14.50

	[[restaurant_menu.items]]
	title = "Crepe with vanilla ice cream"
	description = "Served with warm chocolate sauce and whipped cream"
	price = 13.50

	[[restaurant_menu.items]]
	title = "Caramel custard"
	description = "Served with whipped cream"
	price = 11.00

	[[restaurant_menu.items]]
	title = "Light apple custard"
	description = "Served with whipped cream"
	price = 11.00
	

[[restaurant_menu]]
id = "wine"
name = "Wines"

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