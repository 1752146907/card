<template>
    <div id="app">
        <m-demo/>
        <m-card
            imgSrc="1.jpg"
            summary="很多设计师喜欢用英文，因为中文排版真的不太容易搞。中文字符多、不同字符的笔画差异也很大，使用英文时高大上的设计稿，替换成中文以后，可能会大打折扣。"
        />
        <m-card
            imgSrc="2.jpg"
            summary="网页设计中，针对中文排版的研究很少，没有太多现成的结论供参考。Amaze UI 只能根据一些经验，在字体设置、字号上做一些更适合中文的设置。"
        >
            <template v-slot:footer>
                <div class="footer">
                    <div class="level">中级·888人报名</div>
                    <div class="price">¥299.00</div>
                </div>
            </template>
        </m-card>
        <m-card
                imgSrc="3.jpg"
                :width="379"
                :height="90"
        >
            无论走到哪里，都应该记住，过去都是假的，回忆是一条没有尽头的路，一切以往的春天都不复存在，就连那最坚韧而又狂乱的爱情归根结底也不过是一种转瞬即逝的现实。
            <template v-slot:footer>
                <div class="footer-spring">
                    <div class="level">4步骤·6门课</div>
                    <div class="level">10965收藏</div>
                </div>
            </template>
        </m-card>
    </div>
</template>

<script>

    export default {
        name: 'App',
        components: {}
    }
</script>

<style>
    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }
</style>
