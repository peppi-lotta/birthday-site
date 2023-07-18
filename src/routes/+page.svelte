<script>
	import "./styles.scss";
	import location from "$lib/images/location.png";
	import calendar from "$lib/images/calendar.png";
	import clothes from "$lib/images/clothes.png";
	import time from "$lib/images/time.png";
	import sauna from "$lib/images/sauna.png";
	import cocktail from "$lib/images/cocktail.png";
	import gift from "$lib/images/gift.png";
	import everybody from "$lib/images/kokoporukka.png";
	import peppi from "$lib/images/peppi.jpeg";
	import sini from "$lib/images/sini.jpeg";
	import siniJaPeppi from "$lib/images/siniJaPeppi.png";
	import funkhouse from "$lib/images/funkhouse.jpeg";
</script>

<svelte:head>
	<title>Bileet!</title>
	<meta name="description" />
</svelte:head>

<section class="main_banner">
	<div class="wrap">
		<div class="title">
			<div class="typewriter">
				<span class="first-row">25 + 25 + 10 =</span>
				<h1>60v juhlat!</h1>
			</div>
			<p>
				Sinut on kutsuttu juhlimaan 60 vuotis- juhlia 19.8.2023. Tämä
				voi kuulostaa hämmentävältä, sillä olet (melko) varma, että
				kutsun lähettäjä ei ole lähellekään 60 vuotias. Nämä ovatkin 25
				+ 25 + 10 vuotis- juhlat. Tämä tarkoittaa, että juhlistamme
				25-vuotiaita Peppiä ja Siniä, sekä 10 vuotista
				IsengardFunkHousea.
			</p>
		</div>
		<div class="no_background_image"><img src={everybody} alt="" /></div>
	</div>
</section>

<section class="people">
	<div class="wrap">
		<div class="title">
			<h2>Ketä tässä juhlitaan?</h2>
			<p>
				Saatat edelleen tuntea olosi hämmentyneeksi, mutta näiden
				hauskojen infolaatikoiden jälkeen sinulla on parempi ymmärrys
				siitä, ketä olet tulossa juhlistamaan. Lukiessasi tätä toivomme,
				tunnistat edes yhden laatikon henkilöistä.
			</p>
		</div>

		<div class="text-image-combo">
			<div class="image square-animation"><img src={peppi} alt="" /></div>
			<h3>Peppi</h3>
			<p class="content">
				Peppi on lomautettu koodari ja nämäkin nettisivut ovat Pepin
				kädenjälkeä. Kuten voitte nähdä, hänellä on aivan liikaa vapaa
				aikaa. Peppi ja Sini tapasivat vuonna 2017 kun he molemmat
				aloittivat fysiikan opinnot. Fysiikan opinnot on heivattu
				elämästä, mutta ystävyys jäin. Sini onkin Pepin oma kultahammas.
			</p>
		</div>
		<div class="text-image-combo">
			<div class="image">
				<img src={sini} alt="" />
			</div>
			<h3>Sini</h3>
			<p class="content">
				Sini tutustui Peppiin, kun he aloittivat yhdessä fysiikan
				opinnot. Fyysikon ura jäi valitettavasti lyhyeksi , sillä Sini
				päätti ryhtyä legomasteriksi. Eurasta Turkuun eksynyt
				maalaistyttö löysi opiskelijaelämän, ketjuspeksaamisen ja kaiken
				musisoinnin lomassa hobitin ja tämän takia bileissä esiintyykin
				outo bändi.
			</p>
		</div>
		<div class="text-image-combo">
			<div class="image square-animation">
				<img src={funkhouse} alt="" />
			</div>
			<h3>IsengardFunkHouse</h3>
			<p class="content">
				Kymmenen vuotta sitten (2013) Ratapihan talossa alkoi kuulua
				funkin lätkytys, joka vei eräät hobitit matkalle. Tämä kiertue
				jatkuu edelleen, eikä bändi esittelyjä kaipaa eikä, tällaisista
				hyödykkään. Tämä viisi-hobittinen orkesteri jättää takuulla
				kuumaksi kuin Mordor. Groove on terävämpi kuin tikku Sauronin
				silmässä. Kipua! 
				<br><br>Yst. terv. Joonas, Tuomo, Lauri, Ossi ja Aku
			</p>
		</div>
	</div>
</section>

<section>
	<div class="wrap">
		<div class="no_background_image"><img src={siniJaPeppi} alt="" /></div>
	</div>
</section>

