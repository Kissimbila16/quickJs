<script>
export default {
  name: "FootLayout",
  components: {},
  data(){
    return{
      nome:"DomingosKJ"
    }
  }
};
</script>

<template>
  <footer
    
    style="background: var(--background-footColor);width: 100%; margin: auto"  >
  <h4 class="fw-light fs-3 mt-2 " style="color:var(--color-theme)">
    <br>
    Can you combine with 
  </h4>
    <div
    style="width:90%;margin: auto"
      class="row d-flex  gap-2 m-t-3 col-xl-12 col-lg-12 col-sm-12"
    >
      <div
        class="col-4 col-sm-12 col-xl mt-4 rounded-2 d-flex align-items-center alto"
        style="height: 200px; background-color: var(--color-theme)"
      >
        <ol style="list-style:none;width:100%">
          <li>
              <a href="#https://tsed.io/">Ts.ed</a>
          </li>
          <li>
              <a href="#https://adonisjs.com/">Adonis.js</a>
          </li>
          <li>
              <a href="#https:expressjs.com/">express.js</a>
          </li>
        </ol>
      </div>
      <div
        class="col-4 col-sm-12 col-xl mt-4 rounded-2 d-flex align-items-center alto"
        style="height: 200px; background-color: var(--color-theme)"
      >
         <ol style="list-style:none;width:100%">
          <li>
              <a href="https://nestjs.com/">nest.js</a>
          </li>
          <li>
              <a href="https://feathersjs.com/">feathers.js</a>
          </li>
          <li>
              <a href="https://koajs.com/">koa.js</a>
          </li>
        </ol>
      </div>
      <div
        class="col-4 col-sm-12 col-xl mt-4 rounded-2 d-flex align-items-center alto"
        style="height: 200px; background-color: var(--color-theme)"
      >
         <ol style="list-style:none;width:100%">
          <li>
              <a href="https://docs.djangoproject.com/en/5.0/">Django</a>
          </li>
          <li>
              <a href="https://spring.io/">SpringBoot</a>
          </li>
          <li>
              <a href="https://laravel.com/docs/11.x">laravel</a>
          </li>
        </ol>
      </div>
    </div>
    <div class="row-12 d-grid w-100">
      <hr style="color: var(--color-theme);margin-top:5%">
      <div
        class="d-flex justify-content-center gap-3 align-items-center"
        style="height: 200px"
      >
        <a  style="text-decoration:none;color:var(--color-theme)"  href="mailto:doncajoblac@gmail.com">Email</a>
        <a href="https://wa.me/+244938256058?text=Hello" style="text-decoration:none;color:var(--color-theme)">Whatshapp</a>
      </div>
      <h4 class="text-center fs-5 text-secondary">
        @2024{{nome}}|all reserved
      </h4>
      <br />
    </div>
  </footer>
</template>
<style scoped>
h4 {
  font-family: arial;
  font-weight: 300;
  font-size: 25px;

}
a{
  font-size: 25px;
  font-family: arial;
  font-weight: 200;
  margin-left:1%;
   text-decoration: none;
    color:var(--background-color);
}
li{
   height: 60bpx;
   width: 100%;
    color:var(--background-color);
    margin-top:1%;
}

</style>
