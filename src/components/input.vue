<template>
    <div class="inputtest">
        <div class="text-wrap">
            <input type="text" v-model="txt" class="textbox"></div>输入框的值:<span class="text">{{txt}}</span>
    </div>
</template>

<script>
    export default {
        name: "inputtest",
        data() {
            return {
                txt: ""
            }
        }
    }
</script>

<style scoped lang="less">
    .inputtest {

        .text {
            font-size: 12px;
            display: inline-block;
            width: 60px;
            height: 13px;

        }

    }
</style>
