<template >
    <div class="container-fluid header">
        <div class="row  align-items-center">
            <div class="col-sm-6 text-left">
                <i> Back  </i> 
                <span>CogBooks | Dashboard</span>
            </div>
            <div class="col-sm-6 topbarRight">
                <span>InstructorName </span>
                <i>menu</i>
            </div>
        </div>
        <div class="row align-items-center">Select the list of classes</div>
        <div class="row align-items-end">
            <div class="col reports">
                <span class="pd-3">Engagement</span>
                <span>Progress</span>
                <span>Performance</span>
            </div>
        </div> 
    </div>
</template>
<script>
export default {
    name: Headers,  
}
</script>
<style scoped>
.header{
    background-color: white;
}
.row{
    border-bottom: 1px solid #eee;
    height: 61px
}
.topbarRight{
    text-align-last: right;
}
.reports span{
    padding-right: 48px;
}

    
</style>