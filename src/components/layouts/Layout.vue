<script>
export default {
  name: "LayoutTheme",
  components: {},
  data() {
    return {
      sintaxe: "",
      helloQuick: "",
      ExtQuick: "",
    };
  },
};
</script>

<template>
  <div>
    <section class="d-grid col-sm-12 col-xl-12">
      <div class="w-100 col gap-3 d-grid h-75">
        <br />
        <h2
          class="text-white text-left w-100 mt-5 color-primary"
          style="font-size: 61px; font-family: arial"
        >
          Quick.js
        </h2>

        <h5 class="w-100 row-12 d-flex justify-content-center">
          <h6 class="fs-3 w-75 text-center text-light" style="margin-left: 12%">
            Now you will Write <b>easy</b> and <b>fast</b> using Html, Css and
            Ts
          </h6>
        </h5>
        <h4 class="fs-5 text-center" style="color: var(--color-theme)">
          Qrite fast and Easy with Quick
        </h4>
        <div class="fs-5">
          <br />
          <button
            class="btn btn-transparent fw-bolder border-1 border-secondary"
            style="
              width: auto%;
              color: var(--background-theme);
              background: var(--color-theme);
            "
          >
            Getting Started
          </button>

          <button
            class="btn border-1 border-primary"
            style="
              width: 15%;
              margin-left: 5px;
              color: var(--color-theme);
              background: var(--background-theme);
            "
          >
            Learn
          </button>
        </div>
      </div>
    </section>
  </div>
  <br />
  <h4 class="fw-light fs-3 mt-2" style="color: var(--color-theme)">
    what should you use quick.js
  </h4>
  <div style="width: 90%; margin: auto">
    <div class="row d-flex w-100 m-t-3 gap-5 m-l-0">
      <div
        class="col-sm-12 col-xl mt-4 rounded-2 d-flex align-items-center alto"
        style="
          height: 220px;
          margin-bottom: 4%;
          margin-top: 4% !important;
          background-color: var(--color-theme);
        "
      >
        <div class="d-grid tm">
          <b>
            <h3>sample</h3>
          </b>
          to build3 yours website using Quick ,can you code big things in few
          lines
        </div>
      </div>
      <div
        class="col-sm-12 col-xl mt-4 rounded-2 d-flex align-items-center alto"
        style="
          height: 220px;
          margin-bottom: 4%;
          margin-top: 4% !important;
          background-color: var(--color-theme);
        "
      >
        <div class="d-grid tm">
          <b>
            <h3>Fast to write</h3>
          </b>
          coming with tools to simply your works, making you qrite fast and more
          complex cody
        </div>
      </div>
      <div
        class="col-sm-12 col-xl mt-4 rounded-2 d-flex align-items-center alto"
        style="
          height: 220px;
          margin-bottom: 4%;
          margin-top: 4% !important;
          background-color: var(--color-theme);
        "
      >
        <div class="d-grid tm">
          <b>
            <h3>Typed for more security</h3>
          </b>
          to make you codes more save , we use typed language for more security
          of the language and the templates
        </div>
      </div>
      <div
        class="col-sm-12 col-xl mt-4 rounded-2 d-grid tm align-items-center alto"
        style="
          height: 220px;
          margin-bottom: 4%;
          margin-top: 4% !important;
          background-color: var(--color-theme);
        "
      >
        <div class="d-grid tm">
          <b>
            <h3>Is like html and Ts in one Sheet</h3>
          </b>
          Using Static template and dinamic templates to make the webpage more
          dinamic and sample in the template all in one page , if you want use
          MVC you can use importing the templates
        </div>
      </div>
    </div>

    <br />
    <h4 class="fw-light fs-3 mt-2" style="color: var(--color-theme)">
      About quick.js
    </h4>
    <div
      class="middle d-flex justify-content-center align-center mt-3 col-xl-12 col-sm-12"
    >
      <div
        class="row-12 w-100 m-t-1 d-grid align-items-center justify-content-center h-100"
      >
      <div id="demo" class="carousel slide" data-bs-ride="carousel">

  <!-- Indicators/dots -->
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
     <button type="button" data-bs-target="#demo" data-bs-slide-to="3"></button>
    <button type="button" data-bs-target="#demo" data-bs-slide-to="4"></button>
  </div>

  <!-- The slideshow/carousel -->
  <div class="carousel-inner">
    <div class="carousel-item active ">
      <img src="./../../assets/arrive.jpg" alt="Los Angeles" class="d-block w-100 h-100">
        <div class="carousel-caption">
    <h3>Quick.js</h3>
    <p>Is a framework of javascript for web development Using HTML, TS and CSS3 , and take some thing of Angular!</p>
  </div>
    </div>
    <div class="carousel-item">
      <img src="./../../assets/algo.png" alt="Chicago" class="d-block w-100 h-100 w-100">
        <div class="carousel-caption">
    <h3>Is like JS</h3>
    <p>We can work with IA using libs in Quick.js</p>
  </div>
    </div>
    <div class="carousel-item">
      <img src="./../../assets/loveDo.jpg" alt="New York" class="d-block w-100 h-100 w-100">
        <div class="carousel-caption">
    <h3>We can create</h3>
    <p>You can do what you want do in quick.js!</p>
  </div>
    </div>
     <div class="carousel-item">
      <img src="./../../assets/icon.png" alt="New York" class="d-block w-100 h-100 w-100">
        <div class="carousel-caption">
    <h3>Is Typed</h3>
    <p>We need typed things for more security</p>
  </div>
    </div> <div class="carousel-item">
      <img src="./../../assets/icon.png" alt="New York" class="d-block w-100 h-100 w-100">
        <div class="carousel-caption">
    <h3>Now</h3>
    <p>We can work more fast !</p>
  </div>
    </div>
  </div>

  <!-- Left and right controls/icons -->
  <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
  </button>
