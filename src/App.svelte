<main>
  <h1>Hello {name}! My age is {age}</h1>
  <button class="btn btn-success" type="button" on:click={incrementAge}>
    Increment age
  </button>
</main>

<script>
  let name = 'Eugene'
  let age = 32

  const incrementAge = () => {
    age++
  }
</script>

<style>
</style>
