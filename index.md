<!doctype html>
<html lang="en">
	<head>
		<title>Random pick for lol</title>
		<meta charset="utf-8">
		<meta name="description" content="what champion of league of legend play">
		<meta name="league of legends, champions, lines" content="league of legends champions">

		<title>auto pick</title>
		
		<!-- external CSS link -->
		<link rel="stylesheet" href="css/normalize.css">
		<link rel="stylesheet" href="css/style.css">

		<script>
			var line= prompt("what rol you want to play? ex: Assasin, Fighter, Mage, 						Marksmen, support, tank");
			// Our List of Assasins
			var assasins = [
				'Akali',
				'Ekko',
				'Evelynn',
				'Fiora',
				'Fizz',
				'Irelia',
				'Jax',
				'Katarina',
				'Master Yi',
				'Nocturne',
				'Pyke',
				'Rengar',
				'Shaco',
				'Zed',
				'Tryndamere'
			];
			
			var fighters = [
				'Aatrox',
				'Camile',
				'Darius',
				'Diana',
				'Elise',
				'Fizz',
				'Hecarim',
				'Gragas',
				'Illaoi',
				'Irelia',
				'Jarvan IV',
				'Jayce',
				'Lee sin',
				'Mordekaiser',
				'Olaf',
				'Pantheon',
				'Renekton',
				'Sett',
				'Sion',
				'Trundle',
				'Vi',
			];
			
			var = mages [
				'Ahri',
				'Anivia',
				'Annie',
				'Azir',
				'Brand'
				'Cassiopeia',
				'Heimerdinger',
				'Kassadin',
				'Leblanc',
				'Lissandra',
				'Lux',
				'Morgana',
				'Orianna',
				'Ryze',
				'Syndra',
				'Veigar',
				'Velkoz,
				'Vladimir',
				'Viktor',
				'Xerath',
				'Zoe',
				'Ziggs
			]
			
			var = marksmen [
				'Aphelios',
				'Ashe',
				'Caitlyn',
				'Corki',
				'Draven',
				'Ezreal',
				'Graves',
				'Jhin',
				'Jinx,
				'Kaisa',
				'Kalista',
				'Kindred',
				'Kogmaw',
				'Lucian',
				'Miss fortune',
				'Quinn',
				'Senna',
				'Sivir',
				'Tristana',
				'Teemo',
				'Twitch',
				'Varus',
				'Vayne',
				'Xayah',
			]
			
			var = supports [
				'Lulu',
				'Janna',
				'Karma',
				'Ivern',
				'Nami',
				'Rakan',
				'Sona',
				'Soraka',
				'Yummi',
				'Zilean'
			]
			
			// Our List of Friends
			var tanks = [
				'Alistar',
				'Blitzcrank',
				'Braum',
				'Dr mundo',
				'Galio',
				'Garen',
				'Leona',
				'Nasus',
				'Nautilus',
				'Ornn',
				'Rammus',
				'Sejuani',
				'Shen',
				'Tham kench',
				'Warwick',
				'Zac'
			];
			document.write(bars.length);
			var randomNumber = Math.floor(Math.random()*bars.length);
			var randomNumberFriends = Math.floor(Math.random()*friends.length);
			var barname = bars[randomNumber];
			var friendname = friends[randomNumberFriends];


			document.write("How about you go to <strong>" + barname + "</strong> with <strong>" + friendname + "</strong>?");
		
		</script>
	</head>
	<body>
		<!-- PAGE CONTENT WILL BE PRINTED HERE --> 
	</body>
</html>
