<template>
  <div class="tales-game">
    <b-container class="game-controls">
      <b-row>
        <b-col cols="12" md="6" offset-md="3">
          <b-button block>
            start round
          </b-button>
        </b-col>
      </b-row>
    </b-container>
    <div class="game-area">
      <div class="tiles-row">
        <div class="tile" />
        <div class="tile" />
        <div class="tile opened" />
        <div class="tile" />
        <div class="tile" />
      </div>
      <div class="tiles-row">
        <div class="tile" />
        <div class="tile" />
        <div class="tile" />
        <div class="tile opened" />
        <div class="tile" />
      </div>
      <div class="tiles-row">
        <div class="tile opened" />
        <div class="tile" />
        <div class="tile" />
        <div class="tile" />
        <div class="tile" />
      </div>
      <div class="tiles-row">
        <div class="tile" />
        <div class="tile" />
        <div class="tile" />
        <div class="tile" />
        <div class="tile" />
      </div>
      <div class="tiles-row">
        <div class="tile" />
        <div class="tile" />
        <div class="tile opened" />
        <div class="tile" />
        <div class="tile" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      rows: 5,
      cols: 5
    }
  }
}
</script>

<style scoped>
.game-controls{
    margin-top: 10px;
    margin-bottom: 10px;
}
.game-area{
    display: flex;
    height: 100%;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
.tiles-row{
    display: flex;
    justify-content: center;
}
.tile{
    width: 100px;
    height: 100px;
    background-color: gray;
    margin: 5px;
}
.tile.opened{
    background-color: #81b5e9;
}
</style>
