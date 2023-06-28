<template>
    <div>
        <div class="row">
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
    </div>
</template>

<style scoped>
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
