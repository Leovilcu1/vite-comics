<script>
import AppFooterTop from "./AppFooterTop.vue";
import AppFooterMidle from './AppFooterMidle.vue';
import AppFooterBottom from './AppFooterBottom.vue';
export default{
    name: "AppFooter",
    components:{
        AppFooterTop,
        AppFooterMidle,
        AppFooterBottom
    }
}
</script>

<template>
    <footer>
        <AppFooterTop/>
        <AppFooterMidle/>
        <AppFooterBottom/>
    </footer>
</template>

<style lang="scss" scoped>
 footer{
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: 100% auto;
    background-repeat: no-repeat;
 }
</style>