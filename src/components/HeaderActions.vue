<template>
    <div class="weather-header">
        <div>
            0
        </div>
        <div>
            =
        </div>
    </div>
</template>

<script>
export default {
    name: 'HeaderActions',
}
</script>

<style scoped>
.weather-header {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px;
}
</style>
