<script>
	import "./styles.css";
	import tivoli from "$lib/images/tivoli2.jpg";
	import location from "$lib/images/location.png";
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
				hämmentävältä sillä olet varma, että kutsun lähettäjä ei ole
				lähellekkään 60 vuotias. Nämä ovatkin 25 + 25 + 10 vuotis
				juhlat. Tämä tarkoittaa, että juhlistamme 25 vuotiaita
				Peppi-Lottaa ja Siniä, sekä 10 vuotista IsengardFunkHousea.
				Scrollaa alas päin ja tutustu juhlakaluihimme ja heidän välisiin
				suhteisiinsa paremmin.
			</p>
		</div>
		<div class="no_background_image"><img src={tivoli} alt="" /></div>
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
				että edes yksi laatikoista saisin kellot päässäsi soimaan
				tunnistuksen merkiksi.
			</p>
		</div>

		<div class="text-image-combo">
			<div class="image"><img src={tivoli} alt="" /></div>
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
			<div class="image"><img src={tivoli} alt="" /></div>
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
			<div class="image"><img src={tivoli} alt="" /></div>
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
		<div class="no_background_image"><img src={tivoli} alt="" /></div>
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
					<img src={location} alt="" />
				</div>
				<div class="point">
					ollicitLorem ipsum dolor sit amet, consectetur adipiscing
					elit. Sed auctor ex vel enim sollicitLorem ipsum dolor sit
					amet, consectetur adipiscing elit. Sed auctor ex vel enim
					sollicitLorem ipsum dolor sit amet, consectetur adipiscing
					elit. Sed auctor ex vel enim sollicit
				</div>
			</li>
			<li>
				<div class="icon">
					<img src={location} alt="" />
				</div>
				<div class="point">
					ollicitLorem ipsum dolor sit amet, consectetur adipiscing
					elit. Sed auctor ex vel enim sollicitLorem ipsum dolor sit
					amet, consectetur adipiscing elit. Sed auctor ex vel enim
					sollicitLorem ipsum dolor sit amet, consectetur adipiscing
					elit. Sed auctor ex vel enim sollicit
				</div>
			</li>
			<li>
				<div class="icon">
					<img src={location} alt="" />
				</div>
				<div class="point">
					ollicitLorem ipsum dolor sit amet, consectetur adipiscing
					elit. Sed auctor ex vel enim sollicitLorem ipsum dolor sit
					amet, consectetur adipiscing elit. Sed auctor ex vel enim
					sollicitLorem ipsum dolor sit amet, consectetur adipiscing
					elit. Sed auctor ex vel enim sollicit
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
		padding-top: 400px;
		h1,
		span {
			backdrop-filter: blur(2px);
			padding: 2px;
			width: fit-content;
		}
	}
	.no_background_image {
		z-index: 1;
		max-width: 100%;
		height: auto;
		overflow: hidden;
		margin: 100px 0;

		img {
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
				overflow: hidden;
				max-height: 300px;
				max-width: 100%;
				border-radius: 20px;
				margin-bottom: 50px;
			}

			img {
				object-fit: cover;
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
			&:nth-child(even) {
				flex-direction: row-reverse;
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
