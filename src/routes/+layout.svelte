<section>
  <h1>This is the layout</h1>
  <h2>You're at: {$page.url.pathname}</h2>
  <slot/>
  <img src="./favicon.png" alt="The Svelte logo"/>
  <a href="/">Go to top-level page</a>
  <a href="/firstNested">Go to first nested page</a>
  <a href="/firstNested/secondNested">Go to second nested page</a>
  <a href="/firstNested/secondNested/thirdNested">Go to third nested page</a>
</section>

<script>
  import {page} from "$app/stores";
</script>

<style>
  :global(section) {padding: 1em}

  h1 {margin-bottom: 0}
  h2 {margin-top: 0.25em}

  section {
    font-size: 1.5em;
    background-color: rgba(255, 0, 0, 40%); 
  }
  
  :global(img), a {display: block}
</style>