<template>
    <div class="welcome_abroad p_cont">
        <div class="welcome__moon container">
            <div class="moon_image">
            </div>
            <div class="welcome__main_text">
                <span class="welcome__top_subtitle">
                    To the Moon and Beyond
                </span>
                <span class="welcome__title">
                    WELCOME ABROAD
                </span>
                <span class="welcome__title_line">
                    <span class="line"></span>
                </span>
                <span class="welcome__desc">
                    Space Center Houston has welcomed nearly 20 million visitors and 
                    currently hosts more than 1 million visitors annually in its 250,000-square-foot 
                    educational complex. Space Center Houston has a $73 million impact on the 
                    greater Houston economy, according to a 2016 economic study by Jason Murasko 
                    and Stephen Cotten, associate professors of economics at the University of Houston – Clear Lake.
                </span>
            </div>
        </div>


    </div>
</template>

<style lang="scss" scoped>
@import "../assets/scss/style.scss";

.welcome_abroad{
    background-color: $yellow-bg;
    display: flex;
    flex-wrap: wrap;
    padding-bottom: 100px;
}

.welcome__moon{
    display: flex;
    flex-wrap: wrap;
}
.moon_image{
    display: flex;
    flex-basis: 60%;
    flex-grow: 1;
    // height: 500px;
    height: 590px;
    background-image: url("../assets/img/moon.jpeg");
    background-size: cover;
}

.welcome__main_text{
    display: flex;
    flex: 1 1 auto;
    width: 300px;
    flex-direction: column;
    background-color: #fff;
    padding: 30px 10px;
}

.welcome__top_subtitle{
    font-size: 22px;
}

.welcome__title{
    color: $purple-color;
    font-size: 50px;
    font-weight: 600;
    padding: 30px 0px; 
}

.welcome__title_line{
    height: 10px;
    display: flex;
}
.welcome__title_line .line{
    width: 90px;
    height: 100%;
    background-color: $yellow;
}

.welcome__desc{
    padding-top: 60px;
    width: 100%;
    text-align: justify;
    color: $secondary-color;
    font-style: italic;
    font-size: 1.05em;
}
</style>