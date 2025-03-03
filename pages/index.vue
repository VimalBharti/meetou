<template>
  <div class="bg-white h-full w-full">
    <!-- ========== HEADER ========== -->
    <header class="fixed top-4 inset-x-0 flex flex-wrap md:justify-start md:flex-nowrap z-50 w-full">
      <nav class="relative max-w-[66rem] w-full shadow-xl bg-white rounded-3xl px-5 py-3 md:flex md:items-center md:justify-between  mx-2 lg:mx-auto" aria-label="Global">
        <div class="flex items-center justify-between">
          <!-- Logo -->
          <a class="flex-none rounded-md text-xl inline-block font-semibold focus:outline-none focus:opacity-80" href="#home" aria-label="Preline">
            <img src="/logo.png" class="h-12 w-full object-contain">
          </a>
          <!-- End Logo -->

          <div class="md:hidden">
            <button type="button" class="hs-collapse-toggle size-8 flex justify-center items-center text-sm font-semibold rounded-full bg-white text-gray-800 disabled:opacity-50 disabled:pointer-events-none" data-hs-collapse="#navbar-collapse" aria-controls="navbar-collapse" aria-label="Toggle navigation">
              <svg class="hs-collapse-open:hidden flex-shrink-0 size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                <line x1="3" x2="21" y1="6" y2="6" />
                <line x1="3" x2="21" y1="12" y2="12" />
                <line x1="3" x2="21" y1="18" y2="18" />
              </svg>
              <svg class="hs-collapse-open:block hidden flex-shrink-0 size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                <path d="M18 6 6 18" />
                <path d="m6 6 12 12" />
              </svg>
            </button>
          </div>
        </div>

        <!-- Collapse -->
        <div id="navbar-collapse" class="hs-collapse hidden overflow-hidden transition-all duration-300 basis-full grow md:block">
          <div class="flex flex-col gap-y-4 gap-x-0 mt-5 md:flex-row md:items-center md:justify-end md:gap-y-0 md:gap-x-7 md:mt-0 md:ps-7">
            <a class="text-sm text-gray-800 md:py-4 focus:outline-none focus:text-neutral-300" href="#home" aria-current="page">Home</a>
            <a class="text-sm text-gray-800 md:py-4 focus:outline-none focus:text-neutral-300" href="#services">Services</a>
            <!-- <a class="text-sm text-gray-800 md:py-4 focus:outline-none focus:text-neutral-300" href="#work">Our Work</a> -->
            <a class="text-sm text-gray-800 md:py-4 focus:outline-none focus:text-neutral-300" href="#about">About</a>

            <div>
              <a class="group inline-flex items-center gap-x-2 py-2 px-4 bg-cyan-500 font-medium text-sm text-gray-800 rounded-full focus:outline-none" href="#contact">
                Contact us
              </a>
            </div>
          </div>
        </div>
        <!-- End Collapse -->
      </nav>
    </header>
    <!-- ========== END HEADER ========== -->

    <!-- ========== MAIN CONTENT ========== -->
    <main>
      <!-- Hero -->
      <div class="bg-white object-cover h-[60vh] md:h-[80vh] flex flex-col items-center justify-center bg-[linear-gradient(to_top,rgba(0,0,0,0.8),rgba(255,255,255,0)),url('hero.jpg')] bg-center" 
        id="home"
      >
        <div class="md:max-w-[40vw] px-4 md:px-0 w-full mx-auto pt-20">
          <h1 class="font-semibold text-white text-5xl md:text-6xl text-center">
            <span class="text-cyan-600 font-bold">MeetoU</span> <br/> Transforming ideas into reality
          </h1>
          <div class="max-w-4xl">
            <p class="mt-5 text-neutral-300 text-lg text-center">
              We offer quality Mobile App Development, <br/> Web development, Web Designing ,Digital Marketing
            </p>
          </div>
        </div>
      </div>
      <!-- End Hero -->

      <!-- Clients -->
      <div class="relative overflow-hidden bg-white">

        <div class="relative z-10 md:py-5 w-full bg-gray-100">
          <div class="max-w-5xl  mx-auto shadow-xl rounded-xl border px-4 py-6 bg-white">
            <div class="grid md:grid-cols-3 gap-6">
              <div class="flex item-center gap-3">
                <svg xmlns="http://www.w3.org/2000/svg" width="36" height="36" viewBox="0 0 24 24"><g fill="none"><path stroke="currentColor" stroke-linecap="round" stroke-width="1.5" d="M19.647 15.536H4.353m15.294 0V8c0-1.886 0-2.828-.586-3.414C18.476 4 17.533 4 15.647 4H8.353c-1.886 0-2.828 0-3.414.586S4.353 6.114 4.353 8v7.536m15.294 0l1.744 1.8l.088.092a2 2 0 0 1 .52 1.284l.001.127c0 .15 0 .224-.004.287a2 2 0 0 1-1.87 1.87a5 5 0 0 1-.287.004H4.161c-.15 0-.224 0-.287-.004a2 2 0 0 1-1.87-1.87C2 19.063 2 18.988 2 18.84l.001-.127a2 2 0 0 1 .52-1.284l.088-.092l1.744-1.8M9.5 18.5h5"/><path fill="currentColor" d="M12.75 6.75a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0"/></g></svg>
                <p class="text-sm">Full suite of digital & technology solutions to grow your business</p>
              </div>
              <div class="flex item-center gap-3">
                <svg xmlns="http://www.w3.org/2000/svg" width="40" height="32" viewBox="0 0 640 512"><path fill="currentColor" d="m272.2 64.6l-51.1 51.1c-15.3 4.2-29.5 11.9-41.5 22.5L153 161.9c-10.2 9.1-23.5 14.1-37.2 14.1H96v128c20.4.6 39.8 8.9 54.3 23.4l35.6 35.6l7 7l27 27c6.2 6.2 16.4 6.2 22.6 0c1.7-1.7 3-3.7 3.7-5.8c2.8-7.7 9.3-13.5 17.3-15.3s16.4.6 22.2 6.5l10.8 10.6c11.6 11.6 30.4 11.6 41.9 0c5.4-5.4 8.3-12.3 8.6-19.4c.4-8.8 5.6-16.6 13.6-20.4s17.3-3 24.4 2.1c9.4 6.7 22.5 5.8 30.9-2.6c9.4-9.4 9.4-24.6 0-33.9L340.1 243l-35.8 33c-27.3 25.2-69.2 25.6-97 .9c-31.7-28.2-32.4-77.4-1.6-106.5l70.1-66.2C303.2 78.4 339.4 64 377.1 64c36.1 0 71 13.3 97.9 37.2l30.1 26.8H624c8.8 0 16 7.2 16 16v208c0 17.7-14.3 32-32 32h-32c-11.8 0-22.2-6.4-27.7-16h-84.9c-3.4 6.7-7.9 13.1-13.5 18.7c-17.1 17.1-40.8 23.8-63 20.1c-3.6 7.3-8.5 14.1-14.6 20.2c-27.3 27.3-70 30-100.4 8.1c-25.1 20.8-62.5 19.5-86-4.1L159 404l-7-7l-35.6-35.6c-5.5-5.5-12.7-8.7-20.4-9.3c0 17.6-14.4 31.9-32 31.9H32c-17.7 0-32-14.3-32-32V144c0-8.8 7.2-16 16-16h99.8c2 0 3.9-.7 5.3-2l26.5-23.6C175.5 77.7 211.4 64 248.7 64H259c4.4 0 8.9.2 13.2.6M544 320V176h-48c-5.9 0-11.6-2.2-15.9-6.1l-36.9-32.8C425 120.9 401.5 112 377.1 112c-25.4 0-49.8 9.7-68.3 27.1l-70.1 66.2c-10.3 9.8-10.1 26.3.5 35.7c9.3 8.3 23.4 8.1 32.5-.3l71.9-66.4c9.7-9 24.9-8.4 33.9 1.4s8.4 24.9-1.4 33.9l-.8.8l74.4 74.4c10 10 16.5 22.3 19.4 35.1h74.8zM64 336a16 16 0 1 0-32 0a16 16 0 1 0 32 0m528 16a16 16 0 1 0 0-32a16 16 0 1 0 0 32"/></svg>
                <p class="text-sm">Over 13 years of experience. Trusted by 500+ brands globally</p>
              </div>
              <div class="flex item-center gap-3">
                <svg xmlns="http://www.w3.org/2000/svg" width="42" height="42" viewBox="0 0 24 24"><g fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" color="currentColor"><path d="M19.745 13a7 7 0 1 0-12.072-1"/><path d="M14 6c-1.105 0-2 .672-2 1.5S12.895 9 14 9s2 .672 2 1.5s-.895 1.5-2 1.5m0-6c.87 0 1.612.417 1.886 1M14 6V5m0 7c-.87 0-1.612-.417-1.886-1M14 12v1M3 14h2.395c.294 0 .584.066.847.194l2.042.988c.263.127.553.193.848.193h1.042c1.008 0 1.826.791 1.826 1.767c0 .04-.027.074-.066.085l-2.541.703a1.95 1.95 0 0 1-1.368-.124L5.842 16.75M12 16.5l4.593-1.411a1.985 1.985 0 0 1 2.204.753c.369.51.219 1.242-.319 1.552l-7.515 4.337a2 2 0 0 1-1.568.187L3 20.02"/></g></svg>
                <p class="text-sm">Affordable, process and quality oriented for businesses small and big</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- End Clients -->

      <!-- Works -->
      <div class="max-w-7xl px-4 lg:px-8 py-12 lg:py-24 mx-auto hidden" id="work">
        <div class="mb-6 sm:mb-10 max-w-2xl text-center mx-auto">
          <h1 class="font-medium text-black text-2xl sm:text-4xl dark:text-white">
            Latest work
          </h1>
        </div>

        <!-- Card Grid -->
        <div class=" grid grid-cols-3 gap-4 sm:gap-6 md:gap-8 lg:gap-12">
          <!-- Card -->
          <a class="group block" href="#">
            <div class="aspect-w-16 aspect-h-12 overflow-hidden bg-gray-100 rounded-2xl dark:bg-neutral-800">
              <img class="group-hover:scale-105 transition-transform duration-500 ease-in-out object-cover rounded-2xl" src="https://images.unsplash.com/photo-1575052814086-f385e2e2ad1b?q=80&w=3540&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Image Description">
            </div>

            <div class="pt-4">
              <h3 class="relative inline-block font-medium text-lg text-black before:absolute before:bottom-0.5 before:start-0 before:-z-[1] before:w-full before:h-1 before:bg-gray-600 before:transition before:origin-left before:scale-x-0 group-hover:before:scale-x-100 dark:text-white">
                eYoga
              </h3>
              <p class="mt-1 text-gray-600 dark:text-neutral-400">
                A revamped and dynamic approach to yoga analytics
              </p>

              <div class="mt-3 flex flex-wrap gap-2">
                <span class="py-1.5 px-3 bg-white text-gray-600 border border-gray-200 text-xs sm:text-sm rounded-xl dark:bg-neutral-900 dark:border-neutral-700 dark:text-neutral-400">
                  Discovery
                </span>
                <span class="py-1.5 px-3 bg-white text-gray-600 border border-gray-200 text-xs sm:text-sm rounded-xl dark:bg-neutral-900 dark:border-neutral-700 dark:text-neutral-400">
                  Brand Guidelines
                </span>
                <span class="py-1.5 px-3 bg-white text-gray-600 border border-gray-200 text-xs sm:text-sm rounded-xl dark:bg-neutral-900 dark:border-neutral-700 dark:text-neutral-400">
                  Yoga
                </span>
              </div>
            </div>
          </a>
          <!-- End Card -->

          <!-- Card -->
          <a class="group block" href="#">
            <div class="aspect-w-16 aspect-h-12 overflow-hidden bg-gray-100 rounded-2xl dark:bg-neutral-800">
              <img class="group-hover:scale-105 transition-transform duration-500 ease-in-out object-cover rounded-2xl" src="https://images.unsplash.com/photo-1606107557195-0e29a4b5b4aa?q=80&w=2400&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Image Description">
            </div>

            <div class="pt-4">
              <h3 class="relative inline-block font-medium text-lg text-black before:absolute before:bottom-0.5 before:start-0 before:-z-[1] before:w-full before:h-1 before:bg-gray-600 before:transition before:origin-left before:scale-x-0 group-hover:before:scale-x-100 dark:text-white">
                Nike React
              </h3>
              <p class="mt-1 text-gray-600 dark:text-neutral-400">
                Rewriting sport's playbook for billions of athletes
              </p>

              <div class="mt-3 flex flex-wrap gap-2">
                <span class="py-1.5 px-3 bg-white text-gray-600 border border-gray-200 text-xs sm:text-sm rounded-xl dark:bg-neutral-900 dark:border-neutral-700 dark:text-neutral-400">
                  Brand Strategy
                </span>
                <span class="py-1.5 px-3 bg-white text-gray-600 border border-gray-200 text-xs sm:text-sm rounded-xl dark:bg-neutral-900 dark:border-neutral-700 dark:text-neutral-400">
                  Visual Identity
                </span>
              </div>
            </div>
          </a>
          <!-- End Card -->

          <!-- Card -->
          <a class="group block" href="#">
            <div class="aspect-w-16 aspect-h-12 overflow-hidden bg-gray-100 rounded-2xl dark:bg-neutral-800">
              <img class="group-hover:scale-105 transition-transform duration-500 ease-in-out object-cover rounded-2xl" src="https://images.unsplash.com/photo-1649999920973-ab6bfd0c0017?q=80&w=3542&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Image Description">
            </div>

            <div class="pt-4">
              <h3 class="relative inline-block font-medium text-lg text-black before:absolute before:bottom-0.5 before:start-0 before:-z-[1] before:w-full before:h-1 before:bg-gray-600 before:transition before:origin-left before:scale-x-0 group-hover:before:scale-x-100 dark:text-white">
                Day Spa
              </h3>
              <p class="mt-1 text-gray-600 dark:text-neutral-400">
                Designing a new cocktail can
              </p>

              <div class="mt-3 flex flex-wrap gap-2">
                <span class="py-1.5 px-3 bg-white text-gray-600 border border-gray-200 text-xs sm:text-sm rounded-xl dark:bg-neutral-900 dark:border-neutral-700 dark:text-neutral-400">
                  Brand Strategy
                </span>
                <span class="py-1.5 px-3 bg-white text-gray-600 border border-gray-200 text-xs sm:text-sm rounded-xl dark:bg-neutral-900 dark:border-neutral-700 dark:text-neutral-400">
                  Visual Identity
                </span>
              </div>
            </div>
          </a>
          <!-- End Card -->

          <!-- Card -->
          <a class="group block" href="#">
            <div class="aspect-w-16 aspect-h-12 overflow-hidden bg-gray-100 rounded-2xl dark:bg-neutral-800">
              <img class="group-hover:scale-105 transition-transform duration-500 ease-in-out object-cover rounded-2xl" src="https://images.unsplash.com/photo-1528291954423-c0c71c12baeb?q=80&w=3426&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Image Description">
            </div>

            <div class="pt-4">
              <h3 class="relative inline-block font-medium text-lg text-black before:absolute before:bottom-0.5 before:start-0 before:-z-[1] before:w-full before:h-1 before:bg-gray-600 before:transition before:origin-left before:scale-x-0 group-hover:before:scale-x-100 dark:text-white">
                Diamond Dynamics
              </h3>
              <p class="mt-1 text-gray-600 dark:text-neutral-400">
                From cutting-edge equipment to stylish apparel
              </p>

              <div class="mt-3 flex flex-wrap gap-2">
                <span class="py-1.5 px-3 bg-white text-gray-600 border border-gray-200 text-xs sm:text-sm rounded-xl dark:bg-neutral-900 dark:border-neutral-700 dark:text-neutral-400">
                  Sports Gear
                </span>
                <span class="py-1.5 px-3 bg-white text-gray-600 border border-gray-200 text-xs sm:text-sm rounded-xl dark:bg-neutral-900 dark:border-neutral-700 dark:text-neutral-400">
                  Equipment
                </span>
                <span class="py-1.5 px-3 bg-white text-gray-600 border border-gray-200 text-xs sm:text-sm rounded-xl dark:bg-neutral-900 dark:border-neutral-700 dark:text-neutral-400">
                  Discovery
                </span>
              </div>
            </div>
          </a>
          <!-- End Card -->
        </div>
        <!-- End Card Grid -->

        <div class="mt-10 lg:mt-20 text-center">
          <a class="relative inline-block font-medium md:text-lg text-black before:absolute before:bottom-0.5 before:start-0 before:-z-[1] before:w-full before:h-1 before:bg-gray-600 hover:before:bg-black focus:outline-none focus:before:bg-black dark:text-white dark:hover:before:bg-white dark:focus:before:bg-white" href="#">
            View all Work
          </a>
        </div>
      </div>
      <!-- End Works -->

      <!-- Our STORY. -->
      <div class="bg-white" id="about">
        <div class="max-w-5xl px-4 xl:px-0 py-10 lg:py-20 mx-auto">
          <!-- Title -->
          <div class="max-w-3xl mb-10 lg:mb-14">
            <span class="text-white font-bold bg-cyan-400 px-5 py-2 rounded-xl">WE ARE Innovative</span>
            <h2 class="text-gray-900 font-semibold text-3xl uppercase md:text-4xl mt-4 md:leading-tight">Our STORY.</h2>
          </div>
          <!-- End Title -->

          <!-- Grid -->
          <div class="md:grid md:grid-cols-2 md:gap-10 lg:gap-16 md:items-center">
            <div>
              <!-- Blockquote -->
              <blockquote>
                <p class="font-medium text-xl text-gray-800">
                  MeetoU is a digital first and technology company in Delhi, India that focuses on quality, innovation and positive ROI for our clients. Call us a technology driven firm that combines design aesthetics with technology to bring results to grow our client’s businesses.
                </p>

              </blockquote>
              <!-- End Blockquote -->
            </div>
            <!-- End Col -->

            <div class="hidden md:block mb-24 md:mb-0">
              <img class="rounded-xl" src="https://images.unsplash.com/photo-1671725501928-b7d85698ccd8?q=80&w=3540&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Image Description">
            </div>
            <!-- End Col -->
          </div>
          <!-- End Grid -->
        </div>
      </div>
      <!-- End Testimonials -->

      <!-- Stats -->
      <div class="bg-gray-100 ">
        <div class="max-w-5xl px-4 xl:px-0 py-10 mx-auto">
          <div class="rounded-3xl shadow-xl border bg-white">
            <div class="p-4 lg:p-8 bg-whiite">
              <div class="grid grid-cols-1 sm:grid-cols-3 items-center gap-y-20 gap-x-12">
                <!-- Stats -->
                <div class="relative text-center first:before:hidden before:absolute before:-top-full sm:before:top-1/2 before:start-1/2 sm:before:-start-6 before:w-px before:h-20 before:bg-white before:rotate-[60deg] sm:before:rotate-12 before:transform sm:before:-translate-y-1/2 before:-translate-x-1/2 sm:before:-translate-x-0 before:mt-3.5 sm:before:mt-0">
                  <svg class="flex-shrink-0 size-6 sm:size-8 text-gray-800 mx-auto" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                    <path d="m11 17 2 2a1 1 0 1 0 3-3" />
                    <path d="m14 14 2.5 2.5a1 1 0 1 0 3-3l-3.88-3.88a3 3 0 0 0-4.24 0l-.88.88a1 1 0 1 1-3-3l2.81-2.81a5.79 5.79 0 0 1 7.06-.87l.47.28a2 2 0 0 0 1.42.25L21 4" />
                    <path d="m21 3 1 11h-2" />
                    <path d="M3 3 2 14l6.5 6.5a1 1 0 1 0 3-3" />
                    <path d="M3 4h8" />
                  </svg>
                  <div class="mt-3 sm:mt-5">
                    <h3 class="text-lg sm:text-3xl font-semibold text-gray-800">100+</h3>
                    <p class="mt-1 text-sm sm:text-base text-neutral-400">Satisfied Customers</p>
                  </div>
                </div>
                <!-- End Stats -->

                <!-- Stats -->
                <div class="relative text-center first:before:hidden before:absolute before:-top-full sm:before:top-1/2 before:start-1/2 sm:before:-start-6 before:w-px before:h-20 before:bg-white before:rotate-[60deg] sm:before:rotate-12 before:transform sm:before:-translate-y-1/2 before:-translate-x-1/2 sm:before:-translate-x-0 before:mt-3.5 sm:before:mt-0">
                  <div class="flex justify-center items-center -space-x-5">
                    <img class="relative z-[2] flex-shrink-0 size-8 rounded-full border-[3px] border-neutral-800" src="https://images.unsplash.com/photo-1601935111741-ae98b2b230b0?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=facearea&facepad=2&w=320&h=320&q=80" alt="Image Description">
                    <img class="relative z-[1] flex-shrink-0 size-8 rounded-full border-[3px] border-neutral-800 -mt-7" src="https://images.unsplash.com/photo-1570654639102-bdd95efeca7a?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=facearea&facepad=2&w=320&h=320&q=80" alt="Image Description">
                    <img class="relative flex-shrink-0 size-8 rounded-full border-[3px] border-neutral-800" src="https://images.unsplash.com/photo-1679412330254-90cb240038c5?ixlib=rb-4.0.3&amp;ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;auto=format&amp;fit=facearea&amp;facepad=2.5&amp;w=320&amp;h=320&amp;q=80" alt="Image Description">
                  </div>
                  <div class="mt-3 sm:mt-5">
                    <h3 class="text-lg sm:text-3xl font-semibold text-gray-800">3+</h3>
                    <p class="mt-1 text-sm sm:text-base text-neutral-400">Countries Served</p>
                  </div>
                </div>
                <!-- End Stats -->

                <!-- Stats -->
                <div class="relative text-center first:before:hidden before:absolute before:-top-full sm:before:top-1/2 before:start-1/2 sm:before:-start-6 before:w-px before:h-20 before:bg-white before:rotate-[60deg] sm:before:rotate-12 before:transform sm:before:-translate-y-1/2 before:-translate-x-1/2 sm:before:-translate-x-0 before:mt-3.5 sm:before:mt-0">
                  <svg class="flex-shrink-0 size-6 sm:size-8 text-gray-800 mx-auto" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                    <path d="M11 15h2a2 2 0 1 0 0-4h-3c-.6 0-1.1.2-1.4.6L3 17" />
                    <path d="m7 21 1.6-1.4c.3-.4.8-.6 1.4-.6h4c1.1 0 2.1-.4 2.8-1.2l4.6-4.4a2 2 0 0 0-2.75-2.91l-4.2 3.9" />
                    <path d="m2 16 6 6" />
                    <circle cx="16" cy="9" r="2.9" />
                    <circle cx="6" cy="5" r="3" />
                  </svg>
                  <div class="mt-3 sm:mt-5">
                    <h3 class="text-lg sm:text-3xl font-semibold text-gray-800">50+</h3>
                    <p class="mt-1 text-sm sm:text-base text-neutral-400">Projects Executed</p>
                  </div>
                </div>
                <!-- End Stats -->
              </div>
            </div>
          </div>
        </div>
      </div>
      <!-- End Stats -->

      <!-- Our Service -->
      <div class="bg-white" id="services">
        <!-- Approach -->
        <div class="max-w-5xl px-4 xl:px-0 py-10 lg:pt-20  mx-auto">
          <!-- Title -->
          <div class="max-w-3xl mb-10 lg:mb-14">
            <h2 class="text-gray-900 font-semibold text-2xl md:text-4xl md:leading-tight">Our Services</h2>
            <p class="mt-1 text-neutral-400">Over the years, we have successfully completed projects across various digital services for startups, SMEs and corporates.</p>
          </div>
          <!-- End Title -->

          <!-- Grid -->
          <div class="grid md:grid-cols-3 gap-5 lg:items-center">
            <div class="card w-full rounded-xl shadow border flex flex-col items-center p-6" v-for="service in services" :key="service">
              <Icon :name='service.icon' class="w-8 h-8 text-cyan-600" />
              <h2 class="text-xl font-bold mt-4 text-center">{{ service.title }}</h2>
              <p class="text-sm mt-1 text-center">{{ service.description }}</p>
            </div>
          </div>
          <!-- End Grid -->
        </div>
      </div>
      <!-- End Approach -->

      <!-- Key Tech Expertise -->
       <section class="w-full bg-cyan-900 py-10 md:py-20 px-5 md:px-0">
        <div class="max-w-5xl mx-auto">
          <h2 class="text-4xl font-bold text-white mb-1">Key Tech Expertise</h2>
          <p class="text-gray-100">We analyze your product concept and business specifics, and bind these conclusions with industry standards, market trends, and appropriate tech stacks. Our software development firm builds top products for a particular industry, namely:</p>
        </div>
        <div class="grid grid-cols-2 md:grid-cols-5 gap-4 max-w-5xl mx-auto mt-12">
          <button class="flex flex-col items-center bg-white rounded-2xl py-5">
            <Icon name="mdi:apple-ios" class="w-20 h-20" />
            <span>iOS</span>
          </button>
          <button class="flex flex-col items-center bg-white rounded-2xl py-5">
            <Icon name="devicon:laravel" class="w-20 h-20" />
            <span>Laravel</span>
          </button>
          <button class="flex flex-col items-center bg-white rounded-2xl py-5">
            <Icon name="vscode-icons:file-type-python" class="w-20 h-20" />
            <span>Python</span>
          </button>
          <button class="flex flex-col items-center bg-white rounded-2xl py-5">
            <Icon name="logos:nodejs" class="w-20 h-20" />
            <span>Node.Js</span>
          </button>
          <button class="flex flex-col items-center bg-white rounded-2xl py-5">
            <Icon name="vscode-icons:file-type-reactjs" class="w-20 h-20" />
            <span>React</span>
          </button>
        </div>
       </section>

      <!-- Contact -->
      <div class="max-w-7xl px-4 lg:px-6 lg:px-8 py-12 lg:py-24 mx-auto" id="contact">
        <div class="mb-6 sm:mb-10 max-w-2xl text-center mx-auto">
          <h2 class="font-medium text-black text-2xl sm:text-4xl dark:text-white">
            Contacts
          </h2>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 lg:items-center gap-6 md:gap-8 lg:gap-12">
          <div class="aspect-w-16 aspect-h-6 lg:aspect-h-14 overflow-hidden bg-gray-100 rounded-2xl dark:bg-neutral-800">
            <img class="group-hover:scale-105 transition-transform duration-500 ease-in-out object-cover rounded-2xl" src="https://images.unsplash.com/photo-1572021335469-31706a17aaef?q=80&w=3540&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Image Description">
          </div>
          <!-- End Col -->

          <div class="space-y-8 lg:space-y-16">
            <div>
              <h3 class="mb-5 font-semibold text-black dark:text-white">
                Our address
              </h3>

              <!-- Grid -->
              <div class="grid sm:grid-cols-2 gap-4 sm:gap-6 md:gap-8 lg:gap-12">
                <div class="flex gap-4">
                  <svg class="flex-shrink-0 size-5 text-gray-500 dark:text-neutral-500" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
                    <path d="M20 10c0 6-8 12-8 12s-8-6-8-12a8 8 0 0 1 16 0Z"></path>
                    <circle cx="12" cy="10" r="3"></circle>
                  </svg>

                  <div class="grow">
                    <p class="text-sm text-gray-600 dark:text-neutral-400">
                      Delhi
                    </p>
                    <address class="mt-1 text-black not-italic dark:text-white">
                      India
                    </address>
                  </div>
                </div>
              </div>
              <!-- End Grid -->
            </div>

            <div>
              <h3 class="mb-5 font-semibold text-black dark:text-white">
                Our contacts
              </h3>

              <!-- Grid -->
              <div class="grid sm:grid-cols-2 gap-4 sm:gap-6 md:gap-8 lg:gap-12">
                <div class="flex gap-4">
                  <svg class="flex-shrink-0 size-5 text-gray-500 dark:text-neutral-500" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round">
                    <path d="M21.2 8.4c.5.38.8.97.8 1.6v10a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V10a2 2 0 0 1 .8-1.6l8-6a2 2 0 0 1 2.4 0l8 6Z"></path>
                    <path d="m22 10-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 10"></path>
                  </svg>

                  <div class="grow">
                    <p class="text-sm text-gray-600 dark:text-neutral-400">
                      Email us
                    </p>
                    <p>
                      <a class="relative inline-block font-medium text-black before:absolute before:bottom-0.5 before:start-0 before:-z-[1] before:w-full before:h-1 before:bg-gray-600 hover:before:bg-black focus:outline-none focus:before:bg-black dark:text-white dark:hover:before:bg-white dark:focus:before:bg-white" href="mailto:example@site.so">
                        meetouinnovation@gmail.com
                      </a>
                    </p>
                  </div>
                </div>

                <div class="flex gap-4">

                  <div class="grow hidden">
                    <p class="text-sm text-gray-600 dark:text-neutral-400">
                      Contact Us
                    </p>
                    <p>
                      <a class="relative inline-block font-medium text-black before:absolute before:bottom-0.5 before:start-0 before:-z-[1] before:w-full before:h-1 before:bg-gray-600 hover:before:bg-black focus:outline-none focus:before:bg-black dark:text-white dark:hover:before:bg-white dark:focus:before:bg-white">
                        meetouinnovation@gmail.com
                      </a>
                    </p>
                  </div>
                </div>
              </div>
              <!-- End Grid -->
            </div>
          </div>
          <!-- End Col -->
        </div>
      </div>
      <!-- End Contact -->
    </main>
    <!-- ========== END MAIN CONTENT ========== -->

    <!-- ========== FOOTER ========== -->
    <footer class="mt-auto border-t md:border-t-0 border-gray-200 dark:border-neutral-700">
      <div class="w-full max-w-7xl py-10 md:pt-0 px-4 sm:px-6 lg:px-8 mx-auto">
        <!-- Grid -->
        <div class="grid grid-cols-1 md:grid-cols-3 items-center gap-5">
          <div class="text-left">
            <!-- Logo -->
            <img src="/logo.png" class="h-12 w-full object-contain">
            <!-- End Logo -->
          </div>
          <!-- End Col -->

          <ul class="text-center">
            <li class="inline-block relative pe-8 last:pe-0 last-of-type:before:hidden before:absolute before:top-1/2 before:end-3 before:-translate-y-1/2 before:content-['/'] before:text-black dark:before:text-white">
              <a class="inline-flex gap-x-2 text-sm text-black hover:text-gray-600 dark:text-white dark:hover:text-neutral-300" href="#">
                About
              </a>
            </li>
            <li class="inline-block relative pe-8 last:pe-0 last-of-type:before:hidden before:absolute before:top-1/2 before:end-3 before:-translate-y-1/2 before:content-['/'] before:text-black dark:before:text-white">
              <a class="inline-flex gap-x-2 text-sm text-black hover:text-gray-600 dark:text-white dark:hover:text-neutral-300" href="#">
                Services
              </a>
            </li>
            <li class="inline-block relative pe-8 last:pe-0 last-of-type:before:hidden before:absolute before:top-1/2 before:end-3 before:-translate-y-1/2 before:content-['/'] before:text-black dark:before:text-white">
              <a class="inline-flex gap-x-2 text-sm text-black hover:text-gray-600 dark:text-white dark:hover:text-neutral-300" href="#">
                Blog
              </a>
            </li>
          </ul>
          <!-- End Col -->

          <!-- Social Brands -->
          <div class="text-center md:text-end space-x-2">
            <a class="size-8 inline-flex justify-center items-center gap-x-2 text-sm font-semibold rounded-full border border-transparent text-black hover:text-gray-600 disabled:opacity-50 disabled:pointer-events-none dark:text-white dark:hover:text-neutral-400" href="https://www.instagram.com/meetouinnovation/" target="_blank">
              <Icon name="hugeicons:instagram" class="w-5 h-5" />
            </a>
          </div>
          <!-- End Social Brands -->
        </div>
        <!-- End Grid -->
      </div>
    </footer>
    <!-- ========== END FOOTER ========== -->
  </div>
