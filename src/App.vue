<script setup lang="ts">

	import Axios from "axios"
	import Login from "./components/Login.vue"

	Axios.get("https://tms-api.herokuapp.com/users").then(res => {
		console.log(res.data)
	}).catch(err => {

	})

</script>

<template>
	<Login />
</template>

<style scoped>
</style>
