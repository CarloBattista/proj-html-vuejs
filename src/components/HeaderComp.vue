<template>
    <div class="header">
        <div class="w-60 d-flex align-items-center justify-c-between">
            <div class="region_left">
                <a href="/">
                    <img class="logoSite" src="/_resources/_imgs/logo-dark.png" alt="logo site landrick dark">
                </a>
            </div>
            <div class="region_center"></div>
            <div class="region_right"></div>
        </div>
    </div>
</template>

<script>
export default {
    name: "HeaderComp"
}
</script>

<style scoped>
.header {
    position: sticky;
    z-index: 999;
    width: 100%;
    height: 80px;
    display: flex;
    align-items: center;
}

.logoSite{
    width: 130px;
}
</style>