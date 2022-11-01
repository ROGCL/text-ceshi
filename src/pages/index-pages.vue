<template>
  <div>
    <!-- 大图层 -->
    <div class="bigimg">
        <!-- 头像框 -->
        <div class="head">
            <!-- 头像图片，内置小盒子 -->
            <div class="headimg"></div>
        </div>
        <span>李航</span>
        <!-- 照片图层 -->
        <div class="photo">
            <!-- 照片框 -->
            <div class="potota"></div>
            
            
        </div>
        <!-- 回形针 -->
        <div class="quare"></div>
        <!-- 上传按钮,弹窗 -->
        <div class="submit" @click="turn"></div>
    </div>
  </div>
</template>

<script>
import { Dialog } from 'vant'
export default {
methods:{
    turn(){
       Dialog.alert({
        title:'你是傻的吗???',
        message:'功能还未做完敬请期待'
       }) 
    }
}
}
</script>

<style scoped>
 .bigimg{
    width: 100%;
    height: 19.9467rem;
    background-image: url('@/assets/img/5.png');
    background-repeat: no-repeat;
    background-size: 100% 100%;
 }
 .photo{
    position: absolute;
    left: .84rem;
    top: 4.84rem;
    width: 8.32rem;
    height: 9.92rem;
    background-image: url('@/assets/img/2.png');
    background-repeat: no-repeat;
    background-size: 100% 100%;
 }
 .potota{
    position: absolute;
    left: .4933rem;
    top:.36rem;
    width: 7.2267rem;
    height: 7.2267rem;
    background-image: url('@/assets/img/8.jpg');
    background-repeat: no-repeat;
    background-size: 100% 100%;
 }
 .quare{
    position: absolute;
    right: 0;
    top: 12.4267rem;
    width: 2.5333rem;
    height: 1.8533rem;
    background-image: url('@/assets/img/3.png');
    background-repeat: no-repeat;
    background-size: 100% 100%;
 }
 .submit{
    position: absolute;
    left: 2.7733rem;
    top: 14.9867rem;
    width: 4.56rem;
    height: 1.52rem;
    background-image: url('@/assets/img/4.png');
    background-repeat: no-repeat;
    background-size: 100% 100%;
 }
 .bigimg span{
    position: absolute;
    left: 3.2133rem;
    top: 3.0533rem;
    font-size: .4267rem;
    color: #1f1915;
 }
 .head{
    position: absolute;
    left: .6533rem;
    top: 1.88rem;
    width: 2.0933rem;
    height: 2.1067rem;
    background-image: url('@/assets/img/6.png');
    background-repeat: no-repeat;
    background-size: 100% 100%;
 }
 .headimg{
    position: absolute;
    left: .2667rem;
    top: .28rem;
    width: 1.56rem;
    height: 1.56rem;
    border-radius: 50%;
    background-image: url('@/assets/img/7.jpg');
    background-repeat: no-repeat;
    background-size: 100% 100%;
 }
</style>
<style>
*{
    margin: 0;
    padding: 0;
    list-style: none;
}
/* body{
    position: relative;
    width: 100%;
    height: 100vh;
} */
</style>