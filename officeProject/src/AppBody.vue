<template >
    <div class="contanier-fluid">
        <Header class="mb-3"/>
        <div class="row mb-3">
            <div class="col-lg-10 d-flex flex-column">
                <span>User engagement and activity</span>
                <span>
                    View the engagement and participation of learner <strong>Course Name</strong> course 
                    from 1 Jun 2022 - 30 Jun 2023
                </span>
            </div>
            <div class="col-lg-2">
                <h6>Download Report</h6>
            </div>
        </div>
        <div class="row mb-3">
            <Engagement />
        </div>
        <div class="row mb-3"></div>

        
    </div>
</template>
<script>
import Header from './components/header/Header.vue';
import Engagement from './pages/Engagement.vue';

export default {
    name: "AppBody",
    components:{
        Header,
        Engagement,
    }
    
}
</script>
<style lang="">
    
</style>