
<script>
    import { members } from './members.js';
  </script>
  
  <h1 class="text-3xl font-bold mb-6">About Us</h1>
  
  <div class="flex flex-wrap -mx-4">
    {#each members as member}
    <div class="rounded-md border-gray-50">
        <div >
            <img class="rounded-full" src="{member.photo} alt={member.name}">
        </div>
        <div>
            <p> {member.name}</p>
        </div>
    </div>
    {/each}
  </div>