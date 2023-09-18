<script>
import { SplitCarousel, SplitCarouselItem } from "vue-split-carousel";
export default {
	components: {
		SplitCarousel,
		SplitCarouselItem
	}
};
</script>

<template>
	<section class="carousel_section">
		<div class="container">
			<split-carousel :height="350" :display-amount="5">
				<split-carousel-item>
					<div class="item_carousel">
						<img src="../assets/carousel/bosch.png">
					</div>
				</split-carousel-item>
				<split-carousel-item>
					<div class="item_carousel">
						<img src="../assets/carousel/brembo.png">
					</div>
				</split-carousel-item>
				<split-carousel-item>
					<div class="item_carousel">
						<img src="../assets/carousel/contitech.png">
					</div>
				</split-carousel-item>
				<split-carousel-item>
					<div class="item_carousel">
						<img src="../assets/carousel/delphi.png">
					</div>
				</split-carousel-item>
				<split-carousel-item>
					<div class="item_carousel">
						<img src="../assets/carousel/denso.png">
					</div>
				</split-carousel-item>
				<split-carousel-item>
					<div class="item_carousel">
						<img src="../assets/carousel/magneti.png">
					</div>
				</split-carousel-item>
				<split-carousel-item>
					<div class="item_carousel">
						<img src="../assets/carousel/mahle.png">
					</div>
				</split-carousel-item>
				<split-carousel-item>
					<div class="item_carousel">
						<img src="../assets/carousel/ngk.png">
					</div>
				</split-carousel-item>
				<split-carousel-item>
					<div class="item_carousel">
						<img src="../assets/carousel/skf.png">
					</div>
				</split-carousel-item>
				<split-carousel-item>
					<div class="item_carousel">
						<img src="../assets/carousel/trw.png">
					</div>
				</split-carousel-item>
				<split-carousel-item>
					<div class="item_carousel">
						<img src="../assets/carousel/valeo.png">
					</div>
				</split-carousel-item>
				<split-carousel-item>
					<div class="item_carousel">
						<img src="../assets/carousel/wix.png">
					</div>
				</split-carousel-item>
			</split-carousel>
		</div>
	</section>
</template>

<style lang="scss">
	.carousel_section {
		background-color: #fff;
		height: 350px;
		padding: 30px 0;
		.item_carousel {
			display: flex;
			align-items: center;
			height: 100%;
			width: 100%;
		}
	}
</style>