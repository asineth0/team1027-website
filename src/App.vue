<template>
  <div>
    <!-- header -->
    <HeaderBar />
    <!-- cover -->
    <div
      class="w-full h-72 lg:h-96 from-blue-600 to-blue-800 bg-gradient-to-br flex items-center justify-center flex-col space-y-2 lg:space-y-4"
    >
      <p class="font-bold text-4xl lg:text-6xl text-center">Team 1027</p>
      <p class="text-xl lg:text-2xl text-blue-200">Mechatronic Maniacs</p>
    </div>
    <!-- main -->
    <div class="space-y-8 py-16">
      <div
        class="space-y-6 px-8 lg:mx-auto lg:flex lg:max-w-6xl lg:items-center lg:justify-between lg:space-y-0 lg:space-x-4"
      >
        <div class="divide-y divide-dark-800 lg:max-w-lg">
          <p class="pb-4 text-2xl font-bold">About Our Team</p>
          <p class="pt-4 text-gray-300">
            We're Team 1027, the Mechatronic Maniacs. We are a FIRST Robotics
            team, representing West Springfield High School. Our teams consists
            of students that with an interest in engineering, technology, and
            business.
          </p>
        </div>
        <div
          class="aspect-[16/10] overflow-hidden rounded-md bg-gray-900 lg:flex lg:w-full lg:max-w-lg lg:items-center"
        >
          <img
            src="./assets/team.jpg"
            class="h-full w-full object-cover object-center"
          />
        </div>
      </div>
      <div
        class="space-y-6 px-8 lg:mx-auto lg:flex lg:max-w-6xl lg:items-center lg:justify-between lg:space-y-0 lg:space-x-4 lg:flex-row-reverse"
      >
        <div class="divide-y divide-dark-800 lg:max-w-lg">
          <p class="pb-4 text-2xl font-bold">About FIRST Robotics</p>
          <p class="pt-4 text-gray-300">
            The FIRST Robotics Competition is an annual robotics competition,
            with schools competing nationally and globally. Each year in the
            beginning of January, FIRST announces a new game that teams will
            design & build their robots around.
          </p>
        </div>
        <div
          class="aspect-[16/10] overflow-hidden rounded-md bg-gray-900 lg:flex lg:w-full lg:max-w-lg lg:items-center"
        >
          <img
            src="./assets/robot.jpg"
            class="h-full w-full object-cover object-center"
          />
        </div>
      </div>
    </div>
    <!-- footer -->
    <FooterBar />
  </div>
</template>

<script setup>
import HeaderBar from "./components/HeaderBar.vue";
import FooterBar from "./components/FooterBar.vue";
</script>
