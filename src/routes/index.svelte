<script>
  import "../app.css";
  import Download from "../components/download.svelte";
  import InputWidget from "../components/input-widget.svelte"
  import TitleBar from "../components/title-bar.svelte"
  import TwoSteps from "../components/two-steps.svelte"
  import MenuBar from "../components/menu-bar.svelte"
  import Desktop from "../components/desktop.svelte"
  let myIntention;
</script>

<div class="bg-violet-200 text-center min-h-screen">
  <MenuBar {myIntention} />
  <Desktop>
    <InputWidget bind:myIntention />
  </Desktop>
  <!-- <TitleBar {myIntention}/>
  
  <TwoSteps />
  <Download /> -->
</div>