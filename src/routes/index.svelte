<script>
  import "../app.css";
  import Download from "../components/download.svelte";
  import InputWidget from "../components/input-widget.svelte"
  import TitleBar from "../components/title-bar.svelte"
  import TwoSteps from "../components/two-steps.svelte"
  let myIntention;
</script>

<div class="bg-violet-200 text-center min-h-screen">
  <TitleBar {myIntention}/>
  <InputWidget bind:myIntention />
  <TwoSteps />
  <Download />
</div>