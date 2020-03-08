<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: 'Hello',
  props: {
    msg: String
  },
  data(){
    return{
        msg1:'<span style="color:red;">Hello World</span>'
    }
  }
}
</script>
