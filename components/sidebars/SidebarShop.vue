<template>
    <div class="card">
      <article class="filter-group">
        <header class="card-header">
          <a href="#" data-toggle="collapse" data-target="#collapse_aside1">
            <i class="icon-control fa fa-chevron-down"></i>
            <h6 class="title">Rating</h6>
          </a>
        </header>
        <div class="filter-content collapse show" id="collapse_aside1">
          <div class="card-body">
            <label class="custom-control custom-checkbox">
              <input type="checkbox" checked="" class="custom-control-input" />
              <div class="custom-control-label">Best</div>
            </label>

            <label class="custom-control custom-checkbox">
              <input type="checkbox" checked="" class="custom-control-input" />
              <div class="custom-control-label">Good</div>
            </label>

            <label class="custom-control custom-checkbox">
              <input type="checkbox" checked="" class="custom-control-input" />
              <div class="custom-control-label">Normal</div>
            </label>

            <label class="custom-control custom-checkbox">
              <input type="checkbox" checked="" class="custom-control-input" />
              <div class="custom-control-label">Not good</div>
            </label>
          </div>
          <!-- card-body.// -->
        </div>
      </article>
      <!-- filter-group  .// -->
      <article class="filter-group">
        <header class="card-header">
          <a href="#" data-toggle="collapse" data-target="#collapse_aside2">
            <i class="icon-control fa fa-chevron-down"></i>
            <h6 class="title">Price</h6>
          </a>
        </header>
        <div class="filter-content collapse show" id="collapse_aside2">
          <div class="card-body">
            <input
              type="range"
              class="custom-range"
              min="0"
              max="100"
              name=""
            />
            <div class="form-row">
              <div class="form-group col-md-6">
                <label>Min</label>
                <input class="form-control" placeholder="$0" type="number" />
              </div>
              <div class="form-group text-right col-md-6">
                <label>Max</label>
                <input
                  class="form-control"
                  placeholder="$1,0000"
                  type="number"
                />
              </div>
            </div>
          </div>
          <!-- card-body.// -->
        </div>
      </article>
      <!-- filter-group  .// -->
      <article class="filter-group">
        <header class="card-header">
          <a href="#" data-toggle="collapse" data-target="#collapse_aside3">
            <i class="icon-control fa fa-chevron-down"></i>
            <h6 class="title">Size</h6>
          </a>
        </header>
        <div class="filter-content collapse show" id="collapse_aside3">
          <div class="card-body">
            <label class="checkbox-btn">
              <input type="checkbox" />
              <span class="btn btn-light"> XS </span>
            </label>

            <label class="checkbox-btn">
              <input type="checkbox" />
              <span class="btn btn-light"> SM </span>
            </label>

            <label class="checkbox-btn">
              <input type="checkbox" />
              <span class="btn btn-light"> LG </span>
            </label>

            <label class="checkbox-btn">
              <input type="checkbox" />
              <span class="btn btn-light"> XXL </span>
            </label>
          </div>
          <!-- card-body.// -->
        </div>
      </article>
      <!-- filter-group  .// -->
      <article class="filter-group">
        <header class="card-header">
          <a href="#" data-toggle="collapse" data-target="#collapse_aside4">
            <i class="icon-control fa fa-chevron-down"></i>
            <h6 class="title">Rating</h6>
          </a>
        </header>
        <div class="filter-content collapse show" id="collapse_aside4">
          <div class="card-body">
            <label class="custom-control custom-checkbox">
              <input type="checkbox" checked="" class="custom-control-input" />
              <div class="custom-control-label">Best</div>
            </label>

            <label class="custom-control custom-checkbox">
              <input type="checkbox" checked="" class="custom-control-input" />
              <div class="custom-control-label">Good</div>
            </label>

            <label class="custom-control custom-checkbox">
              <input type="checkbox" checked="" class="custom-control-input" />
              <div class="custom-control-label">Normal</div>
            </label>

            <label class="custom-control custom-checkbox">
              <input type="checkbox" checked="" class="custom-control-input" />
              <div class="custom-control-label">Not good</div>
            </label>
          </div>
          <!-- card-body.// -->
        </div>
      </article>
      <!-- filter-group  .// -->
    </div>
</template>

<style scoped lang="scss">
@import '@/assets/scss/variables.scss';

.card-header a {
  color:$dgrey;
  &:hover {
    color:$mgrey;
  }
}

</style>