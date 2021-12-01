<template>
    <div>
        <h1>I am the Page BODY!</h1>
        <side-panel></side-panel>
        <meet-the-dev></meet-the-dev>
        <meet-the-staff></meet-the-staff>
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

</style>