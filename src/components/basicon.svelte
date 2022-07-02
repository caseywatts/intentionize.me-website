<script>
  import InlineSVG from 'svelte-inline-svg'
  export let iconName;
  const src = `../basicons/${iconName}.svg`
</script>

<InlineSVG src={src} />