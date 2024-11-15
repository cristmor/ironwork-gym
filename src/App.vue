<script setup>
</script>

<template>
  <div id="website" class="bg-black w-full h-100vh text-white font-mono">

    <div id="hero" class="relative min-h-[1000px] flex-col justify-center items-center overflow-hidden">

      <div class="absolute inset-0 bg-[url('./assets/hero.jpg')] bg-cover bg-center filter blur-sm" />
      <div class="absolute inset-0 bg-gradient-to-b from-black/60 via-transparent to-black/60" />
      <div class="absolute inset-0 bg-black/20" />

      <div id="nav" class="relative font-bold text-xl flex justify-center items-center h-[124px]">
        <div class="flex w-full">
          <img alt="logo" class="m-auto ml-8" />
          <button
            class="m-auto mr-6 px-4 py-3 rounded-2xl ease-in-out duration-200 hover:bg-blue-800/50 hover:text-orange-500 active:bg-blue-700">About
            Us</button>
          <button
            class="mx-6 px-4 py-3 rounded-2xl ease-in-out duration-200 hover:bg-blue-800/50 hover:text-orange-500 active:bg-blue-700">Contact
            Us</button>
          <button
            class="text-orange-500 m-auto mx-8 mr-16 px-4 py-3 bg-blue-800/80 rounded-2xl ease-in-out duration-200 hover:bg-blue-700 active:bg-blue-600">Get
            Your
            Free
            Trial</button>
        </div>
      </div>

      <div id="hero-content" class="relative flex-col justify-center items-center max-w-[1400px] px-24 m-auto mt-64">
        <div class="text-[4rem] text-orange-200 font-bold leading-tight max-w-[850px]">
          <p>Transform Your Fitness, Transform Your Life</p>
        </div>
        <div class="flex justify-end">
          <div class="text-xl font-bold text-pretty text-blue-100 mt-40 leading-loose tracking-wider w-3/4">
            <p>Welcome to IronWorks Gym, where your journey to strength, health, and wellness begin.
              Located in the heart
              of
              Austin, TX, we're here to help you achieve your goals with personalized and world-class equiment.</p>
          </div>
        </div>
      </div>
    </div>

    <div id="mission" class="flex justify-center items-center h-[500px]">
      <div class="text-center w-3/4">
        <p class="text-4xl text-orange-400 font-bold mb-4">Driven by Passion, Powered by Community</p>
        <p class="text-xl text-blue-200">IronWork Gym is dedicated to empowering individuals of all fitness levels to
          reach their
          potential. Through
          our
          supportive community, cutting-edge equipment, and expert trainers, we're commited to helping you unlock the
          strength you didn't know you had.</p>
      </div>
    </div>

    <div id="cta" class="relative overflow-hidden">

      <div class="absolute inset-0 bg-[url('./assets/card.jpg')] bg-cover bg-center filter blur-sm" />
      <div class="absolute inset-0 bg-gradient-to-b from-black/60 via-transparent to-black/60" />
      <div class="absolute inset-0 bg-black/20" />

      <div id="cta-content" class="relative flex-col text-center m-24">
        <p class="text-4xl text-orange-500 font-bold mb-2">Membership Options</p>

        <div id="card-container" class="flex justify-center">

          <div id="card" class="m-8 p-8 w-[400px] bg-black/80 rounded-2xl">
            <p class="font-bold text-2xl text-orange-400">Basic Plan</p>
            <p class="font-bold text-xl text-blue-400">Price: $29/month</p>
            <hr class="h-[2px] bg-blue-300/50 my-4 border-0 rounded">
            <div class="text-left px-6">
              <p class="text-2xl text-orange-400">Features:</p>
              <ul class="text-lg text-blue-100 marker:text-blue-100 list-outside list-disc">
                <li class="my-2">Access to gym facilities during staffed hours</li>
                <li class="my-2">Group finess classes (2 per month)</li>
                <li class="my-2">Access to cardio and weightlifting areas</li>
              </ul>
            </div>
            <hr class="h-[2px] bg-blue-300/50 my-4 border-0 rounded">
            <p class="text-left text-xl text-orange-400 mx-6 mb-0">Ideal For: </p>
            <p class="text-left text-lg text-blue-100 mx-6 my-1">Beginners or casual gym-goers looking for
              flexible, basic
              access.</p>
          </div>

          <div id="card" class="m-8 p-8 w-[400px] bg-black/80 rounded-2xl">
            <p class="font-bold text-2xl text-orange-400">Standard Plan</p>
            <p class="font-bold text-xl text-blue-400">Price: $59/month</p>
            <hr class="h-[2px] bg-blue-300/50 my-4 border-0 rounded">
            <div class="text-left px-6">
              <p class="text-2xl text-orange-400">Features:</p>
              <ul class="text-lg text-blue-100 marker:text-blue-100 list-outside list-disc">
                <li class="my-2">24/7 gym access</li>
                <li class="my-2">Unlimited group fitness classes</li>
                <li class="my-2">Complimentary fitness assessment(once per quarter)</li>
              </ul>
            </div>
            <hr class="h-[2px] bg-blue-300/50 my-4 border-0 rounded">
            <p class="text-left text-xl text-orange-400 mx-6 mb-0">Ideal For: </p>
            <p class="text-left text-lg text-blue-100 mx-6 my-1">Members who want more flexibility and group class
              access.</p>
          </div>

          <div id="card" class="m-8 p-8 w-[400px] bg-black/80 rounded-2xl">
            <p class="font-bold text-2xl text-orange-400">Premium Plan</p>
            <p class="font-bold text-xl text-blue-400">Price: $99/month</p>
            <hr class="h-[2px] bg-blue-300/50 my-4 border-0 rounded">
            <div class="text-left px-6">
              <p class="text-2xl text-orange-400">Features:</p>
              <ul class="text-lg text-blue-100 marker:text-blue-100 list-outside list-disc">
                <li class="my-2">24/7 gym access</li>
                <li class="my-2">Unlimited group fitness and specialty classes</li>
                <li class="my-2">Monthly one-on-one session with a persnal trainer</li>
                <li class="my-2">Access to VIP facilities (sauna, stream room)</li>
                <li class="my-2">10% discount on merchandise and supplements</li>
              </ul>
            </div>
            <hr class="h-[2px] bg-blue-300/50 my-4 border-0 rounded">
            <p class="text-left text-xl text-orange-400 mx-6 mb-0">Ideal For: </p>
            <p class="text-left text-lg text-blue-100 mx-6 my-1">Dedicated fitness enthusiasts who want the full
              experience.</p>
          </div>
        </div>
        <button
          class="text-orange-500 text-xl font-bold m-auto mx-8 mr-16 px-4 py-3 bg-blue-800/80 rounded-2xl ease-in-out duration-200 hover:bg-blue-700 active:bg-blue-600">Get
          Your
          Free
          Trial</button>

      </div>

    </div>

    <div id="footer" class="flex justify-center items-center h-[300px]">
      <div class="flex-col justify-center items-center">
        <div class="font-bold text-lg">
          <img alt="logo" />
          <p class="text-center font-bold text-3xl text-orange-500">Contact Us</p>
          <hr class="h-[2px] bg-blue-300/50 my-2 border-0 rounded">
          <div class="px-4">
            <div class="flex">
              <p class="mr-2 text-orange-300">Address:</p>
              <p class="text-blue-200">123 Austin Fitness, Austin, TX 78701</p>
            </div>
            <div class="flex">
              <p class="mr-2 text-orange-300">Phone:</p>
              <p class="text-blue-200">(512) 123-4567</p>
            </div>
            <div class="flex">
              <p class="mr-2 text-orange-300">Email:</p>
              <p class="text-blue-200">info@ironworksaustin.com</p>
            </div>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>

<style scoped></style>
