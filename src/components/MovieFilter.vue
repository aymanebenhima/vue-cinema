<template>
    <div id="movie-filter">
        <h2>Filter results</h2>
        <h3>By time of day</h3>
        <div class="filter-group">
            <check-filter v-for="(time, id) in times" :key="id" category="time" :title="time"></check-filter>
        </div>
        <h3>By genre</h3>
        <div class="filter-group">
            <check-filter v-for="(genre, id) in genres" :key="id" category="genre" :title="genre"></check-filter>
        </div>
    </div>
</template>
<script>
    import genres from '../util/genres';
    import times from '../util/times';
    import CheckFilter from './CheckFilter.vue';
    
    export default {
        data() {
            return {
                genres,
                times
            };
        },
        components: {
            CheckFilter
        }
    }
</script>