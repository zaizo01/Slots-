<template>
  <div id="app">
    <div class="w-full h-full">
        <div class="w-1/2 h-auto border border-gray-400 p-10 rounded shadow-lg mx-auto mt-32">
        <Form>
            <div slot="title">
              <p class="text-2xl font-semibold">Change Password</p>
            </div>
            <div slot="elements" class="flex flex-col">
              <label for="email" class="text-xl fonot-semibold">Email</label>
              <input type="email" name="email" class="border-2 border-gray-600 p-2 rounded">
              <label for="pass" class="text-xl fonot-semibold">Password</label>
              <input type="password" name="pass" class="border-2 border-gray-600 p-2 rounded">
            </div>
            <div slot="button">
                <button class="px-3 py-3 bg-blue-600 text-white font-semibold mt-4 w-40 rounded">Change Password</button>
            </div>
         </Form>
        </div>
    </div>
  </div>
</template>

