<script>
    import Card from "../lib/Card.svelte";
</script>
<seciton id="PROJECTS" class="flex flex-col items-center sm:flex-row sm:justify-center gap-4 p-5 bg-[var(--primary-dark)] ">
    <Card>
        <h1 slot=title> Title </h1>
        <img slot=image src="src/assets/svelte.svg" alt="svelte" class="aspect-video object-contain" />
        <p slot=description> 
            Description
            Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Repellendus accusamus laboriosam quae quia aspernatur? 
            Officia itaque, unde laudantium iste fugiat eius dolor aut eos quia autem ex minus ab esse!
         </p>
        <div slot=demo> Demo </div>
        <div slot=github> Repository </div>
    </Card>
    <Card>
        <h1 slot=title> Title </h1>
        <img slot=image src="src/assets/svelte.svg" alt="svelte" class="aspect-video object-contain" />
        <p slot=description> 
            Description
            Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Repellendus accusamus laboriosam quae quia aspernatur? 
            Officia itaque, unde laudantium iste fugiat eius dolor aut eos quia autem ex minus ab esse!
         </p>
        <div slot=demo> Demo </div>
        <div slot=github> Repository </div>
    </Card>
    <Card>
        <h1 slot=title> Title </h1>
        <img slot=image src="src/assets/svelte.svg" alt="svelte" class="aspect-video object-contain" />
        <p slot=description> 
            Description
            Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Repellendus accusamus laboriosam quae quia aspernatur? 
            Officia itaque, unde laudantium iste fugiat eius dolor aut eos quia autem ex minus ab esse!
         </p>
        <div slot=demo> Demo </div>
        <div slot=github> Repository </div>
    </Card>
</seciton>
