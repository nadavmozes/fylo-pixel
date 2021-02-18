<template>
    <button class="btn-blue white">
        <slot></slot>
    </button>
</template>

<style>
.btn-blue {
    background-color: #44b2d0;
    font-weight: 700;
    border-radius: 100px;
    padding: 15px 40px 15px 40px;
    cursor: pointer;
    border: none;
    outline: none;
    font-size: 15px;
}
</style>

