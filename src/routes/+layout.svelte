<script>
	import Navbar from "../components/Navbar.svelte";
    import "../app.css";
    import Footer from "../components/Footer.svelte";

    let y;
    let innerHeight = 0;
    let innerWidth = 0;

    function goTop() {
        document.body.scrollIntoView();
    }
</script>
  
<svelte:head>
    <title>Brand website Jon</title>
</svelte:head> 

<div class={"fixed bottom-0 w-full duration-200 flex p-10 z-[10] " + (
    y > 0 ? 'opacity-full pointer-events-auto' : 'pointer-events-none opacity-0'
)}>
    <button on:click={goTop}>
        <i class="fa fa-arrow-up fa-lg"></i>
    </button>
</div>

<Navbar/> 

<slot /> 

<Footer/>

<svelte:window bind:scrollY={y} bind:innerHeight bind:innerWidth />