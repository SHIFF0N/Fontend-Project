<template>
<div class="navmain-section"> 
  <b-navbar toggleable="lg" type="dark" variant="dark">
    <div class="container">
    <b-navbar-brand class="ml-auto" href="#">Twitch</b-navbar-brand>
    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
  
    <b-collapse id="nav-collapse" is-nav >
      <b-navbar-nav>
        <b-nav-item href="#">Discover</b-nav-item>
        <b-nav-item href="#">Following</b-nav-item>
        <b-nav-item href="#">Browse</b-nav-item>
        <b-nav-item href="#">Try Prime</b-nav-item>
        
       
      </b-navbar-nav>
      <b-navbar-nav class="ml-auto">
        <b-nav-form>
      <b-form-input class="mr-sm-2" placeholder="Search"></b-form-input>
      <b-button variant="outline-success" class="my-2 my-sm-0" type="submit">Search</b-button>
    </b-nav-form>


        <b-nav-item-dropdown text="Status" right>
          <b-dropdown-item href="#">Admin</b-dropdown-item>
          <b-dropdown-item href="#">Student</b-dropdown-item>
          <b-dropdown-item href="#">Teacher</b-dropdown-item>
        </b-nav-item-dropdown>

        <b-nav-item-dropdown right>
          <template slot="button-content"><em>User</em></template>
          <b-dropdown-item href="#">Profile</b-dropdown-item>
          <b-dropdown-item href="#">Sign Out</b-dropdown-item>
        </b-nav-item-dropdown>
      </b-navbar-nav>
    </b-collapse>
    </div>
  </b-navbar>
</div>
</template>




