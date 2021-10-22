<template>
  <div id="app">
<!--    <img src="./assets/logo.png"> -->
<img src="./img/logo.png" width="38px">
<router-view name="header"></router-view>
    <router-view/>
    <router-view name="footer"></router-view>
  </div>
</template>

<script>
export default {
  name: 'App'
}

</script>

<style>
#app {
}
@import url('https://fonts.googleapis.com/css2?family=Noto+Serif+TC:wght@200;300;400;500;600;700&display=swap');

body {
  background-color: #19caad20;
  font-family: 'Noto Serif TC', serif;
  letter-spacing: 4.5px;
}
section {
  padding: 20px 40px;
}
h1,h2,h3,h4,h5 {
  font-size: 24px;
  font-family: 'Noto Serif TC', serif;
  letter-spacing: 31px;
}
p{
  color: #7e7e7e;
}
h1.titlestyle:before{
  content: '';
  position: absolute;
  width: 37vw;
  height: 1px;
  left: 0;
  margin-top: 22px;
  clear: both;
  background-color: #AF6363;
}
h1.titlestyle:after{
  content: '';
  position: absolute;
  width: 37vw;
  height: 1px;
  right: 0;
  margin-top: 22px;
  clear: both;
  background-color: #AF6363;
}

ul,li {
  margin: 0;
  padding: 0;
  justify-content: center;
    display: table-cell;
  vertical-align: middle;

}
a{
  text-decoration:none!important;
}
.header-top{
  background-color: #FFF5E2;
  position: sticky;
}
.booking-icon{
  background-color: #E58E9B;
  padding: 20px;
  border-radius: 0 0 20px 20px;
  color: #ffffff;
  text-decoration:none;
  display: flex;
  right: 120px;
  position: absolute;
  top: 0;
}

ul.header-top-link li{
  color: #847A62;
  font-size: 10px;
  white-space:nowrap;
}
ul.header-top-link li a{
  color: #847A62;
}

header {
  background-color: #845B5B;
}

.logo img {
  position: relative;
  top: 42px;
  right: 20px;
}
ul.header-menu li{
  color: #ffffff;
  border-right: 1px solid #ffffff;
  margin: 14px;
  padding-right: 30px;
}

ul.header-menu li a:hover {
  content: "";
  background-image: url("./img/linkicon.png");
  background-repeat: no-repeat;
  background-position: 32px 180px;
  color:#847A62;
}
  

.banner-block{
  height: 100vh;
  width: 100vw;
}
.banner-block img{
  width: 100vw;
  max-width: 100%;
}


</style>
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet">
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css">
<link rel="stylesheet" href="https://pro.fontawesome.com/releases/v5.10.0/css/all.css" integrity="sha384-AYmEC3Yw5cVb3ZcuHtOA93w35dYTsvhLPVnYs9eStHfGJvOvKxVfELGroGkvsg+p" crossorigin="anonymous"/>
<link href="./css/style.css" rel="stylesheet" type="text/css">