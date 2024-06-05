<script setup lang="ts">
import Menu from '@/components/Menu.vue';
</script>
<template>
    <!-- Navbar Setup -->
    <nav class="navbar navbar-expand-lg bg-slate-200 dark:bg-slate-800 text-slate-700 dark:text-slate-100">
        <div class="container-fluid">
            <!-- Navbar brand -->
            <a class="navbar-brand" href="#">
                CrebsDEV
            </a>
            <!-- Navbar toggle button -->
            <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#sidebar"
                aria-controls="sidebar">
                <span class="navbar-toggler-icon"></span>
            </button>
            <!-- Top menu in navbar -->
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <Menu />
            </div>
        </div>
    </nav>

    <!-- Sidebar Setup -->
    <div class="offcanvas offcanvas-start" tabindex="-1" id="sidebar">
        <div class="offcanvas-header">
            <h5 class="offcanvas-title text-success">
                Menu
            </h5>
            <button type="button" class="btn-close text-reset" data-bs-dismiss="offcanvas" aria-label="Close">
            </button>
        </div>
        <div class="offcanvas-body bg-slate-800">
            <Menu />
        </div>
    </div>

    <!-- Content Below Navbar and Sidebar Menu -->
    <div class="container-fluid">
        <div class="row">
            <!-- First column for content -->
            <div class="col-lg-11 mx-auto justify-text">
                <h2>Lorem Ipsum</h2>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus sit amet urna tempus, sodales ex
                    et, rutrum dolor. Curabitur ac suscipit lectus. Vestibulum id ornare mauris. In semper pretium sem,
                    sit amet sagittis velit sagittis nec. Nulla eget facilisis nibh, dictum facilisis ex. Curabitur
                    lacus nisi, malesuada non pulvinar a, lacinia eu nulla. Curabitur imperdiet purus et molestie
                    interdum. Phasellus felis lorem, elementum eget pulvinar et, maximus tempus metus. Praesent
                    imperdiet dapibus purus, in mattis sapien posuere vel. Curabitur enim risus, sollicitudin eget porta
                    at, aliquam sed mi.
                </p>
                <p>
                    Morbi consectetur nulla laoreet ante feugiat, vitae finibus arcu blandit. Curabitur posuere, ipsum
                    nec laoreet efficitur, ipsum urna volutpat mi, et semper odio est eget diam. Vestibulum tempus
                    libero a dui pretium, quis lacinia metus euismod. Fusce vitae libero pharetra, sollicitudin dui vel,
                    placerat est. Nullam gravida justo ut orci viverra lobortis. Morbi porta venenatis accumsan. Quisque
                    mollis feugiat enim et porta. Suspendisse sed imperdiet felis. Fusce enim leo, efficitur sit amet
                    molestie ac, auctor sed lacus. Suspendisse potenti. Mauris ac felis felis. Aliquam erat volutpat.
                </p>
            </div>

        </div>
    </div>

</template>