<script>
    import Icons from "../assets/Icons.svelte";
    import Card from "../lib/Card.svelte";
</script>
<seciton id="PROJECTS" class="flex flex-col items-center sm:flex-row sm:justify-center gap-4 p-5 bg-[var(--primary-dark)] rounded-2xl">
    <Card>
        <h1 slot=title> Title </h1>
        <div slot="image">
            <Icons i="html" fill="#E34F26" cls="aspect-video object-contain w-full h-full"/>
        </div>
        <p slot=description> 
            Description
            Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Repellendus accusamus laboriosam quae quia aspernatur? 
            Officia itaque, unde laudantium iste fugiat eius dolor aut eos quia autem ex minus ab esse!
         </p>
        <span slot=demo  > DEMO </span>
        <span slot=github  > CODE </span>
    </Card>
    <Card>
        <h1 slot=title> Title </h1>
        <div slot="image">
            <Icons i="tailwind" fill="#dd6f41" cls="aspect-video object-contain w-full h-full"/>
        </div>
        <p slot=description> 
            Description
            Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Repellendus accusamus laboriosam quae quia aspernatur? 
            Officia itaque, unde laudantium iste fugiat eius dolor aut eos quia autem ex minus ab esse!
         </p>
         <span slot=demo  > DEMO </span>
         <span slot=github  > CODE </span>
    </Card>
    <Card>
        <h1 slot=title> Title </h1>
        <div slot="image">
            <Icons i="css" fill="#1572B6" cls="aspect-video object-contain w-full h-full"/>
        </div>
        <p slot=description> 
            Description
            Lorem ipsum dolor sit amet consectetur adipisicing elit. 
            Repellendus accusamus laboriosam quae quia aspernatur? 
            Officia itaque, unde laudantium iste fugiat eius dolor aut eos quia autem ex minus ab esse!
         </p>
         <span slot=demo  > DEMO </span>
         <span slot=github  > CODE </span>
    </Card>
</seciton>
