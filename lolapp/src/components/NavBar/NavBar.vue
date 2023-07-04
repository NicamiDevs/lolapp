<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-dark" style="height: 3rem;">
        <div class="collapse navbar-collapse d-flex justify-content-start" style="width: 500px;">
            <div class="d-flex" style="width: 250px;">
                <div class="navbar-brand text-light">NicamiLoL</div>
                <RouterLink to="/" class="navbar-brand text-light">Home</RouterLink>
                <RouterLink to="/about" class="navbar-brand text-light">About Us</RouterLink>
            </div>
        </div>
        <form class="form-inline d-flex mr-5" v-if="$route.path === '/'">
            <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
        </form>
    </nav>
</template>