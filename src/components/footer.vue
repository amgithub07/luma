<script setup>

</script>

<template>
    <div class="footer">
        <div class="container my-11">
            <div class="row g-10 g-lg-0">
                <div class="col-12 col-lg-4">
                    <div class="mb-8">
                        <img src="../assets/images/logo-lg.png" alt="流光" width="200" height="51"
                            class="d-inline-block align-text-top" />
                    </div>
                    <div class="mb-8">
                        <p class="fs-4 mb-8">info@your-company.com</p>
                        <button class="btn btn-primary btn-line px-5 py-3">加入LINE立即諮詢</button>
                    </div>
                    <div class="d-flex mb-8">
                        <a role="button" class="text-secondary">
                            <img src="../assets/images/facebook.svg" alt="流光" class="" />
                        </a>
                        <a role="button" class="text-secondary">
                            <img src="../assets/images/instagram.svg" alt="流光" class="" />
                        </a>
                        <a role="button" class="text-secondary">
                            <img src="../assets/images/youtube.svg" alt="流光" class="" />
                        </a>
                    </div>

                </div>
                <div class="col-12 col-lg-4">
                    <h5 class="text-lu-primary fw-bold mb-10">服務項目</h5>
                    <ul>
                        <li>
                            <a href="#">一頁式網站建置</a>
                        </li>
                        <li>
                            <a href="#">品牌官網建置</a>
                        </li>
                    </ul>
                </div>
                <div class="col-12 col-lg-4">
                    <h5 class="text-lu-primary fw-bold mb-10">成功案例</h5>
                    <ul>
                        <li>
                            <a href="#">一頁式網站建置</a>
                        </li>
                        <li>
                            <a href="#">品牌官網建置</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="bg-cover bg-center py-8 text-white text-center">
            <p class="mb-0">© 2025 Luma. All Rights Reserved.</p>
        </div>
    </div>
</template>

<style scoped lang="scss">
//@import "@/assets/styles/imports/_breakpoint";
//@import "@/assets/styles/imports/_colors";
//@import "@/assets/styles/imports/_variables";

.footer .btn-line {
    color: white;
    background-color: #07b53b;
    border: #07b53b;

    &:hover,
    &:focus {
        background-color: #07b53b;
        border: #07b53b;
    }
}

.footer ul>li:not(:last-child) {
    margin-bottom: 32px;
}

.footer .bg-cover {
    background-image: linear-gradient(to right, rgba(105, 109, 211, 1) 10%, rgba(52, 55, 152, 1))
}
</style>