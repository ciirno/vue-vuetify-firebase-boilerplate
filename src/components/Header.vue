<template>
	<v-app-bar
		app
		absolute
		color="primary"
		class="text-h5 font-weight-bold white--text"
		><v-avatar :tile="true">
    <img :src="require('@/assets/logo.png')" alt="logo">
  </v-avatar>Among C</v-app-bar
	>
</template>

<script>
	export default {
		name: "Header",
	};
</script>

<style></style>
