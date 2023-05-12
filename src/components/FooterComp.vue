<template>
    <!-- Footer -->
    <div class="footer">
        <div class="w-70 d-flex align-items-center justify-c-between">
            <div class="up_region__footer">
                <div class="region_left">
                    <div class="container_logo">
                        <a href="/">
                            <img class="logoSite" src="/_resources/_imgs/logo-light.png" alt="logo site landrick light">
                        </a>
                        <p class="web_description">Start working with Landrick that can provide everything you need to generate awareness, drive traffic, connect.</p>
                        <div class="container_socials">
                            <div class="box_social">
                                <a href="/">
                                   <img class="social_icon" src="/_resources/_imgs/facebook-f.svg" alt="social icon">
                                </a>
                            </div>
                            <div class="box_social">
                                <a href="/">
                                   <img class="social_icon" src="/_resources/_imgs/instagram.svg" alt="social icon">
                                </a>
                            </div>
                            <div class="box_social">
                                <a href="/">
                                   <img class="social_icon" src="/_resources/_imgs/twitter.svg" alt="social icon">
                                </a>
                            </div>
                            <div class="box_social">
                                <a href="/">
                                   <img class="social_icon" src="/_resources/_imgs/linkedin-in.svg" alt="social icon">
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="region_center"></div>
                <div class="region_right"></div>
            </div>
            <div class="down_region__footer"></div>
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
    padding: 60px 0;
    background: #202942;
}

.logoSite {
    width: 130px;
}

.web_description{
    color: #9AA3AC;
    font-size: 1rem;
    font-weight: 500;
    margin: 22px 0;
    width: 43%;
}

.container_socials{
    display: flex;
    align-items: center;
}

.box_social{
    width: 32px;
    height: 32px;
    border-radius: 6px;
    margin-right: 6px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    border: 1px solid #A7B0B8;
    background: transparent;
    cursor: pointer;
}

.box_social:last-child{
    margin-right: 0;
}

.box_social a{
    width: 100%;
    height: 100%;
}

.social_icon{
    width: 100%;
    height: 100%;
    transform: scale(.6);
}
</style>