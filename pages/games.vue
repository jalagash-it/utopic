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
    margin: 10px;
}
.tile{
    width: 80px;
    height: 80px;
    background-color: aqua;
    margin: 4px;
}
</style>
