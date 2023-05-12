<template>
    <div class="hero_section">
        <div class="w-70">
            <div class="top_region">
                <div class="region_left">
                    <div class="pins_tag_container">
                        <span class="pin">Development</span>
                    </div>
                    <div class="heading_container">
                        <h1 class="heading">A Complete Devloper Toolset</h1>
                    </div>
                    <div class="description_container">
                        <p class="description">Launch your campaign and benefit from our expertise on designing and managing conversion centered bootstrap4 html page.</p>
                    </div>
                    <div class="cta_container">
                        <a class="btn btn_filled" href="/getstarted">Get Started</a>
                        <a class="btn btn_outline" href="/documentation">Documentation</a>
                    </div>
                    <p class="version">Current Version: v2.6.0</p>
                </div>
                <div class="region_right"></div>
            </div>
            <div class="botttom_region"></div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "HeroComp",
    }
</script>

<style scoped>
.hero_section{
    background: #F8F9FC;
}

.top_region{
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.pins_tag_container{
    margin-bottom: 16px;
    display: flex;
    align-items: center;
}

.pin{
    color: #2F55D4;
    font-size: .8rem;
    font-weight: 400;
    padding: 4px 15px;
    border-radius: 30px;
    background: #E4E9F8;
}
</style>