<template>
          <div class="box"   data-aos="fade-up" data-aos-duration="6000">
            <div class="tile is-ancestor">
              <div class="tile is-parent is-8">
                <article class="tile is-child">
                  <p class="title">Spark Anime</p>
                  <div class="text">
                    <p>This website was developed to help anime fans find new content to watch and keep up with recent releases. By displaying different categories, among other filters, it will help narrow down to what the user is looking for. Using the Anilist API, the catalogue is vast and automatically updated.</p>
                  </div>
                  <div class="text">
                    <div class="center">Tech Stack:</div>
                  </div>
                  <div class="text">
                    <div class="center">
                      <div><img src="https://img.icons8.com/color/48/000000/vue-js.png"/></div>
                      <div><img src="https://img.icons8.com/color/48/000000/graphql.png"/></div>
                      <div><img src="https://img.icons8.com/color/48/000000/bootstrap.png"/></div>
                    </div>
                  </div>
                  <div>
                    <div class="buttons center">
                        <button class="button is-outlined is-rounded is-small text" @click="handleSourceCodeSparkAnime">Source Code</button>
                        <button class="button is-outlined is-rounded is-small text" @click="handleLiveSparkAnime">Live Site</button>
                    </div>
                  </div>
                </article>
              </div>
              <div class="tile is-parent">
                <article class="tile is-child ">
                  <figure class="image image is-5by4">
                    <img src="../assets/SparkAnime.png">
                  </figure>
                </article>
              </div>
            </div>
          </div>
</template>

<script>
export default {
  name: 'Hero',
  methods: {
    handleLiveSparkAnime: function () {
      window.open('https://sparkanime.now.sh/')
    },
    handleSourceCodeSparkAnime: function () {
      window.open('https://github.com/ahagbarth/SparkAnime')
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.about{
  background-color: #fafafa
}
.title{
  font-weight: 500;
  font-family: 'Montserrat';
  display:flex; place-content:center
}
.center{
  display: flex;
  place-content: center
}
.text{
  font-family: 'Montserrat';
  margin: 1rem
}
.image{
  -webkit-box-shadow: 0px 0px 11px 0px rgba(0,0,0,0.75);
-moz-box-shadow: 0px 0px 11px 0px rgba(0,0,0,0.75);
box-shadow: 0px 0px 11px 0px rgba(0,0,0,0.75);
}
@import url(https://fonts.googleapis.com/css?family=Montserrat:400,700);

</style>
