<template>
  <div id="default">
    <Header />
    <Nuxt />
    <Footer />
  </div>
</template>

<style>
html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  color: #666666;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

#default {
  margin: 0 auto;
  width: 100%;
  max-width: 950px;
  box-shadow: 0px 0px 30px -10px;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

a {
  color: #0099cc;
  text-decoration-line: underline;
  text-decoration-color: #0099cc;
}
</style>
