<template>
    <div class="quickstart_container">
        <div class="w-70 text-align-center">
            <div class="container_heading">
                <h4 class="titleSection">Quickstart</h4>
                <h2 class="headingSection">Awesomeisn't it? Let's dive in!</h2>
                <p class="descriptionSection">Start working with <span class="highlight">Landrick</span> that can provide you need to generate awareness, drive traffic, connect.</p>
            </div>
            <div class="container_image">
                <img class="image_quickstart" src="/_resources/_imgs/quickstart-npm.jpg" alt="quickstart">
            </div>
            <div class="container_check">
                <div class="check_container">
                    <i class="fa-regular fa-circle-check"></i>
                    <span class="titleCheck">Organize your data</span>
                </div>
                <div class="check_container">
                    <i class="fa-regular fa-circle-check"></i>
                    <span class="titleCheck">Work with any team</span>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "QuickstartComp",
}
</script>

<style scoped>
.quickstart_container{
    width: 100%;
}

.titleSection{
    color: #2F55D4;
    font-size: 1rem;
    font-weight: 500;
    margin-bottom: 22px;
}

.headingSection{
    color: #161C2D;
    font-size: 2rem;
    font-weight: 700;
    margin-bottom: 22px;
}

.descriptionSection{
    color: #8492A6;
    font-size: 1rem;
    font-weight: 500;
    width: 55%;
    margin: 0 auto;
}

.container_image{
    width: 65%;
    margin: 60px auto 0;
}

.image_quickstart{
    width: 100%;
    margin: 0 auto;
    border-radius: 6px;
    box-shadow: 0 0 3px #000;
}

.container_check{
    width: 65%;
    margin: 0 auto;
    margin-top: 16px;
    display: flex;
    align-items: center;
}

.check_container{
    font-size: 1rem;
    font-weight: 400;
    margin-right: 32px;
    display: flex;
    align-items: center;
}

.check_container:last-child{
    margin-right: 0;
}

.check_container .fa-circle-check{
    color: #2ECA8B;
}

.titleCheck{
    color: #939FB1;
    margin-left: 8px;
}
</style>