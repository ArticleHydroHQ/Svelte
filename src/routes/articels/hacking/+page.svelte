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
      <div>
        <p>For big and small Minecraft servers, hacking is a common problem.</p>
        <h2><br> Common ways of hacking</h2>
        <ul class="list-disc list-inside">
          <li>X-ray</li>
          <li>Using other people’s accounts (only for cracked servers)</li>
          <li>Using hack clients</li>
        </ul>
        <h2><br>Ways of preventing X-ray</h2>
        <ul class="list-disc list-inside">
          <li>Use anti-x-ray such as paper’s anti-xray <a class="text-cyan-600" href="https://docs.papermc.io/paper/anti-xray">guide to set it up</a></li>
        </ul>
        <h2 ><br> Ways of preventing hack clients</h2>
        <ul>
          <li>Install an anti-cheat, there are many options, so go explore, some good ones that <a class="text-cyan-600" href="https://github.com/Soapy7261">Soapy7261</a> has used include</li>
          <li><a class="text-cyan-600" href="https://www.spigotmc.org/resources/themis-anti-cheat-1-17-1-18-1-19-bedrock-support-paper-compatibility-free-optimized.90766">Themis</a> (Free), however mainly targets moved based hacks, not pvp hacks</li>
          <li><a class="text-cyan-600" href="https://www.spigotmc.org/resources/vulcan-anti-cheat-advanced-cheat-detection-1-7-1-19-3.83626">Vulcan</a> (Paid), also has a <a href="https://www.spigotmc.org/resources/vulcanbungee-bungee-hook-for-vulcan-anti-cheat.94194">hook for bungee</a> to sync alerts and scores across your servers, has discord webhook connection options, detects most hacks other than what’s listed that it does not check for in the description, and more, go check it out!</li>
        </ul>
        <h2><br>Ways of preventing account stealing</h2>
        <ul class="list-disc list-inside">
          <li>Disable cracked (preferred)</li>
          <li>A login plugin, not recommended because some contain security issues, and offline mode has other issues linked <a class="text-cyan-600" href="articels/cracked">here</a></li>
        </ul>
      </div>

    </div>
  <div class="w-1/12"></div>
  </div>
  