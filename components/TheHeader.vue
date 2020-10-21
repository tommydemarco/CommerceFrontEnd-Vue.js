<template>
  <header class="section-header">
    <the-mid-header></the-mid-header>

    <nav class="navbar navbar-main navbar-expand-lg">
      <div class="container">
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#main_nav3"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="main_nav3">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link pl-0" href="#">
                <strong>All category</strong></a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Fashion</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Supermarket</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Electronics</a>
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link" to="/blog">Blog</nuxt-link>
            </li>
            <li class="nav-item">
              <nuxt-link class="nav-link" to="/terms-of-use">Terms of use</nuxt-link>
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="http://example.com"
                data-toggle="dropdown"
                aria-haspopup="true"
                aria-expanded="false"
                >More</a
              >
              <div class="dropdown-menu">
                <a class="dropdown-item" href="#">Foods and Drink</a>
                <a class="dropdown-item" href="#">Home interior</a>
                <div class="dropdown-divider"></div>
                <a class="dropdown-item" href="#">Category 1</a>
                <a class="dropdown-item" href="#">Category 2</a>
                <a class="dropdown-item" href="#">Category 3</a>
              </div>
            </li>
          </ul>
          <!-- favorites -->
          <div class="widget-header favorites align-right">
						<a href="#" class="widget-view">
							<div class="icon-area">
								<i class="fa fa-heart"></i>
								<span class="notify">3</span>
							</div>
						</a>
					</div>
        </div>
      </div>
    </nav>

  </header>
</template>

<script>
import TheMidHeader from "@/components/TheMidHeader";

export default {
  components: {
    TheMidHeader,
  },
};
</script>

<style scoped lang="scss">
@import '@/assets/scss/variables.scss';

.navbar.navbar-expand-lg {
    background: $dred;
    padding-top:15px;
    padding-bottom:15px;
}
.navbar.navbar-expand-lg a {
    color:$lgrey;
}
.dropdown-menu a.dropdown-item {
    color:$dgrey;
}
.favorites i {
  color:white;
  font-size: 25px;
}

</style>