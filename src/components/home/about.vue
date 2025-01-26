<script setup>

</script>

<template>
    <div id="About" class="about hero-bg">
        <div class="container align-items-center justify-content-start d-flex h-100">
            <!---->
            <div class="text-start">
                <p class="text-lu-accent-light mb-8">歡迎來到我們的團隊！</p>
                <div class="description-area mb-8">
                    <p class="fs-4 text-white lh-base">
                        我們專注於高品質網站開發團隊，致力於提供量身定制的解決方案，實現您的品牌願景。
                        無論是網頁設計、前端開發、後端系統建設，還是專案管理，我們都能提供精確的解決方案。
                    </p>
                </div>
                <div>
                    <button class="btn btn-lu-accent px-12 py-6">查看更多</button>
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

.about.hero-bg {
    background: url('../../assets/images/hero-bg2.png') no-repeat center;
    background-size: cover;
    height: 480px;
}

.about .description-area {
    max-width: 800px;
}

.about .btn-lu-accent {
    color: white;
    background-color: $lu-accent;
    border: $lu-accent;
    border-radius: 1000px;

    &:hover,
    &:focus,
    &:active {
        color: white !important;
        background-color: $lu-accent-dark !important;
        border: $lu-accent-dark !important;
    }
}
</style>