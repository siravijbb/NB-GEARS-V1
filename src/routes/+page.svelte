

<script>
  import Navbar from './components/navbar.svelte';
 

  

  import Carousel from './Carousel.svelte';

  const images = [
    './11.jpg',
    './12.jpg',
    './13.jpg',
    './14.jpg',
    './15.jpg',
    './16.jpg',
  ];
</script>





<div class="bg-gray-500	shadow-lg ">
  <Navbar />
    <link href="https://cdnjs.cloudflare.com/ajax/libs/flowbite/1.6.3/flowbite.min.css" rel="stylesheet" />
    <main class="Maincon box-border bg-gray-300 m4 rounded-xl p-4 shadow-xl ">
      
      <Carousel class="carousel-container s3 Maincon py-4	 object-scale-down mx-auto pb-10 rounded-3xl" autoplay="5000">
  {#each images as image, index (index)}
    <img class="object-cover object-scale-down center" src={image} />
  {/each}
  <span slot="left-control">&lt;</span>
  <span slot="right-control">&gt;</span>
</Carousel>



        
      
      <!-- The dots/circles -->

        <p class="py-4	">     
          <br>
          <b>For Inspiration and Recognition of Science and Technology (FIRST)</b> is and international youth organization that operates different levels of Robotics competitions from elementary through high school.
          <br>
          <br><b>FIRST</b> Robotics is open to elementary through high school students and combines the excitement of sport with the science and technology. <b>FIRST</b> commonly calls its competitions the Ultimate Sport for the Mind.
          <br>
          <br>A couple of other phrases used by <b>FIRST</b> participants are “the hardest fun you’ll ever have” and “the only high school sport where every kid can go pro.”
          <br>
          <br>Looking ahead to life after high school, the students that participate in <b>FIRST</b> gain access to millions of dollars in scholarships made by available by colleges, universities and corporations who support <b>FIRST</b>.
    </main>

    </div>
    <footer class="mt-12 mb-8 max-w-7xl mx-auto px-4 md:px-6 flex items-center text-gray-600 text-sm sm:text-base">
        <div class="space-x-2 flex">
          <a
            href="https://creatorsgarten.org/ring"
            title="Creatorsgarten"
          >
            <img src="/garten.svg" class="w-6 sm:w-8 aspect-square" alt="webring" />
          </a>
        </div>
        <div class="mx-4 h-6 sm:h-8 border-l-2 border-gray-300" />
        <p>© {new Date().getFullYear()} NB GEARS</p>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/flowbite/1.6.3/flowbite.min.js"></script>
      </footer>

    <style>
    .warper{
        font-family: 'IBM Plex Sans Thai', sans-serif;
        
    
    }
    .Maincon{
            
        font-size: 1.5rem;
            max-width: 1280px ;
            margin: 40px auto;
    }
    * {box-sizing:border-box}

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