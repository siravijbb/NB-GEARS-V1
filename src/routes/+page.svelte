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
			class="carousel-container s3 Maincon py-4	 object-scale-down mx-auto pb-10 rounded-3xl"
			autoplay="5000"
		>
			{#each images as image, index (index)}
				<img class="object-cover object-scale-down center" src={image} />
			{/each}
			<span slot="left-control">&lt;</span>
			<span slot="right-control">&gt;</span>
		</Carousel>

		<!-- The dots/circles -->

		<p class="py-4	">
			<br />
			<b>For Inspiration and Recognition of Science and Technology (FIRST)</b> is and international
			youth organization that operates different levels of Robotics competitions from elementary
			through high school.
			<br />
			<br /><b>FIRST</b> Robotics is open to elementary through high school students and combines
			the excitement of sport with the science and technology. <b>FIRST</b> commonly calls its
			competitions the Ultimate Sport for the Mind.
			<br />
			<br />A couple of other phrases used by <b>FIRST</b> participants are “the hardest fun you’ll
			ever have” and “the only high school sport where every kid can go pro.”
			<br />
			<br />Looking ahead to life after high school, the students that participate in <b>FIRST</b>
			gain access to millions of dollars in scholarships made by available by colleges, universities
			and corporations who support <b>FIRST</b>.
		</p>
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