</div>
      </div>
    </div>

    <br />
    <h4 class="fw-light fs-3 mt-2" style="color: var(--color-theme)">
      Uses of quick.js
    </h4>
    <div class="row d-flex justify-content-center w-100 m-t-3 gap-5 m-l-0">
      <div class="row d-flex w-100 m-t-3 gap-2 m-l-0">
        <div
          class="col-sm-12 col-xl mt-1 rounded-2 d-flex align-items-center alto"
          style="
            height: 170px;
            margin-bottom: 1%;
            margin-top: 1% !important;
            background-color: var(--color-theme);
          "
        >
          Using html to make templates and static and dinamic pages using
          quick.js on front
        </div>
        <div
          class="col-sm-12 col-xl mt-1 rounded-2 d-flex align-items-center alto"
          style="
            height: 170px;
            margin-bottom: 1%;
            margin-top: 1% !important;
            background-color: var(--color-theme);
          "
        >
          Using css the very sample css to make style of page the quick.js use
          Css to make all the style oif the page
        </div>
        <div
          class="col-sm-12 col-xl mt-1 rounded-2 d-flex align-items-center alto"
          style="
            height: 170px;
            margin-bottom: 1%;
            margin-top: 1% !important;
            background-color: var(--color-theme);
          "
        >
          Using ts for make the logic part of the page and using the typed to
          make more security and the page
        </div>
      </div>
      <div class="row d-flex w-100 m-t-3 gap-2 m-l-0">
        <div
          class="col-sm-12 col-xl mt-1 rounded-2 d-flex align-items-center alto"
          style="
            height: 170px;
            margin-bottom: 4%;
            margin-top: -3% !important;
            background-color: var(--color-theme);
          "
        >
          Using struture to make validations and connections via AJAX , may you
          use functions and variables
        </div>
        <div
          class="col-sm-12 col-xl mt-1 rounded-2 d-flex align-items-center alto"
          style="
            height: 170px;
            margin-bottom: 4%;
            margin-top: -3% !important;
            background-color: var(--color-theme);
          "
        >
          Using services to simply the connections with athers classes em using
          SOLID formatt
        </div>
        <div
          class="col-sm-12 col-xl mt-1 rounded-2 d-flex align-items-center alto"
          style="
            height: 170px;
            margin-bottom: 4%;
            margin-top: -3% !important;
            background-color: var(--color-theme);
          "
        >
          Using AJAX to make de connections with APIs and same to give response
          JSON
        </div>
      </div>
    </div>
    <br />
    <h4 class="fw-light fs-3 mt-2" style="color: var(--color-theme)">
      Quick.js is use for
    </h4>
    <div class="row d-flex w-100 m-t-3 gap-5 m-l-0">
      <div
        class="col-sm-12 col-xl mt-4 rounded-2 d-flex align-items-center alto"
        style="
          height: 420px;
          margin-bottom: 4%;
          margin-top: 4% !important;
          background: var(--background-footColor);
        "
      >
        <div class="d-flex justify-content-center align-items-center w-100">
          <div class="d-grid row-12 w-100 text-warning">
            <h4 class="mt-3" style="color: var(--color-theme)">
              Sintaxe Hello Word
            </h4>
            <hr style="color: var(--color-theme); border-width: 10px" />
            <h5
              class="text-left w-100"
              style="text-align: left; margin-left: 15%"
            >
              &lt;html lang="pt-ao" <br />
              data{ var helloText="Hello World" }
              <br />
              &lt;head config={title:"Hello World page" }&#47;&gt; <br />
              &lt;body <br />
              data(){ <br />
              &#47;&#47;give me a commentary<br />
              } &#47;&gt; <br />
              &lt;foot <br />
              data(){ } <br />
              @helloText &#47;&gt; <br />

              &#47;&gt;
            </h5>
          </div>
        </div>
      </div>
      <div
        class="col-sm-12 col-xl mt-4 rounded-2 d-flex align-items-center alto"
        style="
          height: 420px;
          margin-bottom: 4%;
          margin-top: 4% !important;
          background: var(--background-footColor);
        "
      >
        <div class="d-grid row-12 w-100 text-warning">
          <h4 class="mt-3" style="color: var(--color-theme)">Sintaxe</h4>
          <hr style="color: var(--color-theme); border-width: 10px" />
          <h5
            class="text-left w-100"
            style="text-align: left; margin-left: 15%"
          >
            &lt;html lang="pt-ao" <br />
            data{ }
            <br />
            &lt;head config={title:"Hello World page" }&#47;&gt; <br />
            &lt;body <br />
            data(){ } &#47;&gt; <br />
            &lt;foot <br />
            data(){ } <br />
            &#47;&gt; <br />

            &#47;&gt;
          </h5>
        </div>
      </div>
      <div
        class="col-sm-12 col-xl mt-4 rounded-2 d-flex align-items-center alto"
        style="
          height: 420px;
          margin-bottom: 4%;
          margin-top: 4% !important;
          background: var(--background-footColor);
        "
      >
        <div class="d-grid row-12 w-100 text-warning">
          <h4 class="mt-3" style="color: var(--color-theme)">
            Sintaxe sum two variables
          </h4>
          <hr style="color: var(--color-theme); border-width: 10px" />
          <h5
            class="text-left w-100"
            style="text-align: left; margin-left: 15%"
          >
            &lt;html lang="pt-ao" <br />
            data{ string h, w; <br />
            h="Hello";<br />
            w="World";<br />
            var hw=h+w; }
            <br />
            &lt;head config={title:"Hello World page" }&#47;&gt; <br />
            &lt;body <br />
            data(){ } <br />
            &lt;h4&gt;@hw &lt;/h4&gt; &#47;&gt; <br />
            &lt;foot <br />
            data(){ } <br />
            &#47;&gt; <br />

            &#47;&gt;
          </h5>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.color-primary {
  background: linear-gradient(
    to top,
    var(--background-theme),
    var(--color-theme)
  );
  background-clip: text;
  -webkit-text-fill-color: transparent;
}

section {
  height: 610px;
  background: var(--background-foot);
}

.middle {
  background: var(--color-footColor);
  height: 605px;
  margin-bottom: 4%;
  border-color:var(--color-theme)
}

.col4,
.col6 {
  background: var(--color-theme);
  height: 90%;
  border-radius: 10px;
}
.tm{
  background: var(--color-theme);
}
.alto {
  margin-left: 1.5%;
}
.alto:hover {
  margin-top: 5px;
  transition: margin-top 2s;
  opacity: 0.6;
}

.fs-3 {
  color: var(--color-theme) !important;
}
.carousel-item{
   width: 500px;
}
</style>
