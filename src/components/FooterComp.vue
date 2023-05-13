<template>
    <!-- Footer -->
    <div class="footer">
        <div class="w-70">
            <div class="up_region__footer d-flex justify-c-between">
                <div class="region_left">
                    <h2>left</h2>
                </div>
                <div class="region_center">
                    <h2>center</h2>
                </div>
                <div class="region_right">
                    <h2>right</h2>
                </div>
            </div>
            <div class="down_region__footer">
                <div class="copyright">© 2020 Landrick. Design with ❤️ by Shreethemes.</div>
                <ul class="credit_card_grid">
                    <li class="creditCard">
                        <img src="/_resources/_imgs/american-ex.png" alt="credit card">
                    </li>
                    <li class="creditCard">
                        <img src="/_resources/_imgs/discover.png" alt="credit card">
                    </li>
                    <li class="creditCard">
                        <img src="/_resources/_imgs/master-card.png" alt="credit card">
                    </li>
                    <li class="creditCard">
                        <img src="/_resources/_imgs/paypal.png" alt="credit card">
                    </li>
                    <li class="creditCard">
                        <img src="/_resources/_imgs/visa.png" alt="credit card">
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "FooterComp",
    data() {
        return {

        }
    }
}
</script>

<style scoped>
.footer {
    width: 100%;
    padding-top: 60px;
    background: #202942;
}

.down_region__footer{
    width: 100%;
    height: 85px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    border-top: 1px solid #26314F;
}

.copyright{
    color: #979FAA;
    font-size: .8rem;
    font-weight: 400;
}

.credit_card_grid{
    display: flex;
    align-items: center;
}

.creditCard{
    width: 36px;
    height: 26px;
    margin-right: 6px;
}

.creditCard img{
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.creditCard:last-child{
    margin-right: 0;
}
</style>