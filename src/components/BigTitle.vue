<template>
  <div class="select-none bg-mauveClair relative !h-[54.5dvh]">
    <h1 class="text-blanc text-7xl w-full text-center absolute 900:top-[38.5%] top-[40%]">{{ title }}</h1>
    <h3 class="text-blanc text-5xl w-2/4 absolute bottom-0 left-[5vw] leading-[0.25]">{{ category }}</h3>
  </div>
</template>

<script>
export default {
  name: 'BigTitle',
  props: {
    title: String,
    category: String
  }
}
</script>
