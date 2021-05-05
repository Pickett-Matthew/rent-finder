<template>

    <section class="page h-screen w-screen">

        <div class="top-container">

            <div class="top-tile"></div>
            <div class="top-tile"></div>
            <div class="top-tile"></div>

        </div>

        <div class="top-container">

            <div class="mid-tile"></div>
            <div class="mid-tile"></div>

        </div>

    </section>

</template>

<style scoped>

    .page {
        background-color: #eceeef;
        padding: 20px;
    }

    .top-container {
        display: flex;
        flex-flow: row nowrap;
        max-height: 550px;
        justify-content: space-between;
    }

    .top-tile {
        width: 33%;
        height: 100px;
        background-color: #fff;
        border-radius: 12px;
        display: flex;
        flex-flow: row;
        margin: 20px;
     
    }

    .mid-tile {
        width: 50%;
        height: 150px;
        background-color: #fff;
        border-radius: 12px;
        display: flex;
        flex-flow: row nowrap;
        margin: 20px;
    }

</style>