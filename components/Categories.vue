<template>
  <div class="categories">
    <div class="title">
      <div class="divider"></div>
      <strong>Featured categories</strong>
      <div class="divider"></div>
    </div>
    <div class="category-list">
      <CategoryCard
        v-for="category in categories"
        :category="category"
        :key="categories.indexOf(category)"
      />
    </div>
    <div></div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      categories: [
        {
          image:
            'https://www.watsons.com.tr/medias/sys_master/root/h35/h7c/9020509683742/toni&guy2/toni-guy2.jpg',
          title: 'Personal Care',
          text: 'Lorem ipsum dolor sit amet consectetu elit aliquam',
        },
        {
          image:
            'https://www.watsons.com.tr/medias/sys_master/root/h04/h90/9019999453214/lorealskin-1/lorealskin-1.jpg',
          title: 'Skin Care',
          text: 'Lorem ipsum dolor sit amet consectetu elit aliquam',
        },
        {
          image:
            'https://www.watsons.com.tr/medias/sys_master/prd-images/h59/h06/8909166575646/prd-front-166349_365x385/prd-front-166349-365x385.jpeg',
          title: 'Make - Up',
          text: 'Lorem ipsum dolor sit amet consectetu elit aliquam',
        },
        {
          image:
            'https://www.watsons.com.tr/medias/sys_master/prd-images/h97/h4a/8900241391646/prd-front-129720_365x385/prd-front-129720-365x385.jpeg',
          title: 'Mother & Baby',
          text: 'Lorem ipsum dolor sit amet consectetu elit aliquam',
        },
      ],
    }
  },
}
</script>
