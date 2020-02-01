<template>
    <div class="content">
        <div class="imgcontent">
            <Imagem/>
        </div> 
        <div>
            <TxtAcompanhamento/>
        </div>
    </div>
</template>

<script>

import Imagem from "./Imagem"
import TxtAcompanhamento from "./TxtAcompanhamento"

export default {
    name:"Content",
    components:{Imagem, TxtAcompanhamento}
}
</script>

<style>
    .content {
        grid-area: content;
        align-items: center;
    }

    .imgcontent{
        justify-self: center;
    }
</style>