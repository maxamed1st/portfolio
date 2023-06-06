<script>
    import { each } from "svelte/internal";
    let techStack = [
        { src: "src/assets/html5.svg", alt: "html5" },
        { src: "src/assets/css3.svg", alt: "css3" },
        { src: "src/assets/tailwindCSS.svg", alt: "tailwindCSS" },
        { src: "src/assets/python.svg", alt: "python" },
        { src: "src/assets/javascript.svg", alt: "javascript" },
        { src: "src/assets/react.svg", alt: "react" },
        { src: "src/assets/svelte.svg", alt: "svelte" },
        { src: "src/assets/nextdotjs.svg", alt: "nextJS" },
        { src: "src/assets/npm.svg", alt: "npm" },
        { src: "src/assets/git.svg", alt: "git" },
        { src: "src/assets/github.svg", alt: "github" },
        { src: "src/assets/webpack.svg", alt: "webpack" },
    ];
</script>
<!-- tilt back the icons on wider screens -->
<section class="flex flex-col flex-1 text-center items-center my-auto gap-2">
    <header class="text-[2rem] ">TECH STACK</header>
    <div class="grid grid-cols-4 grid-rows-3 gap-1 ">
        {#each techStack as stack (stack.alt)}
            <img src={stack.src} alt={stack.alt} class="h-16 w-16 p-1" />
        {/each}
    </div>
</section>

<style>
    img {
        transform: rotateX(50deg);
    }
</style>
