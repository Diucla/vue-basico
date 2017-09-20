<template>
	<div class="phone-viewport">
        <md-toolbar>
            <md-button class="md-icon button" v-on:click="toggleLeftSidenav">
                <md-icon>menu</md-icon>
            </md-button>
            <h1 class="md-title">{{ title }}</h1>
        </md-toolbar>
    </div>
</template>

<script>
  export default {
    name: 'SumbusComponent',
    data () {
      return {
        title: 'Ecommerce by Sumbus'
      }
    }
  }

</script>

<style>
</style>
