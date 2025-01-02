<template>
  <section class="relative w-full" data-aos="zoom-in-up">
      <div class="absolute top-0 inset-x-0 h-64 flex items-start">
          <div class="h-24 w-2/3 bg-gradient-to-br from-[#570cac] blur-2xl invisible opacity-40"></div>
          <div class="h-20 w-3/5 bg-gradient-to-r from-[#670ccf] opacity-40 blur-2xl"></div>
      </div>
      <div class="w-full px-5 sm:px-8 md:px-12 lg:px-8 max-w-screen-lg lg:max-w-screen-xl mx-auto relative">
          <div class="grid lg:grid-cols-2 gap-10 xl:gap-14 relative pt-24 lg:max-w-none max-w-2xl md:max-w-3xl mx-auto">
              <div class="lg:py-6">
                  <div class="text-center lg:text-left">
                      <h1 class="pt-4 text-white font-bold text-4xl md:text-5xl lg:text-6xl">
                          Hi, I'm <span class="text-transparent bg-clip-text bg-gradient-to-r from-primary to-pink-500">
                              Marwane Skaro
                          </span>😁
                      </h1>
                  </div>
                  <p class="text-gray-300 pt-8 text-center lg:text-left mx-auto max-w-xl">
                    Hi, I'm Marwane Skaro, a passionate software engineering student with a drive for tackling new challenges and a commitment to learning something new every day!
                  </p>
                  <div class="flex items-center gap-3 pt-9 flex-col sm:flex-row sm:w-max sm:mx-auto lg:mx-0">
                    <button class="flex items-center border border-primary px-6 md:px-7 py-3 rounded-full relative group w-full sm:w-max">
                      <svg class="w-6 h-6 text-primary" fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                        <path d="M22.23 0H1.77C.792 0 0 .775 0 1.731V22.27C0 23.225.792 24 1.77 24h20.46c.978 0 1.77-.775 1.77-1.73V1.731C24 .775 23.208 0 22.23 0zM7.19 20.452H3.55V9.038h3.64v11.414zm-1.82-13.06a2.106 2.106 0 01-2.117-2.094 2.106 2.106 0 012.117-2.094c1.17 0 2.117.94 2.117 2.094 0 1.154-.947 2.094-2.117 2.094zM20.451 20.452h-3.641v-5.579c0-1.33-.473-2.236-1.655-2.236-.902 0-1.436.61-1.67 1.2-.086.211-.108.506-.108.801v5.814h-3.641V9.038h3.641v1.534c.482-.745 1.344-1.807 3.26-1.807 2.384 0 4.173 1.554 4.173 4.89v6.797z"/>
                      </svg>
                      <a href="https://www.linkedin.com/in/marwane-skaro-618971239/" target="_blank">
                        <span class="pl-2 text-primary">LinkedIn</span>
                      </a>
                    </button>

                    <button class="flex items-center border border-primary px-6 md:px-7 py-3 rounded-full relative group w-full sm:w-max">
                      <svg class="w-6 h-6 text-primary" fill="currentColor" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
                        <path d="M12 0C5.371 0 0 5.371 0 12c0 5.302 3.438 9.799 8.207 11.387.6.111.793-.261.793-.577 0-.285-.011-1.041-.017-2.043-3.338.726-4.042-1.609-4.042-1.609-.546-1.385-1.333-1.755-1.333-1.755-1.09-.745.083-.73.083-.73 1.204.085 1.837 1.236 1.837 1.236 1.07 1.835 2.805 1.304 3.49.998.108-.775.418-1.305.76-1.606-2.665-.305-5.466-1.332-5.466-5.932 0-1.31.469-2.381 1.236-3.221-.124-.305-.535-1.526.117-3.182 0 0 1.008-.322 3.302 1.23a11.47 11.47 0 013.003-.403 11.47 11.47 0 013.003.403c2.292-1.552 3.3-1.23 3.3-1.23.653 1.656.243 2.877.118 3.182.768.84 1.236 1.911 1.236 3.221 0 4.61-2.804 5.624-5.476 5.922.43.372.814 1.105.814 2.228 0 1.608-.015 2.906-.015 3.303 0 .319.192.694.8.576C20.565 21.796 24 17.302 24 12c0-6.629-5.371-12-12-12z"/>
                      </svg>
                      <a href="https://github.com/marwane2001" target="_blank" >  <span class="pl-2 text-primary">  Github </span></a>
                    </button>
                    <button class="border border-primary px-6 md:px-7 py-3 rounded-full relative group w-full sm:w-max flex justify-center">
                      <div class="hover:scale-105 transition-all ease-in-out flex justify-center items-center relative">
                        <div class="svg-container">
                          <svg class="download-icon" width="18" height="22" viewBox="0 0 18 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path class="download-arrow" d="M13 9L9 13M9 13L5 9M9 13V1" stroke="#f59e0b" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
                            <path d="M1 17V18C1 18.7956 1.31607 19.5587 1.87868 20.1213C2.44129 20.6839 3.20435 21 4 21H14C14.7956 21 15.5587 20.6839 16.1213 20.1213C16.6839 19.5587 17 18.7956 17 18V17" stroke="#f59e0b" stroke-width="2" stroke-linecap="round" />
                          </svg>
                          <div class="download-loader text-white hidden"></div>
                        </div>
                        <a href="/assets/CV_FR.pdf" download="CV_FR.pdf" class="pl-2 text-primary">Download resume</a>
                      </div>
                    </button>
                  </div>
              </div>
              <div class="lg:h-full md:flex">
                  <div class="flex w-full h-96 min-h-[24rem] lg:min-h-[none] lg:w-full lg:h-full items-center relative">
                      <div class="absolute z-0 top-1/2 -translate-y-1/2 w-5/6 right-0 h-[calc(80%+20px)] bg-gradient-to-tr opacity-25 from-[#570cac] to-primary blur-2xl"></div>
                      <div class="absolute h-full z-10 p-2 -translate-y-1/2 top-1/2 lg:right-3 md:right-40 sm:right-16 rounded-full shadow-lg border border-primary">
                          <img src="@/assets/top.jpg" alt="Hero pic" width="500" height="auto" loading="lazy"
                          class="w-full h-full rounded-full object-cover"
                          >
                      </div>
                  </div>
              </div>
          </div>
      </div>
  </section>
</template>
<script setup>
import AOS from 'aos';
import 'aos/dist/aos.css';
AOS.init(
    {
      once: true, // Ensures animations trigger only once
      duration: 1000, // Adjust animation duration
      easing: 'ease-out-back', // Smooth easing for animations
    }
);
</script>