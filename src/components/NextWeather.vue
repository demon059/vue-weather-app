<template>
    <div class="next-weather">
        <div class="next-weather__item">
            <div class="day">
                Завтра
            </div>
            <i class="">O</i>
            <div class="temperature">
                17° / 31°
            </div>
        </div>
        <div class="next-weather__item">
            <div class="day">
                13.03
            </div>
            <i class="">O</i>
            <div class="temperature">
                17° / 31°
            </div>
        </div>
        <div class="next-weather__item">
            <div class="day">
                13.03
            </div>
            <i class="">O</i>
            <div class="temperature">
                17° / 31°
            </div>
        </div>
        <div class="next-weather__item">
            <div class="day">
                13.03
            </div>
            <i class="">O</i>
            <div class="temperature">
                17° / 31°
            </div>
        </div>
        <div class="next-weather__item">
            <div class="day">
                13.03
            </div>
            <i class="icon">O</i>
            <div class="temperature">
                17° / 31°
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'NextWeather',
}
</script>

<style lang="scss" scoped>
.next-weather {
    display: flex;
    align-items: center;
    justify-content: space-around;
    margin-top: 15px;
    padding-top: 15px;
    border-top: 1px solid rgba(255, 255, 255, 0.2);

    &__item {
        text-align: center;
        font-size: 12px;
    }
}
</style>
