<script>
  import Header from "$lib/header/Header.svelte";
  import "../app.css";
	let isSideNavOpen = false;
</script>

<Header/>



<content class="hero ">
  <slot />
</content>

<footer class="footer-center">
</footer>
