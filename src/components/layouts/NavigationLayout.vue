<script>
import Logo from '../logo/Logo.vue';
import {Bars3Icon} from '@heroicons/vue/24/outline';

export default {
    data() {
        return {
            showNav: false,
            navlinks: [
                { name: "Home", link: "#", active: true },
                { name: "Contatos", link: "#", active: false },
                { name: "Sobre", link: "#", active: false },
            ],
            show: false,
            showNavItems: false,
        };
    },
    mounted() {
        this.show = true;
        console.log(this.$route);
        this.teste = this.$route
    },
    components: { 
        Logo,
        Bars3Icon 
    
    }
}
</script>
<template>
    <header class="px-10 hidden sm:block">
        <transition
          enter-active-class="ease-out duration-1000"
          enter-from-class="opacity-75 -translate-x-[30rem] skew-y-3"
          enter-to-class="opacity-100 translate-x-0 skew-0"
          leave-active-class="ease-in duration-200"
          leave-from-class="opacity-100"
          leave-to-class="opacity-0"
        >
        <div v-if="show" class="grid grid-cols-3 my-8 text-white">
        <logo/>
        <div class="flex items-center justify-center space-x-10">
            <button v-for="navlink in navlinks" class="group">
                <p :class="navlink.active ? 'font-bold' : ''">{{ navlink.name }}</p>
                <div
                    :class="[navlink.active ? 'w-3' : 'w-0', 'h-[3px] group-hover:w-full transition-all duration-300 bg-gradient-to-r from-orange-400 to-pink-600 rounded-full']">
                </div>
            </button>
        </div>
        <a href="https://github.com/felipedossantosoliveira/BlogPessoal" target="_blank" class="flex justify-end items-center space-x-2 font-semibold">
            <p class="text-2xl -translate-y-0.5 bg-clip-text text-transparent bg-gradient-to-b to-orange-400 from-pink-600">
                &lt;</p>
            <p>Source code</p>
            <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-github w-7 sm:w-6 lg:w-6"
                viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round"
                stroke-linejoin="round">
                <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                <path
                    d="M9 19c-4.3 1.4 -4.3 -2.5 -6 -3m12 5v-3.5c0 -1 .1 -1.4 -.5 -2c2.8 -.3 5.5 -1.4 5.5 -6a4.6 4.6 0 0 0 -1.3 -3.2a4.2 4.2 0 0 0 -.1 -3.2s-1.1 -.3 -3.5 1.3a12.3 12.3 0 0 0 -6.2 0c-2.4 -1.6 -3.5 -1.3 -3.5 -1.3a4.2 4.2 0 0 0 -.1 3.2a4.6 4.6 0 0 0 -1.3 3.2c0 4.6 2.7 5.7 5.5 6c-.6 .6 -.6 1.2 -.5 2v3.5">
                </path>
            </svg>
            <p class="text-2xl -translate-y-0.5 bg-clip-text text-transparent bg-gradient-to-b to-orange-400 from-pink-600">
                /></p>
        </a >
        </div>
        </transition>
    </header>
    <header class="px-4 sm:hidden">
        <transition
          enter-active-class="ease-out duration-1000"
          enter-from-class="opacity-75 -translate-x-[30rem] skew-y-3"
          enter-to-class="opacity-100 translate-x-0 skew-0"
          leave-active-class="ease-in duration-200"
          leave-from-class="opacity-100"
          leave-to-class="opacity-0"
          >
          <div v-if="show" class="flex justify-between my-8 text-white">
            <logo/>
            <button @click="showNavItems = !showNavItems">
                <Bars3Icon class="w-10 text-white"/>
            </button>
        </div>
    </transition>
    <div>
        <transition
          enter-active-class="ease-out duration-500"
          enter-from-class="opacity-75 -translate-y-24"
          enter-to-class="opacity-100 translate-y-0 "
          leave-active-class="ease-in duration-500"
          leave-from-class="opacity-100 translate-y-0"
          leave-to-class="opacity-75 -translate-y-36"
        >
        <div v-if="showNavItems" class="flex flex-col items-center border-b pb-5 justify-center space-y-2 bg-red-200/30">
            <button v-for="navlink in navlinks" class="group w-full">
                <div class="w-full bg-red-100/20">
                    <p :class="[navlink.active ? 'font-bold' : '', 'text-white']">{{ navlink.name }}</p>
                    <!-- <div
                        :class="[navlink.active ? 'w-3' : 'w-0', 'h-[3px] group-hover:w-full transition-all duration-300 bg-gradient-to-r from-orange-400 to-pink-600 rounded-full']">
                    </div> -->
                </div>
            </button>
        </div>
        </transition>
    </div>
        <!-- <div class="flex items-center justify-center space-x-10">
            <button v-for="navlink in navlinks" class="group">
                <p :class="navlink.active ? 'font-bold' : ''">{{ navlink.name }}</p>
                <div
                    :class="[navlink.active ? 'w-3' : 'w-0', 'h-[3px] group-hover:w-full transition-all duration-300 bg-gradient-to-r from-orange-400 to-pink-600 rounded-full']">
                </div>
            </button>
        </div> -->
        <!-- <a href="https://github.com/felipedossantosoliveira/BlogPessoal" target="_blank" class="flex justify-end items-center space-x-2 font-semibold">
            <p class="text-2xl -translate-y-0.5 bg-clip-text text-transparent bg-gradient-to-b to-orange-400 from-pink-600">
                &lt;</p>
            <p>Source code</p>
            <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-github w-7 sm:w-6 lg:w-6"
                viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round"
                stroke-linejoin="round">
                <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                <path
                    d="M9 19c-4.3 1.4 -4.3 -2.5 -6 -3m12 5v-3.5c0 -1 .1 -1.4 -.5 -2c2.8 -.3 5.5 -1.4 5.5 -6a4.6 4.6 0 0 0 -1.3 -3.2a4.2 4.2 0 0 0 -.1 -3.2s-1.1 -.3 -3.5 1.3a12.3 12.3 0 0 0 -6.2 0c-2.4 -1.6 -3.5 -1.3 -3.5 -1.3a4.2 4.2 0 0 0 -.1 3.2a4.6 4.6 0 0 0 -1.3 3.2c0 4.6 2.7 5.7 5.5 6c-.6 .6 -.6 1.2 -.5 2v3.5">
                </path>
            </svg>
            <p class="text-2xl -translate-y-0.5 bg-clip-text text-transparent bg-gradient-to-b to-orange-400 from-pink-600">
                /></p>
        </a > -->
    </header>
    <transition
          enter-active-class="ease-out duration-1000"
          enter-from-class="opacity-75 translate-x-96 -skew-y-3"
          enter-to-class="opacity-100 translate-x-0 skew-0"
          leave-active-class="ease-in duration-200"
          leave-from-class="opacity-100"
          leave-to-class="opacity-0"
        >
        <div v-if="show" class="mb-10">
            <slot >
            </slot>
        </div>
    </transition>
</template>