<template>
    <div class="welcome__benefits p_cont">
        <div class="welcome__content container">
            <div class="welcome__card first">
                <div class="card_image">

                </div>
                <div class="subtext">
                    There is always something new at Space Center Houston 
                    with an amazing array of traveling exhibits and astounding events.
                </div>
            </div>

            <div class="welcome__card second">
                <div class="card_image second">

                </div>
                <div class="subtext">
                    Space Center Houston has the world’s largest 
                    collection of moon rocks and lunar samples for public view.
                </div>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@import "../assets/scss/style.scss";

.welcome__benefits{
    display: flex;
    background-color: $yellow-bg;
    padding-bottom: 60px;
}

.welcome__content{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    flex-wrap: wrap;
}

.card_image{
    height: 300px;
    background-position: center;
    background-size: cover
}
.first .card_image{
    background-image: url("../assets/img/spacex.jpeg")
}
.second .card_image{  
    background-image: url("../assets/img/rocket.jpeg");
}

.welcome__card{
    display: flex;
    flex-direction: column;
    flex-basis: 45%;
    flex-grow: 1;
    flex-shrink: 1;
    min-width: 300px;
    padding: 0 10px;
}

.subtext{
    padding: 30px 15px;
    font-style: italic
}
</style>