<template>
  <div>
    <div class="all">
        <h1>Hello from component1</h1>
        <p>{{counter1}}</p>
        <button @click="counter1++">App</button>
    </div>
  </div>
</template>

<script>
export default {
    data(){
        return{
            counter1: 1
        }
    }
}
</script>

<style scoped>
    .all{
        display: flex;
        flex-direction: column;
        align-items: center;
        background-color: red;
        width:50vw;
        height: 300px;
    }
</style>