<script>
	import Navbar from '../components/navbar.svelte';
	import Footer from '../components/footer.svelte';
</script>

<div class="bg-gray-500	shadow-lg  ">
	<title>NB GEARS - Contact us</title>
	<Navbar />
	<link
		href="https://cdnjs.cloudflare.com/ajax/libs/flowbite/1.6.3/flowbite.min.css"
		rel="stylesheet"
	/>
	<main class=" box-border bg-gray-300 m4 rounded-xl p-4 shadow-xl Bigcon">
		<div class="" style="Bigcon object-scale-down mx-auto pb-10 rounded-3xl ">
			<h1 class="text-5xl margin: 40px; Bigcon">Contact us Via</h1>
			<p class="Maincon">
				<br />Email:
				<a href="mailto:contact@nbgears.tech" class="text-blue-700">Contact@nbgears.tech</a>
			</p>

			<p class="Maincon">
				Locations<br />
				KING MONGKUT'S UNIVERSITY OF TECHNOLOGY NORTH BANGKOK <br />
				Thai-German Pre-Engineering School Building
				<br />1518 Pracharat 1 Road,Wongsawang, Bangsue,
				<br />Bangkok 10800<br /><br />
				To travel to NB Gears, you can take the MRT to Bang Pho Station and take bus via 32/33(2-6)/64/3-55/117.
			</p>

			<div class=" align-items: center; Maincon">
				<iframe
					title="Location Map"
					width="100%"
					height="450"
					style="border:0"
					loading="lazy"
					allowfullscreen
					src="https://calendar.google.com/calendar/embed?height=600&wkst=1&bgcolor=%23E67C73&ctz=Asia%2FBangkok&showNav=0&showTitle=0&showDate=0&showTabs=0&showPrint=0&showTz=0&showCalendars=1&src=c2lyYXZpamJiQGdtYWlsLmNvbQ&src=OGJkY2ZlMjA0Mjk4NWUwZDE4YzMwOGQ3YTI4M2E3ZWZjNTRiYTI3N2UwNzRiMTEyZjkzNmRkMjM0MDhmN2MyNkBncm91cC5jYWxlbmRhci5nb29nbGUuY29t&color=%237986CB&color=%237CB342"
				/>
			</div>
		</div>
	</main>
</div>
<Footer />

<style>
	.warper {
		font-family: 'IBM Plex Sans Thai', sans-serif;
	}
	.Maincon {
		font-size: 1.5rem;
		max-width: 1280px;
		margin: 40px auto;
	}
	.Bigcon {
		max-width: 1280px;
		margin: 40px auto;
	}
</style>
