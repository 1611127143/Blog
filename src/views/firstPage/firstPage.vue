<script setup></script>

<template>
  <main class="flex justify-center items-center bg-gradient-to-r from-cyan-500 to-blue-500 h-screen">
    <div class="flex w-1/2 h-80 shadow-lg rounded-xl overflow-hidden">
      <img class="w-full h-full" src="../../assets/lara.webp">
      <div class="flex justify-center items-center w-80 bg-white">
        <div class="flex flex-col items-center w-36 h-full space-y-5">
          <h3 class="text-xl my-4 font-black caret-transparent">Login/Register</h3>
          <input type="text" placeholder="USER NAME" class="h-5 outline-none border-b-2"/>
          <input type="text" placeholder="ACCOUNT" class="h-5 outline-none border-b-2"/>
          <input type="password" placeholder="PASSWORD" class="h-5 outline-none border-b-2"/>
          <a href="#" class="text-xs underline">Forget the password?</a>
          <a href="#" class="font-black text-2xl hover:no-underline text-violet-500 mx-auto">Login</a>
        </div>
      </div>
    </div>
  </main>
</template>
