<template>
    <header class="flex justify-between items-center p-6 bg-opacity-50 relative z-20">
<div class=" text-white  texte-3xl font-bold"> Logo</div>
<button type="button" class="block text- focus:outline-none ">
    <span class="text-5xl">

        <img src="https://img.icons8.com/ios-filled/100/ffffff/delete-sign.png" alt="closeit" width="50" height="50">
    </span>
    <span class="text-5xl">
        <img src="https://img.icons8.com/ios-filled/100/ffffff/menu--v6.png" alt="menu" width="50" height="50">
    </span>


</button>
    </header>
</template>

<script setup>
import {ref} from 'vue';
const Menu=ref(
    [
        {
            name:'services',href:'#Services'
        },
        {
            name:'About Me',href:'#About'
        },
        {
            name:'Skills',href:'#Skills'
        },
        {
            name:'Projects',href:'#Projects'
        },
        {
            name:'Testimonials',href:'#Testimonials'
        },
        {
            name:'Contact',href:'#Contact'
        },


    ]
)
</script>