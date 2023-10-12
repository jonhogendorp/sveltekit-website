<script>
  import "../app.css";
  import Main from "../components/Main.svelte";
</script>


<Main/>


  <style lang="postcss">
    :global(html) {
      background-color: theme(colors.white);
    }
    :global(.hero-image){
      background-color: theme(colors.indigo.600);
      height:60vh ;
      min-height:626px;
    }
  </style>