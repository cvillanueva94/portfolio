<template>
  <div class="container">
    <p class="hi text-white">Hi, my name is</p>
      <h2 class="big-heading text-slate-400">Carlos Villanueva.</h2>
      <h3 class="big-heading text-slate-300">Lorem ipsum dolor sit amet.</h3>
    <p className="text-slate-400">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. </p>
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
