<template>
  <div class="card">
  </div>
</template>
<script>
export default {
  name:'Card',
  props:{
    title:{
      type:String
    },
  }
}
</script>
<style scoped>
.card{
  min-width: 300px;
  min-height: 350px;
  box-shadow: -2rem 0 3rem -2rem #000;
  padding: 1.5rem;
  border-radius: 16px;
  background: linear-gradient(
      85deg
      ,#434343,#262626);
  color: #fff;
  display: flex;
  flex-direction: column;
  transition: .2s;
  margin: 0;
  margin-left: -120px;
}
.card:hover{
  transform: rotate(4deg) translateX(-100px);
}
</style>
