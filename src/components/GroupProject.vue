<template>
          <div class="box"  data-aos="fade-up" data-aos-duration="6000">
            <div class="tile is-ancestor">
              <div class="tile is-parent">
                <article class="tile is-child ">
                  <figure class="image image is-5by4">
                    <img src="../assets/GroupProject/HomeScreen.jpg">
                  </figure>
                </article>
              </div>
              <div class="tile is-parent is-8">
                <article class="tile is-child">
                  <p class="title">University Group Project</p>
                  <div class="text">
                    <p>This project is a web-tool that was developed as a group for the university. It was designed for the Food Science students to be able to discover jobs that match their skills. </p>
                  </div>
                  <div class="text">
                    <div class="center">Tech Stack:</div>
                  </div>
                  <div class="text">
                    <div class="center">
                      <div><img src="https://img.icons8.com/color/48/000000/javascript.png"/></div>
                      <div><img src="https://img.icons8.com/offices/48/000000/php-logo.png"/></div>
                      <div><img src="https://img.icons8.com/color/48/000000/css3.png"/></div>
                    </div>
                  </div>
                  <div>
                    <div class="buttons center">
                        <button class="button is-outlined is-rounded is-small text" @click="handleSourceCode">Source Code</button>
                        <button class="button is-outlined is-rounded is-small text" @click="handleLive">Live Site</button>
                    </div>
                  </div>
                </article>
              </div>
            </div>
          </div>
</template>

<script>
export default {
  name: 'GroupProject',
  methods: {
    handleLive: function () {
      window.open('https://www.nottingham.ac.uk/~sazintra/public/cfgc/')
    },
    handleSourceCode: function () {
      window.open('https://github.com/alexhambley/grp')
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
@import url(https://fonts.googleapis.com/css?family=Montserrat:400,700);

</style>
