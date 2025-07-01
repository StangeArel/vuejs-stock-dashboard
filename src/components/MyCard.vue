<template>
    <div class="myCard">
        <slot></slot>
    </div>
</template>

<script>
export default {
    name: 'MyCard'
}
</script>

<style scoped>
.myCard {
    background-color: #011f35;
    border-radius: 16px;
    padding: 24px 32px;
    border: 3px solid red;
}
</style>