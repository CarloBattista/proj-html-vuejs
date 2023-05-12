<template>
    <div class="buildtools_container">
        <div class="w-70 d-flex justify-c-between align-items-center">
            <div class="region_left">
                <h2 class="headingSection">Build tools and extensive documention</h2>
                <p class="subHeadingSection">You can combine all the Landrick templates into a single one. you can take a
                    component from the Application theme and use it in the Website.</p>
                <div class="container_check">
                    <div class="check_container">
                        <i class="fa-regular fa-circle-check"></i>
                        <span class="titleCheck">Digital Marketing Solutions for Tomorrow</span>
                    </div>
                    <div class="check_container">
                        <i class="fa-regular fa-circle-check"></i>
                        <span class="titleCheck">Our Talented & Experienced Marketing Agency</span>
                    </div>
                    <div class="check_container">
                        <i class="fa-regular fa-circle-check"></i>
                        <span class="titleCheck">Create your own skin to match your brand</span>
                    </div>
                </div>
                <div class="cta_container">
                    <a class="btn btn_filled" href="/getstarted">Read More
                        <i class="fa-solid fa-arrow-right"></i>
                    </a>
                </div>
            </div>
            <div class="region_right">
                <div class="container_image">
                    <div class="background_image"></div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "BuildtoolsComp",
}
</script>

<style scoped>
.buildtools_container {
    width: 100%;
    padding: 6vw 0;
}

.buildtools_container .w-70{
    gap: 1em;
}

.headingSection{
    color: #161C2D;
    font-size: 2rem;
    font-weight: 700;
    margin-bottom: 16px;
    width: 45%;
}

.subHeadingSection{
    color: #8492A6;
    font-size: 1rem;
    font-weight: 500;
    width: 60%;
}

.container_check {
    margin-top: 32px;
}

.check_container {
    font-size: 1rem;
    font-weight: 400;
    margin-bottom: 6px;
}

.check_container:last-child {
    margin-bottom: 0;
}

.check_container .fa-circle-check {
    color: #2F55D4;
}

.titleCheck {
    color: #939FB1;
    margin-left: 8px;
}

.cta_container{
    margin-top: 32px;
}

.btn{
    color: #fff;
    background: grey;
    font-size: 1rem;
    font-weight: 400;
    padding: 8px 16px;
    border-radius: 6px;
    margin-right: 13px;
    display: flex;
    align-items: center;
    cursor: pointer;
}

.btn:last-child{
    margin-right: 0;
}

.btn.btn_filled{
    position: relative;
    width: 118px;
    color: #fff;
    background: #2F55D4;
    box-shadow: 0 0 3px rgba(47, 86, 212, .5);
    transition: all 100ms ease;
}

.fa-arrow-right{
    position: absolute;
    right: 0;
    opacity: 0;
    margin-left: 10px;
    transition: all 100ms ease;
}

.btn_filled:hover{
    width: 135px;
    background: #2443AC;
}

.btn_filled:hover .fa-arrow-right{
    opacity: 1;
    transform: translateX(-10px);
}

.container_image{
    width: 450px;
    aspect-ratio: 1;
}

.background_image{
    background-image: url(/_resources/_imgs/1.png);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    height: 100%;
}
</style>