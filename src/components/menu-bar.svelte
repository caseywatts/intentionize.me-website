<script>
  import Basicon from "./basicon.svelte"
  import Logo from "./logo.svelte"
  export let myIntention = "do the dishes";
</script>

<div class="px-4 py-2 flex justify-between bg-violet-800 text-violet-400 stroke-violet-400">
  <div class="flex items-center">
    <span class="px-3 font-semibold text-lg text-violet-50">Intentions<br>in your Menubar</span>
    <span class="px-3 hidden lg:inline-block text-violet-400">File</span>
    <span class="px-3 hidden lg:inline-block text-violet-400">Edit</span>
    <span class="px-3 hidden lg:inline-block text-violet-400">View</span>
    <span class="px-3 hidden lg:inline-block text-violet-400">Go</span>
    <span class="px-3 hidden lg:inline-block text-violet-400">Window</span>
  </div>
  <div class="flex items-center">
    <span class="stroke-violet-50"><Logo height=16/></span>
    <span class="pl-2 pr-3 text-violet-50">{myIntention}</span>
    <span class="px-3 hidden md:inline-block"><Basicon iconName="desktop-computer-mac"/></span>
    <span class="px-3 hidden md:inline-block"><Basicon iconName="moon-night"/></span>
    <span class="px-3 hidden md:inline-block"><Basicon iconName="volume-up"/></span>
    <span class="px-3 hidden md:inline-block"><Basicon iconName="bluetooth"/></span>
    <span class="px-3 hidden md:inline-block"><Basicon iconName="battery-charging"/></span>
    <span class="px-3 hidden md:inline-block"><Basicon iconName="wifi-connection"/></span>
    <span class="px-3 hidden sm:inline-block">Fri Jul 1 9:13 PM</span>
  </div>

</div>