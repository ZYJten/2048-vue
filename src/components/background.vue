<template>
	<div>
		<div class="background">
			<div v-for="i of 16" :key="i" class="grid-cell"></div>
		</div>
	</div>
</template>

<script>
	export default{
		
	}
</script>

<style lang="css" scoped>
	.background{
		width: 460px;
		  height: 460px;
		  padding: 20px;
		  background-color: #bbada0;
		  border-radius: 10px;
		  display: grid;
		  grid-row-gap: 20px;
		  grid-column-gap: 20px;
		  grid-template-columns: repeat(4, 100px);
		  grid-template-rows: repeat(4, 100px);
	}
	.background .grid-cell{
    width: 100px;
    height: 100px;
    border-radius: 5px;
    background-color: #ccc0b3;
	}
</style>
