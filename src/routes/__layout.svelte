<script>
	import '../app.css';
import SideBar from '../components/SideBar.svelte';
import theme from '$lib/shared/stores/theme';
</script>


<main class={$theme}>
	<SideBar/>
	<slot />
</main>

<footer>
	
</footer>

<style>
	
</style>
