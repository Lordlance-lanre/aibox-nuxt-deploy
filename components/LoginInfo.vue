<template>
<div class="mt-14">
	<div class="block mx-24 md:mx-96 justify-center">
		<label class="block mb-2 text-sm font-medium text-white">Username</label>
		<input type="text" class="w-72 md:w-11/12 py-4 rounded-lg border-sky-500 px-3 outline-sky-500" placeholder="Enter Username">
	</div>

	<div class="mt-7 block mx-24 md:mx-96 justify-center">
		<label class="block mb-2 text-sm font-medium text-white">Password</label>
		<input type="text" class="w-72 md:w-11/12 py-4 rounded-lg border-black px-3" placeholder="Enter Password">
		<div class="absolute -mt-10 mx-64 md:mx-96">
			 <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
  			<path stroke-linecap="round" stroke-linejoin="round" d="M3.98 8.223A10.477 10.477 0 001.934 12C3.226 16.338 7.244 19.5 12 19.5c.993 0 1.953-.138 2.863-.395M6.228 6.228A10.45 10.45 0 0112 4.5c4.756 0 8.773 3.162 10.065 7.498a10.523 10.523 0 01-4.293 5.774M6.228 6.228L3 3m3.228 3.228l3.65 3.65m7.894 7.894L21 21m-3.228-3.228l-3.65-3.65m0 0a3 3 0 10-4.243-4.243m4.242 4.242L9.88 9.88" />
			</svg>
		</div>
	</div>

	<div class="flex justify-end mx-16 mt-5 md:hidden">
		<h4 class="text-white">Forgot Password ?</h4>
	</div>

	<div class="mt-7 md:mt-16">
		<button class="flex mx-auto bg-white px-12 py-3 rounded-full text-indigo-600 hover:bg-indigo-900 font-medium hover:text-white">Login</button>
		<div class="absolute -mt-9 md:text-white text-indigo-600 mx-64 md:hidden hover:text-white">
			<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6 hover:text-white">
  			<path stroke-linecap="round" stroke-linejoin="round" d="M17.25 8.25L21 12m0 0l-3.75 3.75M21 12H3" />
			</svg>

		</div>
	</div>
</div>
</template>