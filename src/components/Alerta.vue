<script setup>

</script>

<template>
    <div clasS="alerta">
        <slot></slot>
    </div>
</template>

<style scoped>

    .alerta {
        padding: 1rem;
        font-weight: 900;
        text-transform: uppercase;
        font-size: 1.6rem;
        text-align: center;
        background-color: var(--blanco);
        border-left: .5rem solid #891C1C;
        color: #891C1C;
        margin-bottom: 2rem;
    }
</style>