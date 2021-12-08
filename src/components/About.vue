<template>
    <div class="about p_cont">
        <div class="about__content container">
            <div class="about__title_cont">
                <span class="about__top_subtitle">
                    Fun and engaging education
                </span>
                <span class="about__title">
                    ABOUT THE EDUCATION FOUNDATION
                </span>
                <span class="about__title_line">
                    <span class="line"></span>
                </span>
                <span class="about__title_desc">
                    The Manned Space Flight Education Foundation inonprofit educational 
                    foundation offering extensive science education programs and a space museum.
                    The cornerstone of its education mission is Space Center Houston, a leading 
                    science and space exploration learning center. It is one of Houston’s top 
                    attractions, the area’s No. 1 attraction for international visitors, the Official 
                    Visitor Center of NASA Johnson Space Center and a Smithsonian Affiliate.
                </span>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@import "../assets/scss/style.scss";

.about{
    background-color: $yellow-bg;
}

.about__content{
    padding-top: 100px;
    padding-bottom: 100px;
    display: flex;
    flex-direction: column;
}

.about__title_cont{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}
.about__title_cont span{
    text-align: center;
    width: 100;
}

.about__top_subtitle{
    font-size: 22px;
}

.about__title{
    color: $purple-color;
    font-size: 50px;
    font-weight: 600;
    padding: 30px 0px;
}

.about__title_line{
    height: 10px;
    display: flex;
    justify-content: center;
}
.about__title_line .line{
    width: 90px;
    height: 100%;
    background-color: $yellow;
}

.about__title_desc{
    padding-top: 60px;
    width: 70%;
    text-align: justify;
    color: $secondary-color;
    font-style: italic;
    font-size: 1.05em;
}


</style>