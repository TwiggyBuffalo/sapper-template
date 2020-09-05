<style>
  h1,
  figure,
  p {
    text-align: center;
    margin: 0 auto;
  }

  h1 {
    font-size: 2.8em;
    font-weight: 700;
    margin: 0 0 0.5em 0;
  }

  .link {
    color: #676778;
    text-decoration: none;
  }

  .link:hover {
    text-decoration: underline;
  }

  figure {
    margin: 0 0 1em 0;
  }

  img {
    width: 100%;
    max-width: 400px;
    margin: 0 0 1em 0;
  }

  p {
    line-height: 1.5;
    font-size: 1.5rem;
    margin: 1em auto;
  }

  @media (min-width: 480px) {
    h1 {
      font-size: 4em;
    }
  }
</style>

<svelte:head>
  <title>Sapper project template</title>
</svelte:head>

<h1>
  Welcome to <a class="link" href="https://sapper.svelte.dev/">Sapper!</a>
</h1>

<p>Get started by editing <code>(/src/routes/index.svelte)</code></p>

<figure>
  <img alt="Success Kid" src="successkid.jpg" />
</figure>
