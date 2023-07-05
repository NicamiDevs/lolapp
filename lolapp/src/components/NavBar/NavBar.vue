<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-dark" style="height: 3rem;">
        <div class="collapse navbar-collapse d-flex justify-content-start" style="width: 500px;">
            <div class="d-flex" style="width: 250px;">
                <div class="navbar-brand text-light px-5">NicamiLoL</div>
                <RouterLink to="/" class="navbar-brand text-light">Home</RouterLink>
                <RouterLink to="/about" class="navbar-brand text-light">About Us</RouterLink>
            </div>
        </div>
        <form class="form-inline d-flex px-5" v-if="$route.path === '/'">
            <input class="form-control mr-sm-2" type="search" placeholder="LAS Players" aria-label="Search">
            <button class="btn btn-outline-primary my-2 my-sm-0" type="submit">Buscar</button>
        </form>
    </nav>
</template>