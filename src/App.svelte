<script>
  import Example from "$components/Example.svelte";
  import data from "$data/data.js";
  console.log(data);
</script>

<main>
  <h1>Let's make a chart 😎</h1>
  <h2>
    Get started by deleting all of the contents in <pre>App.svelte</pre>
    🗑
  </h2>
  <Example />
  <footer>
    For help, <a
      href="https://twitter.com/CL_Rothschild"
      target="_blank"
      rel="noopener noreferrer">DM Connor on Twitter ✉️</a
    >
  </footer>
</main>

<style>
  main {
    text-align: center;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: #f0f0f0;
  }

  h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
    font-weight: 700;
  }

  h2 {
    font-size: 1.5rem;
    color: #333;
    margin-bottom: 2rem;
    line-height: 1.5;
  }

  pre {
    padding: 1px 6px;
    display: inline;
    margin: 0;
    background: #ffb7a0;
    border-radius: 3px;
  }

  a {
    color: #ff3e00;
    text-decoration: inherit;
  }

  footer {
    font-size: 1rem;
    color: #333;
  }
</style>
