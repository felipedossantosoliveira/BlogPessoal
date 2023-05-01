<script setup>
import Languages from "./partial/Languages.vue"

</script>
<template>
	<main class="sm:px-10 px-4 mt-10 sm:mt-20">
		<section>
			<div class="flex justify-center w-full">
				<div class="space-y-4">
					<div class="w-36 h-36 overflow-hidden bg-gradient-to-r from-orange-700 to-pink-600 rounded-full">
						<img src="../../assets/img/foto.png" alt="Foto de Felipe dos Santos Oliveira"
							class="-translate-x-1.5  w-full">
					</div>
					<p class="text-center text-neutral-200 text-sm font-semi-bold">Olá, eu sou Felipe!</p>
				</div>
			</div>
			<div
				class="flex justify-center bg-clip-text text-transparent bg-gradient-to-r from-white via-orange-100/80 to-orange-600 text-center mt-5 sm:mt-16 sm:leading-[3rem] font-semibold text-xl sm:text-4xl ">
				<p>Front-end developer.<br>Construindo produtos digitais e<br>proporcionando experiências.</p>
			</div>
			<div class="flex items-center justify-center my-10">
				<button
					class="px-4 py-2 text-neutral-200 border border-orange-200 hover:border-orange-500 rounded-lg flex items-center space-x-2">
					<svg xmlns="http://www.w3.org/2000/svg"
						class="icon icon-tabler icon-tabler-brand-github w-7 sm:w-6 lg:w-6" viewBox="0 0 24 24"
						stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
						<path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
						<path
							d="M9 19c-4.3 1.4 -4.3 -2.5 -6 -3m12 5v-3.5c0 -1 .1 -1.4 -.5 -2c2.8 -.3 5.5 -1.4 5.5 -6a4.6 4.6 0 0 0 -1.3 -3.2a4.2 4.2 0 0 0 -.1 -3.2s-1.1 -.3 -3.5 1.3a12.3 12.3 0 0 0 -6.2 0c-2.4 -1.6 -3.5 -1.3 -3.5 -1.3a4.2 4.2 0 0 0 -.1 3.2a4.6 4.6 0 0 0 -1.3 3.2c0 4.6 2.7 5.7 5.5 6c-.6 .6 -.6 1.2 -.5 2v3.5">
						</path>
					</svg>
					<p>
						github page
					</p>
				</button>
			</div>
		</section>
		<section>
				<Languages />
		</section>
	</main>
</template>	