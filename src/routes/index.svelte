<script>
  import "../app.css";
  import { base } from '$app/paths';

</script>

<div class="bg-violet-200 text-center min-h-screen">
  <div class="bg-sky-600 text-violet-200 shadow-inner shadow-sky-900">
    <div class="p-2">
      <h1 class="text-2xl p-2">Intentions in your Menubar</h1>
      <div class="m-2 p-6 px-10 bg-sky-700 inline-block shadow-inner shadow-sky-900">
        <div class="md: inline-block italic text-lg">"Wait, what was I doing??"</div>
        <div class="md: inline-block pt-4 pl-6 text-right">– you, probably</div>
      </div>
    </div>
  </div>
  <div class="md:flex justify-items-center justify-around items-stretch p-2 space-y-6">
    <div class="bg-violet-300 m-3 rounded-lg border-2 border-violet-600 shadow-lg shadow-violet-900">
      <div class="bg-violet-500 text-violet-100 p-4 text-xl">one</div>
      <div class="p-4">
        <div class="p-3 text-xl">
          <div>
            press
            <pre class="inline bg-violet-200 p-2">control</pre>
            +
            <pre class="inline bg-violet-200 p-2">~</pre>
          </div>
          <div class="p-2">then type your intention</div>
        </div>
        <img class="inline-block w-96" src="{base}/intentions window.png" />
      </div>
    </div>
      
    <div class="bg-violet-300 m-3 rounded-lg border-2 border-violet-600 shadow-lg shadow-violet-900">
      <div class="bg-violet-500 text-violet-100 p-4 text-xl">two</div>
      <div class=" p-4">
        <div class="p-3 text-xl">Now your menubar will remind you 🎉</div>
        <img class="inline-block w-96" src="{base}/intentions menubar.png" />
      </div>
    </div>
  </div>
  <div class="bg-violet-300 border-2 border-violet-600 md:absolute mt-6 bottom-0 w-full">
    <div class="p-8 pt-6 space-y-2">
      <div><a class="bg-violet-500 text-violet-100 p-3 text-lg rounded" href="https://github.com/caseywatts/intentions/releases/latest/download/intentions-mac.zip">download intentions for mac</a></div>
      <div class="pt-2 underline text-blue-800"><a href="https://github.com/caseywatts/intentions/">free and open source</a></div>
      <div class="underline text-blue-800">made by <a href="https://twitter.com/heycaseywattsup">Casey Watts!</a></div>
    </div>
  </div>

</div>