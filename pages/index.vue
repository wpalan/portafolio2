<template>


<div class="bg-gradient-to-r from-black to-violet-700 text-teal-400">
  
 
  <div class="flex">


    <div class="justify-start ml-5">
      <NuxtImg  class="w-60" src="images/profile2.jpg"/>
      <ul>
        <li> W. P. Alan</li>
        <li>Proyectos</li>
        <li>Certificados</li>
        <li>Skills</li>
        <li>Contacto</li>
      </ul>
    </div>
  
    <div class="text-center justify-center ml-[1in]">
    <div>
      <h1 class="mt-10 text-4xl">
      ALAN EMMANUEL WOZNIEZKA PIZARRO
    </h1>
      </div>
    <div class="flex justify-center mt-5">
          <div class="text-center">
          <p class="text-3xl">Binvenidos a mi Portafolio</p>
          <p class="mt-5">Soy desarrollador web en busca de experiencia en el campo para trabajar en pequeños o medianos proyectos y avanzar en mi carrera profesional</p>
          <button> Descargar mi CV </button>
        </div>
    </div>
    </div>
</div>

<div class="text-center mt-20 ">

    <h1 class="text-3xl">Proyectos</h1>


    <div id="indicators-carousel" class="relative w-full" data-carousel="static">
    <!-- Carousel wrapper -->
    <div class="relative h-56 overflow-hidden rounded-lg md:h-96">
         <!-- Item 1 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item="active">
          
        </div>
        <!-- Item 2 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            
        </div>
        <!-- Item 3 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
           
        </div>
        <!-- Item 4 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            
        </div>
        <!-- Item 5 -->
        <div class="hidden duration-700 ease-in-out" data-carousel-item>
            
        </div>
    </div>
    <!-- Slider indicators -->
    <div class="absolute z-30 flex -translate-x-1/2 space-x-3 rtl:space-x-reverse bottom-5 left-1/2">
        <button type="button" class="w-3 h-3 rounded-full" aria-current="true" aria-label="Slide 1" data-carousel-slide-to="0"></button>
        <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 2" data-carousel-slide-to="1"></button>
        <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 3" data-carousel-slide-to="2"></button>
        <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 4" data-carousel-slide-to="3"></button>
        <button type="button" class="w-3 h-3 rounded-full" aria-current="false" aria-label="Slide 5" data-carousel-slide-to="4"></button>
    </div>
    <!-- Slider controls -->
    <button type="button" class="absolute top-0 start-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none" data-carousel-prev>
        <span class="inline-flex items-center justify-center w-10 h-10 rounded-full bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
            <svg class="w-4 h-4 text-white dark:text-gray-800 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 6 10">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 1 1 5l4 4"/>
            </svg>
            <span class="sr-only">Previous</span>
        </span>
    </button>
    <button type="button" class="absolute top-0 end-0 z-30 flex items-center justify-center h-full px-4 cursor-pointer group focus:outline-none" data-carousel-next>
        <span class="inline-flex items-center justify-center w-10 h-10 rounded-full bg-white/30 dark:bg-gray-800/30 group-hover:bg-white/50 dark:group-hover:bg-gray-800/60 group-focus:ring-4 group-focus:ring-white dark:group-focus:ring-gray-800/70 group-focus:outline-none">
            <svg class="w-4 h-4 text-white dark:text-gray-800 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 6 10">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="m1 9 4-4-4-4"/>
            </svg>
            <span class="sr-only">Next</span>
        </span>
    </button>
</div>


 </div>


<div class="text-center row-auto mt-20 flex-row">

  <h1 class="mt-10 text-3xl">Certificados</h1>
  <p> Certificados obtenidos en la Universidad Tecnológica Nacional del curso Profesional FrontEnd Web Developer en los meses de Marzo hasta Noviembre de 2023. </p>
  
  <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
    <div class="p-5">
        
            <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Desarrollo Web en HTML5 y CSS3</h5>
        
       
    </div>

    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
        <div class="p-5">
         <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Desarrollo Web con JavaScript</h5>
        </div>
    </div>

    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
        <div class="p-5">
         <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Desarrollo Web Nivel Avanzado</h5>
        </div>
    </div>

    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
        <div class="p-5">
         <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Desarrollo Web con Bootstrap</h5>
        </div>
    </div>

    <div class="max-w-sm bg-white border border-gray-200 rounded-lg shadow dark:bg-gray-800 dark:border-gray-700">
        <div class="p-5">
         <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Certificado Professional Front End Developer</h5>
        </div>
    </div>

</div>



<div class="text-center mt-20">
<h1 class="text-3xl">Skills</h1>
<h2 class="mt-10">HardSkills</h2>
<h2 class="mt-10">SoftSkills</h2>
<p>Manejo adecuado de los tiempos</p>
<p>Comunicación eficaz entre cliente y profesional, así como entre compañeros de trabajo y el entorno laboral</p>
<p>Adaptabildiad a los estándares obligatorios que se impongan y el respeto adecuado de los mismos, así como a las herramientas y diferentes obligaciones</p>
<p>Creatividad y atención a los detalles</p>
<p>Resolución eficaz de problemas</p>

<p class="mt-20 text-3xl">Contacto</p>

</div>

</div>

</div>

</template>

