<script>
	import Navbar from "../components/Navbar.svelte";
    import "../app.css";
  import Footer from "../components/Footer.svelte";
</script>
  
<svelte:head>
    <title>Brand website Jon</title>
</svelte:head> 

<Navbar/> 

<slot /> 

<Footer/>