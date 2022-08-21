<script lang="ts">
	import { page } from '$app/stores';
	import logo from './svelte-logo.svg';
</script>

<div class="navbar bg-base-300 border-b border-base-200 shadow">
	<div class="flex-1">
		<a class="btn btn-ghost normal-case text-xl" href="/">daisyUI</a>
	</div>
	<div class="flex-none">
		<ul class="menu menu-horizontal p-0">
			<li>
				<a href="/todos"> Todos </a>
			</li>
			<li>
				<a href="/about"> GitHub </a>
			</li>
			<li>
				<a href="/about"> About me</a>
			</li>
		</ul>
	</div>
</div>
