<script lang="ts" setup>
import Navbar from '@/components/NavBar.vue'
</script>
<template>

    <Navbar />
    <div class="container text-center">
        <div class="row align-items-start my-2 dark:hover:bg-red-400">
            <div class="col bg-slate-600 hover:bg-red-300 hover:text-red-700 border border-success">
                One of three columns
            </div>
            <div class="col bg-slate-600 border border-success">
                One of three columns
            </div>
            <div class="col bg-slate-600 border border-success">
                One of three columns
            </div>
        </div>
        <div class="row align-items-center my-2">
            <div class="col bg-slate-600 border border-success">
                One of three columns
            </div>
            <div class="col bg-slate-600 border border-success">
                One of three columns
            </div>
            <div class="col bg-slate-600 border border-success">
                One of three columns
            </div>
        </div>
        <div class="row align-items-end my-2">
            <div class="col bg-slate-600 border border-success">
                One of three columns
            </div>
            <div class="col bg-slate-600 border border-success">
                One of three columns
            </div>
            <div class="col bg-slate-600 border border-success">
                One of three columns
            </div>
        </div>
    </div>
</template>