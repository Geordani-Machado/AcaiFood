<template>
    <div>
        <Header/>
        <h1>Home</h1>
        <p>Welcome to the Home page</p>
    </div>
</template>

<script>
import Header from '../components/Header.vue';

export default {
    name: 'Home',
    mounted() {
        document.title = 'Home';
    },
    components: {
        Header
    }
}
</script>