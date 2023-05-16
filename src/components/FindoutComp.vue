<template>
    <div class="findout_container">
        <div class="w-70 text-align-center">
            <div class="container_heading">
                <h2 class="headingSection">Want to be among the first to find out?</h2>
                <p class="descriptionSection">Start working with <span class="highlight">Landrick</span> that can provide
                    you need to generate awareness, drive traffic, connect.</p>
            </div>
            <div class="container_field_email">
                <div class="container_field">
                    <input class="emailField" type="email" placeholder="Email Address">
                    <button type="submit" class="btn">Get Started</button>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: "FindoutComp",
}
</script>

<style scoped>
.findout_container {
    width: 100%;
    padding: 6vw 0;
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

.container_field_email {
    width: 65%;
    margin: 60px auto 0;
}

.container_field {
    position: relative;
    width: 100%;
    height: 50px;
}

.emailField {
    width: 100%;
    height: 100%;
    padding: 0 30px;
    border-radius: 30px;
    border: 1px solid #8492A6;
    outline: none;
}

.emailField::placeholder {
    color: #8C8C8C;
    font-size: 1rem;
    font-weight: 400;
}

.emailField[type=email] {
    color: #161C2D;
    font-size: 1rem;
    font-weight: 600;
}

.container_field .btn {
    position: absolute;
    top: 50%;
    right: 3px;
    height: calc(100% - 6px);
    padding: 0 20px;
    transform: translate(0, -50%);
    border-radius: 30px;
    border: none;
    background: #2F55D4;
    box-shadow: 0 0 3px rgba(47, 86, 212, .5);
    color: #fff;
    font-size: 1rem;
    font-weight: 400;
    cursor: pointer;
    transition: all 200ms ease;
}

.container_field .btn:hover {
    background: #2443AC;
}

@media only screen and (max-width: 1020px) {
    .findout_container {
        padding-top: 0;
        padding-bottom: 60px;
    }

    .descriptionSection,
    .container_field_email {
        width: 100%;
    }
}
</style>