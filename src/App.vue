<template>
  <div id="app">
    <router-view/>
    <div id="footer">
      <div class="social-icons-wrapper">
        <a href="https://facebook.com/vuejsincpt/" target="_blank">
          <font-awesome-icon :icon="['fab', 'facebook-square']" class="social__icon"/>
        </a>
        <!-- <a href="https://www.twitter.com/@VueJSIsrael" target="_blank">
          <font-awesome-icon :icon="['fab', 'twitter-square']" class="social__icon"/>
        </a> -->
        <a href="https://www.meetup.com/Codebridge/" target="_blank">
          <font-awesome-icon :icon="['fab', 'meetup']" class="social__icon"/>
        </a>
        <a href="https://medium.com/vue-js-in-cape-town" target="_blank">
          <font-awesome-icon :icon="['fab', 'medium']" class="social__icon"/>
        </a>
        <!-- <a href="https://www.instagram.com/vuejsisrael/" target="_blank">
          <font-awesome-icon :icon="['fab', 'instagram']" class="social__icon"/>
        </a> -->
        <!-- <a href="https://www.youtube.com/channel/UC7Ne4vqQa7nldgA0o1fbqKg" target="_blank">
          <font-awesome-icon :icon="['fab', 'youtube-square']" class="social__icon"/>
        </a> -->
      </div>
      <!-- <router-link to="/">Home</router-link> | -->
    </div>
    <div class="credits">
      Thanks to <a a href="http://mayashavin.com/" title="Maya Shavin">Maya</a> and <a href="http://www.dimshik.com/" title="Dima Vishnevetsky">Dima</a> who built the original site for <a href="https://www.vuejsisrael.com">Vue.js Israel</a> ❤
    </div>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

#footer {
  font-size: 35px;
  display: flex;
  justify-content: center;
}

.social__icon {
  margin: 5px;
  color: #263e51;
}

.social-icons-wrapper{
  max-width: 500px;
  width: 100%;
  min-width: 300px;
  display: flex;
  justify-content: space-around;
}

.credits {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 10px;
  color: #263e51;
}

.credits a,
.credits a:active {
  color: #263e51;
}

</style>
