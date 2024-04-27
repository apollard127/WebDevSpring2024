<script>
    import Hero from "$lib/Hero.svelte";
</script>

<Hero/>

<section class="section flow">
    <h2>Art Show Events</h2>
<div class="boxes">
    
    <div class="flow">
        <img src='/Pretty_fish.jpg' alt="featured artists">
        <div>
            <h3>Featured Artists</h3>
        <div class="subheading">May 2024</div>
    </div>
     <p>Complete the form to request an application to exhibit your art work</p>
     <a href="/contact" class="button">Application</a>
    </div>

    <div class="flow">
        <img src='/lake.jpg' alt="placeholder">
        <div><h3>Become a Judge</h3>
        <div class="subheading">May 2024</div>
        </div>
     <p>Complete the form to be on the panel to judge the winners</p>
     <a href="/contact" class="button">Judge</a>
    </div>
</div>
</section>

<style>
    section{
        padding: 3rem;
        background-color: hsl(34, 92%, 43%);
        border-radius: 1rem;
    }
.boxes {
display: grid;
grid-template-columns: repeat(auto-fit, minmax(14rem, 1fr));
gap: 3rem;
}

.subheading {
    text-transform: uppercase;
    font-size: 0.8rem;
    letter-spacing: 1px;
}

.button {
    display: inline-block;
    padding-inline: 1rem;
}
</style>