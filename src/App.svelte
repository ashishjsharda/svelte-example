<script>
  let name = 'world';
</script>

<main>
  <h1>Hello {name}!</h1>
  <input bind:value={name} placeholder="Enter your name">
</main>

<style>
  main {
    text-align: center;
    padding: 50px;
    font-family: Arial, sans-serif;
  }
  input {
    margin-top: 20px;
    padding: 10px;
    font-size: 16px;
  }
</style>
