<template>
    <div class="search">
        <form action="index.html" method="post">
            <span class="glyphicon glyphicon-search"></span>
            <input class="form-control" type="text" name="" value="" placeholder="输入您需要的插件">

        </form>
    </div>
</template>

<script type="text/javascript">
    export default {
    }
</script>

<style media="screen" lang="less">
    .search{
        position: relative;
        margin-left: 500px;
        margin-top: 10px;
        width: 300px;
        height: 30px;
        line-height: 30px;
        input{
            height: 30px;
            padding-left: 35px;
        }
        span{
            position: absolute;
            top: 8px;
            left: 15px;
            color: lightblue;
        }
    }
</style>
