<script>
    import Icons from "../assets/Icons.svelte";
    import Card from "../lib/Card.svelte";
</script>
<seciton id="PROJECTS" class="flex flex-col items-center sm:flex-row sm:justify-center gap-4 p-5 bg-[var(--primary-dark)] rounded-2xl">
    <Card>
        <h1 slot=title> Entries </h1>
        <div slot="image">
            <img src="/public/Entries.png" alt="Screenshot of Entries">
        </div>
        <p slot=description> 
            Organize your thoughts into notes and your notes into Folders. 
            Built with Svelte, Svelte-routing, Firebase, TailwindCSS and DaisyUI
         </p>
        <span slot=demo > <a href=https://entries-7ee81.web.app/ target=_blank> DEMO </a></span>
        <span slot=github > <a href=https://github.com/maxamed1st/entries target=_blank> CODE </a></span>
    </Card>
    <Card>
        <h1 slot=title> Etch A Sketch </h1>
        <div slot="image">
            <img src="/public/Etch-A-Sketch.png" alt="Screenshot of Entries">        </div>
        <p slot=description> 
            Browser based Etch A Sketch. Let your imaginations run wild with this Etch A Sketch 
            built with good ol' vanilla JS
         </p>
         <span slot=demo  > <a href=https://maxamed1st.github.io/Etch-A-Sketch/ target=_blank> DEMO </a></span>
         <span slot=github > <a href=https://github.com/maxamed1st/etch-a-sketch target=_blank> CODE </a></span>
    </Card>
    <Card>
        <h1 slot=title> Toolbox.AI </h1>
        <div slot="image">
            <img src="/public/Toolbox.Ai.png" alt="Screenshot of Entries">        </div>
        <p slot=description> 
            Ai tools collected in one place.
            Here you can read about different AI tools. 
            Built with nextJS, React, Firebase and Tailwind
         </p>
         <span slot=demo  > <a href=https://toolbox-ai-ashy.vercel.app/ target=_blank> DEMO </a></span>
         <span slot=github > <a href=https://github.com/maxamed1st/toolbox.ai target=_blank> CODE </a></span>
    </Card>
</seciton>
