  <script>
  export default {
    name: 'AppHero'
  
  }
  </script>


<template>

  <div class="bottom-header flex">
      <div class="b-head container">
        <h1>Il tuo posto per parlare</h1>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sequi asperiores obcaecati enim reprehenderit quasi, laborum, eum optio maxime cupiditate adipisci, illum magnam magni ipsum laboriosam quibusdam voluptatum officia ullam possimus deserunt omnis blanditiis. Deleniti unde recusandae enim facere? Ut, in?
        </p>
        <a href="#" target="_blank" class="btn-big white-black">Scarica per Mac</a>
        <a href="#" target="_blank" class="btn-big black-white">Apri Discord nel tuo browser</a>
      </div>
    </div>
  
</template>


<style scoped>

h1 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

p {
  font-size: 1.2rem;
  line-height: 35px;
}

.btn-big,
a {
  text-decoration: none;
}

.btn-big{
  display: inline-block;
  padding: 15px 20px;
  border-radius: 30px;
}

.white-black {
  background-color: white;
  color: black;
}

.black-white {
  background-color: black;
  color: white;
}

.flex {
  display: flex;
}

.bottom-header {
  color: white;
  background-image: url(../assets/img/jumbo.png);
  background-size: cover;
  background-position: center;
  padding: 130px 0;
}

.bottom-header {
  justify-content: center;
  align-items: center;
}

.b-head {
  max-width: 800px;
  width: 90%;
  min-width: 600px;
  text-align: center;
}

.b-head p {
  margin-bottom: 20px;
}

.b-head a {
  margin: 0 20px;
}

</style>