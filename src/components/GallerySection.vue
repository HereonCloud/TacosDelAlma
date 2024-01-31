<template>
    <div class="container">
        <div class="left">
            <img src="./../assets/images/Taco.png"/>
            <div class="bottom"><img src="./../assets/images/SayYesText.png"/></div>
        </div>
        <div class="right">
            <img src="./../assets/images/TacoWithLogo.png"/>
        </div>
    </div>
</template>
<style scoped>

    .container {
        display: flex;
        flex-direction: row;
        width: 100%;
    }
    .left, .right {
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
        width: 50%;
    }

    .left img {
        width: 100%;
    }

    .left .bottom {
        width: 100%;
        background-color: #FECE46;
        height: auto;
        padding: 130px 120px;
    }

    .left .bottom img {
        object-fit: cover;
    }

    .right{
        background-color:#E8572B;
        padding: 165px 105px;
    }

    .right img{
        width: auto;
        max-width: 100%;
        object-fit: cover;
    }

    @media (max-width:768px) {
        .container{ 
            flex-direction: column-reverse;
        }

        .right, .left {
            width: 100%;
        }
        .left .bottom {
            padding: 30px 20px;
        }
        .right{
            padding: 30px 20px;
        }
    }
</style>