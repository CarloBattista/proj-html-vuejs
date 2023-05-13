<template>
    <a href="#hero_return">
        <div class="box_button_top">
            <i class="fa-solid fa-arrow-up"></i>
        </div>
    </a>
</template>

<script>
export default {
    name: "ReturnOnTopComp",
    data() {
        return {
            
        }
    },
}
</script>

<style scoped>
.box_button_top {
    position: fixed;
    z-index: 999999;
    bottom: 30px;
    right: 30px;
    width: 35px;
    height: 35px;
    border-radius: 6px;
    border: none;
    outline: none;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #2F55D4;
    box-shadow: 0 2px 2px #2F55D4;
    ;
    cursor: pointer;
    transition: all .5s ease;
}

.box_button_top:hover {
    transform: rotate(45deg);
    background: #2443AC;
}

.box_button_top .fa-arrow-up {
    color: #fff;
    transition: all .5s ease;
}

.box_button_top:hover .fa-arrow-up {
    transform: rotate(-45deg);
}
</style>