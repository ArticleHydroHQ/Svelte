<script>
  import { info } from './info.js';
  import Navbar from '../../navbar.svelte';
    </script>
    <Navbar></Navbar>
  <div class="flex"> 
    <div class="w-2/12 ">
      <div class="border-2 border-stone-500">
        <p class="text-xl">Writen by {info[0].writer} <br><br> Name of the article: {info[0].name}</p>
      </div>
    </div>
    <div class="w-1/12"></div>
    <div class="w-8/12">
      <h1 class="text-center text-4xl">{info[0].name}</h1>
      <p>tex</p>
    </div>
  <div class="w-1/12"></div>
  </div>
  