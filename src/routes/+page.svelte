<script>
    import Icon from "$lib/assets/logo.png"
  import Navbar from "./navbar.svelte";
 </script>
<div class="grid w-screen h-screen">
    <div class="grid grid-cols-2 gap-4">
            <div>
            <span class="text-zinc-50 text-xl ">
                <i class="fa-brands fa-github fa-xl "></i>
            </span>
        </div>
        <div class="text-right">
            <span class="text-zinc-50 text-xl">
                <a href="https://discord.gg/zUu492YQk3">
                    <i class="fa-brands fa-discord fa-xl ">Discord</i>
                </a>
        </div>
    </div>
    <div class="grid grid-cols-3 gap-4">
        <div>
            <!--empy-->
        </div>
        <div >
            <img class="place-content-center" src={Icon} alt="logo"/>
        </div>
        <div>
            <!--empy-->
        </div>
    </div>
    <div class="grid grid-cols-3 gap-4">
        <div>
        </div>
        <div>
            <h1 class="text-2xl text-center">
            Minecraft server info for you
            </h1>
        </div>
        <div></div>
    </div>
    <div class="grid grid-cols-5 gap-4 text-center">
        <div></div>
        <div>
            <a href='/articles'>
                <div class="bg-green-500 rounded-md border-2 hover:border-4 border-blue-900">
                    <button class="color-gold-100">Go to Article's</button>
                </div>
            </a>
        </div>
        <div></div>
        <div>
            
            <p>comming soon!</p>
        </div>
        <div></div>

    </div>
</div>
<Navbar></Navbar>