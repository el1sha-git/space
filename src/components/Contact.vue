<template>
    <div class="contact p_cont">
        <div class="contact__content container">
            <div class="contact__info">
                <span class="text">EMPIRE STATE BUILDING</span>
                <span class="address">350 5th Ave, New York, NY 10118</span>
                <span class="phone_number">1 212-736-3100</span>
                <span class="email">contacts@esbnyc.com</span>
            </div>
            <div class="planet">
                <img src="../assets/img/planet.png" alt="">
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@import "../assets/scss/style.scss";

.contact{
    background-image: url("../assets/img/starfall.jpg");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    color: $main-light-color;
}

.contact__content{
    padding-top: 150px;
    padding-bottom: 150px;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
}

.contact__info{
    display: flex;
    flex-direction: column;
    justify-content: center;
    flex-grow: 1;
    flex-basis: 50%;
}

.contact__info .text{
    font-size: 30px;
    font-weight: 600;
    padding-right: 25%;
}

.contact__info .address{
    padding-top: 30px;
    padding-bottom: 7px;
}

.phone_number{
    padding-bottom: 7px;
}

.planet{
    display: flex;
    flex-grow: 1;
    flex-shrink: 1;
    width: 300px;
    justify-self: center;
    padding: 20px 0px;
}
.planet img{
    max-width: 400px;
    width: 100%;
}
</style>