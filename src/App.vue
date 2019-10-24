<template>
  <div>
    <div style=" background-color: rgb(106, 175, 245); height: 5px; width:100%"></div>
    <div id="app">
      <br /><br/><br/>
      <h1 style="font-size: 40px; color: grey">Favour ori<span style="color: rgb(106, 175, 245); "><b>.</b></span></h1>
      <br/><br/>

      <p>I am a <u>Software Developer</u> passionate about developing innovative products geared toward making life pretty easy.</p>
      <p>On demand, I write some Backend code (Mostly Node Js).</p>
      <p>
        In my spare time, I teach programming at
        <u>Favcode</u> (which I founded in 2018).
      </p>
      <br />
      <p>
        <b>Tools: &nbsp;</b>
        <span style="color:#535c68">Javascript, Node Js, Python, MongoDB, VueJs, HTML5, CSS3</span>
      </p>
      <br/>
      <hr style="border-top: 1px solid #ecf0f1"/>
      <br/>

      
      <p>I am always open to opportunies, so feel free to reach out.</p>
      <p>
        <a href="https://github.com/favourori">Github</a> &nbsp;&nbsp;
        <a href="mailto:favourori96@gmail.com">Email</a> &nbsp; &nbsp;
        <a href="https://twitter.com/favorori1">Twitter</a>
      </p>
    </div>
  </div>
</template>

<script>

export default {
  name: "app",
  components: {
   
  }
};
</script>

<style>
a {
  text-decoration: none;
  color: #121314;
  position: relative;
}
a:after {
  content: "";
  position: absolute;
  z-index: -1;
  top: 60%;
  left: -0.1em;
  right: -0.1em;
  bottom: 0;
  transition: top 200ms cubic-bezier(0, 0.8, 0.13, 1);
  background-color: rgb(106, 175, 245);
}
a:hover:after {
  top: 0%;
}

.darkmode--activated a:after {
  color: black;
}

.darkmode--activated a {
  color: white;
}

#app {
  padding: 0 17px;
  max-width: 900px;
  margin: 0 auto;
}
</style>
