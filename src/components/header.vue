<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
    <nav class="navbar navbar-expand-lg fixed-top navbar-light bg-light">
        <div class="container">
            <RouterLink class="navbar-brand" :to="{ name: 'home' }">
                <h1>
                    <img src="../assets/images/logo-lg.png" alt="Luma流光" width="200" height="51"
                        class="d-inline-block align-text-top" />
                </h1>
            </RouterLink>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <RouterLink class="nav-link" :to="{ name: 'home', hash: '#Services' }">服務項目</RouterLink>
                    </li>
                    <li class="nav-item">
                        <RouterLink class="nav-link" :to="{ name: 'home', hash: '#About' }">關於我們</RouterLink>
                    </li>
                    <li class="nav-item">
                        <RouterLink class="nav-link" :to="{ name: 'home', hash: '#Articles' }">精選文章</RouterLink>
                    </li>
                    <li class="nav-item">
                        <RouterLink class="nav-link" :to="{ name: 'home', hash: '#Contact' }">聯絡我們</RouterLink>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<style scoped lang="scss">
@import "@/assets/styles/imports/_breakpoint";
//@import "@/assets/styles/imports/_colors";
//@import "@/assets/styles/imports/_variables";

.navbar ul>li>a {
    font-weight: 600;
}

.navbar ul>li+li {
    margin-left: 0;

    @include pc {
        margin-left: 24px;
    }
}
</style>
