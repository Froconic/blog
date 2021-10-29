<template>
<div class="art">
    <section class="bg-primary-2 has-divider text-dark">
      <div class="container pb-6">
        <div class="row justify-content-center text-center">
          <div class="col-xl-8 col-lg-9 col-md-10">
            <h2 class="display-3 mb-5">Art </h2>
            <p class="lead">Action <br> Reaction <br> Translation</p>
          </div>
        </div>
      </div>
      <!-- <div class="divider">
        <img src="../assets/img/dividers/divider-2.svg" alt="graphical divider" data-inject-svg />
      </div> -->
    </section>
  <section class="bg-black text-dark pt-5">
      <div class="container">
        <div class="row justify-content-center mb-4">
          <div class="col col-md-auto">
            <Search></Search>

          </div>
        </div>
        <div class="row">
          <div v-for="artwork of artworks" :key="artwork.slug" class="col-sm-6 col-lg-4 mb-4">
            <NuxtLink :to="{name:'art-slug',params: { slug: artwork.slug }} ">
              <img :src="artwork.img" :alt="artwork.alt" class="rounded mb-3">
              <h4 class="mb-1"> {{artwork.title}} </h4>
            </NuxtLink>
          </div>
        </div>
      </div>
    </section>
</div>
</template>

<script>
  export default {
    async asyncData({
      $content,
      params
    }) {
      const artworks = await $content ('artworks').only(['title', 'description', 'category', 'img', 'cover', 'slug', 'createdAt']).sortBy('createdAt', 'asc').fetch()

      return {
        artworks
      }
    },
    methods: {
      formatDate(date) {
        const options = {
          year: 'numeric',
          month: 'long',
          day: 'numeric'
        }
        return new Date(date).toLocaleDateString('en', options)
      }
    },
}

</script>

<style>

</style>