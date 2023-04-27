<script>
import NavigationLayout from "@/components/layouts/NavigationLayout.vue"
export default {
  data() {
    return {
    }
  },
  components: {
    NavigationLayout,
  }
}
</script>

<template>
    <NavigationLayout/>
    <main class="px-10">
        <section>
          <div  class="flex justify-center w-full">
            <div class="space-y-4">
              <div class="w-36 h-36 overflow-hidden bg-gradient-to-r from-orange-700 to-pink-600 rounded-full">
                <img src="../src/assets/img/foto.png" alt="Foto de Felipe dos Santos Oliveira" class="-translate-x-1.5  w-full">
              </div>
              <p class="text-center text-neutral-200 text-sm font-semi-bold">Hi. I am Felipe!</p>
            </div>
          </div>
          <div class="flex justify-center bg-clip-text text-transparent bg-gradient-to-r from-white via-orange-100/80 to-orange-600 text-center my-16 leading-[3rem] font-semibold text-4xl ">
            <p>Front-end developer.<br>Construindo produtos digitais, e<br>experiências.</p>
          </div>
        </section>
        <div class="flex w-full h-2">

        </div>
      <!-- <section class="relative">
        <span class="absolute top-5 left-0 lg:w-72 w-48">
          <figure>
            <img src="../src/assets/img/Foto.jpg" alt="Foto de Felipe dos Santos Oliveira" class="w-full">
          </figure>
          <div class="flex items-center justify-center bg-zinc-800 w-full p-5 mt-5 text-neutral-100 font-semibold text-[0.97rem]">
              <p>Felipe dos Santos Oliveira, 21 anos</p>
          </div>
        </span>
        <div class="h-[39rem] flex ml-24 bg-zinc-900">

        </div>
      </section> -->
    </main>
</template>
