<template>
  <div>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark" data-navbar="fixed">
      <div class="container">

        <div class="navbar-left">
          <button class="navbar-toggler" type="button">&#9776;</button>
          <a class="navbar-brand" href="#">
            <img class="logo-dark" src="/img/logo_actiboost.png" alt="Actiboost">
            <img class="logo-light" src="/img/logo/slack.png" alt="logo">
          </a>
        </div>

        <section class="navbar-mobile">
          <nav class="nav nav-navbar ml-auto">
            <nuxt-link class="nav-link" to="/" >Home</nuxt-link>
            <!-- <a class="nav-link" href="#section-features">Features</a> -->
            <nuxt-link class="nav-link" to="/seller" >Seller</nuxt-link>
            <nuxt-link class="nav-link" to="/partner" >Partner</nuxt-link>
            <!-- <a class="nav-link" href="#section-faq">FAQ</a> -->
            <!-- <a class="nav-link" href="#footer">Contact</a> -->
            <a href="https://app.actiboost.com/login" class="nav-link">Login</a>
          </nav>
        </section>

      </div>
    </nav><!-- /.navbar -->
    <nuxt/>
  </div>
</template>

<style>

</style>
