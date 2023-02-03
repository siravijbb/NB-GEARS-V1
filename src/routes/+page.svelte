<script>
  import Navbar from './components/navbar.svelte';
  
</script>

  

<div class="bg-gray-500	shadow-lg">
  <Navbar />
    <link href="https://cdnjs.cloudflare.com/ajax/libs/flowbite/1.6.3/flowbite.min.css" rel="stylesheet" />
    <main class="Maincon box-border bg-gray-300 m4 rounded-xl p-4 shadow-xl ">
      
      <div class="slideshow-container object-scale-down">

        <!-- Full-width images with number and caption text -->
        <div class="mySlides fade ">
          <div class="numbertext ">1 / 4</div>
          <img src="/11.jpg" style="">
          <div class="text">Caption Text</div>
        </div>
       <script>
          let slideIndex = 1;
showSlides(slideIndex);


// Thumbnail image controls
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let slideIndex = 0;
showSlides();

function showSlides() {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  slideIndex++;
  if (slideIndex > slides.length) {slideIndex = 1}
  slides[slideIndex-1].style.display = "block";
  setTimeout(showSlides, 2000); // Change image every 2 seconds
}
}
        </script>
        <div class="mySlides fade w-auto h-auto object-center	">
          <div class="numbertext">2 / 4</div>
          <img src="/12.jpg" style="">
          <div class="text">Caption Two</div>
        </div>
      
        <div class="mySlides fade w-auto h-auto object-center	">
          <div class="numbertext">3 / 4</div>
          <img src="/16.jpg" style="">
          <div class="text">Caption Three</div>
        </div>
        <div class="mySlides fade w-auto h-auto object-center	">
          <div class="numbertext">4 / 4</div>
          <img src="/14.jpg" style="">
          <div class="text">Caption Two</div>
        </div>
        <div class="mySlides fade w-auto h-auto object-center	">
          <div class="numbertext flex">4 / 4</div>
          <img src="/15.jpg" style=";
          ">
          <div class="text">Caption Two</div>
        </div>
        <div class="mySlides fade w-auto h-auto object-center	">
          <div class="numbertext">4 / 4</div>
          <img src="/13.jpg" style=";
          ">
          <div class="text">Caption Two</div>
        </div>
        
      <br>
        <!-- Next and previous buttons -->

      </div>
      <br>
      
      <!-- The dots/circles -->

        <p>     <b>For Inspiration and Recognition of Science and Technology (FIRST)</b> is and international youth organization that operates different levels of Robotics competitions from elementary through high school.
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
            
        font-size: 1rem;
            max-width: 1280px ;
            margin: 40px auto;
    }
    * {box-sizing:border-box}

 

.slideshow-container {
  position: static;
  object-fit: contain;
  display: flex;
  justify-content: center;
  align-items: center;
  position: static;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
}

.mySlides {
  display: none;
}

/* Next & previous buttons */
.prev,
.next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  margin-top: -22px;
  padding: 16px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover,
.next:hover {
  background-color: rgba(0, 0, 0, 0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active,
.dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {
    opacity: 0.4;
  }
  to {
    opacity: 1;
  }
}

@keyframes fade {
  from {
    opacity: 0.4;
  }
  to {
    opacity: 1;
  }
}
</style>