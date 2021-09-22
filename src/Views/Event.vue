<template>
    <div class="event">
        <!--Oppsett av Grid for Konsert med EventCard.vue-->
        <ul role="list" class="grid grid-cols-1 gap-6 sm:grid-cols-2 md:grid-cols-2 lg:grid-cols-3 mx-12">
        <EventCard/>
        </ul>
        testing

    </div>
</template>

<script>
import EventCard from '@/components/EventCard.vue'
</script>

<style>

</style>