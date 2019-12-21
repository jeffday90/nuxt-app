<template>
    <div>
        <Header />
        <header class="users-header">
            USERS SECTION
        </header>
        <nuxt />
    </div>
</template>

<script>
import Header from '~/components/Header.vue'

export default {
    components: {
        Header
    }
}
</script>

<style scoped>
    .users-header {
        text-align: center;
        padding: 10px;

    }
</style>