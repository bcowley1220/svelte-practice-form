<script>
  let name = "Stranger";
</script>

<style>
  .formWrapper {
    height: 100%;
    width: 100%;
    display: flex;
    flex-flow: column nowrap;
    background: lightblue;
  }
</style>

<div id="" class="formWrapper">
  <form action="" id="" class="">
    <label for="name">
      <input
        type="text"
        bind:value={name}
        id=""
        class=""
        placeholder="First Name" />
    </label>
  </form>
  <h2>Hello {name}</h2>
</div>
