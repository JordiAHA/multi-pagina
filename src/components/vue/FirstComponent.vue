<script setup>
import { ref } from 'vue';
let number = 5 

function Substract (){
    if (number.value > 0){
        number.value--
    }
   
}
function add (){
    number.value++
    console.log(number.value)
}
</script>
<template>
    <div class="max-w-96 bg-slate-200 rounded py-3 px-5 mx-auto">
                       
        <div 
        class="bg-red-400 size-8 flex items-center justify-center rounded-full"
        v-if="number > 0"
        >
            {{ number }}
        </div>
        <di 
        v-if=" nadi te escribe :/"
        >
        
        </di>
        <div class="bg-blue-400 size-8 flex items-center justify-center rounded-full"
        @click="Substract">
            -
        </div>
        <div class="bg-blue-400 size-8 flex items-center justify-center rounded-full"
        @click="add"
        >
            +
        </div>

    </div>
</template>