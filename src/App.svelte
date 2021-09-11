<script lang="ts"> 
  import { getContext } from 'svelte';
  import { fade } from "svelte/transition";
  import { draw } from "svelte/transition";
  import Toggler from "./components/ViewMode.svelte";
  
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
    <p>Jetrax, An OSS Chat Platform Made For Developers!</p>
    <button>Click here to learn more</button>
  </main>
  <br/><br/><br/><br/>
   <p class="imagecol">Fast and secure made using deno.</p> 
   <br/><br/><br/><br/>
   <p class="imagecol2">Open Source on Github</p> 
   <p>Test commit was here.</p>
   <br/><br/><br/><br/>
</div>

<style lang="scss">
  @import "./styles/global.scss";
  @import "./styles/_darkMode.scss";
</style>
