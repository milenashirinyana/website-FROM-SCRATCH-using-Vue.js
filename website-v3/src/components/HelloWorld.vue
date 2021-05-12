<template>
  <div class="hello">
    <div class="menu">
      <ul class="ul">
        <li class="">Resume</li>
        <li class="">Skating</li>
        <li class="li">Kylie Ying</li>
        <li class="">YouTube</li>
        <li class="">About</li>
      </ul>
    </div>
    <div class="app">
        <h1 class="h1">K</h1>
        <h1 class="h1_1">Y</h1>
        <h1 class="h1_2">L</h1>
        <h1 class="h1_3">I</h1>
        <h1 class="h1_4">E</h1>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
ul li{
  list-style: none;
  padding: 16px 10px 0px 10px;
}
ul{
  width: 100%;
  padding-left:0px
}
li{
  text-align: center;
  width:23%;
  font-size:20px;
  color:rgba(80, 64, 19, 0.705);
  transition: 0.3s;
}
li:hover{
  cursor: pointer;
  filter: drop-shadow(1px 1px 1px rgb(255, 255, 255));
}
.li{
  font-size:30px ;
  color:rgba(68, 54, 16, 0.87);
}
.ul{
  width: 100%;
  display: flex;
  justify-content: center;
}
.menu{
  display: flex;
  justify-content: center;
}
.app{
    display: flex;
    letter-spacing: 20px;
    font-size:205px;
    justify-content: center;
}
h1{
    margin:0px;
    font-family: system-ui;
    font-weight: 900;
}
.h1{
    background-image: url("https://i.pinimg.com/564x/25/e2/1f/25e21f99b60c371f6b790186aa83fe98.jpg");
    background-size:cover;
    color: transparent;
    -webkit-background-clip: text;
    background-position: unset;
    filter: drop-shadow(1px 1px 5px #000);
}
.h1_1{
    background-image: url("https://i.pinimg.com/564x/03/29/d5/0329d5f153a620ccd3dea83e997a2817.jpg");
    background-size:cover;
    color: transparent;
    -webkit-background-clip: text;
    background-position: right;
    filter: drop-shadow(1px 1px 5px #000);
}
.h1_2{
    background-image: url("https://i.pinimg.com/564x/e9/03/03/e903037980b9d3223e55a59f269fff08.jpg");
    background-size: cover;
    color: transparent;
    -webkit-background-clip: text;
    background-position: right;
    filter: drop-shadow(1px 1px 5px #000);
}
.h1_3{
    background-image: url("https://i.pinimg.com/564x/ea/29/0f/ea290f5cf21a63354b4863bb3c1a071b.jpg");
    background-size: contain;
    color: transparent;
    -webkit-background-clip: text;
    background-position: center;
    filter: drop-shadow(1px 1px 5px #000);
}
.h1_4{
    background-image: url("https://i.pinimg.com/564x/38/d1/c9/38d1c986afbb0aaf985becbd7ace9045.jpg");
    background-size: 100% 100%;
    color: transparent;
    -webkit-background-clip: text;
    background-position: revert;
    filter: drop-shadow(1px 1px 5px #000);
}
</style>
