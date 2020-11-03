<title>What champ pick?</title>

<!-- external CSS link -->
<link rel="stylesheet" href="css/normalize.css">
<link rel="stylesheet" href="css/style.css">

	<script>
		var role= prompt("what role you want to play? ex. assasin, marksmen, fighter, tank, support, mage");
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

		var  mages = [
				'Ahri',
						'Anivia',
						'Annie',
						'Azir',
						'Brand',
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
				'Velkoz',
		'Vladimir',
				'Viktor',
				'Xerath',
				'Zoe',
				'Ziggs'
		];

		var  marksmens = [
				'Aphelios',
						'Ashe',
						'Caitlyn',
						'Corki',
						'Draven',
						'Ezreal',
						'Graves',
						'Jhin',
						'Jinx',
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

		var  supports = [
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

		var randomAssasin = Math.floor(Math.random()*assasins.length);
		var randomFighter = Math.floor(Math.random()*fighters.length);
		var randomMage = Math.floor(Math.random()*mages.length);
		var randomMarksmen = Math.floor(Math.random()*marksmens.length);
		var randomSupport = Math.floor(Math.random()*supports.length);
		var randomTank = Math.floor(Math.random()*tanks.length);

		/*
		var randomNumberFriends = Math.floor(Math.random()*friends.length);
		var barname = bars[randomNumber];
		var friendname = friends[randomNumberFriends];
		*/

		var assasinName = assasins[randomAssasin];
		var fighterName = fighters[randomFighter];
		var mageName = mages[randomMage];
		var marksmenName = marksmens[randomMarksmen];
		var supportName = supports[randomSupport];
		var tankName = tanks[randomTank];

		if(role.toLowerCase() === 'assasin'){
			document.write("You can play with <strong>" + assasinName);
		}
		else if(role.toLowerCase() === 'fighter'){
			document.write("You can play with <strong>" + fighterName);
		}
		else if(role.toLowerCase() === 'mage'){
			document.write("You can play with <strong>" + mageName);
		}
		else if(role.toLowerCase() === 'marksmen'){
			document.write("You can play with <strong>" + marksmenName);
		}
		else if(role.toLowerCase() === 'support'){
			document.write("You can play with <strong>" + supportName);
		}
		else if(role.toLowerCase() === 'tank'){
			document.write("You can play with <strong>" + tankName);
		}
		else{
			document.write("You must choose a role");
		}


	</script>

</head>

<body>
<!-- PAGE CONTENT WILL BE PRINTED HERE -->
</body>
