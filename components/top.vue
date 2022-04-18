<template>
  <div class="container">
      <div class="pic">
        <img src="~/static/pic.jpg" alt="">
      </div>
      <div class="center">
      <h1>Hossein Javanbakht</h1>
      <h2>Front-end web developer</h2>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.container {
  display: flex;
  margin-bottom: 20px;
}

h1{
  font-size:24px;
  font-weight: 400;
}
h2{
  font-size: 16px;
  font-weight:400;
}
.pic img{
  width: 60px;
  height: 60px;
  border-radius: 999px;
  margin-right: 20px;
}
@media (min-width: 768px) {
  .container {
    flex-direction: column;
    margin-top: 100px;
    align-items: center
  }
  h1{
    font-size: 48px;
  }
  h2{
    font-size: 32px;
  }
  .pic img{
    width: 100px;
    height: 100px;
    margin-bottom: 10px;
  }
  .center *{
    text-align: center;
  }
}
</style>