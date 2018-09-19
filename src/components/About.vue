<template>
  <div class="about">
    <h1> Hello {{ thier_name }}, this is an about page</h1>
    <p>Hello Vue! This is a Skills list app. My second Vue.js project. Vue is a front end javascript framework.</p>
  </div>
</template>

<script>
export default {
    name: 'Skills', 
    data() {
        return {
            thier_name: this.$route.params.name
        }
    }
}
</script>
