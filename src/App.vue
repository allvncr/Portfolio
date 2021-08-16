<template>
  <div id="app">
    <router-view />
  </div>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap');

    $first-color: hsl(250, 69%, 61%);
    $first-color-second: hsl(250, 69%, 61%);
    $first-color-alt: hsl(250, 57%, 53%);
    $first-color-lighter: hsl(250, 92%, 85%);
    $title-color: hsl(250, 8%, 15%);
    $input-color: hsl(250, 8%, 45%);
    $text-color: hsl(250, 8%, 65%);
    $text-color-light: hsl(250, 8%, 65%);
    $body-color: hsl(250, 70%, 96%);
    $body-color: hsl(250, 60%, 99%);
    $container-color: #fff;

    $header-height: 3rem;

    // Font and text
    $big-font-size: 2rem;
    $h1-font-size: 1.5rem;
    $h2-font-size: 1.2rem;
    $h3-font-size: 1.125rem;
    $normal-font-size: .938rem;
    $small-font-size: .813rem;
    $smaller-font-size: .75rem;

    // Font weight
    $font-medium: 500;
    $font-semi-bold: 600;

    // Margin Bottom
    $mb-0-25: .25rem;
    $mb-0-5: .5rem;
    $mb-0-75: .75rem;
    $mb-1: 1rem;
    $mb-1-5: 1.5rem;
    $mb-2: 2rem;
    $mb-2-5: 2.5rem;
    $mb-3: 3rem;

    // z index
    $z-tooltip: 10;
    $z-fixed: 100;
    $z-modal: 1000;

@media screen and (min-width: 968px) {
    $big-font-size: 3rem;
    $h1-font-size: 2.25rem;
    $h2-font-size: 1.5rem;
    $h3-font-size: 1.25rem;
    $normal-font-size: .1rem;
    $small-font-size: .875rem;
    $smaller-font-size: .813rem;
}

// Base
*{
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

html{
    scroll-behavior: smooth;
}

body{
    margin: 0 0 $header-height 0;
    font-family: 'Poppins', sans-serif;
    background-color: $body-color;
    font-size: $normal-font-size;
    color: $text-color;
}

h1, h2, h3, h4{
    color: $title-color;
    font-weight: $font-semi-bold;
}

ul{
    list-style: none;
}

a{
    text-decoration: none;
}

img{
    max-width: 100%;
    height: auto;
}


</style>
