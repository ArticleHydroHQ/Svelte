<script>
  import Navbar from "../navbar.svelte";
  import { articles } from "./articels";
</script>

  <Navbar></Navbar>
  <h1 class="text-3xl font-bold mb-6 text-center">List of article's</h1>
  

<div class="flex gap-8 basis-64 flex-wrap ">
{#each articles as articles }
<a href='{articles.link}'>
  <div class=" rounded-md border-4  text-center flex flex-col justify-center items-center max-w-xs">
    <div class="pd-36">
        <p class="text-3xl">{articles.name}</p>
    </div>
    <div>
        <p class="text-2xl"> Writer: {articles.writer}</p>
        <a class="text-xl" href='{articles.link}'> Read more </a>
    </div>
  </div>
</a>
{/each}
</div>