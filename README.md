<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mfundiso Mzobe - Creative Portfolio</title>

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com/3.4.16"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            primary: '#6366f1',
            secondary: '#4f46e5'
          },
          borderRadius: {
            button: '8px'
          }
        }
      }
    }
  </script>

  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet" />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet" />

  <!-- Remix Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css" />

  <link rel="stylesheet" href="style.css" />
</head>
<body class="relative bg-[#0f172a] text-white font-['Inter']">

  <!-- Header -->
  <header class="fixed top-0 left-0 w-full z-50 bg-[#0f172a]/95 backdrop-blur-sm border-b border-slate-800">
    <div class="container mx-auto px-6 py-4 flex justify-between items-center">
      <a href="#" class="text-2xl font-['Pacifico'] text-white">Mfundiso's Portfolio</a>
      <nav class="hidden md:flex space-x-8">
        <a href="#home" class="nav-link text-slate-300 hover:text-white">Home</a>
        <a href="#portfolio" class="nav-link text-slate-300 hover:text-white">Portfolio</a>
        <a href="#about" class="nav-link text-slate-300 hover:text-white">About</a>
        <a href="#contact" class="nav-link text-slate-300 hover:text-white">Contact</a>
      </nav>
      <button class="md:hidden text-white">
        <i class="ri-menu-line ri-lg"></i>
      </button>
    </div>
  </header>

  <!-- Hero Section -->
  <section id="home" class="min-h-screen pt-24 flex items-center relative overflow-hidden">
    <div class="absolute inset-0">
      <div class="absolute inset-0 bg-gradient-to-r from-[#0f172a] via-[#0f172a] to-transparent z-10"></div>
      <img src="https://static.readdy.ai/image/1106ff0de00291ec2f3a42811feb26cf/e321698e2f9ffd39edaef7781cb3f8eb.jpeg" alt="Hero Background" class="absolute right-0 h-full w-1/2 object-cover object-top">
    </div>

    <div class="container mx-auto px-6 z-10">
      <div class="max-w-2xl">
        <span class="px-3 py-1 bg-primary/20 text-primary rounded-full text-sm font-medium mb-4 inline-block">Creative Designer</span>
        <h1 class="text-5xl md:text-7xl font-bold mb-6 leading-tight">
          I'm a Software <br /><span class="text-primary">Developer</span>
        </h1>
        <p class="text-xl text-slate-300 mb-8 max-w-lg">
          Final year IT student at Nelson Mandela University, passionate about creating innovative software solutions and user-friendly applications.
        </p>

        <div class="flex flex-col sm:flex-row gap-4">
          <a href="#portfolio" class="px-8 py-3 bg-primary text-white font-medium rounded-button hover:bg-primary/90 transition-all flex items-center justify-center">
            View My Work <i class="ri-arrow-right-line ml-2"></i>
          </a>
          <a href="#contact" class="px-8 py-3 border border-slate-700 text-white font-medium rounded-button hover:border-primary transition-all flex items-center justify-center">
            Contact Me
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio" class="py-20 bg-[#0c1424]">
    <div class="container mx-auto px-6 text-center">
      <span class="text-primary font-medium">My Recent Work</span>
      <h2 class="text-4xl font-bold mt-2 mb-16">Portfolio</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">

        <!-- Book Store -->
        <div class="rounded-lg overflow-hidden relative group">
          <img src="https://readdy.ai/api/search-image?query=bookstore%20ui&width=600&height=450" alt="Book Store System" class="w-full h-72 object-cover">
          <div class="absolute inset-0 bg-primary/80 flex flex-col justify-end p-6 opacity-0 group-hover:opacity-100 transition-all">
            <h3 class="text-xl font-bold">Book Store System</h3>
            <p class="text-white/80 mb-4">C# & ASP.NET Core MVC</p>
            <a href="#" class="inline-flex items-center text-white">View Project <i class="ri-arrow-right-line ml-2"></i></a>
          </div>
        </div>

        <!-- Weather App -->
        <div class="rounded-lg overflow-hidden relative group">
          <img src="https://readdy.ai/api/search-image?query=weather%20app%20ui&width=600&height=450" alt="Weather App" class="w-full h-72 object-cover">
          <div class="absolute inset-0 bg-primary/80 flex flex-col justify-end p-6 opacity-0 group-hover:opacity-100 transition-all">
            <h3 class="text-xl font-bold">Weather App</h3>
            <p class="text-white/80 mb-4">HTML, CSS & JavaScript</p>
            <a href="#" class="inline-flex items-center text-white">View Project <i class="ri-arrow-right-line ml-2"></i></a>
          </div>
        </div>

        <!-- To-Do List -->
        <div class="rounded-lg overflow-hidden relative group">
          <img src="https://readdy.ai/api/search-image?query=todo%20list%20app%20ui&width=600&height=450" alt="To-Do List Web App" class="w-full h-72 object-cover">
          <div class="absolute inset-0 bg-primary/80 flex flex-col justify-end p-6 opacity-0 group-hover:opacity-100 transition-all">
            <h3 class="text-xl font-bold">To Do List Web App</h3>
            <p class="text-white/80 mb-4">HTML, CSS & JavaScript</p>
            <a href="#" class="inline-flex items-center text-white">View Project <i class="ri-arrow-right-line ml-2"></i></a>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-20">
    <div class="container mx-auto px-6 grid lg:grid-cols-2 gap-12 items-center">
      <div class="relative">
        <img src="https://static.readdy.ai/image/1106ff0de00291ec2f3a42811feb26cf/e321698e2f9ffd39edaef7781cb3f8eb.jpeg" alt="About Me" class="rounded-lg w-full h-auto">
      </div>
      <div>
        <span class="text-primary font-medium">About Me</span>
        <h2 class="text-4xl font-bold mt-2 mb-6">Crafting Digital Experiences With Passion</h2>
        <p class="text-slate-300 mb-6">
          Final year Diploma student in Information Technology (Software Development) at Nelson Mandela University, driven by a passion for technology and innovation.
        </p>
        <p class="text-slate-300 mb-8">
          Skilled in full-stack development, system analysis, and data-driven solutions. I enjoy creating modern, efficient, and user-focused web applications.
        </p>
        <a href="#" class="px-8 py-3 bg-primary text-white font-medium rounded-button hover:bg-primary/90 inline-flex items-center">
          Download CV <i class="ri-download-line ml-2"></i>
        </a>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-20">
    <div class="container mx-auto px-6 text-center">
      <span class="text-primary font-medium">Get In Touch</span>
      <h2 class="text-4xl font-bold mt-2 mb-16">Contact Me</h2>
      <div class="max-w-lg mx-auto space-y-8 text-left">
        <div>
          <h4 class="font-bold mb-1">Email</h4>
          <p class="text-slate-300">mfundisomzobe@gmail.com</p>
        </div>
        <div>
          <h4 class="font-bold mb-1">Phone</h4>
          <p class="text-slate-300">+27 65 532 3843</p>
        </div>
        <div>
          <h4 class="font-bold mb-1">LinkedIn</h4>
          <a href="https://www.linkedin.com/in/mfundiso-mzobe-87b40a27a/" class="text-primary hover:underline">View Profile</a>
        </div>
      </div>
    </div>
  </section>

  <footer class="py-6 text-center text-slate-500 border-t border-slate-800">
    © 2025 Mfundiso Mzobe. All rights reserved.
  </footer>

</body>
</html>
