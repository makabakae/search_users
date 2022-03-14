
<template>
	<div class="container">
		<searchGit/>
		<ListUsers/>
	</div>
</template>

<script>
	import searchGit from './components/searchGit'
	import ListUsers from './components/ListUsers'
	export default {

		name:'App',
		components:{searchGit,ListUsers},

	}
</script>


