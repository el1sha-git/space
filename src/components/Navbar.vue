<template>
    <div class="navbar p_cont">
            <div class="navbar__content container">
                <p class="navbar__title">SPACE</p>
                <p class="navbar__main_text">Research center</p>
                <p class="navbar__secondary_text">
                    An international space research organization
                    that involve to discover the new space things
                </p>
                <div class="navbar__email_form">
                    <input autocomplete type="text" class="navbar__input" placeholder="Enter a valid email address">
                    <div class="navbar__submit">Submit</div>
                </div>
            </div>
        </div>
</template>

<script>
export default {
    data() {
        return {
            
        }
    },
}
</script>

<style lang="scss" scoped>
@import "../assets/scss/style.scss";

.navbar{
    // TODO: Change to backgound image!!! or three.js integration
    background-color: #0b013c;
    height: 75vh;
    color: $main-light-color;
    display: flex;
    align-items: center;
    font-size: 18px;
}

.navbar__title{
    font-size: 5.2em;
    font-weight: 600;
}

.navbar__main_text{
    font-size: 1.3em;
}

.navbar__secondary_text{
    font-size: 0.9em;
    padding-top: 15px;
    font-style: italic;
    width: 100%;
    max-width: 450px;
    line-height: 26px;
}

.navbar__email_form{
    display: flex;
    margin-top: 40px;

}
.navbar__email_form:hover{
    cursor: pointer;
}


.navbar__input{
    font-size: 1.1em;
    padding: 5px;
    border-radius: 0;
    width: 360px;
    height: 35px;
}
.navbar__input::placeholder{
    font-weight: 300;
}

.navbar__submit{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 49px;
    width: 120px;
    color: $main-color;
    background-color: $yellow;
    font-size: 1em;
    font-weight: 300;
    margin-left: 20px;
}
.navbar__submit::selection{
    color: inherit;
    background-color: inherit
}
</style>
