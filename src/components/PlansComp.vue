<template>
    <div class="plans_container">
        <div class="w-70 text-align-center">
            <div class="container_heading">
                <h2 class="headingSection">Our rates for developer from Landrick team</h2>
                <p class="descriptionSection">Start working with <span class="highlight">Landrick</span> that can provide
                    you need to generate awareness, drive traffic, connect.</p>
            </div>
            <div class="container_cards_plan">
                <div class="plan_card">
                    <div class="container_type_plan">
                        <span class="typePlan">Basic</span>
                    </div>
                    <div class="info_plan_important">
                        <h2 class="price_plan">&#x24;9.00</h2>
                        <div class="payment_cycle">
                            <p class="payCycle">Per month</p>
                        </div>
                        <p class="info_plan">All the basics for businesses that are just getting started.</p>
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
                        <a class="btn btn_filled" href="/getstarted">Buy Now</a>
                    </div>
                    <p class="alert">*No credit card required</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "PlansComp",
}
</script>

<style scoped>
.quickstart_container {
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
    border-radius: 6px;
    text-align: left;
    cursor: pointer;
}

.container_type_plan{
    margin-bottom: 16px;
}

.typePlan{
    color: #2F55D4;
    background: #EAEEFB;
    font-size: .8rem;
    font-weight: 500;
    padding: 8px 15px;
    border-radius: 30px;
}

.price_plan{
    color: #161C2D;
    font-size: 1.7rem;
    font-weight: 700;
}

.payment_cycle{
    margin-bottom: 16px;
}

.payCycle,
.info_plan{
    color: #8492A6;
    font-size: .8rem;
    font-weight: 500;
}

.container_check{
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

.cta_container{
    width: 100%;
}

.btn{
    color: #fff;
    background: grey;
    width: 100%;
    font-size: 1rem;
    font-weight: 400;
    padding: 8px 16px;
    border-radius: 6px;
    margin-right: 13px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
}

.btn:last-child{
    margin-right: 0;
}

.btn.btn_filled{
    position: relative;
    color: #fff;
    background: #2F55D4;
    box-shadow: 0 0 3px rgba(47, 86, 212, .5);
    transition: all 100ms ease;
}

.btn_filled:hover{
    background: #2443AC;
}

.alert{
    color: #8492A6;
    font-size: .8rem;
    font-weight: 500;
    margin-top: 16px;
}
</style>