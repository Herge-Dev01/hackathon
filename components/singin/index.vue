<template>
<section class="bg-gray-50 dark:bg-gray-900 main">
  <div class="flex flex-col items-center justify-center px-6 py-8 mx-auto md:h-screen lg:py-0">
      <a href="#" class="flex items-center mb-6 text-2xl font-semibold text-gray-900 dark:text-white">
          <img class="w-8 h-8 mr-2" src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/logo.svg" alt="logo">
          App Name    
      </a>
      <div class="container w-full bg-white rounded-lg shadow dark:border md:mt-0 sm:max-w-md xl:p-0 dark:bg-gray-800 dark:border-gray-700">
          <div class="p-6 space-y-4 md:space-y-6 sm:p-8">
              <h1 class="text-xl font-bold leading-tight tracking-tight text-gray-900 md:text-2xl">
                  Sign in to your account
              </h1>
              <form class="space-y-4 md:space-y-6" action="#">
                  <div>
                      <label for="email" class="block mb-2 text-sm font-medium">Your phone number</label>
                      <input type="text" name="phoneNumber" id="phoneNumber" class="inputForm border border-gray-300 text-gray-900 sm:text-sm rounded-lg block w-full p-2.5" placeholder="+261*********" required="true">
                  </div>
                  <div>
                      <label for="password" class="block mb-2 text-sm font-medium text-gray-900">Password</label>
                      <input type="password" name="password" id="password" placeholder="" class=" inputForm bg-gray-50 border border-gray-300 text-gray-900 sm:text-sm rounded-lg block w-full p-2.5" required="true">
                  </div>
                  <div class="flex items-center justify-between">
                      <div class="flex items-start">
                          <div class="flex items-center h-5">
                            <input id="remember" aria-describedby="remember" type="checkbox" class="w-4 h-4 border border-gray-300 rounded bg-gray-50 focus:ring-3 focus:ring-primary-300">
                          </div>
                          <div class="ml-3 text-sm">
                            <label for="remember" class="text-gray-700">Remember me</label>
                          </div>
                      </div>
                      <a href="#" class="text-sm font-medium text-gray-700 hover:underline">Forgot password?</a>
                  </div>
                  <button type="submit" class="singinButton w-full text-white bg-primary-600 hover:bg-primary-700 focus:ring-4 focus:outline-none focus:ring-primary-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center">Sign in</button>
                  <p class="text-sm font-light text-gray-700">
                      Don’t have an account yet? <a href="#" class="font-medium text-gray-700 hover:underline">Sign up</a>
                  </p>
              </form>
          </div>
      </div>
  </div>
</section>
</template>
<style>
:root {
    --e-global-color-primary: #FC6D0E;
    --e-global-color-primary-light: #ff802c;
    --e-global-color-secondary: #FFFFFF;
    --e-global-color-text: #000000;
    --e-global-color-accent: #FC6D0E;
    --e-global-color-c297285: #83B986;
    --e-global-color-9a02f9f: #A1C267;
    --e-global-color-f902ef1: #6BB3A7;
    --e-global-color-2dd8287: #FEC700;
    --main-blue: #9DBF9E;
}
* {
    color: #1d1d1d;
}
section.main {
    background: linear-gradient(45deg, #6bb3a7, #a1c267);
}
.main .container {
    background: #91cde4;
}
.inputForm {
    background: #ffffff6e;
    color: #1d1d1d;
}
/* label {
    color: white;
} */
.singinButton {
    background: var(--e-global-color-primary);
}
</style>