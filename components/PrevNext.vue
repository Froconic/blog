<template>
  <div class="flex justify-between">
    <NuxtLink v-if="prev" :to="{name: 'blog-slug', params: { slug:prev.slug }}" class="font-bold text-primary hover:underline"> {{ prev.title }}
    </NuxtLink>
    <span v-else>Noop</span>
    <NuxtLink v-if="next" :to="{name: 'blog-slug', params: { slug:next.slug }}" class="font-bold text-primary hover:underline"> {{ next.title }}
    </NuxtLink>
    <span v-else>Boop</span>
  </div>
</template>

<script>
  export default {
props: {
  prev: {
    trpe: Object,
    default: () => null
  },
  prev: {
    trpe: Object,
    default: () => null
  }
}
  }

</script>

<style>

</style>
