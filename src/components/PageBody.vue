<template>
    <div>
        <h1>I am the Page BODY!</h1>
        <section id="page_content">
        <side-panel></side-panel>
        <meet-the-dev></meet-the-dev>
        <meet-the-staff></meet-the-staff>
        </section>
    </div>
</template>

<script>

import SidePanel from './SidePanel.vue';
import MeetTheDev from './MeetTheDev.vue';
import MeetTheStaff from './MeetTheStaff.vue';


    export default {
        name: 'page-body',
        components: {
            SidePanel,
            MeetTheDev,
            MeetTheStaff
        }
    }
</script>

<style scoped>
    
    div {
        display: grid;
        position: relative;
        width: 100%;
        background-color: red;
    }

    #page_content {
        display: grid;
        grid-auto-flow: column;
        column-gap: 50px;
        margin-top: 50px;
    }


</style>