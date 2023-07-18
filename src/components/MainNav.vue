<template>
  <header class="w-full text-sm">Main Nav</header>
  <div class="fixed left-0 top-0 h-16 w-full bg-white">
    <div class="flex h-full flex-nowrap border-b border-solid border-brand-gray-1 px-8">
      <a href="/" class="flex h-full items-center text-xl">{{ company }}</a>
      <h2 class="ml-8 flex h-full items-center">
        Developed by {{ author.firstName }} {{ author.lastName }}
      </h2>
    </div>
  </div>
</template>

<script>
export default {
  name: 'MainNav',
  data() {
    return {
      company: 'Bobo Careers',
      author: {
        firstName: 'Alper',
        lastName: 'Günindi'
      }
    }
  }
}
</script>
