<script>
  import InlineSVG from 'svelte-inline-svg'
  export let iconName;
  const src = `basicons/${iconName}.svg`
  export let height;
</script>

<InlineSVG src={src} {height} class="inline-block" />