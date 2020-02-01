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
        padding: 20px;
        align-items: center;
    }

    .imgcontent{
        justify-self: center;
        border: 2px solid black;
    }
</style>