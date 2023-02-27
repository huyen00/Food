<template>
    <div class="menuFood pb-5 mb-5">
        <div class="container mx-auto">
            <div class="grid grid-cols-3 gap-4">
                <div>
                    <img src="assets/menuFood.png" class="  " alt="...">
                    <div>
                        <ul>
                            <li class="py-2">
                                <a href="" class="font-bold" >Cơm chiên </a>
                            </li>
                            <li class="py-2 border-t-2">
                                <a href="" class="font-bold">Pizza </a>
                            </li>
                            <li class="py-2 border-t-2">
                                <a href="" class="font-bold">Gà rán </a>
                            </li>
                            <li class="py-2 border-t-2">
                                <a href="" class="font-bold">Hải sản </a>
                            </li>
                            <li class="py-2 border-t-2">
                                <a href="" class="font-bold">Món luộc </a>
                            </li>
                            <li class="py-2 border-t-2">
                                <a href="" class="font-bold">Món nướng </a>
                            </li>
                            <li class="py-2 border-t-2">
                                <a href="" class="font-bold">Món xào </a>
                            </li>
                            <li class="py-2 border-t-2">
                                <a href="" class="font-bold">Đặc sản 3 miền </a>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="col-span-2">
                    <div class="grid grid-cols-3 gap-4">
                        <div class="item_menu p-2 group ">
                            <img src="assets/comchien.jpg" alt="">
                            <div class="block mt-2">
                                <a href=""><h2 class="text-black font-bold">Cơm chiên muối é</h2></a>
                                <span class="text-red-500 block  font-bold">150,000</span>
                                <span class="clamp three-lines text-sm my-3">Nhắc đến muối é sẽ làm cho không ít người liên tưởng đến những ngày còn đói ở quê nhà,buổi sáng tờ mờ khi trời đất còn ướt đẫm hơi sương, nấu nồi cơm nóng dỡ theo trong lá chuối hay mo cau khô, gói vốc muối é để ăn cùng, rồi vác cày dắt trâu ra đồng, sau khi cày xong vạt ruộng, mặt trời lên vừa nóng lưng thì đem cơm ra ăn ngay trên bờ, cơm nóng, muối é mằn mặn, thơm nồng, vậy là no bụng….</span>
                            </div>
                            <div class="mt-5 text-center mb-2 group">
                                <a href="" class="bg-yellow-300 font-bold p-2  group-hover:block rounded-md">Thêm vào giỏ hàng</a>
                            </div>
                        </div>
                        <div class="item_menu p-2 group ">
                            <img src="assets/comchien2.jpg" alt="">
                            <div class="block mt-2">
                                <a href=""><h2 class="text-black font-bold">Cơm chiên muối é</h2></a>
                                <span class="text-red-500 block  font-bold">150,000</span>
                                <span class="clamp three-lines text-sm my-3">Nhắc đến muối é sẽ làm cho không ít người liên tưởng đến những ngày còn đói ở quê nhà,buổi sáng tờ mờ khi trời đất còn ướt đẫm hơi sương, nấu nồi cơm nóng dỡ theo trong lá chuối hay mo cau khô, gói vốc muối é để ăn cùng, rồi vác cày dắt trâu ra đồng, sau khi cày xong vạt ruộng, mặt trời lên vừa nóng lưng thì đem cơm ra ăn ngay trên bờ, cơm nóng, muối é mằn mặn, thơm nồng, vậy là no bụng….</span>
                            </div>
                            <div class="mt-5 text-center mb-2 group">
                                <a href="" class="bg-yellow-300 font-bold p-2  group-hover:block rounded-md">Thêm vào giỏ hàng</a>
                            </div>
                        </div>
                        <div class="item_menu p-2 group ">
                            <img src="assets/3.jpg" alt="">
                            <div class="block mt-2">
                                <a href=""><h2 class="text-black font-bold">Cơm chiên muối é</h2></a>
                                <span class="text-red-500 block  font-bold">150,000</span>
                                <span class="clamp three-lines text-sm my-3">Nhắc đến muối é sẽ làm cho không ít người liên tưởng đến những ngày còn đói ở quê nhà,buổi sáng tờ mờ khi trời đất còn ướt đẫm hơi sương, nấu nồi cơm nóng dỡ theo trong lá chuối hay mo cau khô, gói vốc muối é để ăn cùng, rồi vác cày dắt trâu ra đồng, sau khi cày xong vạt ruộng, mặt trời lên vừa nóng lưng thì đem cơm ra ăn ngay trên bờ, cơm nóng, muối é mằn mặn, thơm nồng, vậy là no bụng….</span>
                            </div>
                            <div class="mt-5 text-center mb-2 group">
                                <a href="" class="bg-yellow-300 font-bold p-2  group-hover:block rounded-md">Thêm vào giỏ hàng</a>
                            </div>
                        </div>
                    </div>
                    
                </div>
                
            </div>
            
        </div>
    </div>
</template>

<script>

export default {
name: 'menuFood',


}
</script>

<style scoped>
.menuFood .container{
    max-width: 1080px;
}
.clamp {
    -webkit-box-orient: vertical;
    display: -webkit-box;
    overflow: hidden;
}
.three-lines {
    -webkit-line-clamp: 3;
}
.item_menu{
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
}
</style>