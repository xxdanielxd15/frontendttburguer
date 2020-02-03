<template>
    <div class="content">
        <div class="imgcontent">
            <Imagem/>
        </div> 
        <div>
            <TxtAcompanhamento/>
        </div>
        <Tabela/>
    </div>
</template>

<script>

import Imagem from "./Imagem"
import TxtAcompanhamento from "./TxtAcompanhamento"
import Tabela from "./Tabela"

export default {
    name:"Content",
    components:{Imagem, TxtAcompanhamento, Tabela}
}
</script>

<style>
    .content {
        grid-area: content;
        display: flex;
        flex-direction:column;
        justify-content: center;
        align-items: center
    }

    .imgcontent{
        justify-self: center;
    }
</style>