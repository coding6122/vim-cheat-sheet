<template>
	<div class="card">
		<header class="card-header">
			<p class="card-header-title">
				{{command}}
			</p>
		</header>
		<div class="card-content">
			<div class="content">
				{{description}}
			</div>
		</div>
	</div>
</template>
<script>
export default {
	props: ['command', 'description']
}
</script>
