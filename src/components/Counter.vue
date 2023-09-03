<template>
  <h2>Counter</h2>
  <button @click="increment">{{counter}}</button>
  <div>
    o
  </div>
</template>

<script>
export default {
    name: 'Counter',

    data() {
        return {
            counter: 0
        }
    },

    methods: {
        increment() {
            this.counter++;
        }
    }
}
</script>

<style>

</style>