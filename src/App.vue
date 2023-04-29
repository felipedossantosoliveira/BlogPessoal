<script>
import NavigationLayout from "@/components/layouts/NavigationLayout.vue"
import IconVue from "@/components/icons/IconVue.vue"
import IconTailwind from "@/components/icons/IconTailwind.vue"
export default {
  data() {
    return {
    }
  },
  components: {
    NavigationLayout,
    IconVue,
    IconTailwind
  }
}
</script>

<template>
  <NavigationLayout>
    <main class="px-10 mt-20">
      <section>
        <div class="flex justify-center w-full">
          <div class="space-y-4">
            <div class="w-36 h-36 overflow-hidden bg-gradient-to-r from-orange-700 to-pink-600 rounded-full">
              <img src="../src/assets/img/foto.png" alt="Foto de Felipe dos Santos Oliveira"
                class="-translate-x-1.5  w-full">
            </div>
            <p class="text-center text-neutral-200 text-sm font-semi-bold">Hi. I am Felipe!</p>
          </div>
        </div>
        <div
          class="flex justify-center bg-clip-text text-transparent bg-gradient-to-r from-white via-orange-100/80 to-orange-600 text-center mt-16 leading-[3rem] font-semibold text-4xl ">
          <p>Front-end developer.<br>Construindo produtos digitais e<br>experiências.</p>
        </div>
        <div class="flex items-center justify-center my-10">
          <button class="px-4 py-2 text-neutral-200 border border-orange-200 hover:border-orange-500 rounded-lg flex items-center space-x-2">
            <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-github w-7 sm:w-6 lg:w-6"
                viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round"
                stroke-linejoin="round">
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
      <div class="flex w-full py-px bg-gradient-to-r from-orange-700 to-pink-600">
        <div class="w-full h-full p-7 bg-zinc-900 grid grid-cols-5">
          <div class="flex justify-center items-end grayscale hover:grayscale-0">
            <IconVue class="w-20"/>
          </div>
          <div class="flex justify-center items-end grayscale">
            <svg class="w-20" viewBox="0 0 1000 1000" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path
                d="M489.5 226.499C328 231.632 280 346.999 269 409.499C283.333 386.332 328.5 335.5 395 335.5C472.5 335.5 531.5 422 567.5 449C611.237 481.803 699.123 525.115 814.5 490C906.5 462 949.167 364.332 958.5 317.999C914 378.499 846.5 414.838 763 371.999C705.5 342.499 662.5 221 489.5 226.499Z"
                fill="#07B6D5" />
              <path
                d="M261 500.999C99.5 506.132 51.5 621.499 40.5 683.999C54.8333 660.832 100 610 166.5 610C244 610 303 696.5 339 723.5C382.737 756.303 470.623 799.615 586 764.5C678 736.5 720.667 638.832 730 592.499C685.5 652.999 618 689.338 534.5 646.499C477 616.999 434 495.5 261 500.999Z"
                fill="#07B6D5" />
            </svg>
          </div>
          <div class="flex justify-center items-end grayscale">
            <svg xmlns="http://www.w3.org/2000/svg" class="w-20" viewBox="0 0 630 630">
              <rect width="630" height="630" fill="#7d6a15" />
              <path
                d="m423.2 492.19c12.69 20.72 29.2 35.95 58.4 35.95 24.53 0 40.2-12.26 40.2-29.2 0-20.3-16.1-27.49-43.1-39.3l-14.8-6.35c-42.72-18.2-71.1-41-71.1-89.2 0-44.4 33.83-78.2 86.7-78.2 37.64 0 64.7 13.1 84.2 47.4l-46.1 29.6c-10.15-18.2-21.1-25.37-38.1-25.37-17.34 0-28.33 11-28.33 25.37 0 17.76 11 24.95 36.4 35.95l14.8 6.34c50.3 21.57 78.7 43.56 78.7 93 0 53.3-41.87 82.5-98.1 82.5-54.98 0-90.5-26.2-107.88-60.54zm-209.13 5.13c9.3 16.5 17.76 30.45 38.1 30.45 19.45 0 31.72-7.61 31.72-37.2v-201.3h59.2v202.1c0 61.3-35.94 89.2-88.4 89.2-47.4 0-74.85-24.53-88.81-54.075z" />
            </svg>
          </div>
          <div class="flex justify-center items-end grayscale">
            <svg class="w-20" viewBox="-52.5 0 361 361" xmlns="http://www.w3.org/2000/svg"
              preserveAspectRatio="xMinYMin meet">
              <path d="M255.555 70.766l-23.241 260.36-104.47 28.962-104.182-28.922L.445 70.766h255.11z" fill="#E44D26" />
              <path d="M128 337.95l84.417-23.403 19.86-222.49H128V337.95z" fill="#F16529" />
              <path
                d="M82.82 155.932H128v-31.937H47.917l.764 8.568 7.85 88.01H128v-31.937H85.739l-2.919-32.704zM90.018 236.542h-32.06l4.474 50.146 65.421 18.16.147-.04V271.58l-.14.037-35.568-9.604-2.274-25.471z"
                fill="#EBEBEB" />
              <path
                d="M24.18 0h16.23v16.035h14.847V0h16.231v48.558h-16.23v-16.26H40.411v16.26h-16.23V0zM92.83 16.103H78.544V0h44.814v16.103h-14.295v32.455h-16.23V16.103h-.001zM130.47 0h16.923l10.41 17.062L168.203 0h16.93v48.558h-16.164V24.49l-11.166 17.265h-.28L146.35 24.49v24.068h-15.88V0zM193.21 0h16.235v32.508h22.824v16.05h-39.06V0z" />
              <path
                d="M127.89 220.573h39.327l-3.708 41.42-35.62 9.614v33.226l65.473-18.145.48-5.396 7.506-84.08.779-8.576H127.89v31.937zM127.89 155.854v.078h77.143l.64-7.178 1.456-16.191.763-8.568H127.89v31.86z"
                fill="#FFF" />
            </svg>
            <!-- <p class="text-neutral-200 text-lg font-bold">Html5</p> -->
          </div>
          <div class="flex justify-center items-end grayscale">
            <svg xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:cc="http://creativecommons.org/ns#"
              xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#" xmlns:svg="http://www.w3.org/2000/svg"
              xmlns="http://www.w3.org/2000/svg" xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
              xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape" class="h-20"
              viewBox="0 0 362.73401 511.99998" id="svg3476" version="1.1" inkscape:version="0.91 r13725"
              sodipodi:docname="CSS3.svg">
              <defs id="defs3478" />
              <sodipodi:namedview id="base" pagecolor="#ffffff" bordercolor="#666666" borderopacity="1.0"
                inkscape:pageopacity="0.0" inkscape:pageshadow="2" inkscape:zoom="0.35" inkscape:cx="181.367"
                inkscape:cy="256" inkscape:document-units="px" inkscape:current-layer="layer1" showgrid="false"
                fit-margin-top="0" fit-margin-left="0" fit-margin-right="0" fit-margin-bottom="0"
                inkscape:window-width="1366" inkscape:window-height="704" inkscape:window-x="0" inkscape:window-y="27"
                inkscape:window-maximized="1" />
              <metadata id="metadata3481">
                <rdf:RDF>
                  <cc:Work rdf:about="">
                    <dc:format>image/svg+xml</dc:format>
                    <dc:type rdf:resource="http://purl.org/dc/dcmitype/StillImage" />
                    <dc:title></dc:title>
                  </cc:Work>
                </rdf:RDF>
              </metadata>
              <g inkscape:label="Calque 1" inkscape:groupmode="layer" id="layer1"
                transform="translate(-193.633,-276.3622)">
                <g id="g3013" transform="translate(119,276.3622)">
                  <polygon id="polygon2989"
                    points="437.367,100.62 404.321,470.819 255.778,512 107.644,470.877 74.633,100.62 "
                    style="fill:#264de4" />
                  <polygon id="polygon2991" points="376.03,447.246 404.27,130.894 256,130.894 256,480.523 "
                    style="fill:#2965f1" />
                  <polygon id="polygon2993" points="150.31,268.217 154.38,313.627 256,313.627 256,268.217 "
                    style="fill:#ebebeb" />
                  <polygon id="polygon2995"
                    points="256,176.305 255.843,176.305 142.132,176.305 146.26,221.716 256,221.716 "
                    style="fill:#ebebeb" />
                  <polygon id="polygon2997"
                    points="256,433.399 256,386.153 255.801,386.206 205.227,372.55 201.994,336.333 177.419,336.333 156.409,336.333 162.771,407.634 255.791,433.457 "
                    style="fill:#ebebeb" />
                  <path id="path2999" d="m 160,0 55,0 0,23 -32,0 0,23 32,0 0,23 -55,0 z"
                    inkscape:connector-curvature="0" />
                  <path id="path3001" d="m 226,0 55,0 0,20 -32,0 0,4 32,0 0,46 -55,0 0,-21 32,0 0,-4 -32,0 z"
                    inkscape:connector-curvature="0" />
                  <path id="path3003" d="m 292,0 55,0 0,20 -32,0 0,4 32,0 0,46 -55,0 0,-21 32,0 0,-4 -32,0 z"
                    inkscape:connector-curvature="0" />
                  <polygon id="polygon3005"
                    points="311.761,313.627 306.49,372.521 255.843,386.191 255.843,433.435 348.937,407.634 349.62,399.962 360.291,280.411 361.399,268.217 369.597,176.305 255.843,176.305 255.843,221.716 319.831,221.716 315.699,268.217 255.843,268.217 255.843,313.627 "
                    style="fill:#ffffff" />
                </g>
              </g>
            </svg>
            <!-- <p class="text-neutral-200 text-lg font-bold">Html5</p> -->
          </div>
        </div>
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
  </NavigationLayout>
</template>
