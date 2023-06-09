<script>
    import Icons from "../assets/Icons.svelte";
</script>
<footer class="flex flex-col gap-10 items-center justify-center bg-[var(--secondary)] text-[var(--primary)] p-10 w-full h-96">
    <div class="text-7xl"> CONNECT </div>
    <div id="CONTACT" class="flex gap-10">
        <a href="https://www.linkedin.com/in/mohamed-hassan-ahmed-b629447a/" class="flex-1 w-16 h-16 sm:w-24 sm:h-24 hover:scale-150"> 
            <Icons i="linkedin" fill=#0A66C2 cls="w-ful h-full flex-1"/>
        </a>
        <a href="https://github.com/maxamed1st" class="flex-1 w-16 h-16  sm:w-24 sm:h-24 hover:scale-150"> 
            <Icons i="github" fill=#181717/>
        </a>
        <a href="https://discord.com/channels/mo#5372" class="flex-1 w-16 h-16  sm:w-24 sm:h-24 hover:scale-150"> 
            <Icons i="discord" fill=#5865F2/>
        </a>
        <a href="mailto:maxamed1st@gmail.com" class="flex-1 w-16 h-16  sm:w-24 sm:h-24 hover:scale-150"> 
            <Icons i="email" />
        </a>
    </div>
</footer>
