<template>
    <div class="event">
        <HeaderNav/>
        <Header/>
        <!--Oppsett av Grid for Konsert med EventCard.vue-->
        <ul role="list" class="grid grid-cols-1 gap-6 sm:grid-cols-2 md:grid-cols-2 lg:grid-cols-3 mx-12">
        <EventCard/>
        </ul>
        testing

    </div>
</template>

<script>
import EventCard from '../components/EventCard.vue'
import HeaderNav from '../components/HeaderNav.vue'
import Header from '../components/Header.vue'


export default{
    components: {
        EventCard,
        HeaderNav,
        Header,
        }
}

</script>

<style>

</style>