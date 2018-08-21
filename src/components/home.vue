<template>
	<div class="section">
		<main-header></main-header>
		<div class="main_content"></div>
		<main-footer></main-footer>
	</div>
</template>

<script>
	import mainHeader from "./header/mainHeader"
	import mainFooter from "./footer/mainFooter"
	export default{
		name:"home",
		data(){
			return {
				
			}
		},
		components:{
			mainHeader,
			mainFooter
		},
		create(){
			
		},
		methods:{
			
		}
	}
</script>

<style lang="less" scoped>
	.main_content{
		width:100%;
		
	}
</style>