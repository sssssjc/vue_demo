<template>
    <div>
        <h2>{{name}}</h2>
        <div :style="styleObj"></div>
    </div>
</template>

<script>
    export default{
        name:'Huo',
        data(){
            return {
                name:'火',
                styleObj:{
                    width:'200px',
                    height:'200px',
                    backgroundColor:'orange'
                }
            }
        }
    }
</script>