<template>
  <div id="app">
    
    <br />
    <h1 style="font-size: 60px">Hello, I'm Favour ori.</h1>
    <p>I am a Software Engineer - passionate about developing innovative products that'll steer the future of computing.</p>
    <p>In my spare time, I teach programming at <u>Favcode</u> (which I founded in 2018). </p>
    <p>I have worked with a few orgs & companies like <u>CultureBase</u>, <u>SAU</u>, <u>SLU</u>, etc</p>
    <br/>
    <p><b>Tools: </b> <span style="color:#535c68">Javascript, Node Js, MongoDB, VueJs</span> </p>
    
    <p>I am always open to opportunies, so feel free to reach out.</p>
    <p><a href="https://github.com/favourori">Github</a> &nbsp;&nbsp;  <a href="favourori96@gmail.com">Email</a> &nbsp; &nbsp;  <a href="https://twitter.com/favorori1">Twitter</a> </p>
    
  </div>
</template>

<script>
export default {
  name: "app",
  components: {}
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
  background-color: #fca6a6;
}
a:hover:after {
  top: 0%;
}

.darkmode--activated a:after{
 
  color: black

}

.darkmode--activated a{
  
  color: white

}

</style>
