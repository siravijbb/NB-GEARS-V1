<script>
  import Navbar from './components/navbar.svelte';
  
</script>

  

<div class="bg-gray-500	shadow-lg">
  <Navbar />
    <link href="https://cdnjs.cloudflare.com/ajax/libs/flowbite/1.6.3/flowbite.min.css" rel="stylesheet" />
    <main class="Maincon box-border bg-gray-300 m4 rounded-xl p-4 shadow-xl">
        <img src="/sample.jpg" class="s3 object-scale-down mx-auto pb-10 rounded-3xl" alt="me"   />
        <p>     Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
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
            
        font-size: 1.875rem;
            max-width: 1280px ;
            margin: 40px auto;
    }
    </style>
    