<template>
    <div class="current-weather">
        <div class="current-weather__icon">
            <i>
                0
            </i>
        </div>
        <div class="current-weather__info">
            <div class="city">
                Пермь
            </div>
            <div class="temperature">
                17
            </div>
            <div class="description">
                Ясно
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'CurrentWeather',
}
</script>

<style lang="scss" scoped>
.current-weather {
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
}
</style>
