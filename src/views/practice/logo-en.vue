<style>
    .case-logo{
        width: 100%;
    }
    .case-logo img{
        width: 100%;
    }
</style>
<template>
    <i-article>
        <article>
            <h1>iView Logo Design</h1>
            <div class="case-logo">
                <img src="../../images/case-logo.png">
            </div>
        </article>
    </i-article>
</template>
<script>
    import iArticle from '../../components/article.vue';
    import iCode from 'iCode';
    import inAnchor from '../../components/anchor.vue';

    export default {
        components: {
            iArticle,
            iCode,
            inAnchor
        },
        data () {
            return {

            }
        },
        methods: {

        }
    };
</script>