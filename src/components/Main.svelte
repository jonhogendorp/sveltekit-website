<script>
    
</script>
<main class="background-radial">
    <div class="hero-image">
        <div class="circle-floating circle-02"></div>
        <div class="circle-floating circle-01"></div>
        <h1 class="landing-text ">
          Welcome to my Portfolio site
        </h1>
    </div>
    <div class="landing-content"></div>
</main>
    <div class="content">
            <div class="landing-content">
                <div class="intro intro-left">
                    <h2>Hi my name is Jon</h2>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aperiam quisquam consequuntur distinctio similique minus dolore sapiente veniam amet repellendus odio eos quis, temporibus eius harum nobis quam quos tenetur saepe!</p>
                </div>
                <div class="intro intro-right"></div>
            </div> 
            <div class="landing-content "></div>
            <div class="landing-content"></div>
    </div>


<style lang="postcss" >
    :global(html) {
  
    }
    .background-radial{
    background: radial-gradient(circle, 
      rgb(40, 0, 161) 0%, 
      rgb(41, 0, 111) 30%,
      rgb(4, 0, 18) 50%);
    }
    :global(.hero-image){
      height:100vh;
      min-height:626px;
    }

    .content{
        background-color: rgb(4,0,18);
    }

    :global(.landing-content){
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        min-height: 70vh;
    }
    :global(.intro){
        width: 35%;
        height: 60%;
        min-height: 400px;
        min-width: 400px;
        padding:1.5rem;
    }
    :global(.intro-left){
        border-top-left-radius: 1rem;
        border-bottom-left-radius: 1rem;
    }
    :global(.intro-right){
        background-color: rgb(78,84,100); 
        border-top-right-radius: 1rem;
        border-bottom-right-radius: 1rem;
    }
    .circle-floating{
        border-radius: 50%;
        z-index: 0;
        position: absolute;
        background-color: rgb(255, 255, 206);
    }
    
    .circle-01{
        height: 100px;
        width: 100px;
        bottom: 60%;
        left: 10%;
    }

    .circle-02{
        height: 50px;
        width: 50px;
        bottom: 70%;
        left: 5%;
    }

</style>