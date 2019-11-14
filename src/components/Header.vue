<template>
    <div>
        <b-nav tabs>
            <b-nav-item disabled><b>Random Science Questions Quiz App</b></b-nav-item>
            <b-nav-item disabled>Directions: See how many you can get right out of 10 questions.</b-nav-item>
            <b-nav-item disabled><b>Counter: {{ numCorrect }}/{{ numTotal }}</b></b-nav-item>
            
        </b-nav>
    </div>
</template>

<script>
export default {
    props: [
        'numCorrect',
        'numTotal'
    ]
}
</script>