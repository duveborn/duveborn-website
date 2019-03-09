<template>
  <HomePage id="app" />
</template>

<script>
import HomePage from './components/HomePage.vue'

export default {
  name: 'app',
  components: {
    HomePage
  }
}
</script>

<style>
@font-face {
       font-family: "pt-sans-regular";
       src: url("/fonts/pt-sans-regular.ttf");
}
@font-face {
       font-family: "pt-sans-narrow-bold";
       src: url("/fonts/pt-sans-narrow-bold.ttf");
}
html {
  height: 100%;
  background-color: white;
}
body {
  font-family: "pt-sans-regular", sans-serif;
  color: #000000;
  -webkit-font-smoothing: none;
  -moz-osx-font-smoothing: unset;
}
h1, h2, h3 {
  font-family: "pt-sans-narrow-bold", sans-serif;
  color: #008C92;
  padding-bottom: 0.05em;
}
header p {
  font-size: x-large;
  padding-bottom: 0.15em;
}
p {
  font-size: normal;
  padding-bottom: 1em;
  /* text-align: justify; */
}
a, a:visited {
  color: #C60000;
  text-decoration: none;
}
a:hover, a:active {
  color: #008C92;
  text-decoration: underline;
}

</style>
