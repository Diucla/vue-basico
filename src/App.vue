<template>
	<header class="phone-viewport">
        <md-toolbar>
            <md-button class="md-icon button" @click.native="toggleLeftSidenav">
                <md-icon>menu</md-icon>
            </md-button>

            <h1 class="md-title">{{ title }}</h1>
        </md-toolbar>

        <md-sidenav class="md-left" rel="leftSidenav">
            <md-toolbar class="md-medium">
                <div class="md-toolbar-container">
                    <h2 class="md-title">Sidenav content</h2>
                </div>

                <p>
                    Lorem Ipsum dolor
                </p>
            </md-toolbar>
        </md-sidenav>
    </header>
</template>

<script>
  export default {
    name: 'SumbusComponent',
    data () {
      return {
        title: 'Ecommerce by Sumbus'
      }
    },

    methods: {
      toggleLeftSidenav () {}
    }
  }
</script>

<style>
</style>
