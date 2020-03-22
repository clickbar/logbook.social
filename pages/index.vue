<template>
  <div class="relative bg-white overflow-hidden">
    <div class="hidden lg:block lg:absolute lg:inset-0">
      <svg
        class="absolute top-0 left-1/2 transform translate-x-64 -translate-y-8"
        width="640"
        height="784"
        fill="none"
        viewBox="0 0 640 784"
      >
        <defs>
          <pattern
            id="9ebea6f4-a1f5-4d96-8c4e-4c2abf658047"
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
          fill="url(#9ebea6f4-a1f5-4d96-8c4e-4c2abf658047)"
        />
      </svg>
    </div>

    <div
      x-data="{ open: false }"
      class="relative pt-6 pb-16 md:pb-20 lg:pb-24 xl:pb-32 mt-24"
    >
      <nav
        class="relative max-w-screen-xl mx-auto flex items-center justify-between px-4 sm:px-6"
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
            <div class="-mr-2 flex items-center md:hidden">
              <button
                type="button"
                class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:bg-gray-100 focus:text-gray-500 transition duration-150 ease-in-out"
                @click="open = true"
              >
                <svg
                  class="h-6 w-6"
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
              href="#"
              class="font-medium text-gray-500 hover:text-gray-900 focus:outline-none focus:text-gray-900 transition duration-150 ease-in-out"
              >Product</a
            >
            <a
              href="#"
              class="ml-10 font-medium text-gray-500 hover:text-gray-900 focus:outline-none focus:text-gray-900 transition duration-150 ease-in-out"
              >Features</a
            >
            <a
              href="#"
              class="ml-10 font-medium text-gray-500 hover:text-gray-900 focus:outline-none focus:text-gray-900 transition duration-150 ease-in-out"
              >Marketplace</a
            >
            <a
              href="#"
              class="ml-10 font-medium text-gray-500 hover:text-gray-900 focus:outline-none focus:text-gray-900 transition duration-150 ease-in-out"
              >Company</a
            >
          </div>
        </div>
        <div class="hidden md:block text-right">
          <span class="inline-flex rounded-md shadow-md">
            <span class="inline-flex rounded-md shadow-xs">
              <a
                href="#"
                class="inline-flex items-center px-4 py-2 border border-transparent text-base leading-6 font-medium rounded-md text-indigo-600 bg-white hover:bg-gray-50 focus:outline-none focus:shadow-outline transition duration-150 ease-in-out"
              >
                Log in
              </a>
            </span>
          </span>
        </div>
      </nav>

      <div
        :class="{ block: open, hidden: !open }"
        class="absolute top-0 inset-x-0 p-2 hidden md:hidden"
      >
        <div
          x-show="open"
          x-transition:enter="duration-150 ease-out"
          x-transition:enter-start="opacity-0 scale-95"
          x-transition:enter-end="opacity-100 scale-100"
          x-transition:leave="duration-100 ease-in"
          x-transition:leave-start="opacity-100 scale-100"
          x-transition:leave-end="opacity-0 scale-95"
          class="rounded-lg shadow-md transition transform origin-top-right"
        >
          <div class="rounded-lg bg-white shadow-xs overflow-hidden">
            <div class="px-5 pt-4 flex items-center justify-between">
              <div>
                <img
                  class="h-8 w-auto"
                  src="/img/logos/workflow-mark-on-white.svg"
                  alt=""
                />
              </div>
              <div class="-mr-2">
                <button
                  type="button"
                  class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:bg-gray-100 focus:text-gray-500 transition duration-150 ease-in-out"
                  @click="open = false"
                >
                  <svg
                    class="h-6 w-6"
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
                href="#"
                class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-gray-900 hover:bg-gray-50 focus:outline-none focus:text-gray-900 focus:bg-gray-50 transition duration-150 ease-in-out"
                >Product</a
              >
              <a
                href="#"
                class="mt-1 block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-gray-900 hover:bg-gray-50 focus:outline-none focus:text-gray-900 focus:bg-gray-50 transition duration-150 ease-in-out"
                >Features</a
              >
              <a
                href="#"
                class="mt-1 block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-gray-900 hover:bg-gray-50 focus:outline-none focus:text-gray-900 focus:bg-gray-50 transition duration-150 ease-in-out"
                >Marketplace</a
              >
              <a
                href="#"
                class="mt-1 block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:text-gray-900 hover:bg-gray-50 focus:outline-none focus:text-gray-900 focus:bg-gray-50 transition duration-150 ease-in-out"
                >Company</a
              >
            </div>
            <div>
              <a
                href="#"
                class="block w-full px-5 py-3 text-center font-medium text-indigo-600 bg-gray-50 hover:bg-gray-100 hover:text-indigo-700 focus:outline-none focus:bg-gray-100 focus:text-indigo-700 transition duration-150 ease-in-out"
              >
                Log ind
              </a>
            </div>
          </div>
        </div>
      </div>

      <div
        class="mt-8 mx-auto max-w-screen-xl px-4 sm:mt-12 sm:px-6 md:mt-20 xl:mt-24"
      >
        <div class="lg:grid lg:grid-cols-12 lg:gap-8">
          <div
            class="sm:text-center md:max-w-2xl md:mx-auto lg:col-span-6 lg:text-left"
          >
            <div
              class="text-sm font-semibold uppercase tracking-wide text-gray-500 sm:text-base lg:text-sm xl:text-base"
            >
              Bald verfügbar
            </div>
            <h2
              class="mt-1 text-4xl tracking-tight leading-10 font-extrabold text-gray-900 sm:leading-none sm:text-6xl lg:text-5xl xl:text-6xl"
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
              <form action="#" method="POST" class="mt-3 sm:flex">
                <input
                  aria-label="Email"
                  class="appearance-none block w-full px-3 py-3 border border-gray-300 text-base leading-6 rounded-md placeholder-gray-500 shadow-sm focus:outline-none focus:placeholder-gray-400 focus:shadow-outline focus:border-blue-300 transition duration-150 ease-in-out sm:flex-1"
                  placeholder="Trag deine E-mail ein"
                />
                <button
                  type="submit"
                  class="mt-3 w-full px-6 py-3 border border-transparent text-base leading-6 font-medium rounded-md text-white bg-gray-800 shadow-sm hover:bg-gray-700 focus:outline-none focus:shadow-outline active:bg-gray-900 transition duration-150 ease-in-out sm:mt-0 sm:ml-3 sm:flex-shrink-0 sm:inline-flex sm:items-center sm:w-auto"
                >
                  Benachrichtige mich
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
            class="mt-12 relative sm:max-w-lg sm:mx-auto lg:mt-0 lg:max-w-none lg:mx-0 lg:col-span-6 lg:flex lg:items-center"
          >
            <svg
              class="absolute top-0 left-1/2 transform -translate-x-1/2 -translate-y-8 scale-75 origin-top sm:scale-100 lg:hidden"
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
              class="relative mx-auto w-full rounded-lg shadow-lg lg:max-w-md"
            >
              <button
                class="relative block w-full rounded-lg overflow-hidden focus:outline-none focus:shadow-outline"
              >
                <img
                  class="w-full"
                  src="https://images.unsplash.com/photo-1556740758-90de374c12ad?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80"
                  alt="Woman making a sale"
                />
                <div
                  class="absolute inset-0 w-full h-full flex items-center justify-center"
                >
                  <svg
                    class="h-20 w-20 text-indigo-500"
                    fill="currentColor"
                    viewBox="0 0 84 84"
                  >
                    <circle opacity="0.9" cx="42" cy="42" r="42" fill="white" />
                    <path
                      d="M55.5039 40.3359L37.1094 28.0729C35.7803 27.1869 34 28.1396 34 29.737V54.263C34 55.8604 35.7803 56.8131 37.1094 55.9271L55.5038 43.6641C56.6913 42.8725 56.6913 41.1275 55.5039 40.3359Z"
                    />
                  </svg>
                </div>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="py-16 bg-gray-50 overflow-hidden lg:py-24">
      <div
        class="relative max-w-xl mx-auto px-4 sm:px-6 lg:px-8 lg:max-w-screen-xl"
      >
        <svg
          class="hidden lg:block absolute left-full transform -translate-x-1/2 -translate-y-1/4"
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
            class="text-center text-3xl leading-8 font-extrabold tracking-tight text-gray-900 sm:text-4xl sm:leading-10"
          >
            Zusammen können wir Infektionsketten brechen
          </h3>
          <p
            class="mt-4 max-w-3xl mx-auto text-center text-xl leading-7 text-gray-500"
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
              class="text-2xl leading-8 font-extrabold text-gray-900 tracking-tight sm:text-3xl sm:leading-9"
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
                      class="flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
                    >
                      <svg
                        class="h-6 w-6"
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
                    <h5 class="text-lg leading-6 font-medium text-gray-900">
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
                      class="flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
                    >
                      <svg
                        class="h-6 w-6"
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
                    <h5 class="text-lg leading-6 font-medium text-gray-900">
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
                      class="flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
                    >
                      <svg
                        class="h-6 w-6"
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
                    <h5 class="text-lg leading-6 font-medium text-gray-900">
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

          <div class="mt-10 -mx-4 relative lg:mt-0">
            <svg
              class="absolute left-1/2 transform -translate-x-1/2 translate-y-16 lg:hidden"
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
          class="hidden lg:block absolute right-full transform translate-x-1/2 translate-y-12"
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
                class="text-2xl leading-8 font-extrabold text-gray-900 tracking-tight sm:text-3xl sm:leading-9"
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
                        class="flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
                      >
                        <svg
                          class="h-6 w-6"
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
                      <h5 class="text-lg leading-6 font-medium text-gray-900">
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
                        class="flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
                      >
                        <svg
                          class="h-6 w-6"
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
                      <h5 class="text-lg leading-6 font-medium text-gray-900">
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

            <div class="mt-10 -mx-4 relative lg:mt-0 lg:col-start-1">
              <svg
                class="absolute left-1/2 transform -translate-x-1/2 translate-y-16 lg:hidden"
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
        class="max-w-screen-xl mx-auto pt-12 pb-16 sm:pt-16 sm:pb-20 px-4 sm:px-6 lg:pt-20 lg:pb-28 lg:px-8"
      >
        <h2 class="text-3xl leading-9 font-extrabold text-gray-900">
          Fragen und Antworten
        </h2>
        <div class="mt-6 border-t-2 border-gray-100 pt-10">
          <dl class="md:grid md:grid-cols-2 md:gap-8">
            <div>
              <div>
                <dt class="text-lg leading-6 font-medium text-gray-900">
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
                <dt class="text-lg leading-6 font-medium text-gray-900">
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
                <dt class="text-lg leading-6 font-medium text-gray-900">
                  Kriegt das Gesundheitsamt meinen Status mitgeteilt?
                </dt>
                <dd class="mt-2">
                  <p class="text-base leading-6 text-gray-500">
                    Nein, darum musst du dich selber kümmern.
                  </p>
                </dd>
              </div>
              <div class="mt-12">
                <dt class="text-lg leading-6 font-medium text-gray-900">
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

    <div class="bg-gray-50 pt-12 sm:pt-16">
      <div class="max-w-screen-xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="max-w-4xl mx-auto text-center">
          <h2
            class="text-3xl leading-9 font-extrabold text-gray-900 sm:text-4xl sm:leading-10"
          >
            Entstanden im Rahmen des Hackathons #WirVsVirus der Bundesregierung.
          </h2>
          <p class="mt-3 text-xl leading-7 text-gray-500 sm:mt-4">
            Adrian Hawlitschek, Idris Nematpur und Alexander von Studnitz.
          </p>
        </div>
      </div>
      <div class="mt-10 pb-12 bg-white sm:pb-16">
        <div class="relative">
          <div class="absolute inset-0 h-1/2 bg-gray-50" />
          <div class="relative max-w-screen-xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="max-w-4xl mx-auto">
              <div class="rounded-lg bg-white shadow-lg sm:grid sm:grid-cols-3">
                <div
                  class="border-b border-gray-100 p-6 text-center sm:border-0 sm:border-r"
                >
                  <p
                    class="text-5xl leading-none font-extrabold text-indigo-600"
                  >
                    72
                  </p>
                  <p class="mt-2 text-lg leading-6 font-medium text-gray-500">
                    Stunden
                  </p>
                </div>
                <div
                  class="border-t border-b border-gray-100 p-6 text-center sm:border-0 sm:border-l sm:border-r"
                >
                  <p
                    class="text-5xl leading-none font-extrabold text-indigo-600"
                  >
                    3
                  </p>
                  <p class="mt-2 text-lg leading-6 font-medium text-gray-500">
                    Hacker
                  </p>
                </div>
                <div
                  class="border-t border-gray-100 p-6 text-center sm:border-0 sm:border-l"
                >
                  <p
                    class="text-5xl leading-none font-extrabold text-indigo-600"
                  >
                    100%
                  </p>
                  <p class="mt-2 text-lg leading-6 font-medium text-gray-500">
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
        class="max-w-screen-xl mx-auto py-12 px-4 sm:px-6 md:flex md:items-center md:justify-between lg:px-8"
      >
        <div class="flex justify-center md:order-2">
          <a href="#" class="text-gray-400 hover:text-gray-500">
            <span class="sr-only">Facebook</span>
            <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
              <path
                fill-rule="evenodd"
                d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"
                clip-rule="evenodd"
              />
            </svg>
          </a>
          <a href="#" class="ml-6 text-gray-400 hover:text-gray-500">
            <span class="sr-only">Instagram</span>
            <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
              <path
                fill-rule="evenodd"
                d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z"
                clip-rule="evenodd"
              />
            </svg>
          </a>
          <a href="#" class="ml-6 text-gray-400 hover:text-gray-500">
            <span class="sr-only">Twitter</span>
            <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
              <path
                d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"
              />
            </svg>
          </a>
          <a href="#" class="ml-6 text-gray-400 hover:text-gray-500">
            <span class="sr-only">GitHub</span>
            <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
              <path
                fill-rule="evenodd"
                d="M12 2C6.477 2 2 6.484 2 12.017c0 4.425 2.865 8.18 6.839 9.504.5.092.682-.217.682-.483 0-.237-.008-.868-.013-1.703-2.782.605-3.369-1.343-3.369-1.343-.454-1.158-1.11-1.466-1.11-1.466-.908-.62.069-.608.069-.608 1.003.07 1.531 1.032 1.531 1.032.892 1.53 2.341 1.088 2.91.832.092-.647.35-1.088.636-1.338-2.22-.253-4.555-1.113-4.555-4.951 0-1.093.39-1.988 1.029-2.688-.103-.253-.446-1.272.098-2.65 0 0 .84-.27 2.75 1.026A9.564 9.564 0 0112 6.844c.85.004 1.705.115 2.504.337 1.909-1.296 2.747-1.027 2.747-1.027.546 1.379.202 2.398.1 2.651.64.7 1.028 1.595 1.028 2.688 0 3.848-2.339 4.695-4.566 4.943.359.309.678.92.678 1.855 0 1.338-.012 2.419-.012 2.747 0 .268.18.58.688.482A10.019 10.019 0 0022 12.017C22 6.484 17.522 2 12 2z"
                clip-rule="evenodd"
              />
            </svg>
          </a>
          <a href="#" class="ml-6 text-gray-400 hover:text-gray-500">
            <span class="sr-only">Dribbble</span>
            <svg class="h-6 w-6" fill="currentColor" viewBox="0 0 24 24">
              <path
                fill-rule="evenodd"
                d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10c5.51 0 10-4.48 10-10S17.51 2 12 2zm6.605 4.61a8.502 8.502 0 011.93 5.314c-.281-.054-3.101-.629-5.943-.271-.065-.141-.12-.293-.184-.445a25.416 25.416 0 00-.564-1.236c3.145-1.28 4.577-3.124 4.761-3.362zM12 3.475c2.17 0 4.154.813 5.662 2.148-.152.216-1.443 1.941-4.48 3.08-1.399-2.57-2.95-4.675-3.189-5A8.687 8.687 0 0112 3.475zm-3.633.803a53.896 53.896 0 013.167 4.935c-3.992 1.063-7.517 1.04-7.896 1.04a8.581 8.581 0 014.729-5.975zM3.453 12.01v-.26c.37.01 4.512.065 8.775-1.215.25.477.477.965.694 1.453-.109.033-.228.065-.336.098-4.404 1.42-6.747 5.303-6.942 5.629a8.522 8.522 0 01-2.19-5.705zM12 20.547a8.482 8.482 0 01-5.239-1.8c.152-.315 1.888-3.656 6.703-5.337.022-.01.033-.01.054-.022a35.318 35.318 0 011.823 6.475 8.4 8.4 0 01-3.341.684zm4.761-1.465c-.086-.52-.542-3.015-1.659-6.084 2.679-.423 5.022.271 5.314.369a8.468 8.468 0 01-3.655 5.715z"
                clip-rule="evenodd"
              />
            </svg>
          </a>
        </div>
        <div class="mt-8 md:mt-0 md:order-1">
          <p class="text-center text-base leading-6 text-gray-400">
            &copy; 2020 logbook.social. All rights reserved.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
