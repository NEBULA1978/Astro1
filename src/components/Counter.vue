<script setup>
import {ref} from 'vue'

const count = ref(0)

</script>

<template>
    <button @clic="count++">Count is: {{ count }}</button>
</template>