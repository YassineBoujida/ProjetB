<template>
    <div>
         <a :class="classButton" href="#">
            <span>{{buttonValue}}</span>
         </a>
    </div>
</template>

<script>
export default {
    name : "ButtonComponent",
    props : ['classButton','buttonValue']
    
}
</script>

<style scoped>

</style>