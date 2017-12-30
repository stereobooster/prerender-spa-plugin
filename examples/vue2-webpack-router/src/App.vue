<template>
  <div id="app">
    <img src="./assets/logo.png" width="200" height="200">
    <h1>{{ msg }}</h1>
    <p>
      <router-link to="/">Home</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/contact">Contact</router-link>
    </p>
    <p>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. In rhoncus ex ex, at gravida nisl suscipit nec. Fusce a euismod massa. Donec malesuada eros dui, eget vehicula dui laoreet et. Cras gravida finibus enim vitae blandit. Ut placerat placerat posuere. Etiam porta ut augue id feugiat. Sed pretium felis et imperdiet euismod. Praesent sed lectus ac velit posuere condimentum. Etiam placerat, odio eget ultricies pharetra, magna nulla porttitor sapien, eget congue tellus mi at orci.
    </p>
    <p>
    Donec eget molestie lorem. Pellentesque aliquam purus vitae dignissim viverra. Ut blandit malesuada eros, id blandit nulla dapibus ut. Duis purus sapien, interdum congue vehicula et, dignissim vel tellus. In enim metus, maximus eleifend metus vel, ultricies sollicitudin augue. Etiam tincidunt nibh vitae egestas posuere. Aenean iaculis pharetra rhoncus. Pellentesque sit amet ipsum quis nulla bibendum finibus ac et mi. Ut dictum tortor ac leo finibus consectetur. Donec id tristique ipsum. Morbi consequat justo eu erat malesuada sollicitudin. Mauris volutpat fermentum euismod. Sed varius enim feugiat odio tristique commodo. Donec justo risus, consectetur ut justo a, facilisis fringilla tortor.
    </p>
    <p>
    Cras id libero ut turpis suscipit interdum ut id risus. Aliquam bibendum maximus commodo. Integer malesuada elementum metus sit amet mollis. Nullam placerat vel elit ac fermentum. Etiam accumsan vehicula mauris sit amet fermentum. Morbi a ex a est tempor vulputate. Vestibulum rhoncus tincidunt mi, id pellentesque lorem. Pellentesque in orci sit amet metus rhoncus consectetur. Cras ullamcorper, leo id facilisis pulvinar, dui ex auctor nisl, suscipit tempor eros ex eu mauris.
    </p>
    <p>
    Aliquam erat volutpat. Maecenas pharetra efficitur mauris, sit amet varius augue efficitur sit amet. Cras ut lectus arcu. Curabitur at efficitur ipsum. Nulla non est a ligula consequat lacinia in ut mauris. Nullam dolor sem, dictum sit amet accumsan sed, volutpat at nunc. Phasellus pulvinar augue eu dui rhoncus tempor at ut neque. Aenean tempus quam eu viverra malesuada. Vivamus varius, purus in porttitor hendrerit, augue sem vulputate elit, in tempus mi urna et risus. Proin ultricies tellus feugiat ipsum consequat consequat. Phasellus a quam tristique, lobortis sem id, gravida lorem.
    </p>
    <p>
    In in metus a odio mollis feugiat. Quisque quis tincidunt ipsum. In posuere, orci ac malesuada molestie, lorem nunc varius eros, nec congue dui sapien at leo. Sed accumsan urna sed sapien dignissim efficitur. Cras vestibulum quis orci at semper. Suspendisse viverra libero odio, eu congue leo fermentum non. Curabitur leo ipsum, semper nec felis quis, lacinia vestibulum nibh. Mauris velit elit, lobortis non ligula eget, sollicitudin lacinia lorem. Donec ornare egestas elit vel pellentesque.
    </p>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to your prerender-spa-plugin Vuejs 2.0 demo app!'
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
