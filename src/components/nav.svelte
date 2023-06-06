<script>
    let links = ["STACK", "PROJECTS", "ABOUT", "CONTACT"];
    let isHidden = true;
    //coditionally change the value of isHidden based on media quaries
    let toggleHidden = () => {
        const mediaQuery = window.matchMedia("(max-width: 640px)");
        if(mediaQuery.matches) return isHidden = !isHidden
    };
</script>

<nav class="bg-[--secondary-dark]  text-center min-w-min ">
    <ul class="flex gap-1 text-2xl relative">
        <li class="mr-auto ">
            <a href="/"> 💆🏾‍♂️ </a> 
        </li>
        <!-- Hamburger menu -->
        <li 
        on:click={toggleHidden}  on:keypress={toggleHidden}
        class=
            {`group grid place-content-center grid-flow-col sm:hidden
            ${ isHidden ? "bg-[var(--accent)]" : "!bg-[var(--accent-analogous)]" }`}
        >
            <!-- the lines in the hamburger menu -->
            <div class={`flex flex-col ${isHidden ? "" : "rotate-90"} [&_*]:w-8 [&_*]:h-2 [&_*]:p-1 overflow-hidden`}>
                <div><hr></div>
                <div><hr></div>
                <div><hr></div>
            </div>
            <!-- align hamburger menu whith dropdown menu -->
            <div class={`${isHidden ? "hidden" : "flex" } w-36`}> </div>
        </li>
        <!-- navbar items -->
        <ul class={`${isHidden ? "hidden" : "block" } absolute top-12 right-0 max-sm:w-48 sm:static sm:flex sm:divide-x`}>
            {#each links as link}
                <li on:click={toggleHidden} on:keypress={toggleHidden}> 
                    <a href="#{link}"> {link} </a>
                </li>
            {/each}
        </ul>
    </ul>
</nav>

<style>
    li {
        background-color: var(--accent);
        color: var(--primary-dark);
        padding: 8px;
        transition: all 0.3s ease;
    }
    li:hover {
        background-color: var(--accent-analogous);
        color: var(--primary);
    }
</style>
