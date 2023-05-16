<template>
    <div class="hero_section" id="hero_return">
        <div class="w-70 d-flex flex-d-column justify-c-evenly align-items-center height-100">
            <div class="top_region">
                <div class="region_left">
                    <div class="pins_tag_container">
                        <span class="pin">Development</span>
                    </div>
                    <div class="heading_container">
                        <h1 class="heading">A Complete Devloper Toolset</h1>
                    </div>
                    <div class="description_container">
                        <p class="description">Launch your campaign and benefit from our expertise on designing and managing
                            conversion centered bootstrap4 html page.</p>
                    </div>
                    <div class="cta_container">
                        <a class="btn btn_filled" href="/getstarted">Get Started
                            <i class="fa-solid fa-arrow-right"></i>
                        </a>
                        <a class="btn btn_outline" href="/documentation">Documentation</a>
                    </div>
                    <p class="version">Current Version: v2.6.0</p>
                </div>
                <div class="region_right">
                    <div class="container_image">
                        <div class="background_image"></div>
                    </div>
                </div>
            </div>
            <div class="botttom_region">
                <div class="container_brands">
                    <div class="card_brand">
                        <img src="/_resources/_imgs/amazon.svg" alt="brand image">
                    </div>
                    <div class="card_brand">
                        <img src="/_resources/_imgs/google.svg" alt="brand image">
                    </div>
                    <div class="card_brand">
                        <img src="/_resources/_imgs/lenovo.svg" alt="brand image">
                    </div>
                    <div class="card_brand">
                        <img src="/_resources/_imgs/paypal.svg" alt="brand image">
                    </div>
                    <div class="card_brand">
                        <img src="/_resources/_imgs/shopify.svg" alt="brand image">
                    </div>
                    <div class="card_brand">
                        <img src="/_resources/_imgs/spotify.svg" alt="brand image">
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "HeroComp",
}
</script>

<style scoped>
.hero_section {
    background: #F8F9FC;
    height: calc(100vh - 80px);
}

.top_region {
    display: flex;
    gap: 1em;
    align-items: center;
    justify-content: space-between;
}

.pins_tag_container {
    margin-bottom: 16px;
    display: flex;
    align-items: center;
}

.pin {
    color: #2F55D4;
    font-size: .8rem;
    font-weight: 400;
    padding: 4px 15px;
    border-radius: 30px;
    background: #E4E9F8;
}

.heading_container {
    width: 45%;
    margin-bottom: 16px;
}

.heading {
    color: #161C2D;
    font-size: 2rem;
    font-weight: 700;
}

.description_container {
    width: 63%;
    margin-bottom: 32px;
}

.description {
    color: #8492A6;
    font-size: .8rem;
    font-weight: 500;
}

.cta_container {
    margin-bottom: 12px;
    display: flex;
    align-items: center;
}

.btn {
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

.btn:last-child {
    margin-right: 0;
}

.btn.btn_filled {
    position: relative;
    width: 124px;
    color: #fff;
    background: #2F55D4;
    box-shadow: 0 0 3px rgba(47, 86, 212, .5);
    transition: all 200ms ease;
}

.fa-arrow-right {
    position: absolute;
    right: 0;
    opacity: 0;
    margin-left: 10px;
    transition: all 200ms ease;
}

.btn_filled:hover {
    width: 140px;
    background: #2443AC;
}

.btn_filled:hover .fa-arrow-right {
    opacity: 1;
    transform: translateX(-10px);
}

.btn.btn_outline {
    color: #2F55D4;
    background: transparent;
    border: 1px solid #2F55D4;
    transition: all 200ms ease;
}

.btn_outline:hover {
    background: #2F55D4;
    border: 1px solid #2F55D4;
    color: #fff;
}

.version {
    color: #8492A6;
    font-size: .8rem;
    font-weight: 400;
}

.container_image {
    width: 450px;
    aspect-ratio: 1;
}

.background_image {
    background-image: url(/_resources/_imgs/about.png);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    height: 100%;
}

.container_brands {
    width: 100%;
    border-top: 1px solid #E4E9F8;
    display: grid;
    grid-template-columns: repeat(6, 1fr);
}

.card_brand {
    width: 100%;
    height: 100px;
}

.card_brand img {
    width: 100%;
    height: 100%;
    transform: scale(.5);
}

@media only screen and (max-width: 1020px) {
    .heading_container {
        width: 70%;
    }

    .container_brands {
        grid-template-columns: repeat(3, 1fr);
    }

    .region_right {
        display: none;
    }
}
</style>