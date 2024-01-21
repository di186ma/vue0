<script setup>

import VHeader from "@/components/VHeader.vue";
import VFooter from "@/components/VFooter.vue";
import VPromo from "@/components/VPromo.vue";
import VPoints from "@/components/VPoints.vue";
import VEasy from "@/components/VEasy.vue";
import VChat from "@/components/VChat.vue";
</script>

<template>
	<v-header/>
	<main>
		<v-promo/>
		<v-points/>
		<v-easy/>
		<v-chat/>
	</main>
	<v-footer/>
</template>

<style scoped>

</style>
