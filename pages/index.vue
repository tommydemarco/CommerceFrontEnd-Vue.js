<template>
  <main-content
    pageTitle="Our Hottest Deals"
    pageSubtitle="discover the best products with amazing discounts"
    aside>
    <template #sidebar>

    </template>
    <template #content>
      
    </template>
  </main-content>
</template>

<script>
import MainContent from '@/components/main/MainContent.vue';
import SidebarShop from '@/components/sidebars/SidebarShop.vue';
import ProductCard from '@/components/main/ProductCard.vue';

export default {
  components: {
    MainContent,
    SidebarShop,
    ProductCard
  }
}
</script>

<style>

</style>
