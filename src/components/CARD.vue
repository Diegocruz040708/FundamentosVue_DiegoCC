<script setup>
// Metodos
</script>
<template>    
<!-- Estructura html -->
    
    <div class="container">
        <h1 class="text-center">Sistema Solar</h1>
        <!-- Inicio del primer row -->
        <div class="row">
            <div class="col-md-6">
                <div class="card text-center">
                    <div class="card-header">
                        <h6>Sol</h6>
                    </div>
                    <div class="card-body">
                        <img width="200" lang="200" src="https://amautas.com/wp-content/uploads/2023/06/C037_EP01-min.jpg" alt="sol">
                        <p class="card-text">Es la estrella central del Sistema Solar y su gravedad es la que mantiene
                             unidos a todos los cuerpos celestes. </p>
                    </div>
                </div>
            </div>

            <div class="col-md-6">
                <div class="card text-center">
                    <div class="card-header">
                        <h6>Planetas</h6>
                    </div>
                    <div class="card-body">
                        <img width="200" lang="200" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRGnIkuu9zGUTUnLXGE3oMcInu1faTcqu3MZQ&s" 
                        alt="planetas">
                        
                        <p class="card-text">El Sistema Solar contiene ocho planetas: 
                            Mercurio, Venus, Tierra, Marte, Júpiter, Saturno, Urano y Neptuno.</p>    
                    </div>
                </div>
            </div>
        </div>
        <!-- fin del primer row -->

        <!-- Inicio del segundo row -->
         <div class="row mt-4">

            <div class="col-md-4">   
            <div class="card" style="width: 18rem;">
                <img src="https://content.nationalgeographic.com.es/medio/2022/07/31/el-planeta-mercurio_3bcc14b3_1200x630.jpg" class="card-img-top" alt="mercurio">
                <div class="card-body text-center">
                    <p class="card-text">Mercurio es el planeta del sistema solar más cercano al Sol y el más pequeño. 
                        Recibió su nombre del dios romano Mercurio. 
                        Forma parte de los denominados planetas interiores y carece de satélites naturales al igual que Venus.</p>
                         <button class="btn btn-warning">Más información</button>
                </div>
            </div>
            </div>

            <div class="col-md-4">   
            <div class="card" style="width: 18rem;">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSt-RyLfCryPlP4DcgGbZyBQDH77Yx_eOGhbQ&s" class="card-img-top" alt="venus">
                <div class="card-body text-center">
                    <p class="card-text">Venus es un planeta rocoso, terrestre y caliente, con una atmósfera densa y tóxica. 
                        Es uno de los cuatro planetas interiores del sistema solar, junto con la Tierra, Marte y Mercurio. </p>
                         <button class="btn btn-warning">Más información</button>
                </div>
            </div>
            </div>

            <div class="col-md-4">   
            <div class="card" style="width: 18rem;">
                <img src="https://static.nationalgeographic.es/files/styles/image_3200/public/940.jpg?w=1600" 
                class="card-img-top" alt="tierra">
                <div class="card-body text-center">
                    <p class="card-text">La Tierra es el planeta donde vivimos, 
                        el tercer planeta del sistema solar y el único que se sabe que alberga vida. </p>
                         <button class="btn btn-warning">Más información</button>
                </div>
            </div>
            </div>
         </div>
        <!-- fin del segundo row -->

    </div>
</template>

<style scoped>
/* Estilos css */
</style>