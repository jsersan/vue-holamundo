<template>
    <div id ="mi-componente">
        <h1>Este es mi componente</h1>
        <h2>{{subtitulo}}</h2>
    </div>
</template>

<script>
export default {
    name: 'miComponente',
    data() {
        return {
            subtitulo: ' Soy el subtítulo de mi componente'
        }
    }
}
</script>