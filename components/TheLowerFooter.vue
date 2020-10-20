<template>
    <section class="footer-copyright border-top">
		<div class="container">
            <p target="_blank" class="float-right text-muted">
                <a href="#">Privacy & Cookies</a> &nbsp   &nbsp 
                <a href="#">Accessibility</a>
            </p>
            <p> &copy 2020 Company  All rights resetved </p>
		</div>		
	</section>
</template>

<style scoped lang="scss">
    @import '@/assets/scss/variables.scss';
    .footer-copyright {
        background: $dred;
        color: white;
        & a {
            color:white
        }
    }
</style>
