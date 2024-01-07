<template>
    <div class="intro">
        <div class="left">
            <p>Tacos del Alma envisions a culinary journey that goes beyond the ordinary, delivering an experience that speaks to the soul. Rooted in a passion for authentic flavors and a commitment to quality, their aim to redefine the taco experience with a touch of artistry and heart.</p>
            <br>
            <p>Mission at Tacos del Alma is to transport their customers to the vibrant streets of Mexico through the art of taco-making. Their strive to create a haven for taco enthusiasts, where each bite is a celebration of tradition, culture, and the pure joy of savoring expertly crafted flavors.</p>
        </div>
        <div class="right">
            <p>Yuliia Hrabysnka 2023</p>
        </div>
    </div>
</template>
<style scoped>
    .intro {
        display: flex;
        width: 100%;
        background-color: #FFE8CD;
        padding:40px 80px;
    }

    .left { 
        width: 50%;
        height:100%;
        display: grid;
        place-content: center;
    }

    .right {
        width: 50%;
        display: grid;
        place-content: end;
    }

    p {
    color: #000;
    font-family: 'Courier New', Courier, monospace;
    font-size: 16px;
    font-style: normal;
    font-weight: 700;
    line-height: 139%;
    letter-spacing: 0.44px;
    }

    @media (max-width:768px) {
        .intro {
            flex-direction: column;
            gap: 20px;
            padding: 20px 40px;
        }

        .left, .right {
            width: 100%;
        }
    }
</style>