<section class="info">
	<div class="wrap">
		<div class="title">
			<h2>Mitä sinun, rakas kutsuvieraamme, pitäisi tietää?</h2>
		</div>
		<ul>
			<li>
				<div class="icon">
					<img src={calendar} alt="" />
				</div>
				<p class="point">
					Juhlat järjestetään lauantaina <b>19.8.2023</b>
				</p>
			</li>
			<li>
				<div class="icon">
					<img src={time} alt="" />
				</div>
				<p class="point">
					Juhlat alkavat klo <b>18.00</b> ja päättyvät Tivolilla
					<b>2.00</b>. Tämä ei kuitenkaan estä jatkamasta
					juhlallisuuksia esimerkiksi läheisessä karaole baarissa ;).
				</p>
			</li>
			<li>
				<div class="icon">
					<img src={location} alt="" />
				</div>
				<p class="point">
					<a href="https://goo.gl/maps/1b3TDE1bamauGCLP8"
						>Tivoli, Uudenmaankatu 16, 20500 Turku</a
					>
				</p>
			</li>
			<li>
				<div class="icon">
					<img src={clothes} alt="" />
				</div>
				<p class="point">
					Toivomme juhlijoiden ilmestyvän paikalle juhlavasti
					pukeutuneena. Pukukoodina on cocktail-mekko, puku tai
					vastaavan kaltainen juhlavapukeutuminen.
				</p>
			</li>
			<li>
				<div class="icon">
					<img src={cocktail} alt="" />
				</div>
				<p class="point">
					Juhlissa ei ole tarjoilua, joten oma pullo mukaan.
				</p>
			</li>
			<li>
				<div class="icon">
					<img src={sauna} alt="" />
				</div>
				<p class="point">
					Juhlatilasta löytyy sauna. Otathan siis omat saunakamat
					mukaan, jos haluat saunoa.
				</p>
			</li>
			<li>
				<div class="icon">
					<img src={gift} alt="" />
				</div>
				<p class="point">
					Emme odota lahjoja. Jos haluat muistaa meitä jotenkin voit
					laittaa Mobile Payssa muutaman rahan, jotka auttavat meitä
					vuokratilan kustannuksissa.
				</p>
			</li>
		</ul>
	</div>
</section>

<style lang="scss">
	section {
		display: flex;
		flex-direction: column;
		align-items: center;
	}

	p {
		text-shadow: 5px 5px 5px #100122;
		backdrop-filter: blur(8px);
		-webkit-backdrop-filter: blur(8px);
		padding: 2px;
		font-size: 20px;
	}
	h3 {
		font-size: 20px;
	}
	.wrap {
		z-index: 1;
		display: flex;
		flex-direction: column;
		align-items: center;
		text-align: left;
		width: calc(100% - 50px);
		max-width: 800px;
		padding: 0 25px;
		.title {
			display: flex;
			flex-direction: column;
			align-items: flex-start;
		}
	}
	h1,
	h2,
	.title span {
		font-weight: 700;
		text-shadow: 2px 2px 5px #100122;
		width: fit-content;
	}
	h1,
	.title span {
		font-size: 70px;
		@media screen and (max-width: 600px) {
			font-size: 50px;
		}
	}
	h2 {
		font-size: 50px;
		padding: 50px 0;
		@media screen and (max-width: 600px) {
			font-size: 30px;
		}
	}
	section.main_banner {
		padding-top: 200px;
		h1,
		span {
			backdrop-filter: blur(3px);
			-webkit-backdrop-filter: blur(3px);
			padding: 2px;
			width: fit-content;
		}
	}
	.no_background_image {
		z-index: 1;
		width: 100%;
		height: auto;
		overflow: hidden;
		margin: 75px;

		img {
			width: 100%;
			object-fit: contain;
		}
	}
	section.people {
		backdrop-filter: blur(15px);
		-webkit-backdrop-filter: blur(15px);
		.text-image-combo {
			width: calc(100% - 50px);
			background-color: #100122;
			border-radius: 20px;
			padding: 50px 25px;
			margin-bottom: 50px;
			.image {
				position: relative;
				overflow: hidden;
				max-width: 100%;
				aspect-ratio: 1;
				border-radius: 20px;
				margin-bottom: 50px;
			}

			img {
				position: absolute;
				top: -20%;
				right: 0;
				width: 100%;
			}
		}
	}
	.typewriter {
		h1 {
			overflow: hidden; /* Ensures the content is not revealed until the animation */
			border-right: 0.15em solid whitesmoke; /* The typwriter cursor */
			white-space: nowrap; /* Keeps the content on a single line */
			margin: 0 auto; /* Gives that scrolling effect as the typing happens */
			letter-spacing: 0.15em; /* Adjust as needed */
			animation: typing 3.5s steps(40, end),
				blink-caret 0.75s step-end infinite;
		}
	}

	/* The typing effect */
	@keyframes typing {
		from {
			width: 0;
		}
		to {
			width: 100%;
		}
	}

	/* The typewriter cursor effect */
	@keyframes blink-caret {
		from,
		to {
			border-color: transparent;
		}
		50% {
			border-color: black;
		}
	}

	section.info {
		backdrop-filter: blur(15px);
		-webkit-backdrop-filter: blur(15px);
		padding-bottom: 100px;
		ul {
			display: flex;
			flex-direction: column;
			align-items: center;
			margin: 0;
			padding: 0;
		}
		li {
			display: flex;
			padding: 25px 0;
			max-width: 400px;
			align-items: center;
			justify-content: center;
			&:nth-child(even) {
				flex-direction: row-reverse;
			}
			a {
				color: white;
				&:hover {
					color: #100122;
				}
			}
		}
		.icon {
			display: flex;
			align-items: center;
			justify-content: flex-end;
			img {
				height: 70px;
				width: 70px;
				object-fit: contain;
				margin: 25px;
			}
		}
	}
</style>
