<template>
		<h1>this is an animal</h1>
		<h1>{{animals}}</h1>
</template>

<script>
	export default{
		data(){
			return {
				animals : {gajah : "mamalia"}
			}
		},
		created(){
			console.log("haii")
		}
	}
</script>