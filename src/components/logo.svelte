<script>
  import InlineSVG from 'svelte-inline-svg'
  const src = `focus.svg`
  export let height;
</script>

<InlineSVG src={src} class="stroke-white" {height}/>