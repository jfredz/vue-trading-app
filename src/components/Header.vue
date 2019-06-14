<template>
<div>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <router-link to="/" class="navbar-brand">Stock Trader</router-link>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <router-link class="nav-item" tag="li" to="/portfolio">
          <a class="nav-link">Portfolio</a>
        </router-link>
        <router-link class="nav-item" tag="li" to="/stocks">
          <a class="nav-link">Stocks</a>
        </router-link>
      </ul>
    </div>
  </nav>
</div>
</template>
