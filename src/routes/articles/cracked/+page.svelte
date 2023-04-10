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
    <p>Cracked, or officially known as online-mode in minecraft server.properties is a setting that allows players to join a server without being checked against the Mojang authentication servers. This can also be used to allow cracked players to join the game.<br><br> </p>
    <p class="font-bold text-xl">There is no premium minecraft. This would imply the existence of a free version, which Mojang does not offer. ALWAYS buy the game and do not use illegal, pirated launchers such as TLauncher.<br><br></p>
    <p class="text-center text-3xl">Risks of using cracked</p>
    <p>Cracked is deeply insecure and allows for many exploits. It's important to note all of these before deciding to open your server to these risks without the necessary measures. <i><b>Again, we advise against turning cracked on for your server.<b><i><br><br></p>
    <p class="text-center text-2xl">Username exploiting</p>
    <p>When using cracked, accounts are not authenticated by Mojang's servers. This essentially means that acccount data is solely tied to usernames. This allows for people to log in with any username, thus receiving all the data tied to that username. Bought accounts can also be affected by this. <i> This can be prevented by installing authentication plugins like LoginSecurity. <i><br><br></p>
    <p class="text-center text-2xl">Bot Raids</p>
    <p> Not to be confused with DDoS-attacks, bot raids are a serious issue on cracked servers lately. A bot raid causes many bots to join your server, possibly overloading it and filling up storage with unnecessary playerdata. You cannot prevent this in cracked servers, just disable cracked and buy the game.<br><br></p>
    <p class="text-center text-2xl font-extrabold">But i have no money!111!1!!</p>
    <p>Get a job, or ask your parents to buy you minecraft as a birthday or christmas gift. This is not an excuse to pirate Minecraft, or any game for that matter. While pirating won’t get you arrested, it remains illegal.</p>
  </div>
<div class="w-1/12"></div>
</div>
