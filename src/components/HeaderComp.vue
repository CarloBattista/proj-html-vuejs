<template>
    <!-- Header -->
    <div class="header">
        <div class="w-70 d-flex align-items-center justify-c-between">
            <div class="region_left">
                <a href="/">
                    <img class="logoSite" src="/_resources/_imgs/logo-dark.png" alt="logo site landrick dark">
                </a>
            </div>
            <div class="region_center">
                <ul class="nav_list">
                    <li class="listItem">
                        <a href="/" id="">Home
                            <i class="fa-solid fa-angle-down"></i>
                        </a>
                    </li>
                    <li class="listItem">
                        <a href="/" id="currentActive">Landing
                            <i class="fa-solid fa-angle-down"></i>
                        </a>
                    </li>
                    <li class="listItem">
                        <a href="/" id="">Pages
                            <i class="fa-solid fa-angle-down"></i>
                        </a>
                    </li>
                    <li class="listItem">
                        <a href="/" id="">Docs
                            <i class="fa-solid fa-angle-down"></i>
                        </a>
                    </li>
                </ul>
            </div>
            <div class="region_right">
                <div class="box_btn">
                    <i class="fa-brands fa-github"></i>
                </div>
                <div class="box_btn">
                    <i class="fa-brands fa-stack-overflow"></i>
                </div>
                <div class="box_btn">
                    <i class="fa-regular fa-user"></i>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "HeaderComp"
}
</script>

<style scoped>
.header {
    position: sticky;
    z-index: 999;
    width: 100%;
    height: 80px;
    display: flex;
    align-items: center;
}

.logoSite{
    width: 130px;
}

.nav_list,
.listItem{
    display: flex;
    align-items: center;
}

.listItem{
    margin: 0 20px;
}

.listItem a{
    color: #161C2D;
    font-size: .9rem;
    font-weight: 500;
    text-transform: uppercase;
}

#currentActive{
    color: #2F55D4;
}

.region_right{
    display: flex;
    align-items: center;
    justify-content: flex-end;
}

.box_btn{
    width: 34px;
    height: 34px;
    border-radius: 6px;
    background: #E4E9F8;
    box-shadow: 0 0 3px rgba(47, 86, 212, .5);
    margin-right: 10px;
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
}

.box_btn:last-child{
    margin-right: 0;
}

.box_btn i{
    color: #2F55D4;
}
</style>