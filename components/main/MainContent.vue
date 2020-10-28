<template>

    <main>
        <header>
            <div class="container">
                <div class="row initial-p text-center py-5">
                    <h1 id="tpage" class="mb-0">{{pageTitle}}</h1>
                    <p id="spage">{{pageSubtitle}}</p>
                </div> 
            </div>
        </header>

        <!-- main content -->
        <div class="container">
            <div class="row py-4">

                <!-- sidebar -->
                <aside class="col-md-3 pt-2" v-if="aside">
                    <slot name="sidebar"></slot>
                </aside>

                <!-- products -->
                <section :class="'col-md-' + mainDivClass + ' pt-2'">
                    <div class="row">
                        <slot name="content"></slot>
                    </div>
                </section>

            </div>
        </div>

        <!-- additional components -->
        <slot name="additional"></slot>

    </main>
</template>

<script>

export default {
    props: {
        pageTitle: {
            type: String,
            required: true
        },
        pageSubtitle: {
            type: String,
            required: true
        },
        aside: {
            type: Boolean,
            default:false
        },
        half: {
           type: Boolean,
           default:false 
        }
    },
    computed: {
        mainDivClass() {
            if(this.aside || (!this.aside && !this.half)) {
                return '9'
            } else {
                return '12'
            }
        }
    }
}
</script>

<style scoped lang="scss">
@import '@/assets/scss/variables.scss';
.initial-p {
    display:block
}
header {
    background: url('../../assets/images/header-background.jpeg');
}
header {
    color:white!important;
}
</style>