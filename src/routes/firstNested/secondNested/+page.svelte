<section>
  <p>This is where the image requests starts to break, try refreshing this page</p>

  <p>
    After refreshing, Vite's HMR console will throw an error saying "<code>Not found: /firstNested/favicon.png</code>".
    <br/>
    It prefixed the image request address with the parent folder... but there's more to this issue, go to the 4th nested page!
  </p>
</section>

<style>
  section {background-color: rgba(0, 0, 255, 40%)}
</style>