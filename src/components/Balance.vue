<template>
    <h4>Your balance</h4>
    <h1 id="blance">{{ total }} DKK</h1>
</template>

<script setup>
import { defineProps } from 'vue';

const props = defineProps ({
    total: {
        type: Number,
        required: true
    },
});
</script>
