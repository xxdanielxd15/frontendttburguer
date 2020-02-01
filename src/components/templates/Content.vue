<template>
    <div class="content">
        <div class="imgcontent">
            <Imagem/>
        </div> 
    </div>
</template>

<script>

import Imagem from "./Imagem"

export default {
    name:"Content",
    components:{Imagem}
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