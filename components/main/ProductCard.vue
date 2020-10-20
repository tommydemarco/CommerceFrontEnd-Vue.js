<template>
    <div class="col-xs-6 col-md-4">
		<figure class="card card-product-grid">
			<div class="img-wrap"> 
				<img src="../../assets/images/items/6.jpg">
				<span class="topbar">
					<a href="#" class="float-right"><i class="fa fa-heart"></i></a>
				</span>
			</div>
			<figcaption class="info-wrap">
				<a href="#" class="title">Leather Sleeve - Macbook 13’’</a>
				<div class="price mt-2">$3753.00</div> <!-- price-wrap.// -->
				<ul class="buttons-ul pt-3">
					<li><a href="#" class="btn btn-red">Buy on Amazon</a></li>
					<li class="ml-2"><a href="#" class="btn btn-grey">Details</a></li>
				</ul>
			</figcaption>
		</figure>
	</div>
</template>

<style scoped lang="scss">
@import '@/assets/scss/variables.scss';
.card {
	& .img-wrap {
		border-top: 3px solid $red;
		border-radius: 0px;
	}
	border-radius:0px;
	& figcaption {
		border-top: 3px solid $red;
	}
}
.buttons-ul {
	list-style-type: none;
	padding-left:0px!important;
	margin-bottom:0px;
	& li {
		list-style-type: none;
		display:inline-block;
	}
}

</style>