<script setup>
const points = [
	{
		img: {
			src: '/message.svg',
			alt: 'message',
		},
		headline: 'Онлайн',
		description: 'Наш чат предлагает бесплатные' +
			' онлайн-консультации для решения' +
			' юридических вопросов.',
	},
	{
		img: {
			src: '/idea.svg',
			alt: 'idea',
		},
		headline: 'Опыт',
		description: 'Наши юристы-консультанты работают' +
			' под надзором опытных юристов,' +
			' которые точно помогут Вам.',
	},
	{
		img: {
			src: '/free.svg',
			alt: 'free',
		},
		headline: 'Доступно',
		description: 'Стоит только зарегистрироваться и' +
			' Вы получите доступ к бесплатным консультациям.',
	},
	{
		img: {
			src: '/time.svg',
			alt: 'time',
		},
		headline: 'Время',
		description: 'Мы экономим Ваше время. Теперь' +
			' необходимости посещать очные' +
			' встречи с юристом все меньше.',
	},
]
</script>

<template>
	<div class="points">
		<div class="container">
			<h1>Бесплатный вход в мир защиты<br class="d-none d-lg-block"/> ваших прав!</h1>
			<div class="row">
				<div class="col-md-6 col-lg-3" v-for="(item, index) in points" :key="index">
					<div class="points_rect">
						<img :src="item.img.src" :alt="item.img.description"/>
						<h2>
							{{ item.headline }}
						</h2>
						<p>
							{{ item.description }}
						</p>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<style scoped>

</style>