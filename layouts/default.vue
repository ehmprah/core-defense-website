<template>
  <div>
    <nuxt />
  </div>
</template>

<style lang="scss">
/* chakra-petch-600 - latin */
@font-face {
  font-family: 'Chakra Petch';
  font-style: normal;
  font-weight: 600;
  src: url('/fonts/chakra-petch-v9-latin-600.eot'); /* IE9 Compat Modes */
  src: local(''),
    url('/fonts/chakra-petch-v9-latin-600.eot?#iefix')
      format('embedded-opentype'),
    /* IE6-IE8 */ url('/fonts/chakra-petch-v9-latin-600.woff2') format('woff2'),
    /* Super Modern Browsers */ url('/fonts/chakra-petch-v9-latin-600.woff')
      format('woff'),
    /* Modern Browsers */ url('/fonts/chakra-petch-v9-latin-600.ttf')
      format('truetype'),
    /* Safari, Android, iOS */
      url('/fonts/chakra-petch-v9-latin-600.svg#ChakraPetch') format('svg'); /* Legacy iOS */
}

html,
body,
p,
ol,
ul,
li,
dl,
dt,
dd,
blockquote,
figure,
fieldset,
legend,
textarea,
pre,
iframe,
hr,
h1,
h2,
h3,
h4,
h5,
h6 {
  margin: 0;
  padding: 0;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-size: 100%;
  font-weight: normal;
}

ul {
  list-style: none;
}

button,
input,
select,
textarea {
  margin: 0;
}

html {
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: inherit;
}

img,
svg,
embed,
object,
audio,
video {
  height: auto;
  max-width: 100%;
}

iframe {
  border: 0;
}

table {
  border-collapse: collapse;
  border-spacing: 0;
}

td,
th {
  padding: 0;
  text-align: left;
}

html {
  font-family: 'Chakra Petch', sans-serif;
  font-size: 18px;
  line-height: 1.5em;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background: #222;
  color: #dbdbdb;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

a,
a:hover {
  text-decoration: none;
  transition: all 0.2s;
  border-bottom: 1px solid;
  color: #26a7ce;
}

a:hover {
  border-color: transparent;
}

p {
  margin-bottom: 1em;
}

h1,
h2 {
  font-size: 1.5em;
  text-transform: uppercase;
  margin-bottom: 1em;
  color: #26a7ce;
}

ul.list {
  padding-left: 1.5em;
  list-style-type: circle;
  text-align: left;
}

ul.list-inline {
  li {
    display: inline;
    margin: 0.5em;
  }
}

.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>
