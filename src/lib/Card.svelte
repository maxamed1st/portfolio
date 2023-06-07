<article class="w-96 bg-white p-5 rounded-lg">
    <slot name="image"></slot>
    <header class="font-thin">
        <slot name="title"></slot>
    </header>
    <main class="font-light break-all pb-2">
        <slot name="description"> No description </slot>
    </main>
    <hr class="text-[var(--secondary)]" />
    <footer class="flex [&_*]:flex-1 text-center ">
            <slot name="demo"> </slot>
            <slot name="github"> </slot>
    </footer>
</article>
