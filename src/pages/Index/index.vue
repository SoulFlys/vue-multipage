<template>
  <div id="index">
      <p>当前为首页</p>
      <a href="/detail.html">内页</a>
  </div>
</template>

<script>
  export default {
    name: 'index',
    mounted(){
        var a = [1,2,3]
        console.log('index');
        _.map(a,v=>{
            console.log(v)
        })
    }
  };
</script>
