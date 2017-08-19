<template>
    <div class="head-box">
        <div class="head">
            <a href="#" class="logo" style="display:inline-block;padding:15px 30px;float:left;">lz</a>
            <ul class="nav clearfix" style="float:left;">
                <li class="active"><a href="#">Link <span class="sr-only">(current)</span></a></li>
                <li><a href="#">Link</a></li>
                <li class="dropdown">
                    <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
                    <ul class="dropdown-menu">
                        <li><a href="#">Action</a></li>
                        <li><a href="#">Another action</a></li>
                        <li><a href="#">Something else here</a></li>
                        <li role="separator" class="divider"></li>
                        <li><a href="#">Separated link</a></li>
                        <li role="separator" class="divider"></li>
                        <li><a href="#">One more separated link</a></li>
                    </ul>
                </li>
                <li class="dropdown">
                    <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
                    <ul class="dropdown-menu">
                        <li><a href="#">Action</a></li>
                        <li><a href="#">Another action</a></li>
                        <li><a href="#">Something else here</a></li>
                        <li role="separator" class="divider"></li>
                        <li><a href="#">Separated link</a></li>
                        <li role="separator" class="divider"></li>
                        <li><a href="#">One more separated link</a></li>
                    </ul>
                </li>
            </ul>
        </div>
        <v-search></v-search>
    </div>
</template>

<script type="text/javascript">
    import search from '../search/search.vue'
    export default {
      components: {
        'v-search': search
      }
    }
</script>

<style media="screen" lang="less">
    .head-box{
        height: 52px;
        .head{
            width: 100%;
            min-width: 800px;
            position: fixed;
            top: 0;
            left: 0;
            border: 1px solid red;
            z-index: 10;
            .nav{
                min-width: 500px;
                li{
                    float:left;padding: 4px;
                }
            }
            .clearfix {
                display: block;
                zoom: 1;
            }
        }
    }
</style>
