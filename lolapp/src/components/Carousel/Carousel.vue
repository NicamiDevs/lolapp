<template>
    <div id="my-carousel" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="https://cdnportal.mobalytics.gg/production/2018/08/Stats-tab-splash.png" class="d-block w-100" style="height: 300px;" alt="Slide 1">
                <div class="carousel-caption d-none d-md-block">
                    <h5 class="text-shadow">Bienvenido a NicamiLoL</h5>
                    <p>¡Podrás observar Estadísticas de jugadores de cualquier parte del Mundo!</p>
                </div>
            </div>
            <div class="carousel-item">
                <img src="https://esports.eldesmarque.com/wp-content/uploads/2018/10/New-runes-preseason.jpg" class="d-block w-100" style="height: 300px;" alt="Slide 2">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Runas</h5>
                    <p>Podrás mantenerte actualizado para la construcción de las Runas según el campeón que elijas</p>
                </div>
            </div>      
            <div class="carousel-item">
                <img src="https://mobalytics.gg/wp-content/uploads/2018/08/Combat-tab.jpg" class="d-block w-100" style="height: 300px;" alt="Slide 3">
                <div class="carousel-caption d-none d-md-block">
                    <h5>Estadísticas</h5>
                    <p>Tus estadísticas y resultados de juego son importantes a la hora de subir de rango en League of Legends</p>
                </div>
            </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#my-carousel" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#my-carousel" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
        </button>
    </div>
</template>

<style>
h5{
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}
</style>