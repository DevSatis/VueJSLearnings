<template >
    <div class="container reportsContanier">
        <div class="row h-100 align-items-center">
            <div class="col-md-4 d-flex ">
                <div class="d-flex align-items-center justify-content-center m-2">
                    <img :src="EngageImg" class="reportLogo" />
                </div>
                <div class="d-flex flex-column justify-content-center reportsNames">
                    <span class="reportTitle">Engagement Dashboard</span>
                    <span class="reportBrief">View the engagement and participation of learners.</span>
                </div>  
            </div>
            <div class="col-md-4 d-flex">
                <div class="d-flex align-items-center justify-content-center m-2">
                    <img :src="ProgressImg" class="reportLogo" />
                </div>
                <div class="d-flex flex-column justify-content-center reportsNames" >
                    <span class="reportTitle">Engagement Dashboard</span>
                    <span class="reportBrief">View the engagement and participation of learners.</span>
                </div> 
            </div>
            <div class="col-md-4 d-flex">
                <div class="d-flex align-items-center justify-content-center m-2">
                    <img :src="PerformanceImg" class="reportLogo" />
                </div >
                <div class="d-flex flex-column justify-content-center reportsNames">
                    <span class="reportTitle">Engagement Dashboard</span>
                    <span class="reportBrief">View the engagement and participation of learners.</span>
                </div>  
            </div>
        </div> 
    </div>
</template>
<script>
import EngageImg from '../../assets/EngageImg.png';
import ProgressImg from '../../assets/ProgressImg.png';
import PerformanceImg from '../../assets/PerforImg.png';
export default {
    name: "DonutChart",
    data() {
    return {
      EngageImg: EngageImg,
      ProgressImg: ProgressImg,
      PerformanceImg: PerformanceImg,
    };
  },
    
}
</script>
<style scoped>
.reportsContanier{
    background: #FAFAFA 0% 0% no-repeat padding-box;
    border: 1px solid #E0E0E0;
    border-radius: 2px;
    height: 106px !important;
    width: 887px !important;
}

.reportTitle{
    font: normal normal 600 16px/16px Open Sans ;
    letter-spacing: 0px;
    color: #0076BD;
    cursor: pointer;
    margin-bottom: 5px;
}
.reportBrief{
    font: normal normal normal 12px/12px Open Sans ;
}
.reportLogo{
    cursor: pointer;
}

    
</style>