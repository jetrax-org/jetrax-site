<script lang="ts">
  import { fade } from "svelte/transition";
  import { draw } from "svelte/transition";
  import Toggler from "./ViewMode.svelte";
</script>

<title>Jetrax</title>

<div>
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <script
    src="https://cdnjs.cloudflare.com/ajax/libs/socket.io/2.0.4/socket.io.js"></script>
  <link
    rel="stylesheet"
    href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
  />
  <Toggler>Toggle</Toggler>
  <main>
    <h1>Jetrax</h1>
    <p>A next gen chat platform for developers</p>
    <button>Click here to learn more</button>
  </main>
  <div >
   <!-- <img src="./pic.png">
   <p class="imagecol">sadasdasd</p> -->
  </div>
</div>  

<style lang="scss">
  @import "./styles/global.scss";
  @import "./styles/_darkMode.scss";
</style>
