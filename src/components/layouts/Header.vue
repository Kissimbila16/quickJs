<script>
export default {
  name: "HeaderLayout",
  components: {},
};
</script>
<template>
  <header class="d-flex justify-center-between row align-items-center m-0">
    <div class="title col-2 ml-0" style="margin-left: 1%">
      <h2 class="text-left w-100 m-0 tc">Quick.js</h2>
    </div>
    <div class="ways col-6 m-l-2">
      <ol class="d-flex align-items-center w-1 mt-4">
        <li>
          <a href="#">Docs</a>
        </li>
        <li>
          <a href="#">Template</a>
        </li>
        <li>
          <a href="#">Learn</a>
        </li>
        <li>
          <a href="#">Analytics</a>
        </li>
      </ol>
    </div>
    <div class="btn-left d-flex justify-content-rigth col-2">
      <button class="btn" style="color: var(--color-theme)">
         <a href="#interpreter">Editor</a>
      </button>
      <button
        class="btn btn-transparent"
        style="background: var(--color-theme); color: var(--background-theme)"
      >
        <a href="#learning">Learn</a>
      </button>
      <button
        class="btn btn-transparent git"
        style="background: var(--color-theme); color: var(--background-theme)"
      >
        <a href="https://github.com/Kissimbila16/QuickFrame">github</a>
      </button>
    </div>
  </header>
</template>
<style scoped>
.btn {
  height: 35px;
  margin: 5px;
}

h2 {
  color: var(--color-theme);
  margin-left: 1%;
}
header{
  height: 60px;
  background: var(--background-theme)!important;
}
.tc,.ways,.btn-left,.title{
  background: var(--background-theme);

}

ol {
  list-style: none;
  text-align: left;
}

li {
  color: var(--color-theme);
  margin-left: 2%;
}
a{
   text-decoration: none;
    color:var(--background-color);
}

.git {
  visibility: visible;
}
@media (max-width: 700px) {
  ol {
    visibility: hidden;
  }
  .git {
    visibility: hidden;
  }
}
</style>
