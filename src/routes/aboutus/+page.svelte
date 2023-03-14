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
  <div class=" rounded-md border-4 text-center">
    <img class="rounded-full border-4" src={member.photo} alt={member.name}>
    <p class="text-center text-3xl">{member.name}</p>
    <p class="text-center text-lg"> {member.function}</p>
    <p class="">{member.description}</p>
  </div>

{/each}
</div>