</template>

<script setup>
definePageMeta({
  colorMode: 'light',
})

const services = ref([
  { title: 'Mobile App development', description: 'Our experienced developers use the latest technology and advanced techniques in order to create an app tailored to your needs and satisfy your requirements. We have a wide range of solutions that is suitable for every type of business.', icon: 'material-symbols-light:phone-iphone-outline'},
  { title: 'Web Development', description: 'We provides high-quality web development services, we believe in giving customers what they want, when they want it. We take pride in our customer support, speed of delivery and resources available to developers.', icon: 'meteor-icons:laptop'},
  { title: 'E-Commerce', description: 'We are  focusing on offering world class E-Commerce solutions for all our clients. We ensure that you are always informed about the latest trends, and provide you with a professional platform to showcase your products and services.', icon: 'material-symbols-light:shopping-cart-outline'},
  { title: 'Digital Marketing', description: 'Our team is always on the move, delivering high-quality digital marketing services to clients all over the world. We are committed to providing customer-centric solutions that help you grow your business by making it visible online.', icon: 'material-symbols:table-chart-view-outline-rounded'},
  { title: 'CMS Development', description: "CMS development will streamline the construction and maintenance of a website, while also helping you reach your target audience. Whether you are an agency launching a new client's site, or just looking to change your personal blog, we can help.", icon: 'material-symbols:settings-outline-rounded'},
  { title: 'Web & Graphics Design', description: "We offers a wide range of customized services in the field of Website and App Design like iPhone & Android App Designing, Web , e-Commerce and Graphic Design . We have a creative, talented, devoted and enthusiastic team, who provide professional result.", icon: 'icon-park-outline:graphic-design-two'},
])
</script>

<style>

</style>