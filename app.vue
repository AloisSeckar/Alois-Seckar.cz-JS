<template>
    <router-view></router-view>
</template>

<style>
  @font-face {
    font-family: kaushanScript;
    src: url(~/assets/KaushanScript-AS.woff2);
  }

  :root {
    --color-bg: #199685;
    --color-primary: #FFCC00;
    --color-secondary: white;
  }

  html {
    font-size: 15px;
  }

  body {
    background-color: var(--color-bg);
    color: var(--color-secondary);
    font-family: Arial, sans-serif;
  }

  a:link, a:visited, a:active {
    color: var(--color-primary);
    text-decoration: none;
  }
  a:hover {
    color: var(--colorc-secondary);
  }
</style>
