<template>
    <div class="great-examples">
       <section class="example-item" v-for="(item,i) in examples" :key="i">
           <header :style="{'backgroundImage': `url(${item.img}`}"></header>
           <p>{{item.name}}</p>
        </section>
    </div>
</template>
<script>
export default {
   name: 'great-examples',
   data() {
       return {
           examples: [
                {
                id: 1212,
                img: require('~/assets/images/1.jpg'),
                name: '伺服电机',
                },
                {
                id: 1212,
                img: require('~/assets/images/2.jpg'),
                name: '伺服电机',
                },
                {
                id: 1212,
                img: require('~/assets/images/3.jpg'),
                name: '伺服电机',
                },
                {
                id: 1212,
                img: require('~/assets/images/4.png'),
                name: '伺服电机',
                }
            ]
       }
   }
}
</script>
<style lang="less">
.great-examples {
    display: flex;
    width: 800px;
    margin: 20px auto;
   .example-item {
      flex: 1;
      > header {
          width: 150px;
          height: 150px;
          background-position: center;
          background-size: cover;
          background-repeat: no-repeat;
          text-align: center;
      }
   }
}
</style>


