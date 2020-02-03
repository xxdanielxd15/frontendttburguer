<template>


  <div class='table-responsive' style="width:1100px">
 <!--Table-->
 <table id="tablePreview" class="table table-sm table-striped table-bordered">
 <!--Table head-->
   <thead>
     <tr class="trfields">
       <th>Data</th>
       <th>Vendas(R$)</th>
       <th>Meta(R$)</th>
       <th>Atingimento de meta(%)</th>
       <th>Quantidade de produtos/cliente</th>
       <th>Ticket médio / cliente</th>
     </tr>
   </thead>
   <!--Table head-->
   <!--Table body-->
   <tbody>

     <tr>
       <th scope="row" class="txtfield">Arpoador</th>
       <td class="aligncenter">0</td>
       <td class="aligncenter">11.200</td>
       <td class="aligncenter">0,0%</td>
       <td class="aligncenter">0,0</td>
       <td class="aligncenter">0,0</td>   
     </tr>

     <tr>
       <th scope="row" class="txtfield">Leblon</th>
       <td class="aligncenter">0</td>
       <td class="aligncenter">12.332</td>
       <td class="aligncenter">0,0%</td>
       <td class="aligncenter">0,0</td>
       <td class="aligncenter">0,0</td> 
     </tr>

     <tr>
       <th scope="row" class="txtfield">Barra</th>
       <td class="aligncenter">0</td>
       <td class="aligncenter">5.418</td>
       <td class="aligncenter">0,0%</td>
       <td class="aligncenter">0,0</td>
       <td class="aligncenter">0,0</td>      
     </tr>

     <tr class="trtotal">
       <th scope="row" class="txtfield">Total</th>
       <td class="aligncenter">0</td>
       <td class="aligncenter">28.950</td>
       <td class="aligncenter">0,0%</td>
       <td class="aligncenter">0,0</td>
       <td class="aligncenter">0,0</td>
     </tr>

   </tbody>
   <!--Table body-->
 </table>
 <!--Table-->
</div>

</template>

<script>
export default {
    name:"Tabela",
}
</script>

<style>
    .divtabela{
        width: 800px;
        align-self: center
    }

    .trfields{
        background-color:#242424;
        color: #fff;
        text-align: center
    }

    .txtfield{
        text-align: center;
        color: #1373d4;
    }

    .aligncenter{
        text-align: center;
    }

    .trtotal{
        background-color: #b5b5b5
    }

    .widthtable{
        width: 950px
    }
  
</style>