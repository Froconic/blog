<template>
  <div class="blog-single">
    <section class="bg-black text-light overlay min-vh-100 d-flex flex-column justify-content-end jarallax" data-jarallax data-speed="0.5">
      <img src="../assets/img/article-11.jpg" alt="Image" class="jarallax-img opacity-60">
      <div class="container">
        <div class="row justify-content-center">
          <div class="col-lg-10 col-xl-8">
            <div class="d-flex justify-content-between align-items-center mb-3">
              <nav aria-label="breadcrumb">
                <ol class="breadcrumb">
                  <li class="breadcrumb-item">
                    <NuxtLink to='/'>Blog</NuxtLink>
                  </li>
                  <li class="breadcrumb-item">
                    <NuxtLink to='/'>Category</NuxtLink>
                  </li>
                </ol>
              </nav>
              <span class="badge badge-primary">
                <img class="icon bg-primary" src="../assets/img/icons/interface/heart.svg" alt="heart interface icon">21</span>
            </div>
            <h1>Navigating the complexity of change aversion</h1>
            <div class="d-flex align-items-center">
              <NuxtLink to='/'>
                <img src="../assets/img/avatars/male-1.jpg" alt="Avatar" class="avatar mr-2">
              </NuxtLink>
              <div>
                <div>by <NuxtLink to='/'>Benjamin Cameron</NuxtLink>
                </div>
                <div class="text-small text-muted">30th October</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="p-0" data-reading-position>
        <div class="container">
          <div class="row justify-content-center">
            <div class="col-xl-7 col-lg-8 col-md-10">
              <article class="article">
                <p class="lead">
                  Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt.
                </p>
                <p>
                  Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas
                  sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt.
                </p>
                <p>
                  Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem
                  ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?
                </p>
                <h4>A heading to shift focus</h4>
                <p>
                  At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis praesentium voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident, similique sunt in culpa qui officia deserunt mollitia
                  animi, id est laborum et dolorum fuga. Et harum quidem rerum facilis est et expedita distinctio. Nam libero tempore, cum soluta nobis est eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas
                  assumenda est, omnis dolor repellendus.
                </p>
                <figure>
                  <img src="../assets/img/article-9.jpg" alt="Image" class="rounded">
                  <figcaption>A caption to describe the image</figcaption>
                </figure>
                <p>
                  Aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?
                </p>
                <blockquote class="bg-light">
                  <div class="h3 mb-2 text-dark">“We couldn’t have done it without the hard-working team from Leap.”</div>
                  <span class="text-small text-muted">– Harvey Dent (via Tareq I.)</span>
                </blockquote>
                <p>
                  Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas
                  sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt.
                </p>
                <h5>A minor heading to summarise</h5>
                <p>Sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur?</p>
                <ul>
                  <li>Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam</li>
                  <li>Corporis suscipit laboriosam</li>
                  <li>Aspernatur aut odit aut fugit eos qui ratione</li>
                  <li>Et quasi</li>
                </ul>
              </article>
            </div>
          </div>
        </div>
    </section>
    <section class="has-divider">
      <div class="container pt-3">
        <div class="row justify-content-center">
          <div class="col-xl-7 col-lg-8 col-md-10">
            <hr>
            <div class="d-flex align-items-center">
              <span class="text-small mr-1">Share this article:</span>
              <div class="d-flex mx-2">
                <NuxtLink to='/' class="btn btn-round btn-primary mx-1">
                  <img class="icon icon-sm" src="../assets/img/icons/social/twitter.svg" alt="twitter social icon">
                </NuxtLink>
                <NuxtLink to='/' class="btn btn-round btn-primary mx-1">
                  <img class="icon icon-sm" src="../assets/img/icons/social/facebook.svg" alt="facebook social icon">
                </NuxtLink>
                <NuxtLink to='/' class="btn btn-round btn-primary mx-1">
                  <img class="icon icon-sm" src="../assets/img/icons/social/linkedin.svg" alt="linkedin social icon">
                </NuxtLink>
              </div>
            </div>
            <hr>
            <h5 class="my-4">4 Comments</h5>
            <ol class="comments">
              <li class="comment">
                <div class="d-flex align-items-center text-small">
                  <img src="../assets/img/avatars/female-4.jpg" alt="Angela Zhao" class="avatar avatar-sm mr-2">
                  <div class="text-muted mr-1">Angela Zhao</div>
                  <div class="text-muted">56 minutes ago</div>
                </div>
                <div class="my-2">
                  Quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
                </div>
                <div>
                  <NuxtLink to='/' class="text-small">Reply</NuxtLink>
                </div>
                <ol class="comments">
                  <li class="comment">
                    <div class="d-flex align-items-center text-small">
                      <img src="../assets/img/avatars/male-5.jpg" alt="Lenny Sims" class="avatar avatar-sm mr-2">
                      <div class="text-muted mr-1">Lenny Sims</div>
                      <div class="text-muted">just now</div>
                    </div>
                    <div class="my-2">
                      Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
                    </div>
                    <div>
                      <NuxtLink to='/' class="text-small">Reply</NuxtLink>
                    </div>
                  </li>
                </ol>
              </li>
              <li class="comment">
                <div class="d-flex align-items-center text-small">
                  <img src="../assets/img/avatars/female-1.jpg" alt="Sarah Priestly" class="avatar avatar-sm mr-2">
                  <div class="text-muted mr-1">Sarah Priestly</div>
                  <div class="text-muted">2 hours ago</div>
                </div>
                <div class="my-2">
                  Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur?
                </div>
                <div>
                  <NuxtLink to='/' class="text-small">Reply</NuxtLink>
                </div>
              </li>
              <li class="comment">
                <div class="d-flex align-items-center text-small">
                  <img src="../assets/img/avatars/male-1.jpg" alt="Benjamin Cameron" class="avatar avatar-sm mr-2">
                  <div class="text-muted mr-1">Benjamin Cameron</div>
                  <div class="text-muted">3 hours ago</div>
                </div>
                <div class="my-2">
                  Sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem
                </div>
                <div>
                  <NuxtLink to='/' class="text-small">Reply</NuxtLink>
                </div>
              </li>
            </ol>
            <hr>
            <h5 class="my-4">Post a comment</h5>
            <form>
              <div class="row">
                <div class="col-md-6 mb-1">
                  <div class="form-group">
                    <input type="text" class="form-control" placeholder="Name" name="comment-name">
                  </div>
                </div>
                <div class="col-md-6 mb-1">
                  <div class="form-group">
                    <input type="email" class="form-control" placeholder="Email Address" name="comment-email">
                  </div>
                </div>
              </div>
              <div class="form-group">
                <textarea class="form-control" name="comment-text" rows="7" placeholder="Comment"></textarea>
              </div>
              <div class="d-flex align-items-center justify-content-between">
                <div class="custom-control custom-checkbox">
                  <input type="checkbox" class="custom-control-input" id="comment-form-opt-in">
                  <label class="custom-control-label text-small" for="comment-form-opt-in">Notify me when someone replies</label>
                </div>
                <button class="btn btn-primary" type="submit">Submit</button>
              </div>
            </form>
          </div>
        </div>
      </div>
      <div class="divider">
        <img class="bg-primary-alt" src="../assets/img/dividers/divider-1.svg" alt="divider graphic">
      </div>
    </section>
    <section class="bg-primary-alt">
      <div class="container">
        <div class="row mb-4">
          <div class="col">
            <h3 class="h2">Related Stories</h3>
          </div>
        </div>
        <div class="row">
          <div class="col-md-6 col-lg-4 d-flex" data-aos="fade-up" data-aos-delay="100">
            <NuxtLink to='/' class="card card-body justify-content-between bg-primary text-light">
              <div class="d-flex justify-content-between mb-3">
                <div class="text-small d-flex">
                  <div class="mr-2">
                    Links
                  </div>
                  <span class="opacity-70">19th December</span>
                </div>
                <span class="badge bg-primary-alt text-primary">
                  <img class="icon icon-sm bg-primary" src="../assets/img/icons/interface/heart.svg" alt="heart interface icon">27
                </span>
              </div>
              <div>
                <h2>A time-tracking app that isn’t a pain.</h2>
                <span class="text-small opacity-70">http://www.website.io/link</span>
              </div>
            </NuxtLink>
          </div>
          <div class="col-md-6 col-lg-4 d-flex" data-aos="fade-up" data-aos-delay="200">
            <div class="card">
              <NuxtLink to='/'>
                <img src="../assets/img/article-1.jpg" alt="Image" class="card-img-top">
              </NuxtLink>
              <div class="card-body d-flex flex-column">
                <div class="d-flex justify-content-between mb-3">
                  <div class="text-small d-flex">
                    <div class="mr-2">
                      <NuxtLink to='/'>Business</NuxtLink>
                    </div>
                    <span class="text-muted">29th November</span>
                  </div>
                  <span class="badge bg-primary-alt text-primary">
                    <img class="icon icon-sm bg-primary" src="../assets/img/icons/interface/heart.svg" alt="heart interface icon">12
                  </span>
                </div>
                <NuxtLink to='/'>
                  <h4>How to build collateral</h4>
                </NuxtLink>
                <p class="flex-grow-1">
                  Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium.
                </p>
                <div class="d-flex align-items-center mt-3">
                  <img src="../assets/img/avatars/female-3.jpg" alt="Image" class="avatar avatar-sm">
                  <div class="ml-1">
                    <span class="text-small text-muted">By</span>
                    <span class="text-small">Abby Sims</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-md-6 col-lg-4 d-flex" data-aos="fade-up" data-aos-delay="300">
            <div class="card">
              <NuxtLink to='/'>
                <img src="../assets/img/article-2.jpg" alt="Image" class="card-img-top">
              </NuxtLink>
              <div class="card-body d-flex flex-column">
                <div class="d-flex justify-content-between mb-3">
                  <div class="text-small d-flex">
                    <div class="mr-2">
                      <NuxtLink to='/'>Design</NuxtLink>
                    </div>
                    <span class="text-muted">27th November</span>
                  </div>
                  <span class="badge bg-primary-alt text-primary">
                    <img class="icon icon-sm bg-primary" src="../assets/img/icons/interface/heart.svg" alt="heart interface icon">23
                  </span>
                </div>
                <NuxtLink to='/'>
                  <h4>Forging your path</h4>
                </NuxtLink>
                <p class="flex-grow-1">
                  Perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium.
                </p>
                <div class="d-flex align-items-center mt-3">
                  <img src="../assets/img/avatars/male-4.jpg" alt="Image" class="avatar avatar-sm">
                  <div class="ml-1">
                    <span class="text-small text-muted">By</span>
                    <span class="text-small">Cedric</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <Footer></Footer>
  </div>
</template>

<script>

</script>

<style>

</style>


