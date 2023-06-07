<script>
    const icons = [
        {"src" : "src/assets/linkedin.svg", "link" : "https://www.linkedin.com/in/mohamed-hassan-ahmed-b629447a/"},
        {"src" : "src/assets/github.svg", "link" : "https://github.com/maxamed1st"},
        {"src" : "src/assets/email.svg", "link" : "mailto:maxamed1st@gmail.com", "target" : "top_"},
        ]
</script>
<footer class="flex flex-col gap-4 items-center text-center bg-[var(--secondary)] text-[var(--primary)] p-10 w-full">
    <div> Connect with <span class="text-[var(--primary-dark)]"> Mohamed Hassan Ahmed </span> </div>
    <div id="CONTACT" class="flex gap-10">
        {#each icons as icon, index (index)}
            <a href={icon.link} target={icon?.target}> 
                <img src={icon.src} alt={icon.link} class="aspect-square object-contain w-5 h-5 hover:scale-150" /> 
            </a>
        {/each}
</div>
</footer>
