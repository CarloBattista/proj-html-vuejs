<template>
    <div class="header">
        <div class="w-70">
            <div class="container_section">
                <div class="container_heading">
                    <h2 class="heading">Key Features</h2>
                    <p class="subHeading">Start working with <span class="highlight">Landrick</span> that can provide everything you need to generate awareness, drive traffic, connect.</p>
                </div>
                <div class="container_cards">
                    <div class="card_features">
                        <div class="box_icon">
                            <i class="fa-regular fa-image"></i>
                        </div>
                        <div class="infoCard">
                            <h3 class="headingCard">Modular</h3>
                            <p class="subHeadingCard">Composed in a pseudo-Latin language which more or Less corresponds.</p>
                        </div>
                        <a href="/readmore">Read More
                            <i class="fa-solid fa-angle-right"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "FeaturesComp",
    data() {
        return {

        }
    }
}
</script>

<style scoped>
.container_section{
    width: 100%;
    padding: 6vw 0;
}

.heading{
    color: #161C2D;
    font-size: 2rem;
    font-weight: 700;
}
</style>