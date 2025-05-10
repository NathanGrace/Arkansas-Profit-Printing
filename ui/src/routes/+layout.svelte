<script lang="ts">
	import '../app.css';
	export const prerender = true;

	let { children } = $props();
</script>

<head>
    <title>Arkansas Profit Printing</title>
    <!-- There's already a head tag in the app.html, might need to put stuff there instead! -->
</head>

<header>
    <nav class="daisy-navbar justify-center">
        <div class="justify-center">
            <a href="./" class="inline-flex">
                <img
                    src="/logos/arkansas-profit-printing-logo.png"
                    alt="Arkansas Profit Printing Home Page"
                    class=""
                />
            </a>
        </div>
    </nav>
</header>

{@render children()}
