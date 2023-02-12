<script>
	import Navbar from '../components/navbar.svelte';
	import Footer from '../components/footer.svelte';
</script>

<div class="bg-gray-500	shadow-lg  ">
	<title>NB GEARS - About us</title>
	<Navbar />
	<link
		href="https://cdnjs.cloudflare.com/ajax/libs/flowbite/1.6.3/flowbite.min.css"
		rel="stylesheet"
	/>
	<main class=" box-border bg-gray-300 m4 rounded-xl p-4 shadow-xl Bigcon warper">
		<div class="" style="Bigcon object-scale-down mx-auto pb-10 rounded-3xl ">
			<h1 class="text-5xl margin: 40px; Bigcon">About Us</h1>
			<img
				src="NR_Gear_logo_white.png"
				class="w-full md:block md:w-auto flex items-center space-x-28 p-5 bg-gray-900 rounded-2xl"
				alt="NORTH BANGKOK GEEKS ENGINEERING AWESOME ROBOTIC SOLUTIONS"
			/>
			<p class="Maincon">
				&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Our story began by Mr.Punroon who was veteran member of
				NC&nbsp;GEARS, He was paticipated in FTC 2021 which he has a dream of FTC Team in thailand
				in our school.he wants to create a team to inspire the newer generation of young people to
				have experience with robotic events and improve their engineering skill in practical
				applications. One of our goals is to prove that teenagers that live in Bangkok also have the
				potential for competition. Via a connection with the NC GEARS team, they are able to give us
				the guidance into starting a proper team. Our team's name, "NB GEARS: stands for "North
				Bangkok Geeks Engineering Awesome Robotic Solutions" similar to our advising team.
			</p>
			<h1 class="text-5xl margin: 40px; Bigcon">Our Team Members</h1>
			<div class="Maincon">
				<div class="flex flex-wrap justify-between">
					<div class="w-25% md:w-1/3 lg:w-1/4 p-4 ">
					<a href="#punroon">
						<div class="hover:shadow-2xl bg-white hover:bg-neutral-200 shadow-lg rounded-lg overflow-hidden" id="punroon">
							<img class="w-full h-56 object-fit object-left" src="punroon.jpg" alt="avatar" />
							<div class="p-4">
								<h1 class="text-xl font-bold">Punroon Rarngrit</h1>
								<p class="text-gray-700 text-base">Founder of NB GEARS</p>
							</div>
						</div>
					</a>
					</div>
					<div class="w-25% md:w-1/3 lg:w-1/4 p-4">
						<a href="#siravij">
						<div class="hover:shadow-2xl bg-white hover:bg-neutral-200 shadow-lg rounded-lg overflow-hidden" id="siravij">
							<img class="w-full h-56 object-fit object-center" src="siravij.webp" alt="avatar" />
							<div class="p-4">
								<h1 class="text-xl font-bold">Siravij Praevisavakij</h1>
								<p class="text-gray-700 text-base">PCB Engineer of NB GEARS</p>
							</div>
						</div>
						</a>
					</div>

					<div class="w-25% md:w-1/3 lg:w-1/4 p-4">
						<a href="#Chayachon">
						<div class="hover:shadow-2xl bg-white hover:bg-neutral-200 shadow-lg rounded-lg overflow-hidden  " id="Chayachon">
							<img class="w-full h-56 object-fit object-right" src="Chayachon.jpg" alt="avatar" />
							<div class="p-4">
								<h1 class="text-xl font-bold">Chayachon Sa-ardiem</h1>
								<p class="text-gray-700 text-base">Head of Marketing at NB GEARS</p>
							</div>
						</div>
						</a>
					</div>
				</div>
				<div class="Maincon">
					<div class="flex flex-wrap justify-between">
						<div class="w-25% md:w-1/3 lg:w-1/4 p-4 ">
						<a href="#kittichok">
							<div class="hover:shadow-2xl bg-white hover:bg-neutral-200 shadow-lg rounded-lg overflow-hidden  " id="kittichok">
								<img class="w-full h-56 object-fit object-left" src="Kittichok.jpg" alt="avatar" />
								<div class="p-4">
									<h1 class="text-xl font-bold">Kittichok Pattanapa</h1>
									<p class="text-gray-700 text-base">Coding Engineer of NB GEARS</p>
								</div>
							</div>
						</a>
						</div>
						<div class="w-25% md:w-1/3 lg:w-1/4 p-4">
							<a href="#Jiradchai">
							<div class="hover:shadow-2xl bg-white hover:bg-neutral-200 shadow-lg rounded-lg overflow-hidden  " id="Jiradchai">
								<img class="w-full h-56 object-fit object-center" src="Jiradchai.jpg" alt="avatar" />
								<div class="p-4">
									<h1 class="text-xl font-bold">Jiradchai Srirattanawong</h1>
									<p class="text-gray-700 text-base">Marketing Teams of NB GEARS</p>
								</div>
							</div>
							</a>
						</div>
	
						<div class="w-25% md:w-1/3 lg:w-1/4 p-4">
							<a href="#Panatorn">
							<div class="hover:shadow-2xl bg-white hover:bg-neutral-200 shadow-lg rounded-lg overflow-hidden  " id="Panatorn">
								<img class="w-full h-56 object-fit object-right" src="Panatorn.jpg" alt="avatar" />
								<div class="p-4">
									<h1 class="text-xl font-bold">Panatorn Ponpet</h1>
									<p class="text-gray-700 text-base">Marketing at NB GEARS</p>
								</div>
							</div>
							</a>
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
		font-size: 1.25rem;
		max-width: 1280px;
		margin: 40px auto;
	}
	.Bigcon {
		max-width: 1280px;
		margin: 40px auto;
	}
</style>
