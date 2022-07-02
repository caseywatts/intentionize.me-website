<script>
  import Basicon from "./basicon.svelte"
  export let myIntention = "do the dishes";
</script>

<div class="px-4 py-2 flex justify-between bg-violet-800 text-violet-400 stroke-violet-400">
  <div class="flex">
    <span class="px-3 font-semibold text-violet-50">Intentions in your Menubar</span>
    <span class="px-3 text-violet-400">File</span>
    <span class="px-3 text-violet-400">Edit</span>
    <span class="px-3 text-violet-400">View</span>
    <span class="px-3 text-violet-400">Go</span>
    <span class="px-3 text-violet-400">Window</span>
  </div>
  <div class="flex">
    <span class="stroke-violet-50"><Basicon iconName="volume-up"/></span>
    <span class="pl-2 pr-3 text-violet-50">{myIntention}</span>
    <span class="px-3"><Basicon iconName="desktop-computer-mac"/></span>
    <span class="px-3"><Basicon iconName="moon-night"/></span>
    <span class="px-3"><Basicon iconName="volume-up"/></span>
    <span class="px-3"><Basicon iconName="bluetooth"/></span>
    <span class="px-3"><Basicon iconName="battery-charging"/></span>
    <span class="px-3"><Basicon iconName="wifi-connection"/></span>
    <span class="px-3">Fri Jul 1 9:13 PM</span>
  </div>

</div>