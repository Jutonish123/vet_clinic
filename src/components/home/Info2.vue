<template>
    <div class="info">
        <div class="info-descr">
            <span class="info-text">
                Клиника располагает современным<br>
                диагностическим оборудованием,<br>
                применяет передовые методы<br>
                исследований и терапии
            </span>
            <div class="info-telefon">
                <button class="info-btn">Записаться на прием</button>
                <span class="info-number">8 800 900 50 10</span>
            </div>
        </div>
            <img class="info-img" src="../../assets/home/block7/mask-g.png" alt="">
    </div>
</template>

<script setup>

</script>

<style lang="sass" scoped>

.info
    height: 423px
    margin: 0 112px 65px 112px
    border-radius: 40px
    background: #35B8FE
    display: grid
    grid-template-columns: repeat(2, 1fr)
    margin-bottom: 100px
    &-img
        margin-top: -98px
        justify-self: end
    &-descr
        justify-self: center
        align-self: center
    &-telefon
        margin-top: 48px
    &-text
        color: #FFF
        font-family: Segoe UI
        font-size: 24px
    &-btn
        color: #000
        font-family: Segoe UI
        font-size: 16px
        padding: 9px 24px
        border-radius: 31px
        background: #FDE2C7
        border: 0
        margin-right: 48px
        &:hover
                box-shadow: 1px 1px 1px 1px rgba(0, 0, 0, 0.6)
    &-number
        color: #FFF
        font-family: Segoe UI
        font-size: 24px
</style>