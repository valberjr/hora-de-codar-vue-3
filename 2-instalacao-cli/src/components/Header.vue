<template>
    <ul>
        <li>
            <a href="#">Home</a>
            <a href="#">Projetos</a>
            <a href="#">Contato</a>
        </li>
        <li v-if="esta_logado">
            <a href="#">Meu Perfil</a>
        </li>
    </ul>
</template>

<script>
export default {
    name: 'Header',
    props: ['esta_logado'],
};
</script>

<style scoped>
ul {
    list-style-type: none;
    display: flex;
    background: #999;
}

li {
    margin-right: 10px;
}

a {
    color: #ddd;
    text-decoration: none;
    transition: none;
}

a:hover {
    color: turquoise;
}
</style>
