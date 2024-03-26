<template>
 <div>
   <HelloWorld/>
 </div>
</template>
<script>
import HelloWorld from './components/HelloWorld.vue'
export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style global>

*{
   font-family: arial!important;;
}

:root{
  --background-theme:#191552;
  --background-foot:#000b0d;
  --background-footColore:linear-gradient(to top , var(--background-theme),var(--slogan-theme));
  --background-footColor:var(--background-foot);
  --color-theme:#6ee2f5;
  --icon-theme:#6ee2f5;
  --slogan-theme:#000000;
}


#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
div{
   margin-top:0%;
   background: var(--background-footColor);
}
</style>
