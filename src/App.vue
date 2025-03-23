<script setup>
import Navbar from './components/Navbar.vue';
import Carrusel from './components/Carrusel.vue';
import ListaV from './components/ListaV.vue';
import ListaC from './components/ListaC.vue';
import Pie from './components/Pie.vue';
</script>

<template lang>
<Navbar />
<div class="row">
    <div class="col-md-6">
        <Carrusel />
        <ListaC />
    </div>
    
    <ListaV />
    
</div>
<Pie />
</template>

<style scoped>

</style>
