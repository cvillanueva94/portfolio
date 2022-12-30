<template>
  <div class="container">
    <p class="hi text-white">Hi, my name is</p>
      <h2 class="big-heading text-slate-400">Carlos Villanueva.</h2>
      <h3 class="big-heading text-slate-300">I build things for the web.</h3>
    <p className="text-slate-400">I’m a software engineer specializing in building (and occasionally designing) exceptional digital experiences. Currently, I’m focused on building accessible, human-centered products at Upstatement.</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2, h3, h4, h5, h6 {
    margin: 0px 0px 10px;
    font-weight: 600;
    /* color: var(--lightest-slate); */
    line-height: 1.1;
}

.container {
  margin: 0px auto;
    padding: 100px 0px;
    max-width: 1000px;
}

.hi {
  text-align: left;
  line-height: 1.1;
  font-family: "SF Mono","Fira Code","Fira Mono","Roboto Mono",monospace;
}

h2{
  display: block;
    font-size: 1.5em;
    margin-block-start: 0.83em;
    margin-block-end: 0.83em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    font-weight: bold;
}

.big-heading{
  margin: 0;
  font-size: clamp(40px, 8vw, 80px)
}
</style>
