<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input type="text" class="search-bar" placeholder="Search....">
      </div>
    </main>
  </div>
</template>

<script>


export default {
  name: 'App',
  data(){
    return{
      api_key:'4a9c00033b921686bfd9a3928b67fc29'
    }
  }
  
}
</script>

<style>
*{
  margin:'0';
  padding:'0';
  box-sizing: border-box;
}
body{
  font-family: 'montserrat', sans-serif;

}
#app{
  background-image: url('./assets/cold-w.jpg');
  background-size: cover;
  background-position: bottom;
  transition: 0.4s;
}
main{
  height: 200vh;
  padding:25px;
  background-image: linear-gradient(to bottom, rgba(0,0,0,0.25), rgba(0,0,0,0.75));
}

.search-box{
  width:100%;
  margin-bottom:30px;
}

.search-box .search-bar{
  display:block;
  width:100%;
  padding:15px;

  color:rgb(15, 15, 15);
  font-size: 20px;

  appearance: none;
  border: none;
  outline:none;
  background:none;

  background-color: rgba(255,255,255, 0.5);
  border-radius: 0px 20px 0px 20px;

}
</style>
