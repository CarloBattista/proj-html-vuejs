<template>
    <div class="footer">
        <div class="w-70">
            <div class="up_region__footer d-flex justify-c-between">
                <div class="region_left">
                    <a href="/">
                        <img class="logoSite" src="/_resources/_imgs/logo-light.png" alt="logo site landrick dark">
                    </a>
                    <p class="description">Start working with Landrick that can provide everything you need to generate
                        awareness, drive traffic, connect.</p>
                    <div class="container_socials">
                        <a href="/" class="box_social">
                            <img class="social_icon" src="/_resources/_imgs/facebook-f.svg" alt="icon social">
                        </a>
                        <a href="/" class="box_social">
                            <img class="social_icon" src="/_resources/_imgs/instagram.svg" alt="icon social">
                        </a>
                        <a href="/" class="box_social">
                            <img class="social_icon" src="/_resources/_imgs/twitter.svg" alt="icon social">
                        </a>
                        <a href="/" class="box_social">
                            <img class="social_icon" src="/_resources/_imgs/linkedin-in.svg" alt="icon social">
                        </a>
                    </div>
                </div>
                <div class="region_center">
                    <ul class="lists_footer_row">
                        <li class="heading_list">Company</li>
                        <li class="link_footer">
                            <a href="/">
                                <i class="fa-solid fa-angle-right"></i>
                                About Us
                            </a>
                        </li>
                        <li class="link_footer">
                            <a href="/">
                                <i class="fa-solid fa-angle-right"></i>
                                Services
                            </a>
                        </li>
                        <li class="link_footer">
                            <a href="/">
                                <i class="fa-solid fa-angle-right"></i>
                                Team
                            </a>
                        </li>
                        <li class="link_footer">
                            <a href="/">
                                <i class="fa-solid fa-angle-right"></i>
                                Pricing
                            </a>
                        </li>
                        <li class="link_footer">
                            <a href="/">
                                <i class="fa-solid fa-angle-right"></i>
                                Project
                            </a>
                        </li>
                        <li class="link_footer">
                            <a href="/">
                                <i class="fa-solid fa-angle-right"></i>
                                Careers
                            </a>
                        </li>
                        <li class="link_footer">
                            <a href="/">
                                <i class="fa-solid fa-angle-right"></i>
                                Blog
                            </a>
                        </li>
                        <li class="link_footer">
                            <a href="/">
                                <i class="fa-solid fa-angle-right"></i>
                                Login
                            </a>
                        </li>
                    </ul>
                    <ul class="lists_footer_row">
                        <li class="heading_list">Company</li>
                        <li class="link_footer">
                            <a href="/">
                                <i class="fa-solid fa-angle-right"></i>
                                Terms of Services
                            </a>
                        </li>
                        <li class="link_footer">
                            <a href="/">
                                <i class="fa-solid fa-angle-right"></i>
                                Privacy Policy
                            </a>
                        </li>
                        <li class="link_footer">
                            <a href="/">
                                <i class="fa-solid fa-angle-right"></i>
                                Documentation
                            </a>
                        </li>
                        <li class="link_footer">
                            <a href="/">
                                <i class="fa-solid fa-angle-right"></i>
                                Changelog
                            </a>
                        </li>
                        <li class="link_footer">
                            <a href="/">
                                <i class="fa-solid fa-angle-right"></i>
                                Components
                            </a>
                        </li>
                    </ul>
                </div>
                <div class="region_right">
                    <ul class="lists_footer_row">
                        <li class="heading_list">Newsletter</li>
                        <li class="link_footer" style="width: 65%;">
                            <a href="/">Sign up and receive the latest tips via email.</a>
                        </li>
                    </ul>
                    <div class="container_field_email">
                        <p class="headingEmailSection">Write your email <span class="highlight_red">*</span></p>
                        <div class="container_input">
                            <div class="field_input_hed">
                                <i class="fa-regular fa-envelope"></i>
                                <span class="text_content">Your email:</span>
                            </div>
                            <div class="container_field_input">
                                <input class="inputEmail" type="email">
                            </div>
                        </div>
                        <div class="container_submit">
                            <button type="submit" class="btn_submit">Subscribe</button>
                        </div>
                    </div>
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
}
</script>

