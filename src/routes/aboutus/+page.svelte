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
<div class="flex gap-8 basis-64  ">
{#each members as member }
  <div class=" rounded-md border-4 text-center ">

    <div>
      <img class="rounded-full border-4 place-self-center" src={member.photo} alt={member.name}>
    </div>
    <p class="text-center text-5xl">{member.name}</p>
    <p class="text-center text-3xl"> {member.function}</p>
    <p class="text-center ">{member.description}</p>
  </div>

{/each}
</div>