<script>
    import { members } from './members.js';
  </script>
  
  <h1 class="text-3xl font-bold mb-6">About Us</h1>
  

<div class="flex gap-8 basis-64 flex-wrap ">
{#each members as member }
  <div class=" rounded-md border-4 {member.color} text-center flex flex-col justify-center items-center max-w-xs">
    <div class="pd-36">
      <img class="rounded-full border-4 content-center " src={member.photo} alt={member.name}>
    </div>
    <div>
      <p class="text-5xl ">{member.name}</p>
      <p class="text-3xl"> {member.function}</p>
      <p class="">{member.description}</p>
    </div>
  </div>

{/each}
</div>