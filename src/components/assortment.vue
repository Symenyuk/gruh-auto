<script setup>

</script>

<template>
	<section class="assortment_section">
		<div class="container">
			<h1>Асортимент</h1>
			<div class="wrap">
				<div class="item">
					<h4>Двигун</h4>
				</div>
				<div class="item">
					<h4>Вентиляція/Охолодження</h4>
				</div>
				<div class="item">
					<h4>Ходова</h4>
				</div>
				<div class="item">
					<h4>Електрика</h4>
				</div>
				<div class="item">
					<h4>Кузовні елементи</h4>
				</div>
				<div class="item">
					<h4>Матеріали</h4>
				</div>
			</div>
		</div>
	</section>
</template>

<style lang="scss">
	.assortment_section {
		background-color: #f2f2f2;
		height: 700px;
		padding: 20px 0;
		h1 {
			font-size: 30px;
			font-weight: 900;
			text-transform: uppercase;
			font-style: italic;
			margin-bottom: 45px;
		}
		.wrap {
			display: grid;
			grid-template-columns: 1fr 1fr 1fr;
			grid-auto-rows: 250px;
			.item {
				display: flex;
				justify-content: center;
				border: 1px solid red;
				> h4 {
					font-size: 16px;
					color: #476B45;
					font-weight: 500;
				}

			}
		}
	}
</style>