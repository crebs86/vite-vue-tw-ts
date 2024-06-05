<script setup lang="ts">
import { RouterLink } from 'vue-router'
</script>
<template>
    <ul class="navbar-nav">
        <li class="nav-item hover:bg-slate-300 dark:hover:bg-slate-700 rounded-2">
            <RouterLink to="/" class="nav-link hover:text-slate-50 dark:text-gray-100">Home</RouterLink>
        </li>
        <li class="nav-item hover:bg-slate-300 dark:hover:bg-slate-700 rounded-2">
            <RouterLink to="/modal" class="nav-link hover:text-slate-50 dark:text-gray-100">Modal
            </RouterLink>
        </li>
        <li class="nav-item hover:bg-slate-300 dark:hover:bg-slate-700 rounded-2">
            <RouterLink to="/badge" class="nav-link hover:text-slate-50 dark:text-gray-100">Badge
            </RouterLink>
        </li>
        <li class="nav-item hover:bg-slate-300 dark:hover:bg-slate-700 rounded-2">
            <RouterLink to="/sidebar" class="nav-link hover:text-slate-50 dark:text-gray-100">Sidebar
            </RouterLink>
        </li>
        <li class="nav-item dropdown hover:bg-slate-300 dark:hover:bg-slate-700 rounded-2">
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
</template>