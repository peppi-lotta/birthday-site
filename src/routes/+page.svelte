<script>
	import "./styles.css";
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
				Onneksi olkoon sinä onnekas ihmisoletettu! Sinut on kutsuttu
				juhlimaan 60 vuotis juhlia 19.8.2023. Tämä voi kuulostaa
				hämmentävältä sillä olet (melko) varma, että kutsun lähettäjä ei
				ole lähellekkään 60 vuotias. Nämä ovatkin 25 + 25 + 10 vuotis
				juhlat. Tämä tarkoittaa, että juhlistamme 25 vuotiaita Peppiä ja
				Siniä, sekä 10 vuotista IsengardFunkHousea.
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
			<div class="content">
				Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed
				auctor ex vel enim sollicitLorem ipsum dolor sit amet,
				consectetur adipiscing elit. Sed auctor ex vel enim
				sollicitLorem ipsum dolor sit amet, consectetur adipiscing elit.
				Sed auctor ex vel enim sollicitLorem ipsum dolor sit amet,
				consectetur adipiscing elit. Sed auctor ex vel enim
				sollicitLorem ipsum dolor sit amet, consectetur adipiscing elit.
				Sed auctor ex vel enim sollicit
			</div>
		</div>
		<div class="text-image-combo">
			<div class="image">
				<img src={sini} alt="" />
			</div>
			<h3>Sini</h3>
			<div class="content">
				Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed
				auctor ex vel enim sollicitLorem ipsum dolor sit amet,
				consectetur adipiscing elit. Sed auctor ex vel enim
				sollicitLorem ipsum dolor sit amet, consectetur adipiscing elit.
				Sed auctor ex vel enim sollicitLorem ipsum dolor sit amet,
				consectetur adipiscing elit. Sed auctor ex vel enim sollicit
			</div>
		</div>
		<div class="text-image-combo">
			<div class="image square-animation">
				<img src={funkhouse} alt="" />
			</div>
			<h3>IsengardFunkHouse</h3>
			<div class="content">
				Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed
				auctor ex vel enim sollicitLorem ipsum dolor sit amet,
				consectetur adipiscing elit. Sed auctor ex vel enim
				sollicitLorem ipsum dolor sit amet, consectetur adipiscing elit.
				Sed auctor ex vel enim sollicit
			</div>
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
			<p>
				Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed
				auctor ex vel enim sollicitLorem ipsum dolor sit amet,
				consectetur adipiscing elit. Sed auctor ex vel enim
				sollicitLorem ipsum dolor sit amet, consectetur adipiscing elit.
				Sed auctor ex vel enim sollicitLorem ipsum dolor sit amet,
				consectetur adipiscing elit. Sed auctor ex vel enim
				sollicitLorem ipsum dolor sit amet, consectetur adipiscing elit.
				Sed auctor ex vel enim sollicit
			</p>
		</div>
		<ul>
			<li>
				<div class="icon">
					<img src={calendar} alt="" />
				</div>
				<div class="point">
					Juhlat järjestetään lauantaina <b>19.8.2023</b>
				</div>
			</li>
			<li>
				<div class="icon">
					<img src={time} alt="" />
				</div>
				<div class="point">
					Juhlat alkavat klo <b>18.00</b> ja päättyvät Tivolilla
					<b>2.00</b>. Tämä ei kuitenkaan estä jatkamasta
					juhlallisuuksia esimerkiksi läheisessä karaole baarissa ;).
				</div>
			</li>
			<li>
				<div class="icon">
					<img src={location} alt="" />
				</div>
				<div class="point">
					<a href="https://goo.gl/maps/1b3TDE1bamauGCLP8"
						>Tivoli, Uudenmaankatu 16, 20500 Turku</a
					>
				</div>
			</li>
			<li>
				<div class="icon">
					<img src={clothes} alt="" />
				</div>
				<div class="point">
					Toivomme juhlijoiden ilmestyvän paikalle juhlavasti
					pukeutuneena. Pukukoodina on cocktail-mekko, puku tai
					vastaavan kaltainen juhlavapukeutuminen.
				</div>
			</li>
			<li>
				<div class="icon">
					<img src={cocktail} alt="" />
				</div>
				<div class="point">Juhlat ovat omapullo mukaan</div>
			</li>
			<li>
				<div class="icon">
					<img src={sauna} alt="" />
				</div>
				<div class="point">
					Juhlatilasta löytyy sauna. Otathan siis omat saunakamat
					mukaan, jos haluat saunoa.
				</div>
			</li>
			<li>
				<div class="icon">
					<img src={gift} alt="" />
				</div>
				<div class="point">
					Emme odota lahjoja. Jos haluat muistaa meitä jotenkin voit
					laittaa Mobile Payssa muutaman rahan, jotka auttavat meitä
					vuokratilan kustannuksissa.
				</div>
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
			p {
				text-shadow: 2px 2px 10px #100122;
				backdrop-filter: blur(8px);
				padding: 2px;
			}
		}
	}
	h1,
	h2,
	.title span {
		font-weight: 700;
		text-shadow: 2px 2px 10px #ffff;
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
		@media screen and (max-width: 600px) {
			font-size: 30px;
		}
	}
	section.main_banner {
		padding-top: 200px;
		h1,
		span {
			backdrop-filter: blur(2px);
			padding: 2px;
			width: fit-content;
		}
	}
	.no_background_image {
		z-index: 1;
		width: 100%;
		height: auto;
		overflow: hidden;
		margin-bottom: 100px;

		img {
			width: 100%;
			object-fit: contain;
		}
	}
	section.people {
		backdrop-filter: blur(15px);
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
		padding-bottom: 100px;
		p {
			text-shadow: 2px 2px 10px #100122;
		}
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
	@keyframes wipe-enter {
		0% {
			opacity: 0;
			transform: translateY(20px);
		}
		100% {
			opacity: 1;
			transform: translateY(0);
		}
	}

	.wipe-enter-element {
		animation: wipe-enter 0.5s forwards;
		opacity: 0;
	}
</style>
