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

<div class="text-center">
  <MenuBar {myIntention} />
  <div class="space-y-8 pt-8">
    <div class="py-2">
      <InstructionsA />
    </div>
    <div class="py-2">
      <InputWidget bind:myIntention/>
    </div>
    <div class="py-2">
      <InstructionsB />
    </div>
    <div class="pt-4 bottom-0 absolute w-full">
      <Download />
    </div>
  </div>
  <!-- <TitleBar {myIntention}/>
  <TwoSteps />-->
</div>