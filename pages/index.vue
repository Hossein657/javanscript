<template>
<div class="wrapper">
  <top/>
  <cards/>
  <p id="smile">Smile :)</p>
</div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>

<style>
*{
  font-family: 'Nunito', sans-serif;
  margin: 0;
  padding: 0;
}
.wrapper{
  box-sizing: border-box;
  width: 100vw;
  height: 100vh;
  background-color: #010D0A;
  color: #fff;
  padding: 30px
}
#smile{
  position: absolute;
  bottom: 30px;
  left: 50%;
  transform: translate(-50%);
}
</style>