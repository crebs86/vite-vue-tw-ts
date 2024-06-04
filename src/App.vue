<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <nav class="navbar navbar-expand-lg bg-slate-200 dark:bg-gray-800 text-gray-700 dark:text-gray-100">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Navbar</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown"
        aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <li class="nav-item hover:bg-slate-300 dark:hover:bg-slate-700">
            <RouterLink to="/" class="nav-link hover:text-slate-50 dark:text-gray-100">Home</RouterLink>
          </li>
          <li class="nav-item hover:bg-slate-300 dark:hover:bg-slate-700">
            <RouterLink to="/modal" class="nav-link hover:text-slate-50 dark:text-gray-100">Modal</RouterLink>
          </li>
          <li class="nav-item hover:bg-slate-300 dark:hover:bg-slate-700">
            <RouterLink to="/badge" class="nav-link hover:text-slate-50 dark:text-gray-100">Badge</RouterLink>
          </li>
          <li class="nav-item hover:bg-slate-300 dark:hover:bg-slate-700">
            <a class="nav-link hover:text-slate-50 dark:text-gray-100" href="#">Pricing</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle hover:text-slate-50 dark:text-gray-100" href="#" role="button"
              data-bs-toggle="dropdown" aria-expanded="false">
              Columns
            </a>
            <ul class="dropdown-menu bg-slate-200 dark:bg-gray-800">
              <li>
                <RouterLink to="/bs-column"
                  class="dropdown-item hover:bg-slate-300 dark:hover:bg-slate-700 text-gray-700 dark:text-gray-50 dark:hover:text-gray-50">
                  BS
                  Column
                </RouterLink>
              </li>
            </ul>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <RouterView />
</template>
