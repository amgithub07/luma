<script setup>

</script>

<template>
    <div class="banner hero-bg">
        <div class="container align-items-center justify-content-center d-flex h-100">
            <!---->
            <div class="text-center">
                <div class="title-area mb-8">
                    <h2>用設計創造價值</h2>
                    <h2>網站引領未來體驗</h2>
                </div>
                <div class="description-area">
                    <p>
                        每一個成功的網站背後，都有一個想要與世界對話的品牌故事。我們將品牌與用戶緊密連結，透過創新設計和精準洞察，將您的願景轉化為直觀且令人難忘的數位體驗，幫助品牌在數位時代閃耀光芒。
                    </p>
                </div>
            </div>
            <!---->
        </div>
    </div>
</template>

<style scoped lang="scss">
@import "@/assets/styles/imports/_breakpoint";
@import "@/assets/styles/imports/_colors";
//@import "@/assets/styles/imports/_variables";

.banner.hero-bg {
    background: url('../../assets/images/hero-bg.png') no-repeat center;
    background-size: cover;
    height: 800px;
}

.banner .title-area h2 {
    font-size: 48px;
    font-weight: 700;
    margin-bottom: 1rem;
    color: $lu-primary;

    @include pc {
        font-size: 72px;
    }
}

.banner .description-area {
    max-width: 684px;
}
</style>