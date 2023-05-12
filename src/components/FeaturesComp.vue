<template>
    <div class="features_container">
        <div class="w-70">
            <div class="container_section">
                <div class="container_heading">
                    <h2 class="heading">Key Features</h2>
                    <p class="subHeading">Start working with <span class="highlight">Landrick</span> that can provide
                        everything you need to generate awareness, drive traffic, connect.</p>
                </div>
                <div class="container_cards">
                    <div v-for="(element, index) in cardfeatures" :key="index" class="card_features">
                        <div class="background_hover_image">
                            <i :class="element.iconCard"></i>
                        </div>
                        <div class="info_card">
                            <div class="box_icon">
                                <i :class="element.iconCard"></i>
                            </div>
                            <div class="infoCard">
                                <h3 class="headingCard">{{ element.titleCard }}</h3>
                                <p class="subHeadingCard">{{ element.subHeading }}</p>
                            </div>
                            <a class="readmore_cta" href="/readmore">Read More
                                <i class="fa-solid fa-angle-right"></i>
                            </a>
                        </div>
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
            // Array di oggetti per card features
            cardfeatures: [
                {
                    iconCard: "fa-regular fa-image",
                    titleCard: "Modular",
                    subHeading: "Composed in a pseudo-Latin language which more or Less corresponds.",
                },
                {
                    iconCard: "fa-regular fa-image",
                    titleCard: "Responsive",
                    subHeading: "Composed in a pseudo-Latin language which more or Less corresponds.",
                },
                {
                    iconCard: "fa-solid fa-qrcode",
                    titleCard: "Customizable",
                    subHeading: "Composed in a pseudo-Latin language which more or Less corresponds.",
                },
                {
                    iconCard: "fa-solid fa-maximize",
                    titleCard: "Scalable",
                    subHeading: "Composed in a pseudo-Latin language which more or Less corresponds.",
                },
            ],
        }
    }
}
</script>

<style scoped>
.features_container{
    width: 100%;
}
.container_section {
    width: 100%;
    padding: 6vw 0;
}

.heading {
    color: #161C2D;
    font-size: 2rem;
    font-weight: 700;
    margin-bottom: 16px;
}

.subHeading {
    color: #8492A6;
    font-size: 1rem;
    font-weight: 500;
    width: 60%;
}

.container_cards {
    padding: 3vw 0;
    display: grid;
    gap: 1em;
    grid-template-columns: repeat(4, 1fr);
}

.card_features {
    position: relative;
    width: 100%;
    padding: 20px;
    background: #fff;
    border: 1px solid #E4E9F8;
    border-radius: 6px;
    cursor: pointer;
    transition: transform 300ms ease;
}

.card_features:hover {
    transform: translateY(-10px);
}

.background_hover_image {
    position: absolute;
    z-index: 1;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    border-radius: 6px;
    overflow: hidden;
    opacity: 0;
    transition: opacity 300ms ease;
}

.card_features:hover .background_hover_image {
    opacity: .1;
}

.background_hover_image i {
    color: #2F55D4;
    font-size: 12rem;
    transform: translateX(20px);
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: flex-end;
}

.info_card {
    position: relative;
    z-index: 5;
}

.box_icon {
    width: 62px;
    height: 62px;
    border-radius: 6px;
    margin-bottom: 22px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #EAEEFB;
}

.box_icon i {
    color: #2F55D4;
    font-size: 1.4rem;
}

.headingCard {
    color: #3C4858;
    font-size: 1.2rem;
    font-weight: 700;
    margin-bottom: 12px;
}

.subHeadingCard {
    color: #8492A6;
    font-size: .8rem;
    font-weight: 500;
    margin-bottom: 22px;
}

.readmore_cta {
    color: #2F55D4;
    font-size: 1rem;
    font-weight: 600;
    display: flex;
    align-items: center;
}

.readmore_cta .fa-angle-right {
    margin-left: 6px;
}
</style>