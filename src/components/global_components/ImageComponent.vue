<template>
    <div>
        <figure :class="classFigure">
            <img :class="classImage" :src="require(`@/assets/${source}`)" />
        </figure>
 
    </div>
</template>

<script>
export default {
    name : "ImageComponent",
    props : ['source','classFigure',"classImage"]
    
}
</script>

<style scoped>

</style>