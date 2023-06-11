<article class="w-96 bg-white p-5 rounded-lg">
    <slot name="image"></slot>
    <header class="font-thin">
        <slot name="title"></slot>
    </header>
    <main class="font-light break-all pb-2">
        <slot name="description"> No description </slot>
    </main>
    <hr class="text-[var(--secondary)] mb-2" />
    <footer class="flex [&_*]:flex-1 text-center gap-4 ">
        <button class="btn left-in ">
            <slot name="demo"> </slot>
        </button>
        <button class="btn right-in">
            <slot name="github"> </slot>
        </button>
    </footer>
</article>
<style>
    .btn { 
        position: relative;
        width: 100%;
        height: 3rem;
        border-width: 1px;
        border-color: var(--secondary);
        border-radius: 8px;
        transition: all, 1s, linnear;
        z-index: 1;
    }
    .btn:hover {
        color: white;
        border: 0;
        transform: scale(110%);
        font-size: larger;
        transition: all, 1s, linnear;
    }
    .btn:before {
        content: "";
        position: absolute;
        background-color: var(--secondary);
        top: 0;
        bottom: 0;
        left: 50%;
        width: 0%;
        transform: translateY(-2%) scaleY(96%) ;
        transition: all, 1s, linnear; 
        z-index: -1;
    }
    .btn:hover:before {
        background-color: var(--accent-x-light);
        border-width: 2px;
        border-color: var(--secondary);
        border-radius: 8px;
        left: 0;
        width: inherit;
        transition: all, 1s, linnear;
    }
</style>
