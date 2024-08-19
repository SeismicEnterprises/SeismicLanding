<template>
	<header>
		<div class="flex py-5 px-3">
			<div class="flex-grow flex items-center z-20">
				<NavMenu />
			</div>
			<div class="flex items-center">
				<a href="#">
					<img class="block lg:hidden" src="images/icon-menu.svg" alt="Menu" />
				</a>
				<div class="hidden lg:flex lg:space-x-10 lg:items-center">
					<div class="hover:text-almost-black cursor-pointer">Forums</div>
					<div class="border-2 hover:border-almost-black hover:text-almost-black rounded-xl px-4 py-2 cursor-pointer">Get Seismic</div>
				</div>
			</div>
		</div>
	</header>
</template>

<script>
import NavMenu from './NavMenu.vue'

export default {
	name: 'Header',
	components: {
		NavMenu
	},
	data() {
		return {}
	}
}
</script>
