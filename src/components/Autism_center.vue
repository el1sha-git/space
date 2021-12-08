<template>
    <div class="autism p_cont">
        <div class="autism__content container">
            <span class="autism__top_subtitle">
                Certified Autism Center
            </span>
            <span class="autism__title">
                EDUCATIONAL COMPLEX AND SPACE MUSEUM
            </span>
            <span class="autism__title_line">
                <span class="line"></span>
            </span>
            <span class="autism__desc">
                The certification process involves rigorous training for staff, 
                inspections and improvements that enable Space Center Houston to 
                better welcome and accommodate guests with autism spectrum disorder 
                and other sensory and cognitive challenges. Space Center Houston was 
                always welcoming to guests with special needs,” McMahon said. “I was 
                able to help support that commitment by leading informal training 
                for my instructor colleagues on working with guests with disabilities, 
                including autism.
            </span>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@import "../assets/scss/style.scss";

.autism{
    display: flex;
    // height: 70vh;
    background-color: $purple-color;
    background-image: url("../assets/img/stars.png");
    background-position: center;
}
.autism__content{
    padding-top: 200px;
    padding-bottom: 200px;
    display: flex;
    flex-direction: column;
    align-items: center;
    color: $main-light-color;
    text-align: center;
}

.autism__top_subtitle{
    font-size: 22px;
}

.autism__title{
    width: 80%;
    font-size: 50px;
    font-weight: 600;
    padding: 30px 0px;
    word-break: normal;
}
@media screen and (max-width: 480px){
    .autism__title{
        font-size: 35px;
    }
}

.autism__title_line{
    height: 10px;
    display: flex; 
}
.autism__title_line .line{
    width: 90px;
    height: 100%;
    background-color: $yellow;   
}

.autism__desc{
    padding-top: 25px;
    width: 65%;
    font-style: italic
}
</style>