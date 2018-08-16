<template>
  <div>
    <div class="background">

      <div class="inset-box">
        <h2>Giving sick kids a power up!</h2>
        <p>Donate video games and consoles to hospitals across the United States</p>
        <button type="button" name="button">Donate now!</button>

        <img class="home-image" src="../../assets/home-image.jpg" alt="">
      </div>

    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {

    }
  }
}
</script>

<style>

button {
  appearance: none;
  border: none;
  display: inline-block;
  background-color: #C3162E;
  padding: 10px 15px;
  color: #fff;
  font-weight: 700;
  -moz-border-radius: 10px;
  -webkit-border-radius: 10px;
  -ms-border-radius: 10px;
  -o-border-radius: 10px;
  border-radius: 10px;
}

h2, p {
  font-family: 'Helvetica', sans-serif;
}
.background {
  height: 500px;
  background-color: #3D3B6F;
  display: flex;
  align-items: center;
  justify-content: center;
}

.inset-box {
  height: 75%;
  width: 75%;
  background-color: white;
  box-shadow: 5px 10px #adabd3;
}

.home-image {
  object-fit: cover;
  height: 200px;

}
</style>