<style scoped>
.footer {
    width: 100%;
    padding-top: 60px;
    background: #202942;
}

.up_region__footer{
    gap: 3em;
}

.region_left {
    width: 100%;
}

.logoSite {
    width: 130px;
}

.description {
    color: #ABB3BB;
    font-size: .8rem;
    font-weight: 500;
    margin: 22px 0;
}

.container_socials {
    display: flex;
    align-items: center;
}

.box_social {
    width: 32px;
    height: 32px;
    border-radius: 6px;
    margin-right: 6px;
    background: transparent;
    border: 1px solid #ABB3BB;
    display: flex;
    align-items: center;
    justify-content: center;
}

.box_social:last-child {
    margin-right: 0;
}

.social_icon {
    width: 100%;
    height: 100%;
    transform: scale(.6);
}

.region_center {
    width: 100%;
    display: flex;
    justify-content: space-around;
}

.heading_list {
    color: #fff;
    font-size: 1.2;
    font-weight: 600;
    margin-bottom: 22px;
}

.link_footer {
    margin-bottom: 8px;
    display: flex;
    align-items: center;
    cursor: pointer;
}

.link_footer a {
    color: #979FAA;
    font-size: .8rem;
    font-weight: 500;
}

.link_footer .fa-angle-right {
    margin-right: 6px;
}

.region_right {
    width: 100%;
}

.headingSection {
    color: #fff;
    font-size: 1.2;
    font-weight: 600;
    margin-bottom: 22px;
}
.subHeadingSection {
    color: #979FAA;
    font-size: .8rem;
    font-weight: 500;
}

.container_input{
    width: 100%;
    display: flex;
    align-items: center;
}

.container_field_email{
    margin-top: 22px;
    margin-bottom: 12px;
}

.headingEmailSection{
    color: #979FAA;
    font-size: .8rem;
    font-weight: 400;
}

.field_input_hed{
    width: 65%;
    height: 40px;
    border-top-left-radius: 6px;
    border-bottom-left-radius: 6px;
    display: flex;
    align-items: center;
    padding: 0 20px;
    color: #959DA9;
    background: #27314F;
}

.field_input_hed .fa-envelope{
    font-size: .8rem;
}
.field_input_hed .text_content{
    font-size: .8rem;
}

.field_input_hed .fa-envelope{
    margin-right: 8px;
}

.container_field_input{
    width: 100%;
    height: 40px;
}

.inputEmail{
    width: 100%;
    height: 100%;
    border: none;
    outline: none;
    padding-right: 20px;
    border-top-right-radius: 6px;
    border-bottom-right-radius: 6px;
    background: #27314F;
}

.inputEmail[type=email]{
    color: #979FAA;
    font-size: .8rem;
    font-weight: 600;
}

.container_submit{
    margin-top: 22px;
    width: 100%;
    height: 40px;
}

.btn_submit{
    width: 100%;
    height: 100%;
    border-radius: 6px;
    background: #222E51;
    box-shadow: 0px 3px 2px rgba(35, 51, 99, .5);
    border: none;
    outline: none;
    color: #2F54D2;
    font-size: 1rem;
    font-weight: 600;
    cursor: pointer;
}

.down_region__footer {
    width: 100%;
    height: 85px;
    margin-top: 3vw;
    display: flex;
    align-items: center;
    justify-content: space-between;
    border-top: 1px solid #26314F;
}

.copyright {
    color: #979FAA;
    font-size: .8rem;
    font-weight: 400;
}

.credit_card_grid {
    display: flex;
    align-items: center;
}

.creditCard {
    width: 36px;
    height: 26px;
    margin-right: 6px;
}

.creditCard img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.creditCard:last-child {
    margin-right: 0;
}
</style>