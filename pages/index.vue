<template>
  <div class="mt-20 mx-2">
    <p class="text-center text-3xl">
      Reswitch Nuxt starter
    </p>
    <p class="text-2xl text-center text-gray-800">
      Nuxt + Tailwind + ESLint + Yarn starter project
    </p>

    <div class="md:container mx-auto my-12">
      <div class="w-11/12 md:w-3/5 mx-auto p-4 shadow-md rounded-md border border-gray-300 mt-4">
        <p class="text-lg">
          This is a default starter project for Reswitch Technologies websites<br>
          &bull; The base framework is <a target="blank" href="https:/nuxtjs.org">Nuxt</a> <br>
          &bull; For styling, we are using <a target="blank" href="https://v1.tailwindcss.com/">TailwindCSS (v1)</a> + SCSS (check the global.scss file) <br>
          &bull; The linter is ESLint <br>
        </p>
        <hr>
        <p class="text-lg">
          If you are using VSCode, use the following extensions <br>
          &bull; Vetur <br>
          &bull; Tailwind CSS Intellisense <br>
          &bull; ESLint (eslint should also be installed globally)
        </p>
      </div>
    </div>

    <div class="container mx-auto text-center mt-4">
      <div class="w-11/12 md:w-3/5 mx-auto">
        <p class="text-xl my-2 uppercase">
          ~ Tailwind examples ~
        </p>
        <div>
          <p class="text-lg text-gray-700 my-1">
            Derived classes using @apply
          </p>
          <button class="re-button primary">
            Primary
          </button>
          <button class="re-button alert">
            Alert
          </button>
          <button class="re-button success">
            Success
          </button>
          <button class="re-button warning">
            Warning
          </button>
        </div>
        <hr>
        <div>
          <p class="text-lg text-gray-700 my-1">
            Gradients
          </p>
          <div class="w-3/4 mx-auto h-12 bg-gradient-to-r from-green-500 to-blue-500 rounded-lg" />
        </div>
        <hr>
        <div>
          <p class="text-lg text-gray-700 my-1">
            Hover effects
          </p>
          <button class="re-button success hover:shadow-lg">
            Shadow on hover
          </button>
        </div>
        <hr>
        <div class="text-lg text-gray-700 my-1">
          These basic examples are just to help you get started and show you the possibilities that Tailwind brings to the table
        </div>
      </div>
    </div>

    <div class="container mt-32 mx-auto mb-12">
      <hr>
      <p class="text-center italic">
        Only TailwindCSS classes were used in the making of this starter project
        <br>= MIT License =
      </p>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">

</style>
