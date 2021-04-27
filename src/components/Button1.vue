<template>
    <button :style="{background:color}"  class="btn ">{{text}}</button>
</template>



<script>
export default {
    name:Button1,
    props:{
        text:String,
        color:String,
    }
}
</script>

