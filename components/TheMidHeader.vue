<template>
  <section class="header-main border-bottom">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-lg-3 col-4">
          <a href="#" class="brand-wrap">
            <img class="logo" src="/assets/images/logo.png" />
          </a>
          <!-- brand-wrap.// -->
        </div>
        <div class="col-lg-6 col-sm-12 order-3 order-lg-2">
          <form action="#" class="search">
            <div class="input-group w-100">
              <select class="custom-select" name="category_name">
                <option value="">All type</option>
                <option value="codex">Special</option>
                <option value="comments">Only best</option>
                <option value="content">Latest</option>
              </select>
              <input
                type="text"
                class="form-control"
                style="width: 60%"
                placeholder="Search"
              />

              <div class="input-group-append">
                <button class="btn btn-primary" type="submit">
                  <i class="fa fa-search"></i>
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
                  <small class="text-muted">Choose here</small>
                  <p>Purchase on Amazon</p>
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

.header-main {
  padding-top:20px;
  padding-bottom:20px;
}
.aside {
  padding-top:8px;
}
.bg-red {
  background: $red;
}

</style>