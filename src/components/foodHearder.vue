<template>
    <div class="foodHeader">
        <hearder />
        <div class="container mx-auto h-full py-4">
            <nav class="h-full flex justify-between">
                <div>
                    <ul class="flex">
                        <li class="px-3">
                            <a href="" class="text-md uppercase font-bold ">Trang Chủ</a>
                        </li>
                        <li class="px-3">
                            <a href="" class="text-md uppercase font-bold">Thực Đơn</a>
                        </li>
                        <li class="px-3">
                            <a href="" class="text-md uppercase font-bold">Khuyến mãi</a>
                        </li>
                    </ul>
                </div>
                <div class="full logo absolute left-2/4">
                    <a href="" class="h-full">
                        <img src="assets/logofood.png" class="h-full logo_food" alt="">
                    </a>
                </div>
                <div>
                    <ul class="flex">
                        <li class="px-3">
                            <a href="" class="text-md uppercase font-bold ">Giới thiệu</a>
                        </li>
                        <li class="px-3">
                            <a href="" class="text-md uppercase font-bold">Liên hệ</a>
                        </li>
                        <li class="px-3">
                            <a href="" class="text-md uppercase font-bold"><font-awesome-icon icon="fa-solid fa-cart-shopping" />Giỏ Hàng</a>
                        </li>
                    </ul>
                </div>
            </nav>
        </div>
        <bannerFood />
        <bannerImage />
        <menuFood />
        <pizzaFood />
        <productReview />
    </div>
</template>

<script>
import hearder from './hearder.vue'
import bannerFood from './home/bannerFood.vue'
import bannerImage from './home/bannerImage.vue'
import menuFood from './home/menuFood.vue'
import pizzaFood from './home/pizza.vue'
import productReview from './home/product_Reviews.vue';
export default {
name: 'foodHeader',
components:{
    hearder,
    bannerFood,
    bannerImage,
    menuFood,
    pizzaFood,
    productReview

}

}
</script>

<style scoped>
/* .foodHeader{
    height: 70px;
} */
.logo{
    top:10px;
}
.logo_food{
    width: 120px;
}
</style>