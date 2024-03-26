<script>
export default {
  name: 'SideTheme',
  components:{

  }
  
}
</script>

<template>
<asidebar>

<section class="h-100 col-xl-6 col-4 col-lg- row-5">
<ul class="lista-menu">
  <li><h4 class="fw-bolder text-center w-100 h-auto"></h4> </li>
<li>Home</li>
<li>Tutorial</li>
<li>Documentation</li>
<li>Mixer</li>
<li>Contact</li>
<li>Version</li>
</ul>

</section>
</asidebar>

</template>


<style scoped>
.lista-menu{
  height: 100vh;
  height:30%;
  list-style: none;
  font-family: arial;
  font-size: 16px;
  position: fixed;
  color:var(--color-theme);
  background-color: linear-gradientt(to bottom, var(--backgroud-theme) , var(--color-theme));
}
</style>