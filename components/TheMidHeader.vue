<template>
  <section class="header-main border-bottom">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-lg-3 col-4">
          <nuxt-link to="/" class="brand-wrap">
            YourCommerceNow
          </nuxt-link>
          <!-- brand-wrap.// -->
        </div>
        <div class="col-lg-6 col-sm-12 order-3 order-lg-2">
          <form action="#" class="search">
            <div class="input-group w-100">
						<select class="custom-select border-right"  name="category_name">
								<option value="">All type</option><option value="codex">Special</option>
								<option value="comments">Only best</option>
								<option value="content">Latest</option>
						</select>
					    <input type="text" class="form-control" placeholder="Search">
					    
					    <div class="input-group-append">
					      <button class="btn btn-grey" type="submit">
					        <i class="fa fa-search"></i> Search
					      </button>
					    </div>
				    </div>
          </form>
          <!-- search-wrap .end// -->
        </div>
        <!-- col.// -->
        <div class="col-lg-3 col-sm-6 col-8 order-2 order-lg-3">
          <div class="d-flex justify-content-end mb-3 mb-lg-0">
            <div class="widget-header">
              <div class="itemside">
                <div class="aside">
                  <i class="icon-xs bg-red rounded-circle fa fa-check text-white"></i>
                </div>
                <div class="info">
                  <small class="text-muted">Choose the product here</small>
                  <p>Purchase safely on Amazon</p>
                </div>
              </div>
            </div>
          </div>
          <!-- widgets-wrap.// -->
        </div>
        <!-- col.// -->
      </div>
      <!-- row.// -->
    </div>
    <!-- container.// -->
  </section>
  <!-- header-main .// -->
</template>

<style scoped lang="scss">
@import '@/assets/scss/variables.scss';
@import url('https://fonts.googleapis.com/css2?family=Norican&display=swap');

.brand-wrap {
  font-family: 'Norican', cursive;
  font-size:35px;
  color: $dgrey;
}
.header-main {
  padding-top:25px;
  padding-bottom:25px;
  background:white;
  border-top:3px solid $dred;
}
.aside {
  padding-top:8px;
}
.bg-red {
  background: $red;
}

</style>