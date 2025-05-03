<script lang="ts">
	import '../app.css';
	
	let { children } = $props();
</script>

<nav class="bg-gray-200">
    <div class="flex">
        <a href="./" class="flex-auto">
            <img src="arkansas-profit-printing-logo.png" alt="Arkansas Profit Printing Home Page">
        </a>
        <a href="/contact" class="flex-auto bg-amber-400">Contact Heath!</a>
    </div>
</nav>

{@render children()}
