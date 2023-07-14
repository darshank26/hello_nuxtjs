<template>

<div>
<NuxtLink to ="/" >Home</NuxtLink> 

<NuxtLink to ="/about" >About</NuxtLink> 
</div>

Hello World

<button @click="moveToAbout">Take Me to About Page</button>

</template>

<script setup>

function moveToAbout()
{
    navigateTo("about")
}

</script>