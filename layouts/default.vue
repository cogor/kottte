<template>
  <div>
    <Nuxt />
  </div>
</template>

<style lang="postcss">
:root {
  --main-white: #ebe9f3;
  --main-purple: #8f74fb;
  --main-red: #de1c4b;
}
html {
  font-family: 'Inter', sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background: #0c0c0c;
}

body {
  overflow-x: hidden;
}
*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}
div {
  .disabled {
    overflow-x: hidden;
    overflow-y: visible;
  }
}
</style>
