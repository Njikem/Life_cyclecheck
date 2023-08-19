<template>
    <div>

    </div>
</template>

<script>

    export default {
     
        

        beforecreated: function (){
            console.log('We just stated creating');
        },

        created: function(){
            console.log(`created already`);
        },

        beforeMount: function() {
            console.log('Soon to be mounted');
            
        },

        mounted: function () {
            console.log('Is mounted');
        },
    }
</script>

<style lang="scss" scoped>

</style>