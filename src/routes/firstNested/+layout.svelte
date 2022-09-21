<section>
  <h3>This is another layout</h3>
  <p>This nested layout is here to demonstrate that the prefixed path issue (revealed in deeper pages) doesn't request a path relative to the nested depth from the layout sourcing the image, it requests the same path regardless of relative layout depth</p>
  <slot/>
  <img src="./favicon.png" alt="The Svelte logo"/>
</section>

<style>
  section {background-color: rgba(0, 255, 0, 40%)}
</style>