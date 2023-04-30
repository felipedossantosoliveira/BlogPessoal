<script setup>
import IconVue from "@/components/icons/IconVue.vue"
import IconTailwind from "@/components/icons/IconTailwind.vue"
import IconJS from "@/components/icons/IconJS.vue"
import IconHTML from "@/components/icons/IconHTML.vue"
import IconCSS from "@/components/icons/IconCSS.vue"

const languages = [
	{
		name: "Vue",
		icon: IconVue,
	},
	{
		name: "Tailwind",
		icon: IconTailwind,
	},
	{
		name: "JavaScript",
		icon: IconJS,
	},
	{
		name: "HTML",
		icon: IconHTML,
	},
	{
		name: "CSS",
		icon: IconCSS,
	},
]
</script>
<template>
	<div class="flex w-full py-px bg-gradient-to-r from-orange-700 to-pink-600">
			<div class="w-full h-full p-7 bg-zinc-900 grid grid-cols-5">
				<div v-for="icon in languages" class="flex justify-center items-end grayscale hover:grayscale-0">
					<component :is="icon.icon" class="w-20" />
				</div>
			</div>
		</div>
</template>