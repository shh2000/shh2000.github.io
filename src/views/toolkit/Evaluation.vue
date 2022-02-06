<template>
    <div class="container">
        <div class="header">
            <div style="padding-top: 20px;color: white;">
                <p style="margin: 20px 0 30px 130px; font-size: 60px">Chinese Team Achievements</p>
                <p style="margin: 0px 0 20px 130px; font-size: 30px">
                    We provide an open-sourced EpiModeling toolkit and<br> 
                    a visualization platform of our weekly prediction and evalution of COVID-19 worldwide.
                </p>
            </div>
        </div>

        <div class="content">
            <div>
                <p class="title">Open-sourced EpiModeling Toolkit</p>
                <a-divider style="margin: 10px 0; background-image: linear-gradient(to right,  rgb(103, 179, 241),  rgb(103, 179, 241), #f6f6f6, #f6f6f6);"></a-divider>
                <p>After the emergence of new coronary pneumonia, many researchers have devoted themselves to the field of infectious disease modeling. Among them, researchers can summarize and classify existing methods to form a review, or use existing technologies to solve new specific problems; they can also design new infectious disease models for specific scientific problems, and use multi-source big data to treat research objects Characterize. After developing a new model, researchers also need to use real data to fit model parameters, run the model to obtain experimental results, and compare with published results</p>
                <p>By reading and summarizing many papers in Nature, Science, PNAS, AAAI, TKDE, KDD, and summarizing the research on the traditional warehouse model in the paper, this study summarizes five main ways to improve the classic warehouse model. , which are horizontal compartment subdivision, vertical compartment subdivision, adding dynamic equations/transfer pathways, parameter dynamization, and improvements based on different propagation architectures. Among them, the first three schemes correspond to the warehouse expansion function, and the latter two correspond to the external data definition and import functions. While investigating and researching, this study fulfills these requirements and tries to establish a unified big data infectious disease modeling framework</p>
                <div class="toolkitbig">
                    <div style="width: 80%; margin: 10px auto 20px auto; text-align: center">
                    <img
                        src="../../assets/img/tree.png"
                        alt="toolkit"
                        height="600"
                    />
                    </div>
                </div>
                <br>
                <a href="https://github.com/Bigscity-epidemic/Epidemic-Modeling-survey">This is the Github Repo of the open-sourced EpiModeling toolkit</a>                
            </div>
        </div>
        <div class="content">
            <div>
                <p class="title">Epidemic Prediction Platform Integrating Big Data</p>
                <a-divider style="margin: 10px 0; background-image: linear-gradient(to right,  rgb(103, 179, 241),  rgb(103, 179, 241), #f6f6f6, #f6f6f6);"></a-divider>
                <p>We use BD-SUEIR epidemic model to predict and simulate COVID-19 worldwide. This is the prediction platform:</p>
                <div class="toolkitbig">
                    <div style="width: 80%; margin: 10px auto 20px auto; text-align: center">
                    <img
                        src="../../assets/img/pre.png"
                        alt="toolkit"
                        height="600"
                    />
                    </div>
                </div>
                <br>
                <p>This is the simulation platform:</p>
                <div class="toolkitbig">
                    <div style="width: 80%; margin: 10px auto 20px auto; text-align: center">
                    <img
                        src="../../assets/img/sim.png"
                        alt="toolkit"
                        height="600"
                    />
                    </div>
                </div>
                <br>
                <a href="http://covid19-report.com/">This is the Github Repo of the open-sourced EpiModeling toolkit</a>   
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data() {
            return {
            };
        },
        components: {
        }
    };
</script>

<style scoped>
.toolkitbig {
  height: 660px;
  background-color: white;
  padding-top: 20px;
  padding-bottom: 20px;
}
.container {
  margin: auto;
  width: 100%;
  height: auto;
  /* border: red solid 1px; */
}
.header {
  width: 100%;
  min-height: 300px;
  background:  rgb(27, 140, 233) linear-gradient(to right,  rgb(27, 140, 233), rgb(11, 247, 188));
  /* border: blue solid 1px; */
}
.content {
    width: 80%;
    height: auto;
    margin: 50px auto 0 auto;
    font-size: 20px;
    line-height: 36px;
    color: black;
    font-family: 'Open Sans', 'Microsoft YaHei', Arial, Helvetica, sans-serif;
    /* border: blue solid 3px; */
}
.title {
    font-size: 32px;
    font-weight: 700;
    font-family: 'Open Sans', 'Microsoft YaHei', Arial, Helvetica, sans-serif;
    margin-bottom: 0;
}
table {
    color: rgba(0, 0, 0, 0.65);
    font-size: 14px;
    font-variant: tabular-nums;
    line-height: 1.5;
    list-style: none;
    font-feature-settings: 'tnum';
    display: table;
    width: 100%;
    text-align: center;
    border-collapse: collapse;
    border-spacing: 0;
    border: 0.1px solid #1890ff;
}
thead {
    display: table-header-group;
    vertical-align: middle;
    border-color: inherit;
}
tbody {
    display: table-row-group;
    vertical-align: middle;
    border-color: inherit;
}
th {
    display: table-cell;
    vertical-align: inherit;
    overflow-wrap: break-word;
    padding: 16px 16px;
    background: #97b9f7;
    border: 0.1px solid #1890ff;
    color: white;
    font-weight: 700;
    font-family: Nunito, 'Microsoft YaHei', Arial, Helvetica, sans-serif;
}
td {
    display: table-cell;
    vertical-align: inherit;
    padding: 16px 16px;
    overflow-wrap: break-word;
    background: white;
    color: black;
    border: 0.1px solid #1890ff;
    font-size: 15px;
    font-family: Nunito, 'Microsoft YaHei', Arial, Helvetica, sans-serif;
}
</style>