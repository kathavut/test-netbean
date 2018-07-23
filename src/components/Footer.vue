<template>
    <footer>
        <p>{{ copylight }}</p>
    </footer>
</template>

<script>
export default {
  data () {
    return {
        copylight:'Copylight 2018 chysoft.co.th'
    }
  }
}
</script>
<style scoped>
    footer{
        background:#222;
        padding:6px;
    }
    p{
        color:lightgreen;
        text-align:center;
    }
</style>