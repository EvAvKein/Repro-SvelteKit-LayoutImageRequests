<section>
  <p>This is where the image requests breaks even more, try refreshing this page</p>

  <p>
    After refreshing, Vite's HMR console will throw an error saying "<code>Not found: /firstNested/secondNested/favicon.png</code>".
    <br/>
    Turns out it's not just prefixing the parent page's path, but the entire path from the home page! (Yes, I tested at further depth and the errors proceed accordingly)
  </p>
</section>

<style>
  section {background-color: rgba(255, 0, 0, 40%)}
</style>