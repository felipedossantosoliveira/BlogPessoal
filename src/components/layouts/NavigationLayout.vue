<script>
export default {
    data() {
        return {
            showNav: false,
        }
    }
}
</script>
<template>
    <header class="bg-zinc-900 py-5 px-5 sm:px-16 xl:px-64 flex flex-wrap justify-between items-center text-white sm:space-y-6 lg:space-y-0">
        <span class="flex items-center lg:justify-start sm:justify-center space-x-4 lg:w-auto sm:w-full">
            <svg class="sm:w-12 w-8" viewBox="0 0 322 397" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M161 356V266C161 249.431 174.431 236 191 236H206C222.569 236 236 222.569 236 206V191C236 174.431 222.569 161 206 161H41C24.4315 161 11 147.569 11 131V116C11 99.4315 24.4315 86 41 86H281C297.569 86 311 72.5685 311 56V41C311 24.4315 297.569 11 281 11H116C99.4315 11 86 24.4315 86 41V356C86 372.569 99.4315 386 116 386H131C147.569 386 161 372.569 161 356Z" stroke="url(#paint0_diamond_5_50)" stroke-width="22"/>
                <defs>
                <radialGradient id="paint0_diamond_5_50" cx="0" cy="0" r="1" gradientUnits="userSpaceOnUse" gradientTransform="translate(207 45) rotate(116.687) scale(523.241 418.593)">
                <stop stop-color="#4C8764"/>
                <stop offset="1" stop-color="#93AFD1"/>
                </radialGradient>
                </defs>
            </svg>
            <p class="sm:text-4xl text-2xl font-bold">Felipe dos Santoss</p>
        </span>
        <button class="sm:hidden" @click="showNav = ! showNav">
            <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-menu-2 w-8" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                <line x1="4" y1="6" x2="20" y2="6"></line>
                <line x1="4" y1="12" x2="20" y2="12"></line>
                <line x1="4" y1="18" x2="20" y2="18"></line>
            </svg>
        </button>
        <nav class="hidden sm:flex items-center justify-center w-full lg:justify-start lg:w-auto">
            <ul class="flex items-center space-x-4 lg:space-x-7 text-sm lg:text-base">
                <li>
                    <a href="https://www.instagram.com/lipe_santossx" target="_blank"
                        class="flex items-center space-x-1">
                        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-address-book w-6 lg:w-9" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                            <path d="M20 6v12a2 2 0 0 1 -2 2h-10a2 2 0 0 1 -2 -2v-12a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2z"></path>
                            <path d="M10 16h6"></path>
                            <circle cx="13" cy="11" r="2"></circle>
                            <path d="M4 8h3"></path>
                            <path d="M4 12h3"></path>
                            <path d="M4 16h3"></path>
                        </svg>
                        Contatos
                    </a>
                </li>
                <li>
                    <a href="https://github.com/felipedossantosoliveira" target="_blank"
                        class="flex items-center space-x-1">
                        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-github w-6 lg:w-9"
                            viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none"
                            stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                            <path
                                d="M9 19c-4.3 1.4 -4.3 -2.5 -6 -3m12 5v-3.5c0 -1 .1 -1.4 -.5 -2c2.8 -.3 5.5 -1.4 5.5 -6a4.6 4.6 0 0 0 -1.3 -3.2a4.2 4.2 0 0 0 -.1 -3.2s-1.1 -.3 -3.5 1.3a12.3 12.3 0 0 0 -6.2 0c-2.4 -1.6 -3.5 -1.3 -3.5 -1.3a4.2 4.2 0 0 0 -.1 3.2a4.6 4.6 0 0 0 -1.3 3.2c0 4.6 2.7 5.7 5.5 6c-.6 .6 -.6 1.2 -.5 2v3.5">
                            </path>
                        </svg>
                        GitHub
                    </a>
                </li>
                <li>
                    <a href="https://www.instagram.com/lipe_santossx" target="_blank"
                        class="flex items-center space-x-1">
                        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-instagram w-6 lg:w-9"
                            viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none"
                            stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                            <rect x="4" y="4" width="16" height="16" rx="4"></rect>
                            <circle cx="12" cy="12" r="3"></circle>
                            <line x1="16.5" y1="7.5" x2="16.5" y2="7.501"></line>
                        </svg>
                        Instagram
                    </a>
                </li>
            </ul>
        </nav>
        <nav v-if="showNav" class="flex items-center justify-center w-full">
            <ul class="pt-4 sm:text-sm lg:text-base space-y-6">
                <li class="">
                    <a href="https://www.instagram.com/lipe_santossx" target="_blank"
                        class="flex justify-start items-center space-x-2">
                        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-address-book w-7 sm:w-6 lg:w-9" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                            <path d="M20 6v12a2 2 0 0 1 -2 2h-10a2 2 0 0 1 -2 -2v-12a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2z"></path>
                            <path d="M10 16h6"></path>
                            <circle cx="13" cy="11" r="2"></circle>
                            <path d="M4 8h3"></path>
                            <path d="M4 12h3"></path>
                            <path d="M4 16h3"></path>
                        </svg>
                        <p>Contatos</p>
                    </a>
                </li>
                <li class="">
                    <a href="https://github.com/felipedossantosoliveira" target="_blank"
                        class="flex justify-start items-center space-x-2">
                        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-github w-7 sm:w-6 lg:w-9"
                            viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none"
                            stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                            <path
                                d="M9 19c-4.3 1.4 -4.3 -2.5 -6 -3m12 5v-3.5c0 -1 .1 -1.4 -.5 -2c2.8 -.3 5.5 -1.4 5.5 -6a4.6 4.6 0 0 0 -1.3 -3.2a4.2 4.2 0 0 0 -.1 -3.2s-1.1 -.3 -3.5 1.3a12.3 12.3 0 0 0 -6.2 0c-2.4 -1.6 -3.5 -1.3 -3.5 -1.3a4.2 4.2 0 0 0 -.1 3.2a4.6 4.6 0 0 0 -1.3 3.2c0 4.6 2.7 5.7 5.5 6c-.6 .6 -.6 1.2 -.5 2v3.5">
                            </path>
                        </svg>
                        <p>GitHub</p>
                    </a>
                </li>
                <li class="">
                    <a href="https://www.instagram.com/lipe_santossx" target="_blank"
                        class="flex justify-start items-center space-x-2">
                        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-instagram w-6 lg:w-9"
                            viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none"
                            stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                            <rect x="4" y="4" width="16" height="16" rx="4"></rect>
                            <circle cx="12" cy="12" r="3"></circle>
                            <line x1="16.5" y1="7.5" x2="16.5" y2="7.501"></line>
                        </svg>
                        <p>
                            Instagram
                        </p>
                    </a>
                </li>
                <li class="flex justify-center items-center">
                    <button class="" @click="showNav = ! showNav">
                        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-chevron-up w-7" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none"></path>
                            <polyline points="6 15 12 9 18 15"></polyline>
                        </svg>
                    </button>
                </li>
            </ul>
        </nav>
    </header>
</template>