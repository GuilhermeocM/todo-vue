<script setup>
    const props = defineProps(['terefasPendentes'])
</script>
<template>
<header class="p-5 mb-4 mt-4 bg-light rounded-3">
    <h1>Minhas tarefas</h1>
    <p>
        Você possui {{ props.terefasPendentes }} tarefas pendentes
    </p>
</header>
</template>