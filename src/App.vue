<script setup>
</script>

<template>
  <div id="website" class="bg-black w-full h-screen text-white font-mono">

    <div id="hero" class="relative h-[800px] flex-col justify-center items-center m-auto overflow-hidden">

      <div class="absolute inset-0 bg-[url('./assets/hero.jpg')] bg-cover bg-center filter blur-sm" />
      <div class="absolute inset-0 bg-gradient-to-b from-black/60 via-transparent to-black/60" />
      <div class="absolute inset-0 bg-black/20" />

      <div id="nav" class="relative font-bold text-xl flex justify-center items-center h-1/6">
        <div class="flex w-full">
          <img alt="logo" class="m-auto ml-8" />
          <button
            class="m-auto mr-6 px-4 py-3 rounded-3xl ease-in-out duration-200 hover:bg-blue-500/30 hover:text-orange-600 active:bg-blue-700">About
            Us</button>
          <button
            class="mx-6 px-4 py-3 rounded-3xl ease-in-out duration-200 hover:bg-blue-500/30 hover:text-orange-600 active:bg-blue-700">Contact
            Us</button>
          <button
            class="text-orange-600 m-auto mx-8 mr-16 px-4 py-3 bg-blue-800 rounded-3xl ease-in-out duration-200 hover:bg-blue-700 active:bg-blue-600">Get
            Your
            Free
            Trial</button>
        </div>
      </div>

      <div id="hero-content" class="relative flex-col justify-center items-center max-w-[1200px] m-auto mt-40">
        <div class="text-[4rem] text-orange-50 font-bold leading-tight max-w-[850px]">
          <p>Transform Your Fitness, Transform Your Life</p>
        </div>
        <div class="flex justify-end">
          <div class="text-xl font-bold text-pretty text-blue-50 mt-40 leading-loose tracking-wider w-3/4">
            <p>Welcome to IronWorks Gym, where your journey to strength, health, and wellness begin.
              Located in the heart
              of
              Austin, TX, we're here to help you achieve your goals with personalized and world-class equiment.</p>
          </div>
        </div>
      </div>
    </div>

    <div id="mission">
      <p>Driven by Passion, Powered by Community</p>
      <p>IronWork Gym is dedicated to empowering individuals of all fitness levels to reach their potential. Through
        our
        supportive community, cutting-edge equipment, and expert trainers, we're commited to helping you unlock the
        strength you didn't know you had.</p>
    </div>

    <div id="cta">

      <p>Membership Options</p>
      <div id="card-container">
        <div id="card">
          <p>Basic Plan</p>
          <p>Price: $29/month</p>
          <p>Features:</p>
          <ul>
            <li>Access to gym facilities during staffed hours</li>
            <li>Group finess classes (2 per month)</li>
            <li>Access to cardio and weightlifting areas</li>
          </ul>
          <p>Ideal For: Beginners or casual gym-goers looking for flexible, basic access.</p>
        </div>

        <div id="card">
          <p>Stand Plan</p>
          <p>Price: $59/month</p>
          <p>Features:</p>
          <ul>
            <li>24/7 gym access</li>
            <li>Unlimited group fitness classes</li>
            <li>Complimentary fitness assessment(once per quarter)</li>
          </ul>
          <p>Ideal For: Members who want more flexibility and group class access.</p>
        </div>

        <div id="card">
          <p>Premium Plan</p>
          <p>Price: $99/month</p>
          <p>Features:</p>
          <ul>
            <li>24/7 gym access</li>
            <li>Unlimited group fitness and specialty classes</li>
            <li>Monthly one-on-one session with a persnal trainer</li>
            <li>Access to VIP facilities (sauna, stream room)</li>
            <li>10% discount on merchandise and supplements</li>
          </ul>
        </div>
      </div>
      <button>Try us for Free</button>

    </div>

    <div id="footer">
      <p>Address: 123 Austin Fitness, Austin, TX 78701</p>
      <p>Phone: (512) 123-4567</p>
      <p>Email: info@ironworksaustin.com</p>
    </div>
  </div>
</template>

<style scoped></style>
