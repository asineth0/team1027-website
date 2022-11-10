<template>
  <div class="bg-gray-900 z-10 sticky top-0">
    <div
      class="h-16 mx-auto px-6 flex items-center justify-between max-w-6xl shadow-md"
    >
      <div class="flex items-center space-x-4">
        <img src="../assets/icon.jpg" class="w-10 h-10 rounded-full" />
        <div class="-space-y-1">
          <p class="font-bold">Team 1027</p>
          <p class="text-gray-400 hidden lg:block">Mechatronic Maniacs</p>
        </div>
      </div>
      <div class="relative">
        <Bars3Icon
          class="h-6 w-6 text-gray-500 transition hover:text-white"
          @click="menu = !menu"
        />
        <div
          v-if="menu"
          class="fixed left-0 top-16 w-screen p-3 lg:absolute lg:right-0 lg:left-auto lg:top-14 lg:w-64 lg:p-0"
        >
          <div
            class="rounded-md border border-gray-600 border-opacity-25 bg-dark-800 bg-opacity-50 p-2 shadow-lg backdrop-blur-2xl"
          >
            <a
              class="flex items-center justify-between rounded-md py-2 px-3 text-gray-200 transition hover:bg-white hover:bg-opacity-5 hover:text-blue-500"
              href="/"
            >
              <p>Home</p>
            </a>
            <a
              class="flex items-center justify-between rounded-md py-2 px-3 text-gray-200 transition hover:bg-white hover:bg-opacity-5 hover:text-blue-500"
              href="https://www.thebluealliance.com/team/1027"
            >
              <p>Events</p>
            </a>
            <a
              class="flex items-center justify-between rounded-md py-2 px-3 text-gray-200 transition hover:bg-white hover:bg-opacity-5 hover:text-blue-500"
              href="https://calendar.google.com/calendar/u/0/r?cid=frc1027@gmail.com"
            >
              <p>Calendar</p>
            </a>
            <a
              class="flex items-center justify-between rounded-md py-2 px-3 text-gray-200 transition hover:bg-white hover:bg-opacity-5 hover:text-blue-500"
              href="mailto:frc1027@gmail.com"
            >
              <p>Sponsor</p>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref } from "vue";
import { Bars3Icon } from "@heroicons/vue/24/solid";

const menu = ref(false);
</script>
