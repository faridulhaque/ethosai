<template>
  <div class="container h-20 mx-auto relative">
    <!-- logo fixed with position -->
    <div class="flex items-center justify-center mt-5 h-1 absolute left-0">
      <a class="" href="https://openqa.ai/">
        <img src="public/logo.png" class="w-35" alt="ethosAI Logo">
      </a>
    </div>

    <div class="flex justify-center items-center mt-10">

      <nav class="space-x-8 border-white px-2 md-px-8 md-py-4 border rounded-full max-w-3xl text-light">
        <NuxtLink to="/" class="hover:text-gray">Home</NuxtLink>
        <NuxtLink to="https://ethos-ai.gitbook.io/ethosai-whitepaper" class="hover:text-gray">Whitepaper
        </NuxtLink>
        <!-- <NuxtLink to="/" class="hover:text-gray">Blog</NuxtLink> -->
        <NuxtLink to="https://www.linkedin.com/company/ethosaione/jobs/" class="hover:text-gray">Careers</NuxtLink>
        <NuxtLink to="mailto: contactethosai@gmail.com" class="hover:text-gray">Contact</NuxtLink>
      </nav>
    </div>
  </div>
</template>