<template>
    <main>
        <div class="weather-container">
            <header-actions />
            <div class="main-weather">
                <measurements />
                <current-weather />
            </div>
            <div class="different-weather">
                <all-day-weather />
                <next-weather />
            </div>
        </div>
    </main>
</template>

<script>
import HeaderActions from './HeaderActions'
import Measurements from './Measurements'
import CurrentWeather from './CurrentWeather'
import AllDayWeather from './AllDayWeather'
import NextWeather from './NextWeather'

export default {
    name: 'WeatherApp',
    components: { NextWeather, AllDayWeather, CurrentWeather, Measurements, HeaderActions },
}
</script>

<style lang="scss">
main {
    width: 100%;
    height: 100%;
    background-color: #cdcbcb;
    background-position: center;
    background-size: cover;
    background-repeat: no-repeat;
    background-image: url('https://images.pexels.com/photos/1417651/pexels-photo-1417651.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260');
    overflow: hidden;
    box-shadow: 0 19px 38px rgba(0, 0, 0, 0.3), 0 15px 12px rgba(0, 0, 0, 0.22);

    @media screen and (min-width: 481px) {
        max-width: 480px;
        max-height: 600px;
        border-radius: 10px;
    }

    .weather {
        &-container {
            display: flex;
            flex-direction: column;
            background: rgba(0, 0, 0, 0.4);
            height: 100%;
            width: 100%;
        }
    }

    .main-weather {
        flex: 1 auto;
        padding: 20px;
        display: flex;
        align-items: center;
        flex-direction: column;
        justify-content: center;
    }

    .different-weather {
        background: rgba(0, 0, 0, 0.6);
        padding: 20px;
    }
}
</style>
