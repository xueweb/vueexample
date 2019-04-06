<template>
    <div class="checkboxtest">
        <input type="radio" v-model="picked" value="1" id="study">
        <label for="study">苹果</label>
        <input type="radio" v-model="picked" value="2" id="read">
        <label for="study">雪梨</label>
         <input type="radio" v-model="picked" value="3" id="play">
         <label for="study">橙</label>
         <p>复选框选择的值：{{picked}}</p>
    </div>
</template>

<script>
    export default {
        name: "checkbox",
        data() {
            return {
                picked: "1",
            }
        }
    }
</script>

<style scoped lang="less">
    .checkboxtest {
        p {
            color: black;
        }
    }
</style>
