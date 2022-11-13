<script setup>
import { ref } from 'vue';
const showMenu = ref(false);
const route = useRoute();
</script>

<template>
  <header class="bg-teal-100">
    <div class="mx-auto max-w-screen-xl px-4 sm:px-6 lg:px-8">
      <div class="flex h-16 items-center justify-between">
        <div class="md:flex md:items-center md:gap-12">
          <a class="block font-bold text-teal-600" href="/">
            <span class="sr-only">Home</span>
            MPP d.o.o.
          </a>
        </div>

        <div class="hidden md:block">
          <nav aria-label="Site Nav">
            <ul class="block md:flex items-center gap-6 text-sm">
              <TheNavbarItem href="/">Domov</TheNavbarItem>
              <TheNavbarItem href="luscilec">Luščilec</TheNavbarItem>
              <TheNavbarItem href="kontakt">Kontakt</TheNavbarItem>
            </ul>
          </nav>
        </div>

        <div class="flex items-center gap-4">
          <div class="flex gap-2">
            <a
              class="
                rounded-md
                bg-teal-200
                px-5
                py-2.5
                text-sm
                font-medium
                text-teal-600
              "
              href="#"
            >
              🇸🇮 Slo
            </a>

            <div class="flex">
              <a
                class="
                  rounded-md
                  bg-teal-200
                  px-5
                  py-2.5
                  text-sm
                  font-medium
                  text-teal-600
                "
                href="#"
              >
                🇬🇧 Eng
              </a>
            </div>
          </div>

          <div class="block md:hidden">
            <button
              @click="showMenu = !showMenu"
              class="
                rounded
                bg-gray-100
                p-2
                text-gray-600
                transition
                hover:text-gray-600/75
              "
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                class="h-5 w-5"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
                stroke-width="2"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M4 6h16M4 12h16M4 18h16"
                />
              </svg>
            </button>
          </div>
        </div>
      </div>
      <div
        :class="{ block: showMenu, hidden: !showMenu }"
        class="block md:hidden"
      >
        <nav aria-label="Site Nav">
          <ul class="block items-center gap-6 text-sm">
            <TheNavbarItem href="/">Domov</TheNavbarItem>
            <TheNavbarItem href="luscilec">Luščilec</TheNavbarItem>
            <TheNavbarItem href="kontakt">Kontakt</TheNavbarItem>
          </ul>
        </nav>
      </div>
    </div>
  </header>
</template>
