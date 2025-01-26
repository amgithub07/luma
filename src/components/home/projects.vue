<script setup>

</script>

<template>
    <div class="projects container my-15">
        <div class="d-flex justify-content-between align-items-center mb-11">
            <h3 class="fw-bold fs-1 title">成功案例</h3>
            <button class="btn btn-lu-primary px-12 py-6">查看所有項目</button>
        </div>
        <div class="row">
            <div class="col-md-6">
                <div class="card border-0">
                    <img src="../../assets/images/projects-01.png" class="card-img-top" alt="一頁式網站建置" />
                    <div class="card-body border-0">
                        <h5 class="card-title  fw-bold">一頁式網站建置</h5>
                    </div>
                </div>
            </div>
            <div class="col-md-6">
                <div class="card border-0">
                    <img src="../../assets/images/projects-02.png" class="card-img-top" alt="品牌網站建置" />
                    <div class="card-body">
                        <h5 class="card-title fw-bold">品牌網站建置</h5>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
//@import "@/assets/styles/imports/_breakpoint";
@import "@/assets/styles/imports/_colors";
//@import "@/assets/styles/imports/_variables";

.btn-lu-primary {
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