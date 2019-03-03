<template>
 <div>
    <router-link to='/'>Home</router-link> |
    <router-link to='/about'>About</router-link> |
  <HelloWorld />
 </div>

</template>

<script>
  import HelloWorld from '../components/HelloWorld'

  export default {
    components: {
      HelloWorld
    }
  }
</script>
