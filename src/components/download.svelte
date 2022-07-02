<script>
	import Basicon from '../components/basicon.svelte';
</script>

<div class="bg-violet-300 border-2 border-violet-600 md:absolute mt-6 bottom-0 w-full">
	<div class="p-4 pt-3 space-y-2 flex justify-around items-center">
		<div class="pt-2 underline text-blue-800 hover:text-blue-500">
			<a href="https://github.com/caseywatts/intentions/">free and open source</a>
		</div>
		<div>
			<a
				class="bg-violet-500 hover:bg-violet-600 text-violet-100 p-3 text-lg rounded flex justify-center align-middle"
				href="https://github.com/caseywatts/intentionize.me/releases/latest/download/intentionize.me-mac.zip"
			>
				<span class=" stroke-violet-50 p-1 flex justify-center items-center">
					<Basicon height="16" iconName="download" />
				</span>
				<span class="p-1"> download intentions for mac </span>
			</a>
		</div>
		<div class="underline text-blue-800 hover:text-blue-500">
			<a href="https://twitter.com/heycaseywattsup">made by Casey Watts!</a>
		</div>
	</div>
</div>
