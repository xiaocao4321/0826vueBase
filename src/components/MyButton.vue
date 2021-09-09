<template>
    <div>
        <h2>我爱赵丽颖</h2>
        <button @click="count++">爱了{{count}}次</button>
    </div>
</template>

<script>
export default {
    name: 'VueDemoMybutton',

    components: { ComponentName },

    directives: { DirectiveName },

    data() {
        return {
            count =0,
        };
    },

    mounted() {
        
    },

    methods: {
        
    },
};
</script>

<style scoped>
  h2{
      color: hotpink;
      }
</style>