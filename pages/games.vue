<template>
    <div>
        <div class="game-area">
            <div class="tiles-row">
                <div class="tile"></div>
                <div class="tile"></div>
                <div class="tile"></div>
                <div class="tile"></div>
                <div class="tile"></div>
            </div>
            <div class="tiles-row">
                <div class="tile"></div>
                <div class="tile"></div>
                <div class="tile"></div>
                <div class="tile"></div>
                <div class="tile"></div>
            </div>
            <div class="tiles-row">
                <div class="tile"></div>
                <div class="tile"></div>
                <div class="tile"></div>
                <div class="tile"></div>
                <div class="tile"></div>
            </div>
            <div class="tiles-row">
                <div class="tile"></div>
                <div class="tile"></div>
                <div class="tile"></div>
                <div class="tile"></div>
                <div class="tile"></div>
            </div>
            <div class="tiles-row">
                <div class="tile"></div>
                <div class="tile"></div>
                <div class="tile"></div>
                <div class="tile"></div>
                <div class="tile"></div>
            </div>
        </div>
    </div>
</template>
<style scoped>
.game-area{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.tiles-row{
    display: flex;
    justify-content: center;
    margin: 5px;
}
.tile{
    width: 100px;
    height: 100px;
    background-color: gray;
    margin: 5px;
}
</style>
