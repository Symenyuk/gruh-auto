<script setup>

</script>

<template>
	<section class="second_section">
		<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1000 100" preserveAspectRatio="none" fill="#5ea465" style="position: absolute;">
			<path class="elementor-shape-fill" d="M738,99l262-93V0H0v5.6L738,99z"></path>
		</svg>
		<div class="container">
			<div class="head_section">
				<h1>У нас Ви можете знайти та придбати запчастини</h1>
			</div>
			<div class="wrap">
				<div class="item"></div>
				<div class="item"></div>
				<div class="item"></div>
			</div>
		</div>
	</section>
</template>

<style lang="scss">
	.second_section {
		height: 800px;
		background-image: url('../assets/tools-on-worktop.jpg');
		background-size: cover;
		position: relative;
		&:after {
			content: '';
			position: absolute;
			top: 0;
			left: 0;
			width: 100%;
			height: 100%;
			background-color: rgba(94, 164, 101, 0.5);
			z-index: 0;
		}
		.head_section {
			position: relative;
			z-index: 1;
			padding: 20px 0;
			margin-left: 250px;
			> h1 {
				font-size: 30px;
				font-weight: 700;
				color: #fff;
				text-transform: uppercase;
				display: flex;
				justify-content: flex-end;
			}
		}
		.wrap {
			display: flex;
			justify-content: space-between;
			margin-top: 140px;
			> .item {
				display: flex;
				align-items: center;
				justify-content: center;
				width: 30%;
				height: 300px;
				background: rgba(#fff, .9);
				position: relative;
				z-index: 1;
				border-radius: 5px;
			}
		}
	}

</style>