<template>
    <div>
        <h1>Trade or view your portfolio</h1>
        <h6>You may Save and Load your dara</h6>
        <h6>Click on 'End Day' to begin a New Day!</h6>
        <hr>
        <p>Your Funds: {{ funds | currency}}</p>
    </div>
</template>
<script>
    export default{
        computed: {
            funds(){
                    return this.$store.getters.funds
            }
        },
        components:{

        }
    }

</script>
<style>

</style>
