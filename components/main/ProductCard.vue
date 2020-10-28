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
				<h5 class="title">Leather Sleeve - Macbook 13’’</h5>
				<div class="price mt-2">$3753.00</div>
			</figcaption>
		</figure>
	</div>
</template>

<style scoped lang="scss">
@import '@/assets/scss/variables.scss';

.card-product-grid {
	border: 1px solid $lgrey;
	border-radius: 5px;
	&:hover {
		box-shadow: none;
		border: 1px solid $red;
	}
}
.title {
	font-size:1.5rem!important;
	font-weight:400;
}


</style>