<script>
    /**
   * @type {any}
   */
     export let aboutUsBlocks;
  </script>
  
  {#each aboutUsBlocks as block}
    <div class="about-us-block">
      <img class="profile-picture" src="https://example.com/profile-pic.png" alt="Profile Picture">
      <div class="info-block">
        <h2 class="name">{block.name}</h2>
        <p class="function">{block.functionText}</p>
        <p class="introduction">{block.introduction}</p>
      </div>
    </div>
  {/each}
  