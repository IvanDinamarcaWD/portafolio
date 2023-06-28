<template>
    <div class="bg-success row w-100 m-0 p-0">
        <div class="row w-100 p-0 m-0">
            <div class="col d-flex justify-content-center">
                <div class="d-flex" id="letra_m">
                    <span class="display-1">M</span>
                </div>
            </div>
            <div class="col d-flex justify-content-center">
                <div class="d-flex" id="letra_v">
                    <span class="display-1">V</span>
                </div>
            </div>
            <div class="col d-flex justify-content-center">
                <div class="d-flex" id="letra_c">
                    <span class="display-1">C</span>
                </div>
            </div>
        </div>
        <div class="row w-100 p-0 m-0 d-flex justify-content-center rounded-4">
            <img src="../../public/img/foto_perfil.jpg" alt="" id="imagen_portafolio" class="mt-5">
        </div>
        <div class="row w-100 p-0 m-0 text-center">
            <h1>I'm Iván Dinamarca</h1>
            <h2>Web Developer</h2>
        </div>
        <div class="row w-100 p-0 m-0 text-white">
            <div class="col bg-black m-3 rounded-4">
                <span class="texto_comandos">>ng serve</span>
            </div>
            <div class="col bg-black m-3 rounded-4">
                <span>>npm run dev</span>
            </div>
            <div class="col bg-black m-3 rounded-4">
                <span>>npm start</span>
            </div>
        </div>
    </div>
</template>

<style scoped>

    #imagen_portafolio{
        width: 250px;
    }

    #letra_m{
        animation-name: sube_y_baja_m;
        animation-duration: 4s;
        animation-delay: 0s;
        animation-iteration-count: infinite;
        position:relative;
    }

    @keyframes sube_y_baja_m{
        0%{top:0px}
        50%{top:120px}
        100%{top:0px}
    }

    #letra_v{
        animation-name: sube_y_baja_v;
        animation-duration: 4s;
        animation-delay: 0.6s;
        animation-iteration-count: infinite;
        position:relative;
    }

    @keyframes sube_y_baja_v{
        0%{top:0px}
        50%{top:120px}
        100%{top:0px}
    }

    #letra_c{
        animation-name: sube_y_baja_c;
        animation-duration: 4s;
        animation-delay: 1.2s;
        animation-iteration-count: infinite;
        position:relative;
    }

    @keyframes sube_y_baja_c{
        0%{top:0px}
        50%{top:120px}
        100%{top:0px}
    }
</style>
