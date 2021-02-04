<template>
	<v-app>
		<Header />
		<v-main>
			
		</v-main>
		<v-footer>Among C &copy; 2021</v-footer>
	</v-app>
</template>

<script>
	import Header from "@/components/Header.vue";
	export default {
		name: "About",
		components: {
			Header,
		},
	};
</script>