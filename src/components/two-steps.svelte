<script>
  import { base } from '$app/paths';
</script>

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