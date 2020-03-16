<template>
    <div class="all-day-weather">
        <div class="all-day-weather__item">
            <div class="day">
                сейчас
            </div>
            <i class="">O</i>
            <div class="temperature">
                17°
            </div>
        </div>
        <div class="all-day-weather__item">
            <div class="day">
                14:00
            </div>
            <i class="">O</i>
            <div class="temperature">
                17°
            </div>
        </div>
        <div class="all-day-weather__item">
            <div class="day">
                14:00
            </div>
            <i class="">O</i>
            <div class="temperature">
                17°
            </div>
        </div>
        <div class="all-day-weather__item">
            <div class="day">
                14:00
            </div>
            <i class="">O</i>
            <div class="temperature">
                17°
            </div>
        </div>
        <div class="all-day-weather__item">
            <div class="day">
                14:00
            </div>
            <i class="">O</i>
            <div class="temperature">
                17°
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'AllDayWeather',
}
</script>

<style lang="scss" scoped>
.all-day-weather {
    display: flex;
    align-items: center;
    justify-content: space-around;

    &__item {
        text-align: center;
        font-size: 12px;
    }
}
</style>
