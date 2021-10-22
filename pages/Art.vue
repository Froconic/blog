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
            <ul data-isotope-filters data-isotope-id="projects" class="nav mb-3">
              <li class="nav-item">
                <NuxtLink to='/' class="nav-link active" data-filter="*">All</NuxtLink>
              </li>
              <li class="nav-item">
              <NuxtLink to='/' class="nav-link" data-filter="Branding">Branding</NuxtLink>
              </li>
              <li class="nav-item">
                <NuxtLink to='/' class="nav-link" data-filter="Digital">Digital</NuxtLink>
              </li>
              <li class="nav-item">
                <NuxtLink to='/' class="nav-link" data-filter="Art Direction">Art Direction</NuxtLink>
              </li>
            </ul>
          </div>
        </div>
        <div class="row" data-isotope-collection data-isotope-id="projects">
          <div class="col-sm-6 col-lg-4 mb-4" data-isotope-item data-category="Branding">
            <NuxtLink to='/'>
              <img src="../assets/img/portfolio-item-6.jpg" alt="Volkswagen Australia" class="rounded mb-3">
              <h4 class="mb-1">Volkswagen Australia</h4>
              <div class="text-small text-muted">Branding</div>
            </NuxtLink>
          </div>
          <div class="col-sm-6 col-lg-4 mb-4" data-isotope-item data-category="Art Direction">
            <NuxtLink to='/'>
              <img src="../assets/img/portfolio-item-5.jpg" alt="Go Commerce" class="rounded mb-3">
              <h4 class="mb-1">Go Commerce</h4>
              <div class="text-small text-muted">Art Direction</div>
            </NuxtLink>
          </div>
          <div class="col-sm-6 col-lg-4 mb-4" data-isotope-item data-category="Digital">
            <NuxtLink to='/'>
              <img src="../assets/img/portfolio-item-4.jpg" alt="Tribe" class="rounded mb-3">
              <h4 class="mb-1">Tribe</h4>
              <div class="text-small text-muted">Digital</div>
            </NuxtLink>
          </div>
          <div class="col-sm-6 col-lg-4 mb-4" data-isotope-item data-category="Art Direction">
            <NuxtLink to='/'>
              <img src="../assets/img/portfolio-item-3.jpg" alt="Beker EV" class="rounded mb-3">
              <h4 class="mb-1">Beker EV</h4>
              <div class="text-small text-muted">Art Direction</div>
            </NuxtLink>
          </div>
          <div class="col-sm-6 col-lg-4 mb-4" data-isotope-item data-category="Branding">
            <NuxtLink to='/'>
              <img src="../assets/img/portfolio-item-2.jpg" alt="Oculus Go" class="rounded mb-3">
              <h4 class="mb-1">Oculus Go</h4>
              <div class="text-small text-muted">Branding</div>
            </NuxtLink>
          </div>
          <div class="col-sm-6 col-lg-4 mb-4" data-isotope-item data-category="Digital">
            <NuxtLink to='/'>
              <img src="../assets/img/portfolio-item-1.jpg" alt="Leap iOS" class="rounded mb-3">
              <h4 class="mb-1">Leap iOS</h4>
              <div class="text-small text-muted">Digital</div>
            </NuxtLink>
          </div>
        </div>
      </div>
    </section>
</div>
</template>

<script>

</script>

<style>

</style>