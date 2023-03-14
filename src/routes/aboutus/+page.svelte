<script>
    import { members } from './members.js';
  </script>
  
  <h1 class="text-3xl font-bold mb-6">About Us</h1>
  
<!--  <div class="flex flex-wrap -mx-4">
    {#each members as member}
    <div class="rounded-md border-gray-500">

    <p>{member.function}</p>
    </div>
    {/each}
  </div>-->
<div class="flex row  flex-wrap ">
{#each members as member }
  <div class=" rounded-md border-4">
    <img class="rounded-full" src={member.photo} alt={member.name}>    
  </div>

{/each}
</div>