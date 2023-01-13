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
    <main class="xl:mx-56 mx-16 my-14">
      <section class="relative">
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
      </section>
    </main>
</template>
