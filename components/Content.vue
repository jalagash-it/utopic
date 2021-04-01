<template>
  <b-container>
    <div class="content">
      <b-row>
        <b-col cols="3">
          <b-nav vertical class="w-25">
            <b-nav-item active>Active</b-nav-item>
            <b-nav-item>Link</b-nav-item>
            <b-nav-item>Another Link</b-nav-item>
          </b-nav></b-col
        >
        <b-col cols="9">
          <div class="main">
            <b-row class="main-title">
              <h1>All Games</h1>
              <a href="#">What are Early Access games?</a>
            </b-row>
            <b-row class="main-card">
              <b-col>
                <h3>Today's games</h3>

                <b-row>
                  <b-col cols="4">
                    <b-card
                      title="Card Title"
                      img-src="https://picsum.photos/600/300/?image=25"
                      img-alt="Image"
                      img-top
                      tag="article"
                      style="max-width: 10rem"
                      class="mb-2"
                    >
                      <b-card-text> Some quick </b-card-text>
                    </b-card>
                  </b-col>
                  <b-col cols="4">
                    <b-card
                      title="Card Title"
                      img-src="https://picsum.photos/600/300/?image=25"
                      img-alt="Image"
                      img-top
                      tag="article"
                      style="max-width: 10rem"
                      class="mb-2"
                    >
                      <b-card-text> Some quick </b-card-text>
                    </b-card>
                  </b-col>
                  <b-col cols="4">
                    <b-card
                      title="Card Title"
                      img-src="https://picsum.photos/600/300/?image=25"
                      img-alt="Image"
                      img-top
                      tag="article"
                      style="max-width: 10rem"
                      class="mb-2"
                    >
                      <b-card-text> Some quick </b-card-text>
                    </b-card>
                  </b-col>
                </b-row>
              </b-col>
            </b-row>
            <b-row class="main-card">
              <b-col>
                <h3>Speed</h3>

                <b-row>
                  <b-col cols="4">
                    <b-card
                      title="Card Title"
                      img-src="https://picsum.photos/600/300/?image=25"
                      img-alt="Image"
                      img-top
                      tag="article"
                      style="max-width: 10rem"
                      class="mb-2"
                    >
                      <b-card-text> Some quick </b-card-text>
                    </b-card>
                  </b-col>
                  <b-col cols="4">
                    <b-card
                      title="Card Title"
                      img-src="https://picsum.photos/600/300/?image=25"
                      img-alt="Image"
                      img-top
                      tag="article"
                      style="max-width: 10rem"
                      class="mb-2"
                    >
                      <b-card-text> Some quick </b-card-text>
                    </b-card>
                  </b-col>
                  <b-col cols="4">
                    <b-card
                      title="Card Title"
                      img-src="https://picsum.photos/600/300/?image=25"
                      img-alt="Image"
                      img-top
                      tag="article"
                      style="max-width: 10rem"
                      class="mb-2"
                    >
                      <b-card-text> Some quick </b-card-text>
                    </b-card>
                  </b-col>
                </b-row>
              </b-col>
            </b-row>
          </div>
        </b-col>
      </b-row>
    </div>
  </b-container>
</template>
<style scoped>
.main {
  background-color: #fff;
  padding: 20px;
  margin-bottom: 50px;
}
.main-title {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
</style>
