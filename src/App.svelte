<!-- SCRIPTS /////////////////////////////////////////// -->
<script>
  import Header from "./components/Header.svelte";
  import Footer from "./components/Footer.svelte";
</script>

<!-- MARKUP ////////////////////////////////////////////// -->
<div id="app-container">
  <Header />
  <Footer />
</div>

<!-- STYLES ///////////////////////////////////////////// -->
<style>
  #app-container {
    max-width: 760px;
    min-height: 100vh;
    margin: 0 auto;
    border: 4px solid blue;
    display: flex;
    flex-direction: column;
    justify-content: center;
  }
</style>