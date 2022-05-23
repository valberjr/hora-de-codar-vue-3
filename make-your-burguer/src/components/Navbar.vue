<template>
    <div>
        <router-link to="/">
            <img src="" id="logo" />
        </router-link>
        <nav id="nav">
            <router-link to="/">Home</router-link> |
            <router-link to="/pedidos">Pedidos</router-link>
        </nav>
    </div>
</template>

<script>
export default {
    name: 'Navbar',
};
</script>

<style scoped></style>
