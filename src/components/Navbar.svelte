<script>
    import "../app.css";
</script>

<div class="navbar ">
    <header class="wrapper">
        <a href="/" class="header-link"> 
            Home
        </a>
        <a href="/" class="header-link">
            Contact
        </a>
        <a href="/about" class="header-link">
            About
        </a>
        <a href="/" class="header-link">
            Download
        </a>
        <a href="/" class="header-link">
            Work
        </a>
    </header>
    <header class="wrapper mobile-wrapper">

    </header>
</div>

<style lang="postcss">
    .navbar{
        position: absolute;
        width: 100%;
    }

    .wrapper{
    color: white;
    font-size: 20px;
    width: 100%;
    margin: 40px 0;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    z-index: 2;
    /* border-bottom: 1px solid white; */
}
.wrapper a{
    margin: 0 2rem;
    z-index: 1;
    text-decoration: none;
    color: var(--white);
    font-family: 'Roboto', sans-serif;
    font-weight: 500;
}

.wrapper a:hover{
    text-decoration: underline;
}

.mobile-wrapper{
    display: none;
}

</style>