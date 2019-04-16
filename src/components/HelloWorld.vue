<template>
  <div class="main">
    <router-link class="content" to="/info">
      <img src="//m.360buyimg.com/babel/jfs/t1/1468/11/3377/138213/5b997bf3Eda5b24a4/0ace3ed19582dbe6.jpg!q70.jpg" alt="">
      <p>价格：123</p>
    </router-link>
    <router-link class="content" to="/info"></router-link>
    <router-link class="content" to="/info"></router-link>
    <router-link class="content" to="/info"></router-link>
    <router-link class="content" to="/info"></router-link>
    <router-link class="content" to="/info"></router-link>
    <router-link class="content" to="/info"></router-link>
  </div> 
</template>
<script>
export default {
  name: 'HelloWorld',
  data(){
    return {}
  }
}
</script>
<style scoped>
.main {
  display: flex;
  flex-wrap: wrap;
}
.content {
justify-content: space-between;
height: 260px;
width: 165px;
background-color: #eee;
margin: 5px;
}
.content img {
  width: 100%;
  margin-bottom: 10px;
}
.content p {
  font-size: 12px;
}
</style>

