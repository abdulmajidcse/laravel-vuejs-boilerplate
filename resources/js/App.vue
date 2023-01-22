<script>
export default {
    data() {
        return {
            count: 0,
        };
    },
};
</script>

<template>
    <h2>Laravel Vuejs Boilerplate</h2>
    <button @click="count++">Count is: {{ count }}</button>
</template>
