<script>
    export default { 
        data() {
            return {
                width: '200',
                height: '200',
                myImg: '/assets/me.png'
            }
        },
    }
</script>

<template>

    <!-- add code here -->
    <!-- ; is a short-hand notation for v-bind -->
    <div id="ex2">
        <!-- <img 
        v-bind:src="myImg" 
        v-bind:width="width" 
        v-bind:height="height">
        </img> -->
        <img 
        :src="myImg" 
        :width="width" 
        :height="height">
        </img>
    </div>
   
</template>
