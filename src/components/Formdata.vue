<script setup lang="ts"></script>

<template>
  <div class="w-full h-auto flex items-center justify-center p-6">
    <form class="bg-white p-8 rounded-lg shadow-lg w-full max-w-lg">
      <h2 class="text-2xl font-semibold mb-6">Contact Us</h2>
      <div class="space-y-6">
        <div class="flex gap-4">
          <div class="flex-1">
            <label for="firstname" class="block text-sm font-medium text-gray-500">Firstname *</label>
            <input id="firstname" type="text" class="mt-1 block border border-black  w-full  rounded-md shadow-sm focus:border-teal-500 focus:ring focus:ring-teal-500 focus:ring-opacity-50" />
          </div>

          <div class="flex-1">
            <label for="lastname" class="block text-sm font-medium text-gray-500">Lastname *</label>
            <input id="lastname" type="text" class="mt-1 block w-full border border-black rounded-md shadow-sm focus:border-teal-500 focus:ring focus:ring-teal-500 focus:ring-opacity-50" />
          </div>
        </div>

        <div>
          <label for="email" class="block text-sm font-medium text-gray-500">Email Address *</label>
          <input id="email" type="email" class="mt-1 block w-full border border-black rounded-md shadow-sm focus:border-teal-500 focus:ring focus:ring-teal-500 focus:ring-opacity-50" />
        </div>

        <div>
          <label class="block text-sm font-medium text-gray-500">Query Type *</label>
          <div class="mt-2 flex gap-4">
            <label class="flex items-center space-x-2 border border-black rounded-md p-[10px] w-full">
              <input type="radio" name="query_type" class="h-4 w-4 text-teal-600 focus:ring-teal-500" />
              <span class="text-gray-700">General Enquiry</span>
            </label>

            <label class="flex items-center space-x-2 border border-black rounded-md p-[10px] w-full">
              <input type="radio" name="query_type" class="h-4 w-4 text-teal-600    focus:ring-teal-500" />
              <span class="text-gray-700">Support Request</span>
            </label>
          </div>
        </div>

        <div>
          <label for="message" class="block text-sm font-medium text-gray-500">Message *</label>
          <textarea id="message" class="mt-1 block w-full border border-black rounded-md shadow-sm focus:border-teal-500 focus:ring focus:ring-teal-500 focus:ring-opacity-50" rows="4"></textarea>
        </div>

        <div class="flex items-center space-x-2">
          <input id="consent" type="checkbox" class="h-4 w-4 text-teal-600 border-gray-300 focus:ring-teal-500" />
          <label for="consent" class="text-gray-700 text-sm">I consent to being contacted by the team</label>
        </div>

        <button type="submit" class="w-full bg-teal-600 text-white py-2 px-4 rounded-md shadow hover:bg-teal-700 focus:outline-none focus:ring-2 focus:ring-teal-500 focus:ring-opacity-50">Submit</button>
      </div>
    </form>
  </div>
</template>
