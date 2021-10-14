<template>
  <div>
    <b-navbar type="dark" variant="dark">
      <b-navbar-nav>
        <b-nav-item to="/">Home</b-nav-item>

        <!-- Navbar dropdowns -->
        <b-nav-item to="About">About me</b-nav-item>
        <b-nav-item to="CV">CV</b-nav-item>
        <b-nav-item to="Blog">Blog</b-nav-item>

        <b-nav-item-dropdown text="Drop down" right>
          <b-dropdown-item to="#">Account</b-dropdown-item>
          <b-dropdown-item to="#">Settings</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>
    </b-navbar>
  </div>
</template>


