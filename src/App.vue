<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
  export default {
    name: 'App'
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

  /* reset
---------------------------------------- */

  * {
    -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
    outline: 0;
  }

  body,
  h1,
  h2,
  h3,
  h4,
  h5,
  h6,
  hr,
  p,
  blockquote,
  dl,
  dt,
  dd,
  ul,
  ol,
  li,
  pre,
  form,
  fieldset,
  legend,
  button,
  input,
  textarea,
  th,
  td {
    margin: 0;
    padding: 0;
    vertical-align: baseline;
  }

  img {
    border: 0 none;
    vertical-align: top;
  }

  i,
  em {
    font-style: normal;
  }

  ol,
  ul {
    list-style: none;
  }

  input,
  select,
  button,
  h1,
  h2,
  h3,
  h4,
  h5,
  h6 {
    font-size: 100%;
    font-family: inherit;
  }

  table {
    border-collapse: collapse;
    border-spacing: 0;
  }

  a,
  a:visited {
    text-decoration: none;
    color: #333;
  }

</style>
