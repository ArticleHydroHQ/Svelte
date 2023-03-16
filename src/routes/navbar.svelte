<script>
    import { onMount } from 'svelte';
  import { get } from 'svelte/store';
  let name;

onMount(() => {
  name = get(info)?.name;
});
</script>
<nav class="flex items-center justify-between bg-gray-900 text-white py-4 px-8">
    <ul class="flex">
        <li class="mr-6">
            <p class="font-bold">Article Hydro HQ</p>
          </li>
      <li class="mr-6">
        <a href="/" class="hover:bg-gray-700 px-3 py-2 rounded-md">Home</a>
      </li>
      <li class="mr-6">
        <a href="/aboutus" class="hover:bg-gray-700 px-3 py-2 rounded-md">About us</a>
      </li>
      <li class="mr-6">
        <a href="/articels" class="hover:bg-gray-700 px-3 py-2 rounded-md">Article's</a>
      </li>

    </ul>
  </nav>
  