<template>
    <div class="gallery">
        <br><br>
        <h1><b>{{ title }}</b></h1>
        <br><br>
  <img src="@/assets/background.jpg" alt="Image 1">
  <img src="@/assets/sushi.jpg" alt="Image 2">
  <img src="@/assets/temple.jpg" alt="Image 3">
  <img src="@/assets/tradition.jpg" alt="Image 4">
  <img src="@/assets/tourist.jpg" alt="Image 5">
  <img src="@/assets/tradition1.jpeg" alt="Image 6">
  <img src="@/assets/food.jpg" alt="Image 7">
  <img src="@/assets/place.jpg" alt="Image 8">
  <br><br>
    </div>
</template>

<script>
export default{
    name: 'gallery',
    data (){
        return{
            title: 'Gallery'
        }
    }
}
</script>

<style scoped>
.gallery {
  flex-wrap: wrap;
  justify-content: center;
}

.gallery img {
  width: 400px;
  height: 400px;
  margin: 10px;
  object-fit: cover;
  cursor: pointer;
}

.gallery img:hover {
  opacity: 0.7;
}
</style>