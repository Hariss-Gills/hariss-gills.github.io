<script>
  import Navbar from "./Navbar.svelte";
</script>

<div class="drawer absolute inset-0">
  <input id="my-drawer" type="checkbox" class="drawer-toggle" />
  <div class="drawer-content">
    <!-- Page content here -->
    <Navbar drawerId={"my-drawer"} />
  </div>

  <div class="drawer-side">
    <label for="my-drawer" class="drawer-overlay"/>
    <ul class="menu p-4 overflow-y-auto w-80 bg-base-300 text-base-content">
      <!-- Sidebar content here -->
       <li><a>Sidebar Item 1</a></li>
      <li><a>Sidebar Item 2</a></li>
    </ul>
  </div>
</div>
