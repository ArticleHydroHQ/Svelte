<script>
import { info } from './info.js';
import Navbar from '../../navbar.svelte';
  </script>
  <Navbar></Navbar>
<div class="flex"> 
  <div class="w-1/12"></div>
  <div class="w-10/12">
    <h1 class="text-center text-4xl">{info[0].name}</h1>
    <p>text</p>
  </div>
  <div class="w-1/12"></div>
</div>
