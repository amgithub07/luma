<script setup>

</script>

<template>
    <div id="Contact" class="banner-third hero-bg">
        <div class="container align-items-center justify-content-start d-flex h-100">
            <!---->
            <div class="text-start text-white">
                <h3 class="mb-2">準備好讓您的品牌閃耀嗎？</h3>
                <h3 class="">立即行動，打造專屬品牌官網！</h3>
                <div class="mt-8">
                    <button class="btn btn-lu-primary px-12 py-6">填寫需求單</button>
                </div>
            </div>
            <!---->
        </div>
    </div>
</template>

<style scoped lang="scss">
//@import "@/assets/styles/imports/_breakpoint";
@import "@/assets/styles/imports/_colors";
//@import "@/assets/styles/imports/_variables";

.banner-third.hero-bg {
    background: linear-gradient(rgba(174, 145, 67, 0.8), rgba(125, 95, 33, 0.8)), url('../../assets/images/hero-bg3.jpg') no-repeat center;
    background-size: cover;
    height: 480px;
}

.banner-third .btn-lu-primary {
    color: white;
    background-color: $lu-primary;
    border: $lu-primary;
    border-radius: 1000px;

    &:hover,
    &:focus,
    &:active {
        color: white !important;
        background-color: $lu-primary-dark !important;
        border: $lu-primary-dark !important;
    }
}
</style>