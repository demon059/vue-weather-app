<template>
    <div id="app">
        <div class="app">
            <weather-app />
        </div>
    </div>
</template>

<style lang="scss"></style>
<script>
import WeatherApp from './components/WeatherApp'
export default {
    components: { WeatherApp },
}
</script>

<style>
/** Global **/
@import url('https://fonts.googleapis.com/css?family=Montserrat:300,400,500,600,700,800,900&display=swap&subset=cyrillic');

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Montserrat', sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: rgba(255, 255, 255, 0.9);
    background-color: #484f60;
}

a {
    text-decoration: none;
    color: inherit;
    transition: color 0.2s ease-in;
}

/** App **/
.app {
    height: 100vh;
    width: 100vw;

    display: flex;
    justify-content: center;
    align-items: center;
}
</style>
