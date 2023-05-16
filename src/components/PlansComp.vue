<template>
    <div class="plans_container">
        <div class="w-70 text-align-center">
            <div class="container_heading">
                <h2 class="headingSection">Our rates for developer from Landrick team</h2>
                <p class="descriptionSection">Start working with <span class="highlight">Landrick</span> that can provide
                    you need to generate awareness, drive traffic, connect.</p>
            </div>
            <div class="container_cards_plan">
                <div v-for="(element, index) in cardsPlan" :key="index" class="plan_card">
                    <div class="badge_best_plan " :class="{ 'activeBadge': element.best }">
                        <img src="/_resources/_imgs/badge_best.svg" alt="badeg best plan" draggable="false">
                    </div>
                    <div class="container_type_plan">
                        <span class="typePlan">{{ element.typePlan }}</span>
                    </div>
                    <div class="info_plan_important">
                        <h2 class="price_plan">&#x24;{{ element.pricePlan }}</h2>
                        <div class="payment_cycle">
                            <p class="payCycle">{{ element.cyclePay }}</p>
                        </div>
                        <p class="info_plan">{{ element.infoPlan }}</p>
                    </div>
                    <div class="container_check">
                        <div class="check_container">
                            <i class="fa-regular fa-circle-check"></i>
                            <span class="titleCheck">Full Access</span>
                        </div>
                        <div class="check_container">
                            <i class="fa-regular fa-circle-check"></i>
                            <span class="titleCheck">Enhanced Security</span>
                        </div>
                        <div class="check_container">
                            <i class="fa-regular fa-circle-check"></i>
                            <span class="titleCheck">Source Files</span>
                        </div>
                        <div class="check_container">
                            <i class="fa-regular fa-circle-check"></i>
                            <span class="titleCheck">1 Domain Free</span>
                        </div>
                        <div class="check_container">
                            <i class="fa-regular fa-circle-check"></i>
                            <span class="titleCheck">Enhanced Security</span>
                        </div>
                    </div>
                    <div class="cta_container">
                        <a class="btn btn_filled" href="#">{{ element.buttonText }}</a>
                    </div>
                    <p class="alert">{{ element.alertMessage }}</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "PlansComp",
    data() {
        return {
            // Array di oggetti nper cards abbonamenti
            cardsPlan: [
                {
                    best: false,
                    typePlan: "Basic",
                    pricePlan: "9.00",
                    cyclePay: "Per month",
                    infoPlan: "All the basics for businesses that are just getting started.",
                    buttonText: "Buy Now",
                    alertMessage: "*No credit card required",
                },
                {
                    best: true,
                    typePlan: "Business",
                    pricePlan: "39.00",
                    cyclePay: "Per month",
                    infoPlan: "Better for growing businesses that want more customers.",
                    buttonText: "Buy Now",
                    alertMessage: "*No credit card required",
                },
                {
                    best: false,
                    typePlan: "Enterprise",
                    pricePlan: "79.00",
                    cyclePay: "Per month",
                    infoPlan: "Advanced features for pros who need more customization.",
                    buttonText: "Buy Now",
                    alertMessage: "*No credit card required",
                },
            ],
        }
    },
}
</script>

<style scoped>
.plans_container {
    width: 100%;
}

.headingSection {
    color: #161C2D;
    font-size: 2rem;
    font-weight: 700;
    margin-bottom: 22px;
}

.descriptionSection {
    color: #8492A6;
    font-size: 1rem;
    font-weight: 500;
    width: 55%;
    margin: 0 auto;
}

.container_cards_plan {
    width: 100%;
    margin-top: 3vw;
    display: grid;
    gap: 1em;
    grid-template-columns: repeat(3, 1fr);
}

.plan_card {
    position: relative;
    width: 100%;
    padding: 20px;
    background: #fff;
    border: 1px solid #E4E9F8;
    box-shadow: 0 2px 2px rgba(173, 181, 189, .2);
    border-radius: 6px;
    text-align: left;
    cursor: pointer;
}

/* .badge_best_plan{
    position: absolute;
    top: 0;
    right: 0;
    padding: 2px 15px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #F17425;
    color: #fff;
    font-size: 1rem;
    font-weight: 500;
} */

.badge_best_plan {
    position: absolute;
    top: -7px;
    right: -7px;
    display: none;
}

.activeBadge {
    display: flex;
}

.badge_best_plan img {
    width: 80px;
}

.container_type_plan {
    margin-bottom: 16px;
}

.typePlan {
    color: #2F55D4;
    background: #EAEEFB;
    font-size: .8rem;
    font-weight: 500;
    padding: 8px 15px;
    border-radius: 30px;
}

.price_plan {
    color: #161C2D;
    font-size: 1.7rem;
    font-weight: 700;
}

.payment_cycle {
    margin-bottom: 16px;
}

.payCycle,
.info_plan {
    color: #8492A6;
    font-size: .8rem;
    font-weight: 500;
}

.container_check {
    width: 100%;
    margin: 22px 0;
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

.cta_container {
    width: 100%;
}

.btn {
    color: #fff;
    background: grey;
    width: 100%;
    font-size: 1rem;
    font-weight: 600;
    padding: 8px 16px;
    border-radius: 6px;
    margin-right: 13px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
}

.btn:last-child {
    margin-right: 0;
}

.btn.btn_filled {
    position: relative;
    color: #fff;
    background: #2F55D4;
    box-shadow: 0 0 3px rgba(47, 86, 212, .5);
    transition: all 200ms ease;
}

.btn_filled:hover {
    background: #2443AC;
}

.alert {
    color: #8492A6;
    font-size: .8rem;
    font-weight: 500;
    margin-top: 16px;
}

@media only screen and (max-width: 1020px) {
    .plans_container {
        padding: 60px 0;
    }

    .descriptionSection {
        width: 100%;
    }

    .container_cards_plan {
        grid-template-columns: repeat(1, 1fr);
    }
}
</style>