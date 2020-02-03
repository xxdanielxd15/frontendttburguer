<template>

<div class="header">
  <b-navbar class="darktheme" toggleable="lg" type="dark" variant="dark black">
    <b-navbar-brand href="#" class="ttburgertxt">T.T Burger</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="#">{{subtitle}}</b-nav-item>
      </b-navbar-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">

        <b-nav-item-dropdown right>
          <!-- Using 'button-content' slot -->
          <template v-slot:button-content>
            <em>Opções</em>
          </template>
          <b-dropdown-item href="#">logout</b-dropdown-item>
          
        </b-nav-item-dropdown>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>

<script>


export default {
    name:"Header",
    props:{
        title: String,
        subtitle: String,
        titlelogout:String,
    }
}
</script>

<style lang="scss">
    .header {
        grid-area: header;
        background-color: black;
      
    }
    
     @font-face {
        font-family: 'Brothers Regular';
        src: url('../../assets/font/Brothers Regular.otf') format('opentype');
        font-weight: normal;
        font-style: normal;
        line-: 1.5;
    }

    .ttburgertxt{
        font-family: 'Brothers Regular';
        color:#fff;
        font-size: 16px;

        
    }


</style>