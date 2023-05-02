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
        <p>
          <h2>What's a Minecraft Plugin?</h2><p>
          A plugin is extra code you add to your Minecraft server to change the default behavior of the game.
          You can use them to create commands, objects, functions, etc.
          </p><h2><br>How can I use plugins?</h2>
          <p>
          Plugins are server-side only then, you don't need to install them on your client. You just have to install them on your server and, if you want, configure them through plugins folders as described in their own documentations.</p>
          <h2><br>What can I do if a Plugin doesn't work?</h2>
          <p>
          You should check if the plugin is compatible with your server version and your server logs.
          If the plugin is compatible with your server version and the log doesn't show any errors, you can try reading the plugin documentation, asking to the plugin author for support or just removing it.
          <h2> <br>Where can I find plugins?</h2>
          <p>You can find plugins in:</p>
          <ul class="list-disc list-inside text-cyan-400">
            <li><a class="text-cyan-400" href="https://spigotmc.org/"> spigotmc</a></li>
            <li><a class="text-cyan-400" href="https://bukkit.org/">bukkit</a></li>
            <li><a class="text-cyan-400" href="https://modrinth.com/plugins">modrinth plugins</a></li>
          </ul>

      </div>
    <div class="w-1/12"></div>
    </div>
    