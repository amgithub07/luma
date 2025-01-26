<script setup>

</script>

<template>
    <div id="Articles" class="articles">
        <div class="container py-15">
            <div class="mb-11 text-center text-white">
                <p class="mb-8 fw-bold"><i class="bi bi-stars"></i>流光亮點</p>
                <h3 class="fw-bold fs-1 mb-8">以人為本服務體驗</h3>
                <p class="description-area mx-auto">
                    以創新設計牽引視覺焦點，用精準洞察打動人心，將品牌的願景化作直觀難忘的數位體驗。
                </p>
            </div>
            <div class="row">
                <div class="col-12 col-lg-4">
                    <div class="card border-0 rounded-0 bg-transparent">
                        <img src="../../assets/images/highlights-01.jpg" class="card-img-top" alt="突破創新" />
                        <div class="card-body text-white">
                            <h5 class="card-title fw-bold fs-3 mb-8">突破創新</h5>
                            <div>
                                我們融合尖端技術與前瞻設計，為您的品牌打造突破性的互動體驗。結合微動畫設計，讓用戶每次訪問都感到新鮮且愉悅，進一步提升品牌吸引力。
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-12 col-lg-4">
                    <div class="card border-0 rounded-0 bg-transparent">
                        <img src="../../assets/images/highlights-02.jpg" class="card-img-top" alt="以人為本" />
                        <div class="card-body text-white">
                            <h5 class="card-title fw-bold fs-3 mb-8">以人為本</h5>
                            <div>
                                每一個細節都以用戶為中心設計，確保每次訪問都能帶來愉悅且深刻的體驗，更讓用戶與品牌建立長久的情感連結。
                            </div>
                        </div>
                    </div>
                </div>
                <div class=" col-12 col-lg-4">
                    <div class="card border-0 rounded-0 bg-transparent">
                        <img src="../../assets/images/highlights-03.jpg" class="card-img-top" alt="精準執行" />
                        <div class="card-body text-white">
                            <h5 class="card-title fw-bold fs-3 mb-8">精準執行</h5>
                            <div>
                                從需求分析到專案落地，我們運用專業洞察與系統化管理，確保每一步都符合品牌目標。無論是設計、開發還是測試，我們都以效率與品質為核心，幫助您快速實現願景。
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
@import "@/assets/styles/imports/_breakpoint";
@import "@/assets/styles/imports/_colors";
@import "@/assets/styles/imports/_variables";

.articles {
    background-color: #7D5F21;
}

.articles .description-area {
    max-width: 400px;
}

.articles .card-img-top {
    height: 296px;
    object-fit: cover
}
</style>