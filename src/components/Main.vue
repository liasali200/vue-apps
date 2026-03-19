<script setup>
// import HelloWorld from "@/components/HelloWorld.vue";

import {ref} from 'vue';
const name = ref('Lia')


</script>

<template>
    <section>
        <h3>Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes</h3>
        <button>Next Quote</button>
    </section>

</template>

<style scoped>

h3{
    color: #f3f9f3;
    font-weight: 600;
}

button{
    background-color: #277429; /* Green */
    border: none;
    border-radius: 2em;
    box-shadow: 0 3px 3px 0 rgba(0, 0, 0, 0.2);
    color: white;
    margin-top: 1rem;
    padding: 7px 28px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
}
</style> 