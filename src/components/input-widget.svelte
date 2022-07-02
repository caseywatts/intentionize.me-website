<script>
  import Logo from "../components/logo.svelte";
  export let myIntention = "finish proposal";
  const placeholder = "set your intention"
  const iconPath = "/focus.svg";
  const updateTitle = () => {};
  const setTitleAndHideWindow = () => {};

  function* spellingGenerator () {
    let string = "finish proposal"
    for (let i = 1; i <= string.length; i++) {
      yield string.slice(0,i)
    }
  }
  let spellinging = spellingGenerator()
  const displayNextCharacter = () => {
    const currentState = spellinging.next()
    if (currentState.done == false) {
      myIntention = currentState.value
    }
  }
  setInterval(displayNextCharacter, 100)
</script>

<div class="p-8">
  <div class="flex justify-center">
    <div class="input-box rounded-xl shadow-lg shadow-black">
      <form on:submit|preventDefault>
        <div style="display:flex; justify-content: center; align-items: center;">
          <span style="margin-right: 10px;" alt="Intentions app logo">
            <Logo height=20/>
            </span>
          <input autofocus class="intention-input" type="text" bind:value={myIntention} {placeholder} on:keyup={updateTitle} />
        </div>
        <div style="display:none; margin-top: 10px;"><button on:click={setTitleAndHideWindow}>Update</button></div>
      </form>
    </div>
  </div>
</div>

<style>
  form {
    margin: 0;
    padding: 0;
  }
  input {
    margin: 0;
    outline-color: #ae90da;
    outline-width: 10px;
  }
  .intention-input {
    width: 300px;
    text-align: center;
  }
  .input-box {
    text-align:center;
    display:flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: #c2c3eb;
    height: 100px;
    width: 400px;
  }
</style>