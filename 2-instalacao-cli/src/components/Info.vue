<template>
    <div>
        <p v-if="esta_trabalhando">Estou trabalhando no momento.</p>
        <p v-else>Estou em busca de novas oportunidades</p>
        <p>Utilizo as seguintes Tecnologias:</p>
        <ul>
            <li>Angular</li>
            <li>React</li>
            <li>Vue</li>
        </ul>
        <p v-show="mostrar_email">Mande uma mensagem para: {{ email }}</p>
    </div>
</template>

<script>
export default {
    name: 'Info',
    data() {
        return {
            esta_trabalhando: false,
            mostrar_email: true,
            email: 'junior@email.com',
        };
    },
};
</script>
