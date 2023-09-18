<script setup>
import first from './components/first.vue'
import second from './components/second.vue'
// import third from './components/third.vue'
// import fourth from './components/fourth.vue'
import fifth from './components/assortment.vue'
import sixth from './components/calousel.vue'
import seventh from './components/seventh.vue'

</script>


<template>
	<header>
		<div class="right_background">

		</div>


		<div class="container">
			<div class="logo">
				<img alt="Vue logo" class="logo" src="./assets/logo9.svg" width="200" height="100"/>
<!--				<h1>Автозапчастини</h1>-->
			</div>
			<div class="description">
				<h1>Гуртово-роздрібна торгівля<br> автозапчастинами до автомобілів</h1>
			</div>

			<div class="right_box">
				<div class="phones">
					<a href="tel:050-671-30-26" class="Blondie">050-671-30-26 <span>Володимир</span></a>
					<a href="tel:050-776-22-21" class="Blondie">050-776-22-21 <span>Надія</span></a>
					<a href="tel:050-750-22-36" class="Blondie">050-750-22-36 <span>Олександр</span></a>
				</div>
			</div>
		</div>

	</header>

	<main>
		<first/>
		<second/>
<!--		<third/>-->
<!--		<fourth/>-->
		<fifth/>
		<sixth/>
		<seventh/>
		<!--    <TheWelcome />-->

	</main>
	<footer>
		<div class="container">
			<div class="top_box">
				<div class="instagram">
					<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><title>instagram</title><path d="M7.8,2H16.2C19.4,2 22,4.6 22,7.8V16.2A5.8,5.8 0 0,1 16.2,22H7.8C4.6,22 2,19.4 2,16.2V7.8A5.8,5.8 0 0,1 7.8,2M7.6,4A3.6,3.6 0 0,0 4,7.6V16.4C4,18.39 5.61,20 7.6,20H16.4A3.6,3.6 0 0,0 20,16.4V7.6C20,5.61 18.39,4 16.4,4H7.6M17.25,5.5A1.25,1.25 0 0,1 18.5,6.75A1.25,1.25 0 0,1 17.25,8A1.25,1.25 0 0,1 16,6.75A1.25,1.25 0 0,1 17.25,5.5M12,7A5,5 0 0,1 17,12A5,5 0 0,1 12,17A5,5 0 0,1 7,12A5,5 0 0,1 12,7M12,9A3,3 0 0,0 9,12A3,3 0 0,0 12,15A3,3 0 0,0 15,12A3,3 0 0,0 12,9Z" /></svg>
				</div>
				<div class="facebook">
					<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><title>facebook</title><path d="M12 2.04C6.5 2.04 2 6.53 2 12.06C2 17.06 5.66 21.21 10.44 21.96V14.96H7.9V12.06H10.44V9.85C10.44 7.34 11.93 5.96 14.22 5.96C15.31 5.96 16.45 6.15 16.45 6.15V8.62H15.19C13.95 8.62 13.56 9.39 13.56 10.18V12.06H16.34L15.89 14.96H13.56V21.96A10 10 0 0 0 22 12.06C22 6.53 17.5 2.04 12 2.04Z" /></svg>
				</div>


			</div>
			<div class="middle_box">
				<nav>
					<ul>
						<li>Гарантія</li>
						<li>Умови повернення</li>
						<li>Доставка</li>
						<li>Допомога</li>
						<li>Партнерам</li>
						<li>Співпраця з нами</li>
					</ul>
				</nav>

				<div class="contacts">
					<h4>Контакти</h4>

				</div>

				<div class="contacts">
					<h4>Графік роботи</h4>

					<div>Понеділок - П'ятниця: 9:00 - 18:00</div>
					<div>Субота: 9:00 - 16:00</div>
					<div>Неділя: вихідний</div>
				</div>
			</div>
			<div class="bottom_box"></div>
		</div>
	</footer>
</template>

<style lang="scss">
header {
	height: 100px;
	background-color: #f2f2f2;
	position: relative;
	.right_background {
		position: absolute;
		right: 0;
		top: 0;
		background-color: #476B45;
		width: 40%;
		height: 100%;
	}
	.container {
		display: flex;
		align-items: center;
		justify-content: space-between;

		.logo {
			display: flex;
			justify-content: center;
			flex-direction: column;
			align-items: center;
			width: 200px;
			height: 50px;
		}
		.description {
			margin-left: -200px;
			> h1 {
				font-size: 17px;
				font-weight: 600;
				color: #476B45;
				//color: #5ea465;
			}
		}

		.right_box {
			display: flex;
			justify-content: center;
			flex-direction: column;
			align-items: flex-end;
			width: 40%;
			height: 100%;
			position: relative;
			background-color: #476B45;
			&:after {
				content: '';
				position: absolute;
				top: 0;
				left: 0;
				right: 0;
				width: 0;
				height: 0;
				//border-bottom: 100px solid #476B45;
				//border-left: 100px solid transparent;

				border-bottom: 100px solid #f2f2f2;
				border-right: 100px solid transparent;
			}
			.phones {
				> a {
					padding-left: 30px;
					display: flex;
					font-size: 16px;
					background-image: url('./assets/icons/phone-outgoing.svg');
					background-repeat: no-repeat;
					color: #fff;
					> span {
						padding-left: 7px;
					}
				}
			}

		}
	}
}


footer {
	width: 100%;
	height: 400px;
	background-color: #476B45;
	padding: 20px 0;
	.container {

	}
	.top_box {
		display: flex;
		height: 65px;
		border-bottom: 1px solid rgba(#fff, .3);
		margin-bottom: 20px;
		.instagram, .facebook {
			width: 40px;
			height: 40px;
			fill: #fff;
		}
	}
	.middle_box {
		display: flex;
		justify-content: space-between;
		nav {
			ul {
				list-style-type: none;
				margin: 0;
				padding: 0;
				> li {
					color: #fff;
					padding: 5px 0;
					> a {
						color: #fff;
					}
				}
			}
		}
		.contacts {
			> h4 {
				text-transform: uppercase;
				color: #fff;
				font-weight: 500;
				margin-bottom: 10px;
			}
			> div {
				color: #fff;
			}
		}
	}
	.bottom_box {

	}
}

</style>
