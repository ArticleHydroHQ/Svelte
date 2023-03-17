<!--if you use this you NEED THE INFO.JS WHERE EVER YOU NEED IT! CHECK FOR ERRORS!-->
<script>
  import { info } from './info.js';
  let currentPlace = info[0];
</script>

<nav class="flex items-center  bg-gray-800 text-white py-4 px-8">
  <ul class="flex">
    <li class="mr-6">
      <p class="text-xl">Article Hydro HQ</p>
    </li>
    <li class="mr-6">
      <a href="/" class="hover:bg-gray-700 px-3 py-2 rounded-md">home</a>
    </li>
    <li class="mr-6">
      <a href="../../aboutus" class="hover:bg-gray-700 px-3 py-2 rounded-md">about us</a>
    </li>
    <li class="mr-6">
      <a href="../../articels" class="hover:bg-gray-700 px-3 py-2 rounded-md">article </a>
    </li>

    <li class="mr-6 text-right border-l-indigo-100">you are looking at {currentPlace.name}</li>
    <li class="mr-6" >written by {currentPlace.writer}</li>

  </ul>
</nav>
