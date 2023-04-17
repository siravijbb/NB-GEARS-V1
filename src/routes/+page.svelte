<script>
	import Navbar from './components/navbar.svelte';
	import Footer from './components/footer.svelte';

	import Carousel from './Carousel.svelte';

	const images = ['./11.jpg', './12.jpg', './13.jpg', './14.jpg', './15.jpg', './16.jpg'];
</script>

<div class="bg-gray-500	shadow-lg ">
	<title>NB GEARS - Home</title>
	<Navbar />
	<link
		href="https://cdnjs.cloudflare.com/ajax/libs/flowbite/1.6.3/flowbite.min.css"
		rel="stylesheet"
	/>
	<main class="Maincon box-border bg-gray-300 m4 rounded-xl p-4 shadow-xl ">
		<Carousel
			class="carousel-container s3 Maincon py-4 object-scale-down mx-auto pb-10 rounded-3xl"
			autoplay="5000"
		>
			{#each images as image, index (index)}
				<img class="object-cover object-scale-down center mx-auto  max-h-96" src={image} />
			{/each}
			<span slot="left-control">&lt;</span>
			<span slot="right-control">&gt;</span>
		</Carousel>

		<!-- The dots/circles -->

		<p class="py-4	">
			<br />
			<b>Our Mission</b> To expose the students around the area on STEM and to reveal the hidden
			talents of each person.
			<br />
			<br /><b>Our Vision</b> Our vision is to show the capability of Thai engineering at its best
			and emphasize the creativity of our members.
			<br />
		</p>
		<h2 class="text-center"><b>Key Values</b></h2>
		<div class="py-4">
			<div class="grid grid-cols-2 gap-4 ">
				<div class="bg-gray-200 p-4 rounded-xl hover:bg-gray-400">
					<h2 class="text-center font-bold">Work as a team, think as a team.</h2>

					<p>
						A team cannot operate without a team, and an effective team needs to be open-minded and
						creative in their own ways.
					</p>
				</div>
				<div class="bg-gray-200 p-4 rounded-xl hover:bg-gray-400">
					<h2 class="text-center font-bold ">Think logically!</h2>

					<p>
						We care about being right and it often takes reasoning from first principles to get
						there.
					</p>
				</div>
				<div class="bg-gray-200 p-4 rounded-xl hover:bg-gray-400">
					<h2 class="text-center font-bold ">Gracious professionalism</h2>

					<p>A slogan by the FIRST robotic. The pinnacle of being a good player.</p>
				</div>
				<div class="bg-gray-200 p-4 rounded-xl hover:bg-gray-400">
					<h2 class="text-center font-bold ">Situational flexibility</h2>

					<p>We aim to be prepared for every situation posted in the unforeseeable future.</p>
				</div>
				<div class="bg-gray-200 p-4 rounded-xl hover:bg-gray-400">
					<h2 class="text-center font-bold ">Work as a team, think as a team.</h2>

					<p>
						A team cannot operate without a team, and an effective team needs to be open-minded and
						creative in their own ways.
					</p>
				</div>
				<div class="bg-gray-200 p-4 rounded-xl hover:bg-gray-400">
					<h2 class="text-center font-bold ">Think logically!</h2>

					<p>
						We care about being right and it often takes reasoning from first principles to get
						there.
					</p>
				</div>
			</div>

			<div class="grid grid-cols-1 gap-4 py-4">
				<div class="bg-gray-200 p-4 rounded-xl hover:bg-gray-400">
					<h2 class="text-center font-bold">Optimism</h2>

					<p class="text-center">
						We had already won at the moment we are at the field. <br />
						By just being in the competition, we had already won the grand prize of the competition,
						experiences.
					</p>
				</div>
				<div class="bg-gray-200 p-4 rounded-xl hover:bg-gray-400">
					<h2 class="text-center font-bold">The true meaning</h2>

					<p class="text-center">“Once a GEARS always a GEARS.”, NC GEARS.</p>
				</div>
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
	* {
		box-sizing: border-box;
	}

	div2 {
		height: 950rem;
		width: 950rem;
	}

	span2 {
		display: inline-block;
		margin-top: 10rem;
	}
	img2 {
		height: auto;
		max-width: 720px;
	}

	span {
		display: inline-flexbox;
		margin-top: 40px;
		margin: 40px auto;
	}
	.carousel-container {
		display: flex;
		align-items: center;
		justify-content: center;
		
	}
</style>
