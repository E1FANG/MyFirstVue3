<template>
  <h1>{{ msg }}</h1>
  <button @click="count++">count is: {{ count }}</button>
  <p>Edit <code>components/HelloWorld.vue</code> to test hot module replacement.</p>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  data() {
    return {
      count: 0
    }
  },
  mounted() {
    console.log(`this is mounted`)
    console.log('this is so fast, Amazing!')
    console.log(`test mac git`);
    console.log('test rename git');
  }
}
</script>
