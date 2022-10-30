<script setup>
import { RouterLink } from "vue-router";
</script>

<template>
  <nav class="navbar navbar-expand-lg bg-light fixed-top">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <img
          src="@/assets/coderdojo-logo.png"
          alt="CoderDojo Helmond"
          class="coderdojo-logo"
        />
      </a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <router-link class="nav-link" exact-active-class="active" :to="'/'"
              >DOJO</router-link
            >
          </li>
          <li class="nav-item">
            <router-link
              class="nav-link"
              exact-active-class="active"
              :to="'stichting'"
              >STICHTING
            </router-link>
          </li>
          <li class="nav-item">
            <router-link
              class="nav-link"
              exact-active-class="active"
              :to="'vacatures'"
              >VACATURES
            </router-link>
          </li>
          <li class="nav-item">
            <router-link
              class="nav-link"
              exact-active-class="active"
              :to="'contact'"
              >CONTACT</router-link
            >
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style scoped>
.coderdojo-logo {
  max-height: 50px;
}
</style>
