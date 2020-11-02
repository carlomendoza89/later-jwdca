<template>
  <div id="app">
    <LandingPage />
  </div>
</template>

<script>
import LandingPage from "./components/LandingPage";

export default {
  name: "App",
  components: {
    LandingPage,
  },
};
</script>

<style lang="scss">
#app {
  color: $primary;
  font-family: $paragraph;
}
p {
  color: $secondary;
}
section {
  background: $background;
  padding-top: 50px;
  padding-bottom: 80px;
}
.section-fading {
  background: linear-gradient(rgb(250, 248, 245) 0%, rgb(255, 255, 255) 100%)
}
.section-header {
  text-align: center;
  margin: 16px 0 32px;
}
.into-header {
  font-size: $xl-font-size;
}
.container {
  max-width: 1200px;
}
.button {
  color: $salmon;
  border: 1px solid $salmon;
  border-radius: 50px;
  text-decoration: none;
  padding: 10px 20px;
  font-weight: $medium-font-weight;
}
.button:hover {
  color: $background;
  background: $salmon;
  text-decoration: none;
}
.button .icon {
  line-height: $paragraph-line_height;
  height: $paragraph-size;
  vertical-align: middle;
}
.xl-font {
  font-family: $xl-font;
  font-weight: $medium-font-weight;
  font-size: $xl-font-size;
  line-height: $xl-font-line_height;
}
h1 {
  font-family: $header1;
  font-weight: $medium-font-weight;
  font-size: $header1-size;
  line-height: $header1-line_height;
}
h2 {
  font-family: $header2;
  font-weight: $bold-font-weight;
  font-size: $header2-size;
  line-height: $header2-line_height;
}
h3 {
  font-family: $header3;
  font-weight: $regular-font-weight;
  font-size: $header3-size;
  line-height: $header3-line_height;
}
h4 {
  font-family: $header4;
  font-weight: $regular-font-weight;
  font-size: $header4-size;
  line-height: $header4-line_height;
}
h5 {
  font-family: $header5;
  font-weight: $regular-font-weight;
  font-size: $header5-size;
  line-height: $header5-line_height;
}
h6 {
  font-family: $header6;
  font-weight: $medium-font-weight;
  font-size: $header6-size;
  line-height: $header6-line_height;
  text-transform: uppercase;
  letter-spacing: 1px;
}
p {
  font-family: $paragraph;
  font-weight: $regular-font-weight;
  font-size: $paragraph-size;
  line-height: $paragraph-line_height;
}
.poppins-bold {
  font-family: "Poppins-Bold", "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.salmon-text {
  color: $salmon;
}
</style>
