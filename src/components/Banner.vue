<template>
  <div class="container">
    <div class="content">
      <div class="text">
        <h1 class="title">Fernanda Rufino</h1>
        <p>Dentista feliz, apaixonada por histórias e sorrisos</p>
      </div>
    </div>
  </div>
</template>

<script>
export default{
  name: 'Banner'
}
</script>

<style lang="scss" scoped>
.container{
  background-color: white;
  .content{
    background-color: red;
    .text{
      width: 100%;
      border: 1px solid pink;
    }
  }
}
</style>