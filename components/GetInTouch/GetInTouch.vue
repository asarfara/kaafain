<script setup lang="ts">

</script>

<template>
  <section class="py-20">
    <div class="container mx-auto px-3">
      <div class="max-w-2xl lg:max-w-3xl mx-auto">
        <div class="mb-12 text-center">
          <h2 class="text-4xl font-bold font-heading">Get in touch!</h2>
          <p class="text-gray-400">We will be glad to hear from you</p>
        </div>
        <div class="flex flex-wrap -mx-3 text-center">
          <div class="w-1/2 lg:w-1/3 px-3 mb-12">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="mb-6 h-8 w-8 mx-auto text-blue-600">
              <path fill-rule="evenodd" d="M1.5 4.5a3 3 0 013-3h1.372c.86 0 1.61.586 1.819 1.42l1.105 4.423a1.875 1.875 0 01-.694 1.955l-1.293.97c-.135.101-.164.249-.126.352a11.285 11.285 0 006.697 6.697c.103.038.25.009.352-.126l.97-1.293a1.875 1.875 0 011.955-.694l4.423 1.105c.834.209 1.42.959 1.42 1.82V19.5a3 3 0 01-3 3h-2.25C8.552 22.5 1.5 15.448 1.5 6.75V4.5z" clip-rule="evenodd" />
            </svg>
            <div class="leading-relaxed">
              <span class="text-sm text-gray-400">Phone</span>
              <p>+ 48 654-430-309</p>
              <p>+ 1 6532-430-309</p></div>
          </div>
          <div class="w-1/2 lg:w-1/3 px-3 mb-12">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="mb-6 h-8 w-8 mx-auto text-blue-600">
              <path d="M1.5 8.67v8.58a3 3 0 003 3h15a3 3 0 003-3V8.67l-8.928 5.493a3 3 0 01-3.144 0L1.5 8.67z" />
              <path d="M22.5 6.908V6.75a3 3 0 00-3-3h-15a3 3 0 00-3 3v.158l9.714 5.978a1.5 1.5 0 001.572 0L22.5 6.908z" />
            </svg>
            <div class="leading-relaxed">
              <span class="text-sm text-gray-400">E-mail</span>
              <p>contact@monst.com</p>
              <p>pat@example.com</p>
            </div>
          </div>
        </div>
        <div>
          <form>
            <div class="mb-4 text-sm">
              <span class="mr-4 font-semibold">Departament:</span>
              <label class="mr-4">
                <input class="mr-1" type="radio" name="department" value="1"><span>Support</span>
              </label>
              <label>
                <input class="mr-1" type="radio" name="department" value="2">
                <span>Sales</span>
              </label>
            </div>
            <div class="flex flex-wrap mb-4 -mx-3">
              <div class="w-full lg:w-1/2 px-3 mb-4 lg:mb-0">
                <div class="mb-4">
                  <input class="w-full p-4 text-xs font-semibold leading-none bg-gray-50 rounded outline-none" type="text" placeholder="Subject">
                </div>
                <div class="mb-4">
                  <input class="w-full p-4 text-xs font-semibold leading-none bg-gray-50 rounded outline-none" type="text" placeholder="Name">
                </div>
                <div class="mb-4">
                  <input class="w-full p-4 text-xs font-semibold leading-none bg-gray-50 rounded outline-none" type="email" placeholder="name@example.com">
                </div>
                <div>
                  <label class="flex px-2 bg-gray-50 rounded">
                    <input class="hidden" type="file" name="Choose file">
                    <span class="my-1 ml-auto px-4 py-3 text-xs text-white font-semibold leading-none bg-gray-500 hover:bg-gray-600 rounded cursor-pointer"> Browse</span>
                  </label>
                </div>
              </div>
              <div class="w-full lg:w-1/2 px-3">
                <textarea class="w-full h-full p-4 text-xs font-semibold leading-none resize-none bg-gray-50 rounded outline-none"
                placeholder="Message...">

                </textarea>
              </div>
            </div>
            <div class="flex justify-between items-center">
              <label>
                <input class="mr-1" type="checkbox" name="terms" value="1">
                <span class="text-sm font-semibold">I agree to terms and conditions.</span>
              </label>
              <button class="py-4 px-8 text-sm text-white font-semibold leading-none bg-blue-400 hover:bg-blue-500 rounded" type="submit">
                Submit
              </button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="postcss">

</style>
