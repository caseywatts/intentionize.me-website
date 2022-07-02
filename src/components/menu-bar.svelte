<script>
  import Basicon from "./basicon.svelte"
  export let myIntention = "do the dishes";
</script>

<div class="px-4 py-2 flex justify-between bg-violet-800 text-white fill-white stroke-white">
  <div class="flex">
    <span class="px-3">Finder</span>
    <span class="px-3">File</span>
    <span class="px-3">Edit</span>
    <span class="px-3">View</span>
    <span class="px-3">Go</span>
    <span class="px-3">Window</span>
  </div>
  <div class="flex">
    <span class=""><Basicon iconName="volume-up"/></span>
    <span class="pl-2 pr-3">{myIntention}</span>
    <span class="px-3"><Basicon iconName="desktop-computer-mac"/></span>
    <span class="px-3"><Basicon iconName="moon-night"/></span>
    <span class="px-3"><Basicon iconName="volume-up"/></span>
    <span class="px-3"><Basicon iconName="bluetooth"/></span>
    <span class="px-3"><Basicon iconName="battery-charging"/></span>
    <span class="px-3"><Basicon iconName="wifi-connection"/></span>
    <span class="px-3">Fri Jul 1 9:13 PM</span>
  </div>

</div>