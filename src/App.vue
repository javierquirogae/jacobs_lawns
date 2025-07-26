<template>
  <div class=" text-white w-full" style="background-image: url('/src/assets/grass.jpg')">


    <!-- Page content -->
    <div class="relative z-10 flex flex-col items-center px-4 py-16 lg:px-20">
      <!-- Header -->
      <header class="text-center mb-26">
        <h1 class="text-6xl font-extrabold mb-4 drop-shadow-2xl">Jacob's Lawns</h1>
        <p class="text-2xl font-semibold drop-shadow-xl">Reliable. Affordable. Professional Lawn Care.</p>
      </header>

      <!-- Content cards -->
      <main class="w-full max-w-4xl space-y-12">
        <!-- Services -->
        <section class="bg-white bg-opacity-90 rounded-3xl p-8 shadow-2xl text-gray-900 text-xl leading-relaxed">
          <h2 class="text-3xl font-bold mb-4 border-b border-green-400 pb-3">Our Services</h2>
          <ul class="list-disc pl-6 space-y-2">
            <li>Lawn Mowing</li>
            <li>Seasonal Cleanup</li>
          </ul>
        </section>

        <!-- About -->
        <section class="bg-white bg-opacity-90 rounded-3xl p-8 shadow-2xl text-gray-900 text-xl leading-relaxed">
          <h2 class="text-3xl font-bold mb-4 border-b border-green-400 pb-3">About Us</h2>
          <p>
            Jacob's Lawns is a locally owned and operated business dedicated to keeping your lawn maintained.
            With a commitment to quality service, we bring care and professionalism to every yard.
          </p>
        </section>

        <!-- Contact -->
        <section class="bg-white bg-opacity-90 rounded-3xl p-8 shadow-2xl text-gray-900 text-xl leading-relaxed">
          <h2 class="text-3xl font-bold mb-4 border-b border-green-400 pb-3">Contact Us</h2>
          <p>
            Email: <a href="mailto:jacobquiroga01@gmail.com"
              class="text-green-700 underline font-medium">jacobquiroga01@gmail.com</a>
          </p>
          <p>
            Phone: <a href="tel:4706518124" class="text-green-700 underline font-medium">(470) 651-8124</a>
          </p>
        </section>
      </main>

      <!-- Footer -->
      <footer class=" text-lg text-white text-center opacity-80">
        &copy; 2025 Jacob's Lawns. All rights reserved.
      </footer>
    </div>
  </div>
</template>

<script>
import grassImage from './assets/grass.jpg';
import './output.css'
export default {
  name: 'App',
  data() {
    return {
      grassImage,
    };
  },
};
</script>

<style>
html,
body {
  height: 100%;
  margin: 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
</style>
