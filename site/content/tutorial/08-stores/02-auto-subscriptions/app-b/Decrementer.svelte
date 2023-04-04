<script>
	import { count } from './stores.js';

	function decrement() {
		count.update(n => (n > 0) ? n - 1 : 0);
	}
</script>

<button on:click={decrement}>
	-
</button>
