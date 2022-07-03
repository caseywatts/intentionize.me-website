<script>
  import "../app.css";
  import Download from "../components/download.svelte";
  import InputWidget from "../components/input-widget.svelte"
  import TitleBar from "../components/title-bar.svelte"
  import TwoSteps from "../components/two-steps.svelte"
  import MenuBar from "../components/menu-bar.svelte"
  import Desktop from "../components/desktop.svelte"
  import InstructionsA from "../components/instructions-a.svelte"
  import InstructionsB from "../components/instructions-b.svelte"
  let myIntention;
</script>

<svelte:head>
	<title>Intentionize.me</title>
</svelte:head>

<div class="flex flex-col justify-between min-h-screen text-center">
  <MenuBar {myIntention} />
  <div class="pt-8 space-y-8 flex-1">
    <div class="py-2">
      <InstructionsA />
    </div>
    <div class="py-2">
      <InputWidget bind:myIntention/>
    </div>
    <div class="py-2">
      <InstructionsB />
    </div>
  </div>
  <div class="pt-4 w-full">
    <Download />
  </div>
</div>
