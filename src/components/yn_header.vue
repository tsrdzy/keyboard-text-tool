<template>
    <header>
        <div class="logo">
            <i class="iconfont">&#xe60e;</i>
            <h2>源鸟 - 键盘测试工具</h2>
        </div>
    </header>
    <hr>
</template>

<script>
export default {
    data() {
        return {}
    },
}

</script>
<style lang=less scoped>
hr {
    border: 0;
    height: 1px;
    background: #333;
    background-image: linear-gradient(to right, #252525, #616161, #a1a1a1);
}

header {
    padding: 5px 5px 0 5px;
    height: 20px;
    color: #000;

    .logo {
        display: flex;
        font-size: 16px;
        height: 20px;
        line-height: 20px;

        i {
            font-size: 20px;
            height: 24px;
            line-height: 24px;
        }
    }
}
</style>
