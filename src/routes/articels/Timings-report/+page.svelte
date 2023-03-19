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
      <div class="w-8/12 leading-relaxed">
        <h1 class="text-center leading-10">{info[0].name}</h1>
        <h2 class="leading-7"> Server softwares that include timings</h2>
        <ul class="list-disc">
            <li><a class="text-cyan-600" href="https://pufferfish.host/downloads">Pufferfish</a> (V2, disabled by default)</li>
            <li><a class="text-cyan-600" href="https://papermc.io">Paper</a> (V2)</li>
            <li><a class="text-cyan-600" href="https://www.spigotmc.org">Spigot</a> (V1)</li>
        </ul>
        <h2 class="leading-7"><br>Server softwares that <i>don't</i> include timings</h2>
        <ul class="list-disc">
            <li><a class="text-cyan-600" href="https://github.com/Bloom-host/Petal">Petal</a>(Includes spark instead, development seems to be dead)</li>
            <li><a class="text-cyan-600" href="https://purpurmc.org">Purpur</a>(Includes spark instead)</li>
            <li><a class="text-cyan-600" href="https://bukkit.org">Bukkit</a>(Outdated and insecure, use <a href="https://papermc.io">Paper</a>instead)</li>
        </ul>
        <h2><br>How to get a timings report</h2>
        <p>Turn on the server join as an OP then run <code >/timings on</code>
            then wait or play, about 10-15 minutes then run <code >/timings paste</code> and open the link in your browser or share it with the support that has told you to make this
        </p>
        <h2> <br>How to get a spark report</h2>
        <p>Alternatively, you can run <code >/spark profiler start</code> and wait however long you wait as long as there are no restarts.
          When you want it to stop run <code >/spark profiler stop</code>
        </p>
        <h2><br>Should i use timings or spark?</h2>
        <p>Timings is included with most server softwares, however does constantly drain about 5% of your ticks even if its off (!!!)<br></p>
        <p><a class="text-cyan-600" href="https://spark.lucko.me">Spark</a> is more powerful and can be used with any server software that supports bukkit plugins, and doesn’t drain your server when its not in use.<br></p>
        <p><br>Ultimately, it’s up to you, but <a class="text-cyan-600" href="https://spark.lucko.me">spark</a> is recommended.</p>
      </div>
    <div class="w-1/12"></div>
    </div>