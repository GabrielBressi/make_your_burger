<template>
  <div id="main-banner">
    <h1>Make Your Burger</h1>
  </div>
</template>

<script>
export default{
  name: "Banner"
}
</script>

<style scoped>
 #main-banner{
  background-image: url('/public/img/burger.jpg');
  background-position: 0 -250px;
  background-size: cover;
  height: 500px;
  display: flex;
  align-items: center;
  justify-content:flex-start;
 }

 #main-banner h1 {
  color: #FFF;
  text-align: center;
  font-size: 60px;
  background-color: #222;
  padding: 20px 40px;
 }

 @media screen and (max-width: 2100px) {
  #main-banner{
    background-repeat: no-repeat;
    background-position: 100%;
   
  }
 }


 @media screen and (max-width: 1200px) {
  #main-banner{
    background-repeat: no-repeat;
    background-position: 10%;
  }
 }

 @media screen and (max-width: 900px) {
  #main-banner{
    background-repeat: no-repeat;
    background-position: 10%;
  }

  #main-banner h1 {
    background: rgba(0,0,0,.5);
   }
 }

 @media screen and (max-width: 500px) {
  #main-banner{
    background-position: 90%;
    background-repeat: no-repeat;
   }

   #main-banner h1 {
    background: rgba(0,0,0,.5);
   }
 }
 
</style>