<script>
  import BrandLogo from "./NavBarComponents/BrandLogo.svelte";
  import SectionsNav from "./NavBarComponents/Sections/SectionsNav.svelte";
  import DropdownSections from "./NavBarComponents/Sections/DropdownSections.svelte";
</script>

<div class="navbar bg-base-100">

  <DropdownSections />

  <BrandLogo />

  <SectionsNav />


  <div class="flex-none">
    <div class="dropdown dropdown-end">
      <label for="" tabindex="0" class="btn btn-ghost btn-circle" role="button">
        <div class="indicator">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 3h2l.4 2M7 13h10l4-8H5.4M7 13L5.4 5M7 13l-2.293 2.293c-.63.63-.184 1.707.707 1.707H17m0 0a2 2 0 100 4 2 2 0 000-4zm-8 2a2 2 0 11-4 0 2 2 0 014 0z" /></svg>
          <span class="badge badge-sm indicator-item">8</span>
        </div>
      </label>
      <div tabindex="0" class="mt-3 card card-compact dropdown-content w-52 bg-base-100 shadow" role="button">
        <div class="card-body">
          <span class="font-bold text-lg">8 Items</span>
          <span class="text-info">Subtotal: $999</span>
          <div class="card-actions">
            <button class="btn btn-primary btn-block">View cart</button>
          </div>
        </div>
      </div>
    </div>
    <div class="dropdown dropdown-end">
      <label for="" tabindex="0" class="btn btn-ghost btn-circle avatar" role="button">
        <div class="w-10 rounded-full">
          <img src="https://daisyui.com/images/stock/photo-1534528741775-53994a69daeb.jpg" alt="avatar" />
        </div>
      </label>
      <ul tabindex="0" class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52" role="menu">
        <li>
          <a href="/profile" class="justify-between">
            Profile 
            <span class="badge">New</span>
          </a>
        </li>
        <li><a href="/logout">Logout</a></li>
      </ul>
    </div>
  </div>
</div>

<style>


  
</style>