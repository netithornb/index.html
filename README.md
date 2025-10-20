<meta charset="utf-8"/>
<link crossorigin="" href="https://fonts.gstatic.com/" rel="preconnect"/>
<link as="style" href="https://fonts.googleapis.com/css2?display=swap&amp;family=Inter:wght@400;500;700;900" onload="this.rel='stylesheet'" rel="stylesheet"/>
<title>Stitch Design</title>
<link href="data:image/x-icon;base64," rel="icon" type="image/x-icon"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script>
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              primary: "#0d40a5",
              "background-light": "#f6f6f8",
              "background-dark": "#101622",
            },
            fontFamily: {
              display: ["Inter"],
            },
            borderRadius: {
              DEFAULT: "0.25rem",
              lg: "0.5rem",
              xl: "0.75rem",
              full: "9999px"
            },
          },
        },
      };
    </script>
</head>
<body class="font-display bg-background-light dark:bg-background-dark">
<div class="relative flex h-auto min-h-screen w-full flex-col overflow-x-hidden group/design-root">
<div class="layout-container flex h-full grow flex-col">
<header class="flex flex-col items-center justify-center whitespace-nowrap border-b border-background-light/10 dark:border-background-dark/10 px-10 py-4 bg-background-light dark:bg-background-dark sticky top-0 z-50 shadow-sm">
<div class="flex flex-col items-center gap-2 text-stone-800 dark:text-stone-200 w-full">
<div class="w-12 h-12 text-primary">
<svg fill="none" viewBox="0 0 48 48" xmlns="http://www.w3.org/2000/svg">
<path d="M24 30C30.6274 30 36 24.6274 36 18C36 11.3726 30.6274 6 24 6C17.3726 6 12 11.3726 12 18C12 24.6274 17.3726 30 24 30Z" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="4"></path>
<path d="M24 42C30.6274 42 36 36.6274 36 30C36 23.3726 30.6274 18 24 18C17.3726 18 12 23.3726 12 30C12 36.6274 17.3726 42 24 42Z" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="4"></path>
</svg>
</div>
<h2 class="text-xl font-bold tracking-tight text-stone-900 dark:text-white">Syndicate Law Offices</h2>
</div>
<nav class="hidden md:flex items-center gap-8 mt-4">
<a class="text-sm font-medium text-stone-600 dark:text-stone-300 hover:text-primary dark:hover:text-primary transition-colors" href="#">About Us</a>
<a class="text-sm font-medium text-stone-600 dark:text-stone-300 hover:text-primary dark:hover:text-primary transition-colors" href="#">Practice Areas</a>
<a class="text-sm font-medium text-stone-600 dark:text-stone-300 hover:text-primary dark:hover:text-primary transition-colors" href="#contact">Contact</a>
</nav>
<div class="flex items-center gap-4 absolute top-4 right-10">
<button class="flex min-w-[84px] cursor-pointer items-center justify-center overflow-hidden rounded-lg h-10 px-4 bg-background-light/80 dark:bg-background-dark/80 text-stone-700 dark:text-stone-300 text-sm font-bold border border-stone-200 dark:border-stone-700 hover:bg-stone-200 dark:hover:bg-stone-800 transition-colors">
<span class="truncate">Thai</span>
</button>
<div class="bg-center bg-no-repeat aspect-square bg-cover rounded-full size-10" style='background-image: url("https://lh3.googleusercontent.com/aida-public/AB6AXuB0KwRyVdjKnKBbAzR-YqOJy_MuEeUEhFU0zvRKfMYbXYeB6C2ddkgLrCI_NxuqawlKFx8hWPveSronhZc3aTD-e2obWWgnPYNyYRqiDwxdTtDdWagZ7CWam4uyYgaMW52_kapyfQvxTOybJwzJ7w2BsP-Nb3J7ApNUFnsRJk_nF85uWZbaI_SyYQyAoTnNX0gSnhZBTEgCQJxsde4OWH0BVOMMn65En_N_1SMKKFjV3kiCxdYHm2NoHWSaTT_08eDeWFixsBu_PPHY");'></div>
</div>
</header>
<main class="flex-1">
<section class="relative min-h-[60vh] flex items-center justify-center text-center text-white bg-cover bg-center" style='background-image: linear-gradient(rgba(13, 64, 165, 0.4), rgba(16, 22, 34, 0.8)), url("https://lh3.googleusercontent.com/aida-public/AB6AXuCthf3LMf7Yz0KhepgDp-LplVTJxrlfbDeeJdu-GVwHkpLdNTGiqPR7FYvpTLFPnFWFrFD1YH3GjQ_w0dm4jdPKiByOmqD3Vp8UOXHGldjpq8WFETQx7HSJlSLXRyGVHEibBf-btsg5SvEEj_xTDCOafcvlqB3Two-K38WB4QwguAkrSQJI6PbIf2FNZ5Y0jRde_pHLNfFxxXhX7VrS94zQ-pDV-u6vuThkzZGuJF2Qtmp13CgaLMYGWdHwCoRg4fnmc1S3l3GcQt5v");'>
<div class="max-w-4xl px-4">
<h1 class="text-4xl md:text-6xl font-black tracking-tighter">Upholding Justice. Securing Your Business and Future.</h1>
<p class="mt-4 text-lg md:text-xl max-w-2xl mx-auto text-stone-200">Syndicate Law Offices provides comprehensive legal services with a focus on integrity, expertise, and client success.</p>
<button class="mt-8 inline-flex items-center justify-center rounded-lg h-12 px-6 bg-primary text-white text-base font-bold tracking-wide hover:bg-primary/90 transition-colors shadow-lg">Contact Us</button>
</div>
</section>
<div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8 py-16 sm:py-24">
<section class="mb-24 text-center" id="about">
<h2 class="text-3xl font-bold tracking-tight text-stone-900 dark:text-white sm:text-4xl">About Us</h2>
<p class="mt-6 max-w-3xl mx-auto text-lg leading-8 text-stone-600 dark:text-stone-400">Syndicate Law Offices is a leading law firm dedicated to providing exceptional legal representation across a wide range of practice areas. Our team of experienced attorneys is committed to achieving the best possible outcomes for our clients through strategic counsel and diligent advocacy.</p>
</section>
<section class="mb-24" id="practice-areas">
<h2 class="text-3xl font-bold tracking-tight text-stone-900 dark:text-white sm:text-4xl text-center">Practice Areas</h2>
<div class="mt-12 grid grid-cols-1 gap-12 sm:grid-cols-2 lg:grid-cols-1">
<div class="flex flex-col gap-6 p-6 rounded-xl bg-background-light/50 dark:bg-background-dark/50 shadow-sm">
<h3 class="text-xl font-semibold leading-7 text-stone-900 dark:text-white">Corporate &amp; Business Law</h3>
<p class="text-base leading-6 text-stone-600 dark:text-stone-400">Comprehensive legal solutions for businesses of all sizes, from startups to established corporations. We advise on company formation, corporate governance, mergers &amp; acquisitions, and regulatory compliance to ensure your business operates smoothly and legally.</p>
</div>
<div class="flex flex-col gap-6 p-6 rounded-xl bg-background-light/50 dark:bg-background-dark/50 shadow-sm">
<h3 class="text-xl font-semibold leading-7 text-stone-900 dark:text-white">Contracts &amp; Transactional Law</h3>
<p class="text-base leading-6 text-stone-600 dark:text-stone-400">Expert drafting, review, and negotiation of all types of commercial contracts and agreements. We ensure your interests are protected in every transaction, minimizing risk and maximizing value.</p>
</div>
<div class="flex flex-col gap-6 p-6 rounded-xl bg-background-light/50 dark:bg-background-dark/50 shadow-sm">
<h3 class="text-xl font-semibold leading-7 text-stone-900 dark:text-white">Litigation &amp; Dispute Resolution</h3>
<p class="text-base leading-6 text-stone-600 dark:text-stone-400">Aggressive and effective representation in court and alternative dispute resolution forums. Our expertise covers a wide range of disputes, including:</p>
<ul class="list-disc list-inside space-y-2 text-stone-600 dark:text-stone-400">
<li><strong>Civil Cases:</strong> Contract disputes, tort claims, and property disputes.</li>
<li><strong>Criminal Cases:</strong> Defense representation for a variety of criminal charges.</li>
<li><strong>Labor Cases:</strong> Representing both employers and employees in employment disputes.</li>
<li><strong>Family Cases:</strong> Handling sensitive matters such as divorce, custody, and support.</li>
<li><strong>Inheritance Cases:</strong> Assisting with will contests and estate disputes.</li>
</ul>
</div>
<div class="flex flex-col gap-6 p-6 rounded-xl bg-background-light/50 dark:bg-background-dark/50 shadow-sm">
<h3 class="text-xl font-semibold leading-7 text-stone-900 dark:text-white">IP &amp; Tech Law</h3>
<p class="text-base leading-6 text-stone-600 dark:text-stone-400">Protecting your innovations, brand, and data in the digital age. Our services include trademark and copyright registration, IP licensing, and ensuring compliance with data privacy regulations like the PDPA.</p>
</div>
<div class="flex flex-col gap-6 p-6 rounded-xl bg-background-light/50 dark:bg-background-dark/50 shadow-sm">
<h3 class="text-xl font-semibold leading-7 text-stone-900 dark:text-white">Real Estate &amp; Property Law</h3>
<p class="text-base leading-6 text-stone-600 dark:text-stone-400">Navigating complex property transactions and disputes. We assist with sales and purchases, leasing, development projects, and litigation related to real estate.</p>
</div>
</div>
</section>
<section id="contact">
<div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-start">
<div>
<h2 class="text-3xl font-bold tracking-tight text-stone-900 dark:text-white sm:text-4xl">Contact &amp; Location</h2>
<form action="mailto:netithorn.ban@gmail.com" class="mt-8 space-y-6" enctype="text/plain" method="POST">
<div>
<label class="block text-sm font-medium text-stone-700 dark:text-stone-300" for="name">Name</label>
<div class="mt-1">
<input autocomplete="name" class="form-input block w-full rounded-lg border-stone-300 dark:border-stone-700 bg-background-light/50 dark:bg-background-dark/50 shadow-sm focus:border-primary focus:ring-primary text-stone-900 dark:text-white placeholder-stone-400 dark:placeholder-stone-500" id="name" name="name" placeholder="Your Name" type="text"/>
</div>
</div>
<div>
<label class="block text-sm font-medium text-stone-700 dark:text-stone-300" for="email">Email</label>
<div class="mt-1">
<input autocomplete="email" class="form-input block w-full rounded-lg border-stone-300 dark:border-stone-700 bg-background-light/50 dark:bg-background-dark/50 shadow-sm focus:border-primary focus:ring-primary text-stone-900 dark:text-white placeholder-stone-400 dark:placeholder-stone-500" id="email" name="email" placeholder="Your Email" type="email"/>
</div>
</div>
<div>
<label class="block text-sm font-medium text-stone-700 dark:text-stone-300" for="message">Message</label>
<div class="mt-1">
<textarea class="form-textarea block w-full rounded-lg border-stone-300 dark:border-stone-700 bg-background-light/50 dark:bg-background-dark/50 shadow-sm focus:border-primary focus:ring-primary text-stone-900 dark:text-white placeholder-stone-400 dark:placeholder-stone-500" id="message" name="message" placeholder="Your Message" rows="4"></textarea>
</div>
</div>
<div>
<button class="inline-flex items-center justify-center rounded-lg h-12 px-6 bg-primary text-white text-base font-bold tracking-wide hover:bg-primary/90 transition-colors shadow-lg w-full" type="submit">Send Message</button>
</div>
</form>
</div>
<div class="w-full aspect-w-1 aspect-h-1 rounded-xl overflow-hidden mt-12 md:mt-0">
<img alt="Map" class="w-full h-full object-cover" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAXoQsrsdtzP0eES8OB38sIZUosol9sXxd9Mkv_c8NUHyS-a4OL3dCUm7WZiQ_E1-T7MFo0C6Tr7PgNjHa0F_arIZqEiGrayUV9KZvRTgyaX9rbgNcpzKf88wXUfthHGP-r3wNwT0a-8yg3P4tZ5a8eQWSNxYDcDjTEPJPhigRHn11pIDxrsPwGEgvkInk2zBwRP8nj899hOjtFdjZMa2PfyivsLnd9oVItLU-l1yzZIU9wFZI-J6JFFv5EIHffyrq_9yRew8m_aI2k"/>
</div>
</div>
</section>
</div>
</main>
<footer class="bg-background-light/50 dark:bg-background-dark/50 border-t border-background-light/10 dark:border-background-dark/10">
<div class="max-w-7xl mx-auto py-12 px-4 sm:px-6 lg:px-8">
<div class="flex justify-center space-x-6 mb-8">
<a class="text-stone-500 dark:text-stone-400 hover:text-primary dark:hover:text-white" href="https://www.facebook.com/profile.php?id=61576550558611&amp;mibextid=wwXIfr&amp;mibextid=wwXIfr" target="_blank">
<svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
<path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.891h-2.33V21.878C18.343 21.128 22 16.991 22 12z"></path>
</svg>
</a>
<a class="text-stone-500 dark:text-stone-400 hover:text-primary dark:hover:text-white" href="#">
<svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
<path d="M12 0C5.373 0 0 5.373 0 12s5.373 12 12 12c2.445 0 4.73-.72 6.633-1.957l-1.07-3.882c-.22-.796.333-1.614 1.173-1.614h3.764c.22 0 .4-.18.4-.4v-3.765c0-.84-.818-1.393-1.614-1.173l-3.882 1.07C16.73 15.28 14.445 16 12 16c-2.209 0-4-1.791-4-4s1.791-4 4-4c2.209 0 4 1.791 4 4 0 .418.064.821.182 1.202l1.637.45c.997.273 1.905-.443 1.905-1.464V8.4c0-4.639-3.761-8.4-8.4-8.4zm0 6c-3.314 0-6 2.686-6 6s2.686 6 6 6 6-2.686-6-6-2.686-6-6-6z"></path>
</svg>
</a>
</div>
<div class="flex justify-center space-x-6">
<a class="text-stone-500 dark:text-stone-400 hover:text-stone-900 dark:hover:text-white" href="#">Privacy Policy</a>
<a class="text-stone-500 dark:text-stone-400 hover:text-stone-900 dark:hover:text-white" href="#">Terms of Service</a>
<a class="text-stone-500 dark:text-stone-400 hover:text-stone-900 dark:hover:text-white" href="#">Legal Disclaimers</a>
</div>
<p class="mt-8 text-center text-base text-stone-500 dark:text-stone-400">© 2025 Syndicate Law Offices. All rights reserved.</p>
</div>
</footer>
</div>
</div>
</body></html>
