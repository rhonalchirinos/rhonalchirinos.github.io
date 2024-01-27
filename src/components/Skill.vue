
<script setup>
import { ref } from 'vue';

const elements = ref(
    [
        "/skills/angular.png",
        "/skills/aws.png",
        "/skills/botstrap.png",
        "/skills/composer.png",
        "/skills/django.png",
        "/skills/docker.png",
        "/skills/ExpressJS.png",
        "/skills/gcloud.png",
        "/skills/git.png",
        "/skills/git.png.png",
        "/skills/ionic.png",
        "/skills/java.png",
        "/skills/js.png",
        "/skills/laravel.png",
        "/skills/linux.png",
        "/skills/memcache.png",
        "/skills/mongo.jpeg",
        "/skills/mysql.png",
        "/skills/nest.png",
        "/skills/node.jpg",
        "/skills/node.png",
        "/skills/php.png",
        "/skills/postgres.png",
        "/skills/presta.png",
        "/skills/python.png",
        "/skills/react.png",
        "/skills/redis.png",
        "/skills/rxjs.png",
        "/skills/sass.jpg",
        "/skills/socketio.png",
        "/skills/terminal.png",
        "/skills/ubuntu.png",
        "/skills/vita.png",
        "/skills/vuejs.png",
        "/skills/webpack.png",
    ].sort((a, b) => 0.5 - Math.random())
)
</script>

<template>
    <div class="px-4 sm:px-12">
        <h2 class="my-4 text-xl font-bold italic">COMPETENCIAS</h2>
        <div class="flex flex-wrap">
            <div v-for="element in elements" class="shadow-md m-4">
                <img :src="element" class="w-full h-32 p-5" />
            </div>
        </div>
    </div>
</template>