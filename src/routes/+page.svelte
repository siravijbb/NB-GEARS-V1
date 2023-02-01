<script>
  import Navbar from './components/navbar.svelte';
</script>
  

<div class="warper mx-4 ">
  <Navbar />
    
    <main class="Maincon box-border bg-gray-300 m4 rounded-xl p-4 shadow-xl">
        <img src="/pic.webp" class="s3 mx-auto pb-10 rounded-3xl" alt="me"   />
        <p>     I am an failure analysis engineer, Who looking for new challanges from past experience from sattlelite PCB to a new challenges. In web programing, I'm currently learning web technologies with using some experience with coding in school.
                Also when I had free time, I am a maker who made phototype of things that I wanted to combine to reduce size, Over the past 3 years,<br>I have been hosting server as additional hobby which made me familar with networking. <br>And also I owned scooter for using in Bangkok for reducing and precise timing in life schedual.</p>
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
        <p>© {new Date().getFullYear()} Siravij Praevisavakij</p>
      </footer>

    <style>
    .warper{
        font-family: 'IBM Plex Sans Thai', sans-serif;
        
    
    }
    .Maincon{
            
        font-size: 1.875rem;
            max-width: 1280px ;
            margin: 40px auto;
    }
    </style>
    