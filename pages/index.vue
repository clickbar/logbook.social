<template>
  <div class="relative overflow-hidden bg-white">
    <div class="relative pt-6 pb-16 md:pb-20 lg:pb-24 xl:pb-32">
      <nav
        class="relative flex items-center justify-between max-w-screen-xl px-4 mx-auto sm:px-6"
      >
        <div class="flex items-center flex-1">
          <div class="flex items-center justify-between w-full md:w-auto">
            <a href="#">
              <svg
                class="h-16 text-gray-800"
                viewBox="0 0 400 200"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M38 124V41H50V124H38Z"
                  fill="currentColor"
                />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M326 41H338V93.837C343.864 91.4634 348 85.7148 348 79H360C360 87.6682 356.061 95.4164 349.876 100.552C357.177 105.679 362 113.999 362 124H350C350 116.375 345.142 110.149 338 107.901V124H326V41Z"
                  fill="currentColor"
                />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M164 101V41H176V80.2108C179.53 78.1687 183.629 77 188 77C201.255 77 212 87.7452 212 101C212 114.255 201.255 125 188 125C174.745 125 164 114.255 164 101ZM176 101C176 107.627 181.373 113 188 113C194.627 113 200 107.627 200 101C200 94.3726 194.627 89 188 89C181.373 89 176 94.3726 176 101Z"
                  fill="currentColor"
                />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M242 89C235.373 89 230 94.3726 230 101C230 107.627 235.373 113 242 113C248.627 113 254 107.627 254 101C254 94.3726 248.627 89 242 89ZM218 101C218 87.7452 228.745 77 242 77C255.255 77 266 87.7452 266 101C266 114.255 255.255 125 242 125C228.745 125 218 114.255 218 101Z"
                  fill="currentColor"
                />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M296 90C289.373 90 284 95.3726 284 102C284 108.627 289.373 114 296 114C302.627 114 308 108.627 308 102C308 95.3726 302.627 90 296 90ZM272 102C272 88.7452 282.745 78 296 78C309.255 78 320 88.7452 320 102C320 115.255 309.255 126 296 126C282.745 126 272 115.255 272 102Z"
                  fill="currentColor"
                />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M80 89C73.3726 89 68 94.3726 68 101C68 107.627 73.3726 113 80 113C86.6274 113 92 107.627 92 101C92 94.3726 86.6274 89 80 89ZM56 101C56 87.7452 66.7452 77 80 77C93.2548 77 104 87.7452 104 101C104 114.255 93.2548 125 80 125C66.7452 125 56 114.255 56 101Z"
                  fill="currentColor"
                />
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M122 101C122 94.3726 127.373 89 134 89C140.627 89 146 94.3726 146 101C146 107.627 140.627 113 134 113C127.373 113 122 107.627 122 101ZM134 77C120.745 77 110 87.7452 110 101C110 112.183 117.649 121.58 128 124.244V131.419L140 127.419V124.244C150.351 121.58 158 112.183 158 101C158 87.7452 147.255 77 134 77ZM140 130.581L128 134.581V137.756C117.649 140.42 110 149.817 110 161C110 174.255 120.745 185 134 185C147.255 185 158 174.255 158 161C158 149.817 150.351 140.42 140 137.756V130.581ZM122 161C122 154.373 127.373 149 134 149C140.627 149 146 154.373 146 161C146 167.627 140.627 173 134 173C127.373 173 122 167.627 122 161Z"
                  fill="currentColor"
                />
              </svg>
            </a>
            <div class="flex items-center -mr-2 md:hidden">
              <button
                type="button"
                class="inline-flex items-center justify-center p-2 text-gray-400 transition duration-150 ease-in-out rounded-md hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:bg-gray-100 focus:text-gray-500"
                @click="open = true"
              >
                <svg
                  class="w-6 h-6"
                  stroke="currentColor"
                  fill="none"
                  viewBox="0 0 24 24"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M4 6h16M4 12h16M4 18h16"
                  />
                </svg>
              </button>
            </div>
          </div>
          <div class="hidden md:block md:ml-10">
            <a
              href="#features"
              class="ml-10 font-medium text-gray-500 transition duration-150 ease-in-out hover:text-gray-900 focus:outline-none focus:text-gray-900"
              >Features</a
            >
            <a
              href="#faq"
              class="ml-10 font-medium text-gray-500 transition duration-150 ease-in-out hover:text-gray-900 focus:outline-none focus:text-gray-900"
              >Fragen und Antworten</a
            >
          </div>
          <div class="hidden md:block md:ml-10">
            <a href="https://wirvsvirushackathon.org/">
              <img src="~assets/img/Logo_Projekt_01.png" width="200" />
            </a>
          </div>
        </div>
      </nav>

      <div
        :class="{ block: open, hidden: !open }"
        class="absolute inset-x-0 top-0 hidden p-2 md:hidden"
      >
        <div
          x-show="open"
          x-transition:enter="duration-150 ease-out"
          x-transition:enter-start="opacity-0 scale-95"
          x-transition:enter-end="opacity-100 scale-100"
          x-transition:leave="duration-100 ease-in"
          x-transition:leave-start="opacity-100 scale-100"
          x-transition:leave-end="opacity-0 scale-95"
          class="transition origin-top-right transform rounded-lg shadow-md"
        >
          <div class="overflow-hidden bg-white rounded-lg shadow-xs">
            <div class="flex items-center justify-between px-5 pt-4">
              <div>
                <img
                  class="w-auto h-8"
                  src="/img/logos/workflow-mark-on-white.svg"
                  alt=""
                />
              </div>
              <div class="-mr-2">
                <button
                  type="button"
                  class="inline-flex items-center justify-center p-2 text-gray-400 transition duration-150 ease-in-out rounded-md hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:bg-gray-100 focus:text-gray-500"
                  @click="open = false"
                >
                  <svg
                    class="w-6 h-6"
                    stroke="currentColor"
                    fill="none"
                    viewBox="0 0 24 24"
                  >
                    <path
                      stroke-linecap="round"
                      stroke-linejoin="round"
                      stroke-width="2"
                      d="M6 18L18 6M6 6l12 12"
                    />
                  </svg>
                </button>
              </div>
            </div>
            <div class="px-2 pt-2 pb-3">
              <a
                href="#features"
                class="block px-3 py-2 mt-1 text-base font-medium text-gray-700 transition duration-150 ease-in-out rounded-md hover:text-gray-900 hover:bg-gray-50 focus:outline-none focus:text-gray-900 focus:bg-gray-50"
                >Features</a
              >
              <a
                href="#faq"
                class="block px-3 py-2 mt-1 text-base font-medium text-gray-700 transition duration-150 ease-in-out rounded-md hover:text-gray-900 hover:bg-gray-50 focus:outline-none focus:text-gray-900 focus:bg-gray-50"
                >Fragen und Antworten</a
              >
            </div>
            <div>
              <a
                href="#"
                class="block w-full px-5 py-3 font-medium text-center text-indigo-600 transition duration-150 ease-in-out bg-gray-50 hover:bg-gray-100 hover:text-indigo-700 focus:outline-none focus:bg-gray-100 focus:text-indigo-700"
              >
                Log ind
              </a>
            </div>
          </div>
        </div>
      </div>

      <div
        class="max-w-screen-xl px-4 mx-auto mt-8 sm:mt-12 sm:px-6 md:mt-20 xl:mt-24"
      >
        <div class="lg:grid lg:grid-cols-12 lg:gap-8">
          <div
            class="sm:text-center md:max-w-2xl md:mx-auto lg:col-span-6 lg:text-left"
          >
            <div
              class="text-sm font-semibold tracking-wide text-gray-500 uppercase sm:text-base lg:text-sm xl:text-base"
            >
              Bald verfügbar
            </div>
            <h2
              class="mt-1 text-4xl font-extrabold leading-10 tracking-tight text-gray-900 sm:leading-none sm:text-6xl lg:text-5xl xl:text-6xl"
            >
              Ein Logbuch für
              <br class="hidden md:inline" />
              <span class="text-indigo-600"> deine sozialen Interaktionen</span>
            </h2>
            <p
              class="mt-3 text-base text-gray-500 sm:mt-5 sm:text-xl lg:text-lg xl:text-xl"
            >
              Mit Hilfe von Logbook kannst du deine sozialen Begegnungen einfach
              eintragen und anschauen. Sollte sich dein Covid-19-Status ändern,
              kannst du einfach ausgewählten Kontakten dies mitteilen. Du bist
              immer in vollster Kontrolle über deinen Daten. Wir speichern
              deinen Status dabei niemals auf einem Server.
            </p>
            <div
              class="mt-5 sm:max-w-lg sm:mx-auto sm:text-center lg:text-left lg:mx-0"
            >
              <p class="text-base font-medium text-gray-900">
                Meld dich an, um mitzubekommen wann es losgeht.
              </p>
              <form
                class="mt-3 sm:flex"
                name="callback"
                method="post"
                data-netlify="true"
                data-netlify-honeypot="address"
                @submit.prevent="handleSubmit"
              >
                <input
                  id="email"
                  aria-label="Email"
                  name="email"
                  type="email"
                  :disabled="submitted"
                  class="block w-full px-3 py-3 text-base leading-6 placeholder-gray-500 transition duration-150 ease-in-out border border-gray-300 rounded-md shadow-sm appearance-none focus:outline-none focus:placeholder-gray-400 focus:shadow-outline focus:border-blue-300 sm:flex-1"
                  placeholder="Trag deine E-mail ein"
                />
                <div class="hidden">
                  <input type="text" name="address" />
                </div>
                <button
                  type="submit"
                  class="w-full px-6 py-3 mt-3 text-base font-medium leading-6 text-white transition duration-150 ease-in-out bg-gray-800 border border-transparent rounded-md shadow-sm hover:bg-gray-700 focus:outline-none focus:shadow-outline active:bg-gray-900 sm:mt-0 sm:ml-3 sm:flex-shrink-0 sm:inline-flex sm:items-center sm:w-auto"
                >
                  {{
                    submitted ? 'E-Mail eingetragen!' : 'Benachrichtige mich'
                  }}
                </button>
              </form>
              <p class="mt-3 text-sm leading-5 text-gray-500">
                Wir nehmen Datenschutz sehr ernst. Lies unsere
                <a href="#" class="font-medium text-gray-900 underline"
                  >Datenschutzerklärung</a
                >.
              </p>
            </div>
          </div>
          <div
            class="relative mt-12 sm:max-w-lg sm:mx-auto lg:mt-0 lg:max-w-none lg:mx-0 lg:col-span-6 lg:flex lg:items-center"
          >
            <svg
              class="absolute top-0 origin-top transform scale-75 -translate-x-1/2 -translate-y-8 left-1/2 sm:scale-100 lg:hidden"
              width="640"
              height="784"
              fill="none"
              viewBox="0 0 640 784"
            >
              <defs>
                <pattern
                  id="4f4f415c-a0e9-44c2-9601-6ded5a34a13e"
                  x="118"
                  y="0"
                  width="20"
                  height="20"
                  patternUnits="userSpaceOnUse"
                >
                  <rect
                    x="0"
                    y="0"
                    width="4"
                    height="4"
                    class="text-gray-200"
                    fill="currentColor"
                  />
                </pattern>
              </defs>
              <rect
                y="72"
                width="640"
                height="640"
                class="text-gray-50"
                fill="currentColor"
              />
              <rect
                x="118"
                width="404"
                height="784"
                fill="url(#4f4f415c-a0e9-44c2-9601-6ded5a34a13e)"
              />
            </svg>
            <div
              class="relative w-full mx-auto rounded-lg shadow-lg lg:max-w-md"
            >
              <iframe
                width="560"
                height="315"
                src="https://www.youtube-nocookie.com/embed/xRn-b24aogM"
                frameborder="0"
                class="rounded-lg shadow-xl"
                allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
                allowfullscreen
              />
            </div>
          </div>
        </div>
      </div>
    </div>

    <div id="features" class="py-16 overflow-hidden bg-gray-50 lg:py-24">
      <div
        class="relative max-w-xl px-4 mx-auto sm:px-6 lg:px-8 lg:max-w-screen-xl"
      >
        <svg
          class="absolute hidden transform -translate-x-1/2 lg:block left-full -translate-y-1/4"
          width="404"
          height="784"
          fill="none"
          viewBox="0 0 404 784"
        >
          <defs>
            <pattern
              id="b1e6e422-73f8-40a6-b5d9-c8586e37e0e7"
              x="0"
              y="0"
              width="20"
              height="20"
              patternUnits="userSpaceOnUse"
            >
              <rect
                x="0"
                y="0"
                width="4"
                height="4"
                class="text-gray-200"
                fill="currentColor"
              />
            </pattern>
          </defs>
          <rect
            width="404"
            height="784"
            fill="url(#b1e6e422-73f8-40a6-b5d9-c8586e37e0e7)"
          />
        </svg>

        <div class="relative">
          <h3
            class="text-3xl font-extrabold leading-8 tracking-tight text-center text-gray-900 sm:text-4xl sm:leading-10"
          >
            Zusammen können wir Infektionsketten brechen
          </h3>
          <p
            class="max-w-3xl mx-auto mt-4 text-xl leading-7 text-center text-gray-500"
          >
            Mit Hilfe von Logbook können wir schnell potentielle
            Infektionsketten nachvollziehen und somit gezielter gegen den
            Coranavirus ankämpfen.
          </p>
        </div>

        <div
          class="relative mt-12 lg:mt-24 lg:grid lg:grid-cols-2 lg:gap-8 lg:items-center"
        >
          <div class="relative">
            <h4
              class="text-2xl font-extrabold leading-8 tracking-tight text-gray-900 sm:text-3xl sm:leading-9"
            >
              Erfasse deine sozialen Begegnungen
            </h4>
            <p class="mt-3 text-lg leading-7 text-gray-500">
              Mit Logbook kannst du im Handumdrehen deine sozialen Begegnungen
              eintragen und auch visualisieren. Hierbei kannst du zwischen drei
              verschiedenen Begegnungskategorien auswählen.
            </p>

            <ul class="mt-10">
              <li>
                <div class="flex">
                  <div class="flex-shrink-0">
                    <div
                      class="flex items-center justify-center w-12 h-12 text-white bg-indigo-500 rounded-md"
                    >
                      <svg
                        class="w-6 h-6"
                        stroke="currentColor"
                        fill="none"
                        viewBox="0 0 24 24"
                      >
                        <path
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="2"
                          d="M17 20H22V18C22 16.3431 20.6569 15 19 15C18.0444 15 17.1931 15.4468 16.6438 16.1429M17 20H7M17 20V18C17 17.3438 16.8736 16.717 16.6438 16.1429M7 20H2V18C2 16.3431 3.34315 15 5 15C5.95561 15 6.80686 15.4468 7.35625 16.1429M7 20V18C7 17.3438 7.12642 16.717 7.35625 16.1429M7.35625 16.1429C8.0935 14.301 9.89482 13 12 13C14.1052 13 15.9065 14.301 16.6438 16.1429M15 7C15 8.65685 13.6569 10 12 10C10.3431 10 9 8.65685 9 7C9 5.34315 10.3431 4 12 4C13.6569 4 15 5.34315 15 7ZM21 10C21 11.1046 20.1046 12 19 12C17.8954 12 17 11.1046 17 10C17 8.89543 17.8954 8 19 8C20.1046 8 21 8.89543 21 10ZM7 10C7 11.1046 6.10457 12 5 12C3.89543 12 3 11.1046 3 10C3 8.89543 3.89543 8 5 8C6.10457 8 7 8.89543 7 10Z"
                        />
                      </svg>
                    </div>
                  </div>
                  <div class="ml-4">
                    <h5 class="text-lg font-medium leading-6 text-gray-900">
                      Auto-Import aus deinem Addressbuch
                    </h5>
                    <p class="mt-2 text-base leading-6 text-gray-500">
                      Alle deine Telefonkontakte sind schon da, du musst nicht
                      mühselig für jeden also es manuell verwalten.
                    </p>
                  </div>
                </div>
              </li>
              <li class="mt-10">
                <div class="flex">
                  <div class="flex-shrink-0">
                    <div
                      class="flex items-center justify-center w-12 h-12 text-white bg-indigo-500 rounded-md"
                    >
                      <svg
                        class="w-6 h-6"
                        stroke="currentColor"
                        fill="none"
                        viewBox="0 0 24 24"
                      >
                        <path
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="2"
                          d="M4 6H20M4 12H20M4 18H20"
                        />
                      </svg>
                    </div>
                  </div>
                  <div class="ml-4">
                    <h5 class="text-lg font-medium leading-6 text-gray-900">
                      Alle deine Begegnungen auf einem Blick
                    </h5>
                    <p class="mt-2 text-base leading-6 text-gray-500">
                      Verliere keine Begegnung, dank der intuitiven
                      Zeitstrahlansicht.
                    </p>
                  </div>
                </div>
              </li>
              <li class="mt-10">
                <div class="flex">
                  <div class="flex-shrink-0">
                    <div
                      class="flex items-center justify-center w-12 h-12 text-white bg-indigo-500 rounded-md"
                    >
                      <svg
                        class="w-6 h-6"
                        stroke="currentColor"
                        fill="none"
                        viewBox="0 0 24 24"
                      >
                        <path
                          stroke-linecap="round"
                          stroke-linejoin="round"
                          stroke-width="2"
                          d="M13 10V3L4 14h7v7l9-11h-7z"
                        />
                      </svg>
                    </div>
                  </div>
                  <div class="ml-4">
                    <h5 class="text-lg font-medium leading-6 text-gray-900">
                      Eingabe im Handumdrehen
                    </h5>
                    <p class="mt-2 text-base leading-6 text-gray-500">
                      Suche deine Kontakte aus deinem Addressbuch oder füge
                      Favoriten hinzu, denen du oft begegnest.
                    </p>
                  </div>
                </div>
              </li>
            </ul>
          </div>

          <div class="relative mt-10 -mx-4 lg:mt-0">
            <svg
              class="absolute transform -translate-x-1/2 translate-y-16 left-1/2 lg:hidden"
              width="784"
              height="404"
              fill="none"
              viewBox="0 0 784 404"
            >
              <defs>
                <pattern
                  id="ca9667ae-9f92-4be7-abcb-9e3d727f2941"
                  x="0"
                  y="0"
                  width="20"
                  height="20"
                  patternUnits="userSpaceOnUse"
                >
                  <rect
                    x="0"
                    y="0"
                    width="4"
                    height="4"
                    class="text-gray-200"
                    fill="currentColor"
                  />
                </pattern>
              </defs>
              <rect
                width="784"
                height="404"
                fill="url(#ca9667ae-9f92-4be7-abcb-9e3d727f2941)"
              />
            </svg>
            <img
              class="relative mx-auto shadow-lg"
              width="400"
              src="~assets/img/begegnungen.png"
              alt=""
            />
          </div>
        </div>

        <svg
          class="absolute hidden transform translate-x-1/2 translate-y-12 lg:block right-full"
          width="404"
          height="784"
          fill="none"
          viewBox="0 0 404 784"
        >
          <defs>
            <pattern
              id="64e643ad-2176-4f86-b3d7-f2c5da3b6a6d"
              x="0"
              y="0"
              width="20"
              height="20"
              patternUnits="userSpaceOnUse"
            >
              <rect
                x="0"
                y="0"
                width="4"
                height="4"
                class="text-gray-200"
                fill="currentColor"
              />
            </pattern>
          </defs>
          <rect
            width="404"
            height="784"
            fill="url(#64e643ad-2176-4f86-b3d7-f2c5da3b6a6d)"
          />
        </svg>

        <div class="relative mt-12 sm:mt-16 lg:mt-24">
          <div
            class="lg:grid lg:grid-flow-row-dense lg:grid-cols-2 lg:gap-8 lg:items-center"
          >
            <div class="lg:col-start-2">
              <h4
                class="text-2xl font-extrabold leading-8 tracking-tight text-gray-900 sm:text-3xl sm:leading-9"
              >
                Teile deine Status
              </h4>
              <p class="mt-3 text-lg leading-7 text-gray-500">
                In der laufenden Coranavirus-Pandemie haben wir festgestellt,
                wie wichtig es ist, schnell Infektionsketten nachverfolgen zu
                können. Deshalb ist es auch ein zentraler Bestandteil von
                Logbook.
              </p>

              <ul class="mt-10">
                <li>
                  <div class="flex">
                    <div class="flex-shrink-0">
                      <div
                        class="flex items-center justify-center w-12 h-12 text-white bg-indigo-500 rounded-md"
                      >
                        <svg
                          class="w-6 h-6"
                          stroke="currentColor"
                          fill="none"
                          viewBox="0 0 24 24"
                        >
                          <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            stroke-width="2"
                            d="M7 8h10M7 12h4m1 8l-4-4H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-3l-4 4z"
                          />
                        </svg>
                      </div>
                    </div>
                    <div class="ml-4">
                      <h5 class="text-lg font-medium leading-6 text-gray-900">
                        Wähle aus, wer benachrichtigt werden soll
                      </h5>
                      <p class="mt-2 text-base leading-6 text-gray-500">
                        Nicht jeder muss umbedingt erfahren, ob sich dein
                        Covid-19-Status geändert hat, deswegen hast du immer
                        vollste Kontrolle wer dein Update bekommt.
                      </p>
                    </div>
                  </div>
                </li>
                <li class="mt-10">
                  <div class="flex">
                    <div class="flex-shrink-0">
                      <div
                        class="flex items-center justify-center w-12 h-12 text-white bg-indigo-500 rounded-md"
                      >
                        <svg
                          class="w-6 h-6"
                          stroke="currentColor"
                          fill="none"
                          viewBox="0 0 24 24"
                        >
                          <path
                            d="M12 15V17M6 21H18C19.1046 21 20 20.1046 20 19V13C20 11.8954 19.1046 11 18 11H6C4.89543 11 4 11.8954 4 13V19C4 20.1046 4.89543 21 6 21ZM16 11V7C16 4.79086 14.2091 3 12 3C9.79086 3 8 4.79086 8 7V11H16Z"
                            stroke-width="2"
                            stroke-linecap="round"
                            stroke-linejoin="round"
                          />
                        </svg>
                      </div>
                    </div>
                    <div class="ml-4">
                      <h5 class="text-lg font-medium leading-6 text-gray-900">
                        Privacy first
                      </h5>
                      <p class="mt-2 text-base leading-6 text-gray-500">
                        Wir speichern deinen Status verschlüsselt auf deinem
                        Gerät und auf keinem Server. Außerdem ist die App
                        Open-Source und kann somit von jedem überprüft werden.
                      </p>
                    </div>
                  </div>
                </li>
              </ul>
            </div>

            <div class="relative mt-10 -mx-4 lg:mt-0 lg:col-start-1">
              <svg
                class="absolute transform -translate-x-1/2 translate-y-16 left-1/2 lg:hidden"
                width="784"
                height="404"
                fill="none"
                viewBox="0 0 784 404"
              >
                <defs>
                  <pattern
                    id="e80155a9-dfde-425a-b5ea-1f6fadd20131"
                    x="0"
                    y="0"
                    width="20"
                    height="20"
                    patternUnits="userSpaceOnUse"
                  >
                    <rect
                      x="0"
                      y="0"
                      width="4"
                      height="4"
                      class="text-gray-200"
                      fill="currentColor"
                    />
                  </pattern>
                </defs>
                <rect
                  width="784"
                  height="404"
                  fill="url(#e80155a9-dfde-425a-b5ea-1f6fadd20131)"
                />
              </svg>
              <img
                class="relative mx-auto shadow-lg"
                width="350"
                src="~assets/img/profil.png"
                alt=""
              />
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="bg-white">
      <div
        class="max-w-screen-xl px-4 py-12 mx-auto text-center sm:px-6 lg:py-16 lg:px-8"
      >
        <h2
          class="text-3xl font-extrabold leading-9 tracking-tight text-gray-900 sm:text-4xl sm:leading-10"
        >
          Wir brauchen deine Unterstützung.
          <br />
          Like unser Youtube-Video.
        </h2>
        <div class="flex justify-center mt-8">
          <div class="inline-flex rounded-md shadow">
            <a
              href="#email"
              class="inline-flex items-center justify-center px-5 py-3 text-base font-medium leading-6 text-white transition duration-150 ease-in-out bg-indigo-600 border border-transparent rounded-md hover:bg-indigo-500 focus:outline-none focus:shadow-outline"
            >
              E-Mail-Adresse eintragen
            </a>
          </div>
          <div class="inline-flex ml-3">
            <a
              href="https://www.youtube.com/watch?v=xRn-b24aogM"
              target="_blank"
              class="inline-flex items-center justify-center px-5 py-3 text-base font-medium leading-6 text-indigo-700 transition duration-150 ease-in-out bg-indigo-100 border border-transparent rounded-md hover:text-indigo-600 hover:bg-indigo-50 focus:outline-none focus:shadow-outline focus:border-indigo-300"
            >
              Youtube-Video liken
            </a>
          </div>
        </div>
      </div>
    </div>

    <div id="faq" class="bg-white">
      <div
        class="max-w-screen-xl px-4 pt-12 pb-16 mx-auto sm:pt-16 sm:pb-20 sm:px-6 lg:pt-20 lg:pb-28 lg:px-8"
      >
        <h2 class="text-3xl font-extrabold leading-9 text-gray-900">
          Fragen und Antworten
        </h2>
        <div class="pt-10 mt-6 border-t-2 border-gray-100">
          <dl class="md:grid md:grid-cols-2 md:gap-8">
            <div>
              <div>
                <dt class="text-lg font-medium leading-6 text-gray-900">
                  Was speichert ihr auf dem Server?
                </dt>
                <dd class="mt-2">
                  <p class="text-base leading-6 text-gray-500">
                    Wir speichern nur eure Telefonnummer und eine User-ID auf
                    dem Server, damit andere Leute, die deine Telefonnummer und
                    Logbook haben, dir ein Status-Update schicken können. Euer
                    Covid-19-Status wird niemals auf einem Server gespeichert.
                  </p>
                </dd>
              </div>
              <div class="mt-12">
                <dt class="text-lg font-medium leading-6 text-gray-900">
                  Können Kontakte meine Covid-19-Status sehen?
                </dt>
                <dd class="mt-2">
                  <p class="text-base leading-6 text-gray-500">
                    Nein. Nur Kontakte, mit denen du explizit deinen Status
                    teilst, können das. Dies kannst du zu jeder Zeit auch in
                    Logbook sehen.
                  </p>
                </dd>
              </div>
            </div>
            <div class="mt-12 md:mt-0">
              <div>
                <dt class="text-lg font-medium leading-6 text-gray-900">
                  Kriegt das Gesundheitsamt meinen Status mitgeteilt?
                </dt>
                <dd class="mt-2">
                  <p class="text-base leading-6 text-gray-500">
                    Nein, darum musst du dich selber kümmern.
                  </p>
                </dd>
              </div>
              <div class="mt-12">
                <dt class="text-lg font-medium leading-6 text-gray-900">
                  Kann ich mir den Code anschauen?
                </dt>
                <dd class="mt-2">
                  <p class="text-base leading-6 text-gray-500">
                    Klar, den Code findest du auf Github.
                  </p>
                </dd>
              </div>
            </div>
          </dl>
        </div>
      </div>
    </div>

    <div class="pt-12 bg-gray-50 sm:pt-16">
      <div class="max-w-screen-xl px-4 mx-auto sm:px-6 lg:px-8">
        <div class="max-w-4xl mx-auto text-center">
          <h2
            class="text-3xl font-extrabold leading-9 text-gray-900 sm:text-4xl sm:leading-10"
          >
            Entstanden im Rahmen des Hackathons #WirVsVirus der Bundesregierung.
          </h2>
          <p class="mt-3 text-xl leading-7 text-gray-500 sm:mt-4">
            Adrian Hawlitschek, Idris Nematpur und Alexander von Studnitz.
          </p>
        </div>
      </div>
      <div class="pb-12 mt-10 bg-white sm:pb-16">
        <div class="relative">
          <div class="absolute inset-0 h-1/2 bg-gray-50" />
          <div class="relative max-w-screen-xl px-4 mx-auto sm:px-6 lg:px-8">
            <div class="max-w-4xl mx-auto">
              <div class="bg-white rounded-lg shadow-lg sm:grid sm:grid-cols-3">
                <div
                  class="p-6 text-center border-b border-gray-100 sm:border-0 sm:border-r"
                >
                  <p
                    class="text-5xl font-extrabold leading-none text-indigo-600"
                  >
                    48
                  </p>
                  <p class="mt-2 text-lg font-medium leading-6 text-gray-500">
                    Stunden
                  </p>
                </div>
                <div
                  class="p-6 text-center border-t border-b border-gray-100 sm:border-0 sm:border-l sm:border-r"
                >
                  <p
                    class="text-5xl font-extrabold leading-none text-indigo-600"
                  >
                    3
                  </p>
                  <p class="mt-2 text-lg font-medium leading-6 text-gray-500">
                    Hacker
                  </p>
                </div>
                <div
                  class="p-6 text-center border-t border-gray-100 sm:border-0 sm:border-l"
                >
                  <p
                    class="text-5xl font-extrabold leading-none text-indigo-600"
                  >
                    100%
                  </p>
                  <p class="mt-2 text-lg font-medium leading-6 text-gray-500">
                    Zuhause
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="bg-white">
      <div
        class="max-w-screen-xl px-4 py-12 mx-auto sm:px-6 md:flex md:items-center md:justify-between lg:px-8"
      >
        <div class="flex justify-center md:order-2">
          <a
            href="https://twitter.com/IdrisNobel"
            class="ml-6 text-gray-400 hover:text-gray-500"
          >
            <span class="sr-only">Twitter</span>
            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
              <path
                d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"
              />
            </svg>
          </a>
          <a
            href="https://github.com/clickbar/social-contact-tracker-app"
            class="ml-6 text-gray-400 hover:text-gray-500"
          >
            <span class="sr-only">GitHub</span>
            <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
              <path
                fill-rule="evenodd"
                d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"
                clip-rule="evenodd"
              />
            </svg>
          </a>
        </div>
        <div class="mt-8 md:mt-0 md:order-1">
          <p class="text-base leading-6 text-center text-gray-400">
            &copy; 2020 logbook.social. All rights reserved.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data: () => ({ submitted: false }),
  methods: {
    async handleSubmit(event) {
      // TODO: do we have any polyfills for fetch / await / async (cause IE11) or use XHR instead?
      // let the browser handle all the form stuff (there have been some issues with form validation and v-model)
      // although it is not clearly documented, netlify handles multipart form data just fine!
      const formData = new FormData(event.target)
      try {
        await fetch('/', {
          method: 'POST',
          body: formData,
        })
        this.submitted = true
      } catch (e) {
        // TODO: handle Error
      }
    },
  },
}
</script>
