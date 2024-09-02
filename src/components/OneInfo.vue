<script setup lang="ts">
interface Props {
	title: string;
	content: string;
}
defineProps<Props>();
</script>

<template>
	<section class="box">
		<h3>{{title}}</h3>
		<p>{{content}}</p>
	</section>
</template>

<style scoped>
.box {
	border: green 1px solid;
	margin: 10px;
	color: red;
}
</style>
