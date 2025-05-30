<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mfundiso Mzobe - Creative Portfolio</title>
<script src="https://cdn.tailwindcss.com/3.4.16"></script>
<script>tailwind.config={theme:{extend:{colors:{primary:'#6366f1',secondary:'#4f46e5'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css">
<link rel="stylesheet" href="style.css">

</head>
<body class="relative">
<div class="cursor-dot hidden md:block"></div>
<div class="cursor-outline hidden md:block"></div>
<!-- Header/Navigation -->
<header class="fixed top-0 left-0 w-full z-50 bg-[#0f172a] bg-opacity-95 backdrop-blur-sm border-b border-slate-800">
<div class="container mx-auto px-6 py-4">
<div class="flex justify-between items-center">
<a href="#" class="text-2xl font-['Pacifico'] text-white">Mfundiso's Portfolio</a>
<nav class="hidden md:flex space-x-8">
<a href="#home" class="nav-link text-slate-300 hover:text-white transition-colors">Home</a>
<a href="#portfolio" class="nav-link text-slate-300 hover:text-white transition-colors">Portfolio</a>
<a href="#about" class="nav-link text-slate-300 hover:text-white transition-colors">About</a>
<a href="#contact" class="nav-link text-slate-300 hover:text-white transition-colors">Contact</a>
</nav>
<button class="md:hidden w-10 h-10 flex items-center justify-center text-white">
<i class="ri-menu-line ri-lg"></i>
</button>
</div>
</div>
</header>
<!-- Mobile Menu (Hidden by default) -->
<div class="fixed inset-0 bg-[#0f172a] z-40 hidden flex-col justify-center items-center">
<nav class="flex flex-col space-y-6 text-center">
<a href="#home" class="text-xl text-white hover:text-primary transition-colors">Home</a>
<a href="#portfolio" class="text-xl text-white hover:text-primary transition-colors">Portfolio</a>
<a href="#about" class="text-xl text-white hover:text-primary transition-colors">About</a>
<a href="#contact" class="text-xl text-white hover:text-primary transition-colors">Contact</a>
</nav>
<button class="absolute top-6 right-6 w-10 h-10 flex items-center justify-center text-white">
<i class="ri-close-line ri-lg"></i>
</button>
</div>
<!-- Hero Section -->
<section id="home" class="min-h-screen pt-24 flex items-center relative overflow-hidden">
<div class="absolute inset-0 z-0">
<div class="absolute inset-0 bg-gradient-to-r from-[#0f172a] via-[#0f172a] to-transparent z-10"></div>
<img src="https://static.readdy.ai/image/1106ff0de00291ec2f3a42811feb26cf/e321698e2f9ffd39edaef7781cb3f8eb.jpeg "  alt="Hero Background" class="absolute right-0 h-full w-1/2 object-cover object-top">
</div>
<div class="container mx-auto px-6 z-10 w-full">
<div class="max-w-2xl">
<div class="mb-4 inline-block">
<span class="px-3 py-1 bg-primary bg-opacity-20 text-primary rounded-full text-sm font-medium">Creative Designer</span>
</div>
<h1 class="text-5xl md:text-7xl font-bold mb-6 text-white leading-tight">
I'm a Software <br>
<span class="text-primary">Developer</span>
</h1>
<p class="text-xl text-slate-300 mb-8 max-w-lg">
Final year IT student at Nelson Mandela University, passionate about creating innovative software solutions and user-friendly applications.
</p>
<div class="flex flex-col sm:flex-row gap-4">
<a href="#portfolio" class="px-8 py-3 bg-primary hover:bg-opacity-90 text-white font-medium !rounded-button whitespace-nowrap transition-all flex items-center justify-center">
View My Work
<i class="ri-arrow-right-line ml-2"></i>
</a>
<a href="#contact" class="px-8 py-3 border border-slate-700 hover:border-primary text-white font-medium !rounded-button whitespace-nowrap transition-all flex items-center justify-center">
Contact Me
</a>
</div>
<div class="mt-16 flex items-center gap-8">
<a href="#" class="text-slate-400 hover:text-white transition-colors">
<div class="w-10 h-10 flex items-center justify-center">
<i class="ri-dribbble-line ri-lg"></i>
</div>
</a>
<a href="#" class="text-slate-400 hover:text-white transition-colors">
<div class="w-10 h-10 flex items-center justify-center">
<i class="ri-behance-line ri-lg"></i>
</div>
</a>
<a href="#" class="text-slate-400 hover:text-white transition-colors">
<div class="w-10 h-10 flex items-center justify-center">
<i class="ri-instagram-line ri-lg"></i>
</div>
</a>
<a href="#" class="text-slate-400 hover:text-white transition-colors">
<div class="w-10 h-10 flex items-center justify-center">
<i class="ri-linkedin-line ri-lg"></i>
</div>
</a>
</div>
</div>
</div>
</section>
<!-- Portfolio Section -->
<section id="portfolio" class="py-20 bg-[#0c1424]">
<div class="container mx-auto px-6">
<div class="text-center mb-16">
<span class="text-primary font-medium">My Recent Work</span>
<h2 class="text-4xl font-bold mt-2 text-white">Portfolio</h2>
</div>
<div class="mb-10 flex justify-center">
<div class="inline-flex bg-slate-800 p-1 rounded-full">
<button class="px-6 py-2 rounded-full bg-primary text-white font-medium whitespace-nowrap">All</button>

</div>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">

<!-- Portfolio Item 4 -->
<div class="portfolio-item rounded-lg overflow-hidden relative group">
<img src="https://readdy.ai/api/search-image?query=modern%20online%20bookstore%20interface%20showing%20book%20catalog%2C%20shopping%20cart%2C%20and%20checkout%20process%2C%20dark%20theme%20with%20elegant%20typography%20and%20book%20covers%20displayed%2C%20clean%20and%20professional%20e-commerce%20design%20for%20books&width=600&height=450&seq=4&orientation=landscape" alt="Book Store System" class="w-full h-72 object-cover">
<div class="portfolio-overlay absolute inset-0 bg-primary bg-opacity-80 flex flex-col justify-end p-6">
<h3 class="text-xl font-bold text-white">Book Store System</h3>
<p class="text-white text-opacity-80 mb-4">C# & ASP.NET Core MVC</p>
<a href="#" class="text-white inline-flex items-center">
View Project
<i class="ri-arrow-right-line ml-2"></i>
</a>
</div>
</div>
<!-- Portfolio Item 5 -->
<div class="portfolio-item rounded-lg overflow-hidden relative group">
<img src="https://readdy.ai/api/search-image?query=modern%20weather%20application%20interface%20showing%20temperature%2C%20weather%20conditions%2C%20and%20forecast%2C%20dark%20theme%20with%20weather%20icons%20and%20dynamic%20backgrounds%2C%20clean%20and%20minimalist%20design%20with%20weather%20data%20visualization%2C%20professional%20weather%20app%20UI%20showcase&width=600&height=450&seq=5&orientation=landscape" alt="Weather App" class="w-full h-72 object-cover">
<div class="portfolio-overlay absolute inset-0 bg-primary bg-opacity-80 flex flex-col justify-end p-6">
<h3 class="text-xl font-bold text-white">Weather App</h3>
<p class="text-white text-opacity-80 mb-4">HTML, CSS & JavaScript</p>
<a href="#" class="text-white inline-flex items-center">
View Project
<i class="ri-arrow-right-line ml-2"></i>
</a>
</div>
</div>
<!-- Portfolio Item 6 -->
<div class="portfolio-item rounded-lg overflow-hidden relative group">
<img src="https://readdy.ai/api/search-image?query=modern%20to-do%20list%20web%20application%20interface%20with%20clean%20design%2C%20task%20management%20dashboard%2C%20dark%20theme%20with%20blue%20accents%2C%20showing%20task%20cards%20and%20interactive%20elements%2C%20professional%20web%20app%20showcase&width=600&height=450&seq=6&orientation=landscape" alt="To Do List Web App" class="w-full h-72 object-cover">
<div class="portfolio-overlay absolute inset-0 bg-primary bg-opacity-80 flex flex-col justify-end p-6">
<h3 class="text-xl font-bold text-white">To Do List Web App</h3>
<p class="text-white text-opacity-80 mb-4">HTML, CSS & JavaScript</p>
<a href="#" class="text-white inline-flex items-center">
View Project
<i class="ri-arrow-right-line ml-2"></i>
</a>
</div>
</div>
</div>
<div class="text-center mt-12">

<i class="ri-arrow-right-line ml-2"></i>
</a>
</div>
</div>
</section>
<!-- About Section -->
<section id="about" class="py-20">
<div class="container mx-auto px-6">
<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
<div class="relative">
<div class="absolute -top-6 -left-6 w-24 h-24 bg-primary bg-opacity-20 rounded-lg"></div>
<div class="absolute -bottom-6 -right-6 w-24 h-24 bg-primary bg-opacity-20 rounded-lg"></div>
<img src="https://static.readdy.ai/image/1106ff0de00291ec2f3a42811feb26cf/e321698e2f9ffd39edaef7781cb3f8eb.jpeg" alt="About Me" class="w-full h-auto rounded-lg relative z-10">
</div>
<div>
<span class="text-primary font-medium">About Me</span>
<h2 class="text-4xl font-bold mt-2 mb-6 text-white">Crafting Digital Experiences With Passion</h2>
<p class="text-slate-300 mb-6">
Final year  student in Information Technology Software Development at Nelson Mandela University, driven by a passion for technology and innovation. I specialize in web development, user-friendly interface design, and data analytics.
</p>
<p class="text-slate-300 mb-8">
Experienced in both collaborative and individual projects, I bring strong troubleshooting, problem-solving, and analytical thinking skills. My expertise extends to systems design and analysis, decision support systems, and cost-effective coding practices.
</p>
<div class="grid grid-cols-2 gap-6 mb-8">
<div>
<h3 class="text-white font-bold mb-4">Education</h3>
<div class="mb-4">
<div class="flex justify-between mb-1">
<span class="text-slate-300"><!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mfundiso Mzobe - Creative Portfolio</title>
<script src="https://cdn.tailwindcss.com/3.4.16"></script>
<script>tailwind.config={theme:{extend:{colors:{primary:'#6366f1',secondary:'#4f46e5'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css">
<link rel="stylesheet" href="style.css">

</head>
<body class="relative">
<div class="cursor-dot hidden md:block"></div>
<div class="cursor-outline hidden md:block"></div>
<!-- Header/Navigation -->
<header class="fixed top-0 left-0 w-full z-50 bg-[#0f172a] bg-opacity-95 backdrop-blur-sm border-b border-slate-800">
<div class="container mx-auto px-6 py-4">
<div class="flex justify-between items-center">
<a href="#" class="text-2xl font-['Pacifico'] text-white">Mfundiso's Portfolio</a>
<nav class="hidden md:flex space-x-8">
<a href="#home" class="nav-link text-slate-300 hover:text-white transition-colors">Home</a>
<a href="#portfolio" class="nav-link text-slate-300 hover:text-white transition-colors">Portfolio</a>
<a href="#about" class="nav-link text-slate-300 hover:text-white transition-colors">About</a>
<a href="#contact" class="nav-link text-slate-300 hover:text-white transition-colors">Contact</a>
</nav>
<button class="md:hidden w-10 h-10 flex items-center justify-center text-white">
<i class="ri-menu-line ri-lg"></i>
</button>
</div>
</div>
</header>
<!-- Mobile Menu (Hidden by default) -->
<div class="fixed inset-0 bg-[#0f172a] z-40 hidden flex-col justify-center items-center">
<nav class="flex flex-col space-y-6 text-center">
<a href="#home" class="text-xl text-white hover:text-primary transition-colors">Home</a>
<a href="#portfolio" class="text-xl text-white hover:text-primary transition-colors">Portfolio</a>
<a href="#about" class="text-xl text-white hover:text-primary transition-colors">About</a>
<a href="#contact" class="text-xl text-white hover:text-primary transition-colors">Contact</a>
</nav>
<button class="absolute top-6 right-6 w-10 h-10 flex items-center justify-center text-white">
<i class="ri-close-line ri-lg"></i>
</button>
</div>
<!-- Hero Section -->
<section id="home" class="min-h-screen pt-24 flex items-center relative overflow-hidden">
<div class="absolute inset-0 z-0">
<div class="absolute inset-0 bg-gradient-to-r from-[#0f172a] via-[#0f172a] to-transparent z-10"></div>
<img src="https://static.readdy.ai/image/1106ff0de00291ec2f3a42811feb26cf/e321698e2f9ffd39edaef7781cb3f8eb.jpeg "  alt="Hero Background" class="absolute right-0 h-full w-1/2 object-cover object-top">
</div>
<div class="container mx-auto px-6 z-10 w-full">
<div class="max-w-2xl">
<div class="mb-4 inline-block">
<span class="px-3 py-1 bg-primary bg-opacity-20 text-primary rounded-full text-sm font-medium">Creative Designer</span>
</div>
<h1 class="text-5xl md:text-7xl font-bold mb-6 text-white leading-tight">
I'm a Software <br>
<span class="text-primary">Developer</span>
</h1>
<p class="text-xl text-slate-300 mb-8 max-w-lg">
Final year IT student at Nelson Mandela University, passionate about creating innovative software solutions and user-friendly applications.
</p>
<div class="flex flex-col sm:flex-row gap-4">
<a href="#portfolio" class="px-8 py-3 bg-primary hover:bg-opacity-90 text-white font-medium !rounded-button whitespace-nowrap transition-all flex items-center justify-center">
View My Work
<i class="ri-arrow-right-line ml-2"></i>
</a>
<a href="#contact" class="px-8 py-3 border border-slate-700 hover:border-primary text-white font-medium !rounded-button whitespace-nowrap transition-all flex items-center justify-center">
Contact Me
</a>
</div>
<div class="mt-16 flex items-center gap-8">
<a href="#" class="text-slate-400 hover:text-white transition-colors">
<div class="w-10 h-10 flex items-center justify-center">
<i class="ri-dribbble-line ri-lg"></i>
</div>
</a>
<a href="#" class="text-slate-400 hover:text-white transition-colors">
<div class="w-10 h-10 flex items-center justify-center">
<i class="ri-behance-line ri-lg"></i>
</div>
</a>
<a href="#" class="text-slate-400 hover:text-white transition-colors">
<div class="w-10 h-10 flex items-center justify-center">
<i class="ri-instagram-line ri-lg"></i>
</div>
</a>
<a href="#" class="text-slate-400 hover:text-white transition-colors">
<div class="w-10 h-10 flex items-center justify-center">
<i class="ri-linkedin-line ri-lg"></i>
</div>
</a>
</div>
</div>
</div>
</section>
<!-- Portfolio Section -->
<section id="portfolio" class="py-20 bg-[#0c1424]">
<div class="container mx-auto px-6">
<div class="text-center mb-16">
<span class="text-primary font-medium">My Recent Work</span>
<h2 class="text-4xl font-bold mt-2 text-white">Portfolio</h2>
</div>
<div class="mb-10 flex justify-center">
<div class="inline-flex bg-slate-800 p-1 rounded-full">
<button class="px-6 py-2 rounded-full bg-primary text-white font-medium whitespace-nowrap">All</button>

</div>
</div>
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">

<!-- Portfolio Item 4 -->
<div class="portfolio-item rounded-lg overflow-hidden relative group">
<img src="https://readdy.ai/api/search-image?query=modern%20online%20bookstore%20interface%20showing%20book%20catalog%2C%20shopping%20cart%2C%20and%20checkout%20process%2C%20dark%20theme%20with%20elegant%20typography%20and%20book%20covers%20displayed%2C%20clean%20and%20professional%20e-commerce%20design%20for%20books&width=600&height=450&seq=4&orientation=landscape" alt="Book Store System" class="w-full h-72 object-cover">
<div class="portfolio-overlay absolute inset-0 bg-primary bg-opacity-80 flex flex-col justify-end p-6">
<h3 class="text-xl font-bold text-white">Book Store System</h3>
<p class="text-white text-opacity-80 mb-4">C# & ASP.NET Core MVC</p>
<a href="#" class="text-white inline-flex items-center">
View Project
<i class="ri-arrow-right-line ml-2"></i>
</a>
</div>
</div>
<!-- Portfolio Item 5 -->
<div class="portfolio-item rounded-lg overflow-hidden relative group">
<img src="https://readdy.ai/api/search-image?query=modern%20weather%20application%20interface%20showing%20temperature%2C%20weather%20conditions%2C%20and%20forecast%2C%20dark%20theme%20with%20weather%20icons%20and%20dynamic%20backgrounds%2C%20clean%20and%20minimalist%20design%20with%20weather%20data%20visualization%2C%20professional%20weather%20app%20UI%20showcase&width=600&height=450&seq=5&orientation=landscape" alt="Weather App" class="w-full h-72 object-cover">
<div class="portfolio-overlay absolute inset-0 bg-primary bg-opacity-80 flex flex-col justify-end p-6">
<h3 class="text-xl font-bold text-white">Weather App</h3>
<p class="text-white text-opacity-80 mb-4">HTML, CSS & JavaScript</p>
<a href="#" class="text-white inline-flex items-center">
View Project
<i class="ri-arrow-right-line ml-2"></i>
</a>
</div>
</div>
<!-- Portfolio Item 6 -->
<div class="portfolio-item rounded-lg overflow-hidden relative group">
<img src="https://readdy.ai/api/search-image?query=modern%20to-do%20list%20web%20application%20interface%20with%20clean%20design%2C%20task%20management%20dashboard%2C%20dark%20theme%20with%20blue%20accents%2C%20showing%20task%20cards%20and%20interactive%20elements%2C%20professional%20web%20app%20showcase&width=600&height=450&seq=6&orientation=landscape" alt="To Do List Web App" class="w-full h-72 object-cover">
<div class="portfolio-overlay absolute inset-0 bg-primary bg-opacity-80 flex flex-col justify-end p-6">
<h3 class="text-xl font-bold text-white">To Do List Web App</h3>
<p class="text-white text-opacity-80 mb-4">HTML, CSS & JavaScript</p>
<a href="#" class="text-white inline-flex items-center">
View Project
<i class="ri-arrow-right-line ml-2"></i>
</a>
</div>
</div>
</div>
<div class="text-center mt-12">

<i class="ri-arrow-right-line ml-2"></i>
</a>
</div>
</div>
</section>
<!-- About Section -->
<section id="about" class="py-20">
<div class="container mx-auto px-6">
<div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
<div class="relative">
<div class="absolute -top-6 -left-6 w-24 h-24 bg-primary bg-opacity-20 rounded-lg"></div>
<div class="absolute -bottom-6 -right-6 w-24 h-24 bg-primary bg-opacity-20 rounded-lg"></div>
<img src="https://static.readdy.ai/image/1106ff0de00291ec2f3a42811feb26cf/e321698e2f9ffd39edaef7781cb3f8eb.jpeg" alt="About Me" class="w-full h-auto rounded-lg relative z-10">
</div>
<div>
<span class="text-primary font-medium">About Me</span>
<h2 class="text-4xl font-bold mt-2 mb-6 text-white">Crafting Digital Experiences With Passion</h2>
<p class="text-slate-300 mb-6">
Final year Diploma student in Information Technology Software Development at Nelson Mandela University, driven by a passion for technology and innovation. I specialize in web development, user-friendly interface design, and data analytics.
</p>
<p class="text-slate-300 mb-8">
Experienced in both collaborative and individual projects, I bring strong troubleshooting, problem-solving, and analytical thinking skills. My expertise extends to systems design and analysis, decision support systems, and cost-effective coding practices.
</p>
<div class="grid grid-cols-2 gap-6 mb-8">
<div>
<h3 class="text-white font-bold mb-4">Education</h3>
<div class="mb-4">
<div class="flex justify-between mb-1">
<span class="text-slate-300">Diploma in Information Technology Software Development</span>
<span class="text-primary">Nelson Mandela University</span>
</div>
<p class="text-sm text-slate-400">Final Year Student</p>
</div>
<div class="mb-4">
<div class="flex justify-between mb-1">
<span class="text-slate-300">Web Development (HTML, CSS, jQuery)</span>
<span class="text-primary">85%</span>
</div>
<div class="skill-bar">
<div class="skill-progress" style="width: 85%"></div>
</div>
</div>
<div class="mb-4">
<div class="flex justify-between mb-1">
<span class="text-slate-300">Frameworks (ASP.Net Core MVC, Entity Framework)</span>
<span class="text-primary">88%</span>
</div>
<div class="skill-bar">
<div class="skill-progress" style="width: 88%"></div>
</div>
</div>
<div>
<div class="flex justify-between mb-1">
<span class="text-slate-300">Database Management (SQL Server)</span>
<span class="text-primary">92%</span>
</div>
<div class="skill-bar">
<div class="skill-progress" style="width: 92%"></div>
</div>
</div>
</div>
<div>
<h3 class="text-white font-bold mb-4">Development Tools & Version Control</h3>
<div class="flex flex-col space-y-4">
<div>
<p class="text-primary font-medium">IDEs</p>
<p class="text-white">PyCharm, Visual Studio, Visual Studio Code</p>
</div>
<div>
<p class="text-primary font-medium">Version Control</p>
<p class="text-white">Git, GitHub</p>
</div>
<div>
<p class="text-primary font-medium">Additional Libraries</p>
<p class="text-white">Dapper, LINQ</p>
</div>
</div>
</div>
</div>
<a href="#" class="px-8 py-3 bg-primary hover:bg-opacity-90 text-white font-medium !rounded-button whitespace-nowrap transition-all inline-flex items-center justify-center">
Download CV
<i class="ri-download-line ml-2"></i>
</a>
</div>
</div>
</div>
</section>
<!-- Contact Section -->
<section id="contact" class="py-20">
<div class="container mx-auto px-6">
<div class="text-center mb-16">
<span class="text-primary font-medium">Get In Touch</span>
<h2 class="text-4xl font-bold mt-2 text-white">Contact Me</h2>
</div>
<div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
<div>
<div class="mb-8">
<h3 class="text-2xl font-bold text-white mb-4">Let's Talk About Your Project</h3>
<p class="text-slate-300">
I'm always open to discussing new projects, creative ideas or opportunities to be part of your vision.
</p>
</div>
<div class="space-y-6">
<div class="flex items-start">
<div class="w-12 h-12 bg-primary bg-opacity-20 rounded-lg flex items-center justify-center mr-4 flex-shrink-0">
<div class="w-6 h-6 flex items-center justify-center text-primary">
<i class="ri-mail-line"></i>
</div>
</div>
<div>
<h4 class="text-white font-medium mb-1">Email</h4>
<p class="text-slate-300">mfundisomzobe@gmail.com</p>
</div>
</div>
<div class="flex items-start">
<div class="w-12 h-12 bg-primary bg-opacity-20 rounded-lg flex items-center justify-center mr-4 flex-shrink-0">
<div class="w-6 h-6 flex items-center justify-center text-primary">
<i class="ri-phone-line"></i>
</div>
</div>
<div>
<h4 class="text-white font-medium mb-1">Phone</h4>
<p class="text-slate-300">+27 65 532 3843</p>
</div>
</div>
<div class="flex items-start">
<div class="w-12 h-12 bg-primary bg-opacity-20 rounded-lg flex items-center justify-center mr-4 flex-shrink-0">
<div class="w-6 h-6 flex items-center justify-center text-primary">
<i class="ri-linkedin-fill"></i>
</div>
</div>
<div>
<h4 class="text-white font-medium mb-1">LinkedIn</h4>
<a href="https://www.linkedin.com/in/mfundiso-mzobe-87b40a27a/" class="text-slate-300 hover:text-primary transition-colors">View Profile</a>
</div>
</div>
</div>
<div class="mt-8">
<h4 class="text-white font-medium mb-4">Follow Me</h4>
<div class="flex space-x-4">
<a href="#" class="w-10 h-10 bg-[#131c31] rounded-full flex items-center justify-center text-slate-300 hover:text-white hover:bg-primary transition-colors">
<div class="w-5 h-5 flex items-center justify-center">
<i class="ri-dribbble-line"></i>
</div>
</a>
<a href="#" class="w-10 h-10 bg-[#131c31] rounded-full flex items-center justify-center text-slate-300 hover:text-white hover:bg-primary transition-colors">
<div class="w-5 h-5 flex items-center justify-center">
<i class="ri-behance-line"></i>
</div>
</a>
<a href="#" class="w-10 h-10 bg-[#131c31] rounded-full flex items-center justify-center text-slate-300 hover:text-white hover:bg-primary transition-colors">
<div class="w-5 h-5 flex items-center justify-center">
<i class="ri-instagram-line"></i>
</div>
</a>
<a href="#" class="w-10 h-10 bg-[#131c31] rounded-full flex items-center justify-center text-slate-300 hover:text-white hover:bg-primary transition-colors">
<div class="w-5 h-5 flex items-center justify-center">
<i class="ri-linkedin-line"></i>
</div>
</a>
</div>
</div>
</div>
<div>
<form class="space-y-6">
<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
<div>
<label for="name" class="block text-slate-300 mb-2">Name</label>
<input type="text" id="name" class="w-full px-4 py-3 rounded bg-[#131c31] border-none focus:ring-2 focus:ring-primary" placeholder="Your Name">
</div>
<div>
<label for="email" class="block text-slate-300 mb-2">Email</label>
<input type="email" id="email" class="w-full px-4 py-3 rounded bg-[#131c31] border-none focus:ring-2 focus:ring-primary" placeholder="Your Email">
</div>
</div>
<div>
<label for="subject" class="block text-slate-300 mb-2">Subject</label>
<input type="text" id="subject" class="w-full px-4 py-3 rounded bg-[#131c31] border-none focus:ring-2 focus:ring-primary" placeholder="Subject">
</div>
<div>
<label for="message" class="block text-slate-300 mb-2">Message</label>
<textarea id="message" rows="5" class="w-full px-4 py-3 rounded bg-[#131c31] border-none focus:ring-2 focus:ring-primary" placeholder="Your Message"></textarea>
</div>
<button type="submit" class="w-full px-8 py-3 bg-primary hover:bg-opacity-90 text-white font-medium !rounded-button whitespace-nowrap transition-all flex items-center justify-center">
Send Message
<i class="ri-send-plane-line ml-2"></i>
</button>
</form>
</div>
</div>
</div>
</section>
<!-- Footer -->
<footer class="py-10 bg-[#0c1424] border-t border-slate-800">
<div class="container mx-auto px-6">
<div class="flex flex-col md:flex-row justify-between items-center">
<div class="mb-4 md:mb-0">
<a href="#" class="text-2xl font-['Pacifico'] text-white">Mfundiso's Portfolio</a>
</div>
<div class="mb-4 md:mb-0">
<ul class="flex flex-wrap justify-center gap-6">
<li><a href="#home" class="text-slate-300 hover:text-white transition-colors">Home</a></li>
<li><a href="#portfolio" class="text-slate-300 hover:text-white transition-colors">Portfolio</a></li>
<li><a href="#about" class="text-slate-300 hover:text-white transition-colors">About</a></li>
<li><a href="#contact" class="text-slate-300 hover:text-white transition-colors">Contact</a></li>
</ul>
</div>
<div>
<p class="text-slate-400 text-sm">&copy; 2025 Mfundiso Mzobe. All rights reserved.</p>
</div>
</div>
</div>
</footer>
<!-- Back to Top Button -->
<button id="backToTop" class="fixed bottom-6 right-6 w-12 h-12 bg-primary rounded-full flex items-center justify-center text-white opacity-0 invisible transition-all duration-300 z-50">
<div class="w-6 h-6 flex items-center justify-center">
<i class="ri-arrow-up-line"></i>
</div>
</button>
<script>
document.addEventListener('DOMContentLoaded', function() {
// Mobile menu toggle
const menuButton = document.querySelector('.md\\:hidden');
const closeButton = document.querySelector('.absolute.top-6.right-6');
const mobileMenu = document.querySelector('.fixed.inset-0.bg-\\[\\#0f172a\\]');
if (menuButton && closeButton && mobileMenu) {
menuButton.addEventListener('click', function() {
mobileMenu.classList.remove('hidden');
mobileMenu.classList.add('flex');
});
closeButton.addEventListener('click', function() {
mobileMenu.classList.remove('flex');
mobileMenu.classList.add('hidden');
});
// Close mobile menu when clicking on a link
const mobileLinks = mobileMenu.querySelectorAll('a');
mobileLinks.forEach(link => {
link.addEventListener('click', function() {
mobileMenu.classList.remove('flex');
mobileMenu.classList.add('hidden');
});
});
}
// Smooth scrolling for anchor links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
anchor.addEventListener('click', function(e) {
e.preventDefault();
const targetId = this.getAttribute('href');
if (targetId === '#') return;
const targetElement = document.querySelector(targetId);
if (targetElement) {
window.scrollTo({
top: targetElement.offsetTop - 80,
behavior: 'smooth'
});
}
});
});
// Back to top button
const backToTopButton = document.getElementById('backToTop');
if (backToTopButton) {
window.addEventListener('scroll', function() {
if (window.pageYOffset > 300) {
backToTopButton.classList.remove('opacity-0', 'invisible');
backToTopButton.classList.add('opacity-100', 'visible');
} else {
backToTopButton.classList.remove('opacity-100', 'visible');
backToTopButton.classList.add('opacity-0', 'invisible');
}
});
backToTopButton.addEventListener('click', function() {
window.scrollTo({
top: 0,
behavior: 'smooth'
});
});
}
});
document.addEventListener('DOMContentLoaded', function() {
// Custom cursor effect
const cursorDot = document.querySelector('.cursor-dot');
const cursorOutline = document.querySelector('.cursor-outline');
if (cursorDot && cursorOutline && window.innerWidth > 768) {
window.addEventListener('mousemove', function(e) {
const posX = e.clientX;
const posY = e.clientY;
cursorDot.style.left = `${posX}px`;
cursorDot.style.top = `${posY}px`;
// Add a slight delay to the outline cursor for a trailing effect
setTimeout(() => {
cursorOutline.style.left = `${posX}px`;
cursorOutline.style.top = `${posY}px`;
}, 100);
});
// Hover effect on interactive elements
const interactiveElements = document.querySelectorAll('a, button, input, textarea, .portfolio-item');
interactiveElements.forEach(el => {
el.addEventListener('mouseenter', () => {
cursorDot.style.width = '0px';
cursorDot.style.height = '0px';
cursorOutline.style.width = '60px';
cursorOutline.style.height = '60px';
cursorOutline.style.borderColor = 'rgba(99, 102, 241, 0.8)';
});
el.addEventListener('mouseleave', () => {
cursorDot.style.width = '8px';
cursorDot.style.height = '8px';
cursorOutline.style.width = '40px';
cursorOutline.style.height = '40px';
cursorOutline.style.borderColor = 'rgba(99, 102, 241, 0.5)';
});
});
}
});
document.addEventListener('DOMContentLoaded', function() {
// Portfolio filter functionality
const filterButtons = document.querySelectorAll('.inline-flex.bg-slate-800 button');
if (filterButtons.length > 0) {
filterButtons.forEach(button => {
button.addEventListener('click', function() {
// Remove active class from all buttons
filterButtons.forEach(btn => {
btn.classList.remove('bg-primary', 'text-white');
btn.classList.add('text-slate-300');
});
// Add active class to clicked button
this.classList.remove('text-slate-300');
this.classList.add('bg-primary', 'text-white');
// Here you would normally filter the portfolio items
// For this demo, we're just changing the button styles
});
});
}
});
</script>
</body>
</html> Information Technology Software Development</span>
<span class="text-primary">Nelson Mandela University</span>
</div>
<p class="text-sm text-slate-400">Final Year Student</p>
</div>
<div class="mb-4">
<div class="flex justify-between mb-1">
<span class="text-slate-300">Web Development (HTML, CSS, jQuery)</span>
<span class="text-primary">85%</span>
</div>
<div class="skill-bar">
<div class="skill-progress" style="width: 85%"></div>
</div>
</div>
<div class="mb-4">
<div class="flex justify-between mb-1">
<span class="text-slate-300">Frameworks (ASP.Net Core MVC, Entity Framework)</span>
<span class="text-primary">88%</span>
</div>
<div class="skill-bar">
<div class="skill-progress" style="width: 88%"></div>
</div>
</div>
<div>
<div class="flex justify-between mb-1">
<span class="text-slate-300">Database Management (SQL Server)</span>
<span class="text-primary">92%</span>
</div>
<div class="skill-bar">
<div class="skill-progress" style="width: 92%"></div>
</div>
</div>
</div>
<div>
<h3 class="text-white font-bold mb-4">Development Tools & Version Control</h3>
<div class="flex flex-col space-y-4">
<div>
<p class="text-primary font-medium">IDEs</p>
<p class="text-white">PyCharm, Visual Studio, Visual Studio Code</p>
</div>
<div>
<p class="text-primary font-medium">Version Control</p>
<p class="text-white">Git, GitHub</p>
</div>
<div>
<p class="text-primary font-medium">Additional Libraries</p>
<p class="text-white">Dapper, LINQ</p>
</div>
</div>
</div>
</div>
<a href="#" class="px-8 py-3 bg-primary hover:bg-opacity-90 text-white font-medium !rounded-button whitespace-nowrap transition-all inline-flex items-center justify-center">
Download CV
<i class="ri-download-line ml-2"></i>
</a>
</div>
</div>
</div>
</section>
<!-- Contact Section -->
<section id="contact" class="py-20">
<div class="container mx-auto px-6">
<div class="text-center mb-16">
<span class="text-primary font-medium">Get In Touch</span>
<h2 class="text-4xl font-bold mt-2 text-white">Contact Me</h2>
</div>
<div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
<div>
<div class="mb-8">
<h3 class="text-2xl font-bold text-white mb-4">Let's Talk About Your Project</h3>
<p class="text-slate-300">
I'm always open to discussing new projects, creative ideas or opportunities to be part of your vision.
</p>
</div>
<div class="space-y-6">
<div class="flex items-start">
<div class="w-12 h-12 bg-primary bg-opacity-20 rounded-lg flex items-center justify-center mr-4 flex-shrink-0">
<div class="w-6 h-6 flex items-center justify-center text-primary">
<i class="ri-mail-line"></i>
</div>
</div>
<div>
<h4 class="text-white font-medium mb-1">Email</h4>
<p class="text-slate-300">mfundisomzobe@gmail.com</p>
</div>
</div>
<div class="flex items-start">
<div class="w-12 h-12 bg-primary bg-opacity-20 rounded-lg flex items-center justify-center mr-4 flex-shrink-0">
<div class="w-6 h-6 flex items-center justify-center text-primary">
<i class="ri-phone-line"></i>
</div>
</div>
<div>
<h4 class="text-white font-medium mb-1">Phone</h4>
<p class="text-slate-300">+27 65 532 3843</p>
</div>
</div>
<div class="flex items-start">
<div class="w-12 h-12 bg-primary bg-opacity-20 rounded-lg flex items-center justify-center mr-4 flex-shrink-0">
<div class="w-6 h-6 flex items-center justify-center text-primary">
<i class="ri-linkedin-fill"></i>
</div>
</div>
<div>
<h4 class="text-white font-medium mb-1">LinkedIn</h4>
<a href="https://www.linkedin.com/in/mfundiso-mzobe-87b40a27a/" class="text-slate-300 hover:text-primary transition-colors">View Profile</a>
</div>
</div>
</div>
<div class="mt-8">
<h4 class="text-white font-medium mb-4">Follow Me</h4>
<div class="flex space-x-4">
<a href="#" class="w-10 h-10 bg-[#131c31] rounded-full flex items-center justify-center text-slate-300 hover:text-white hover:bg-primary transition-colors">
<div class="w-5 h-5 flex items-center justify-center">
<i class="ri-dribbble-line"></i>
</div>
</a>
<a href="#" class="w-10 h-10 bg-[#131c31] rounded-full flex items-center justify-center text-slate-300 hover:text-white hover:bg-primary transition-colors">
<div class="w-5 h-5 flex items-center justify-center">
<i class="ri-behance-line"></i>
</div>
</a>
<a href="#" class="w-10 h-10 bg-[#131c31] rounded-full flex items-center justify-center text-slate-300 hover:text-white hover:bg-primary transition-colors">
<div class="w-5 h-5 flex items-center justify-center">
<i class="ri-instagram-line"></i>
</div>
</a>
<a href="#" class="w-10 h-10 bg-[#131c31] rounded-full flex items-center justify-center text-slate-300 hover:text-white hover:bg-primary transition-colors">
<div class="w-5 h-5 flex items-center justify-center">
<i class="ri-linkedin-line"></i>
</div>
</a>
</div>
</div>
</div>
<div>
<form class="space-y-6">
<div class="grid grid-cols-1 md:grid-cols-2 gap-6">
<div>
<label for="name" class="block text-slate-300 mb-2">Name</label>
<input type="text" id="name" class="w-full px-4 py-3 rounded bg-[#131c31] border-none focus:ring-2 focus:ring-primary" placeholder="Your Name">
</div>
<div>
<label for="email" class="block text-slate-300 mb-2">Email</label>
<input type="email" id="email" class="w-full px-4 py-3 rounded bg-[#131c31] border-none focus:ring-2 focus:ring-primary" placeholder="Your Email">
</div>
</div>
<div>
<label for="subject" class="block text-slate-300 mb-2">Subject</label>
<input type="text" id="subject" class="w-full px-4 py-3 rounded bg-[#131c31] border-none focus:ring-2 focus:ring-primary" placeholder="Subject">
</div>
<div>
<label for="message" class="block text-slate-300 mb-2">Message</label>
<textarea id="message" rows="5" class="w-full px-4 py-3 rounded bg-[#131c31] border-none focus:ring-2 focus:ring-primary" placeholder="Your Message"></textarea>
</div>
<button type="submit" class="w-full px-8 py-3 bg-primary hover:bg-opacity-90 text-white font-medium !rounded-button whitespace-nowrap transition-all flex items-center justify-center">
Send Message
<i class="ri-send-plane-line ml-2"></i>
</button>
</form>
</div>
</div>
</div>
</section>
<!-- Footer -->
<footer class="py-10 bg-[#0c1424] border-t border-slate-800">
<div class="container mx-auto px-6">
<div class="flex flex-col md:flex-row justify-between items-center">
<div class="mb-4 md:mb-0">
<a href="#" class="text-2xl font-['Pacifico'] text-white">Mfundiso's Portfolio</a>
</div>
<div class="mb-4 md:mb-0">
<ul class="flex flex-wrap justify-center gap-6">
<li><a href="#home" class="text-slate-300 hover:text-white transition-colors">Home</a></li>
<li><a href="#portfolio" class="text-slate-300 hover:text-white transition-colors">Portfolio</a></li>
<li><a href="#about" class="text-slate-300 hover:text-white transition-colors">About</a></li>
<li><a href="#contact" class="text-slate-300 hover:text-white transition-colors">Contact</a></li>
</ul>
</div>
<div>
<p class="text-slate-400 text-sm">&copy; 2025 Mfundiso Mzobe. All rights reserved.</p>
</div>
</div>
</div>
</footer>
<!-- Back to Top Button -->
<button id="backToTop" class="fixed bottom-6 right-6 w-12 h-12 bg-primary rounded-full flex items-center justify-center text-white opacity-0 invisible transition-all duration-300 z-50">
<div class="w-6 h-6 flex items-center justify-center">
<i class="ri-arrow-up-line"></i>
</div>
</button>
<script>
document.addEventListener('DOMContentLoaded', function() {
// Mobile menu toggle
const menuButton = document.querySelector('.md\\:hidden');
const closeButton = document.querySelector('.absolute.top-6.right-6');
const mobileMenu = document.querySelector('.fixed.inset-0.bg-\\[\\#0f172a\\]');
if (menuButton && closeButton && mobileMenu) {
menuButton.addEventListener('click', function() {
mobileMenu.classList.remove('hidden');
mobileMenu.classList.add('flex');
});
closeButton.addEventListener('click', function() {
mobileMenu.classList.remove('flex');
mobileMenu.classList.add('hidden');
});
// Close mobile menu when clicking on a link
const mobileLinks = mobileMenu.querySelectorAll('a');
mobileLinks.forEach(link => {
link.addEventListener('click', function() {
mobileMenu.classList.remove('flex');
mobileMenu.classList.add('hidden');
});
});
}
// Smooth scrolling for anchor links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
anchor.addEventListener('click', function(e) {
e.preventDefault();
const targetId = this.getAttribute('href');
if (targetId === '#') return;
const targetElement = document.querySelector(targetId);
if (targetElement) {
window.scrollTo({
top: targetElement.offsetTop - 80,
behavior: 'smooth'
});
}
});
});
// Back to top button
const backToTopButton = document.getElementById('backToTop');
if (backToTopButton) {
window.addEventListener('scroll', function() {
if (window.pageYOffset > 300) {
backToTopButton.classList.remove('opacity-0', 'invisible');
backToTopButton.classList.add('opacity-100', 'visible');
} else {
backToTopButton.classList.remove('opacity-100', 'visible');
backToTopButton.classList.add('opacity-0', 'invisible');
}
});
backToTopButton.addEventListener('click', function() {
window.scrollTo({
top: 0,
behavior: 'smooth'
});
});
}
});
document.addEventListener('DOMContentLoaded', function() {
// Custom cursor effect
const cursorDot = document.querySelector('.cursor-dot');
const cursorOutline = document.querySelector('.cursor-outline');
if (cursorDot && cursorOutline && window.innerWidth > 768) {
window.addEventListener('mousemove', function(e) {
const posX = e.clientX;
const posY = e.clientY;
cursorDot.style.left = `${posX}px`;
cursorDot.style.top = `${posY}px`;
// Add a slight delay to the outline cursor for a trailing effect
setTimeout(() => {
cursorOutline.style.left = `${posX}px`;
cursorOutline.style.top = `${posY}px`;
}, 100);
});
// Hover effect on interactive elements
const interactiveElements = document.querySelectorAll('a, button, input, textarea, .portfolio-item');
interactiveElements.forEach(el => {
el.addEventListener('mouseenter', () => {
cursorDot.style.width = '0px';
cursorDot.style.height = '0px';
cursorOutline.style.width = '60px';
cursorOutline.style.height = '60px';
cursorOutline.style.borderColor = 'rgba(99, 102, 241, 0.8)';
});
el.addEventListener('mouseleave', () => {
cursorDot.style.width = '8px';
cursorDot.style.height = '8px';
cursorOutline.style.width = '40px';
cursorOutline.style.height = '40px';
cursorOutline.style.borderColor = 'rgba(99, 102, 241, 0.5)';
});
});
}
});
document.addEventListener('DOMContentLoaded', function() {
// Portfolio filter functionality
const filterButtons = document.querySelectorAll('.inline-flex.bg-slate-800 button');
if (filterButtons.length > 0) {
filterButtons.forEach(button => {
button.addEventListener('click', function() {
// Remove active class from all buttons
filterButtons.forEach(btn => {
btn.classList.remove('bg-primary', 'text-white');
btn.classList.add('text-slate-300');
});
// Add active class to clicked button
this.classList.remove('text-slate-300');
this.classList.add('bg-primary', 'text-white');
// Here you would normally filter the portfolio items
// For this demo, we're just changing the button styles
});
});
}
});
</script>
</body>
</html>
