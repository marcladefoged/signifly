<template>
<div class="filter">
    <h3>FILTER</h3>
    <div class="filtering">
        <h4 
            v-for="filter in filters" 
            :key="filter"
            @click="() => filterCases(filter)"
        >
            {{ filter }}
        </h4>


        <!-- <h4>All work</h4>
        <h4>Branding</h4>
        <h4>E-commerce</h4>
        <h4>Digital Experience</h4>
        <h4>Campaigns and films</h4> -->
    </div>
    <p class="vision">
        We combine creativity and technology to deliver work that is fit for the future and deeply rooted in strategy.
    </p>
    </div>
    
</template>

<script>

const filters = [
    'All work',
    'Branding',
    'E-commerce',
    'Digital Experience',
    'Campaigns and films'
]

export default {
    props: [
    'filterCases'
    ],
    data () {
        return {
            filters
        }
    }
}



</script>

<style scoped>

h3 {
    margin-left: 10vw;
    margin-top: 5vw;
    font-size: 0.8rem;
}

.filter {
    display: flex;
    
}

.filtering {
    margin-left: 10vw;
    margin-top: 8vh;
    font-size: 0.8rem;
}

.vision {
    color: #647689;
    position: relative;
    margin-top: 10vh;
   margin-left: auto;
   width: 25vw;
   height: 2vh;
   margin-right: 10vw;
}

@media all and (max-width: 576px) {
    
    .filtering {
    margin-left: -12vw;
    }

    .vision {
        width: 30vw;
    }
}



</style>