<template>
  <div class="container">
    <div class="header">
      <div style="padding-top: 20px;color: white;">
        <p style="margin: 20px 0 30px 130px; font-size: 60px">BRICS EpiModeling Project</p>
        <p style="margin: 0px 0 20px 130px; font-size: 30px">
          <!-- LibCity can be installed with pip, with Conda or from source. -->
          This project research the datas, factors, models and applications of COVID-19 modeling. 
        </p>
      </div>
    </div>

    <div class="content">
        <div>
            <!-- <p class="title">System requirements</p>
            <a-divider style="margin: 10px 0; background-image: linear-gradient(to right,  rgb(103, 179, 241),  rgb(103, 179, 241), #f6f6f6, #f6f6f6);"></a-divider>
            <p>LibCity works with the following operating systems:</p>
            <ul>
                <li>Linux</li>
                <li>Windows 10</li>
                <li>macOS X</li>
            </ul>
            <p>LibCity requires torch version 1.7.0 or later. If you want to use LibCity with GPU, please ensure that please ensure that CUDA or CUDAToolkit version is 9.2 or later. This requires NVIDIA driver version >= 396.26 (for Linux) or >= 397.44 (for Windows10).</p>
            <br> -->

            <!-- <p class="title">Conda</p>
            <a-divider style="margin: 10px 0; background-image: linear-gradient(to right,  rgb(103, 179, 241),  rgb(103, 179, 241), #f6f6f6, #f6f6f6);"></a-divider>
            <p>If you use Conda, you can install LibCity with:</p>
            <div class="code">
                <code data-lang="bash">
                    # Best practice, create an environment rather than install in the base env<br>
                    conda create -n libcity<br>
                    # Activate the environment<br>
                    conda activate libcity<br>
                    # The actual install command<br>
                    conda install libcity
                </code>
            </div>
            <br>

            <p class="title">Pip</p>
            <a-divider style="margin: 10px 0; background-image: linear-gradient(to right,  rgb(103, 179, 241),  rgb(103, 179, 241), #f6f6f6, #f6f6f6);"></a-divider>
            <p>If you use pip, you can install LibCity with:</p>
            <div class="code">
                <code data-lang="bash">pip install libcity</code>
            </div>
            <br> -->
            
            <p class="title">Research Topics</p>
            <a-divider style="margin: 10px 0; background-image: linear-gradient(to right,  rgb(103, 179, 241),  rgb(103, 179, 241), #f6f6f6, #f6f6f6);"></a-divider>
            <!-- <p>Download the source files from GitHub:</p> -->
            <p>This project sets up three topics, which are undertaken by research teams in China, Russia and Brazil respectively. The subject setting is carried out in accordance with the principles of vertical division and horizontal cooperation, that is, each subject covers all levels from data collection to model application to ensure the integrity and independence of the research work of all parties, thereby controlling research risks; At the level, the research content of each team has different focuses, complementing each other's advantages and avoiding repeated research.</p>
            <table>
                <thead>
                <tr>
                    <th>Country</th>
                    <th>Topic</th>
                    <th>Tasks</th>
                    <th>Task Level</th>
                </tr>
                </thead>
                <tbody>
                <tr>
                    <td width="10%" rowspan="4">China</td>
                    <td width="30%" rowspan="4">Modeling of COVID-19 via integrating AI and epidemiological models</td>
                    <td width="10%">Data</td>
                    <td width="50%">Automatic collection and fusion processing of global data on COVID-19</td>
                </tr>
                <tr>
                    <td width="10%">Factor</td>
                    <td width="50%">Extraction of socioeconomic and viral gene sequences influencing factors based on machine learning methods</td>
                </tr>
                <tr>
                    <td width="10%">Model</td>
                    <td width="50%">Modelling of the COVID-19 epidemic with the fusion of artificial intelligence methods and epidemiology</td>
                </tr>
                <tr>
                    <td width="10%">Application</td>
                    <td width="50%">The application of epidemic policy formulation support and economic impact analysis under normalized prevention and control</td>
                </tr>

                <tr>
                    <td width="10%" rowspan="4">Russia</td>
                    <td width="30%" rowspan="4">Agent-based modeling of COVID-19 pandemic</td>
                    <td width="10%">Data</td>
                    <td width="50%">Collect and analyze regional epidemic data in Russia (Moscow and Chelyabinsk), China (Wuhan) and Brazil</td>
                </tr>
                <tr>
                    <td width="10%">Factor</td>
                    <td width="50%">Statistical methods for extracting and analyzing factors such as administrative measures, climate and environment</td>
                </tr>
                <tr>
                    <td width="10%">Model</td>
                    <td width="50%">Develop a more heterogeneous epidemic propagation model based on the existing Agent-based model</td>
                </tr>
                <tr>
                    <td width="10%">Application</td>
                    <td width="50%">Modelling and predictive simulation applications for epidemiological situations in Wuhan, Moscow, and selected Brazilian cities using an improved Agent-based model</td>
                </tr>

                <tr>
                    <td width="10%" rowspan="4">Brazil</td>
                    <td width="30%" rowspan="4">Mathematical models for understanding vulnerability in population groups and impact on health system demands and vaccination programs</td>
                    <td width="10%">Data</td>
                    <td width="50%">Individual case data collection for public health systems</td>
                </tr>
                <tr>
                    <td width="10%">Factor</td>
                    <td width="50%">Extract demographic factors such as indigenous community, age class, ethnic category, and medical intervention factors such as medical conditions, non-drug interventions, and vaccinations</td>
                </tr>
                <tr>
                    <td width="10%">Model</td>
                    <td width="50%">Studying Compartmental Models with Space-Time Stochastic Properties</td>
                </tr>
                <tr>
                    <td width="10%">Application</td>
                    <td width="50%">Application of hospital needs assessment, population vulnerability assessment, and vaccination program assessment for healthcare systems, and analysis of spatiotemporal dynamics of infected populations in Brazilian cities</td>
                </tr>
                </tbody>
            </table>
            <br>

            <p class="title">Research Content and Cooperations</p>
            <a-divider style="margin: 10px 0; background-image: linear-gradient(to right,  rgb(103, 179, 241),  rgb(103, 179, 241), #f6f6f6, #f6f6f6);"></a-divider>
            <p>This project aims to develop a set of multi-level, multi-angle and multi-method simulation and prediction models for the new crown pneumonia epidemic through the multilateral scientific research cooperation of China, Russia and Brazil, using their respective advantageous fields. The research content of this project includes four parts: data collection, extraction of influencing factors, model establishment, and model application of the new crown pneumonia epidemic modeling, covering the entire process of the new crown epidemic model from data input to practical application.</p>
            
            <table>
                <thead>
                <tr>
                    <th>Level</th>
                    <th>Overall Goals</th>
                    <th>Team</th>
                    <th>Tasks</th>
                </tr>
                </thead>
                <tbody>
                <tr>
                    <td width="10%" rowspan="3">Data</td>
                    <td width="30%" rowspan="3">This project will collect and establish a new crown pneumonia epidemic data set covering multiple elements from the three levels of global → region → case, and study the automatic collection and sorting method of epidemic data</td>
                    <td width="10%">China</td>
                    <td width="50%">Automated collection and organization of novel coronavirus gene sequencing data and global social and economic data</td>
                </tr>
                <tr>
                    <td width="10%">Russia</td>
                    <td width="50%">Collection of Regional Epidemic Data</td>
                </tr>
                <tr>
                    <td width="10%">Brazil</td>
                    <td width="50%">Collection of individual case-level data</td>
                </tr>  

                <tr>
                    <td width="10%" rowspan="3">Factor</td>
                    <td width="30%" rowspan="3">This project will extract and analyze the factors of epidemic transmission from the perspectives of new coronavirus gene sequencing, social economy, administrative measures, climate and environment, population composition, and intervention measures</td>
                    <td width="10%">China</td>
                    <td width="50%">Extraction and analysis of socioeconomic factors and gene sequence elements using machine learning methods</td>
                </tr>
                <tr>
                    <td width="10%">Russia</td>
                    <td width="50%">Extraction and analysis of administrative measures, climate and environment using statistical methods</td>
                </tr>
                <tr>
                    <td width="10%">Brazil</td>
                    <td width="50%">Extraction and analysis of factors for prevention and control interventions such as vaccines and non-drug interventions</td>
                </tr>   

                <tr>
                    <td width="10%" rowspan="3">Model</td>
                    <td width="30%" rowspan="3">This project will carry out modeling research on micro-individuals and groups, and use artificial intelligence methods to improve the modeling effect of epidemiological dynamics models, and develop new coronary pneumonia epidemic prediction and simulation models suitable for diverse application scenarios</td>
                    <td width="10%">China</td>
                    <td width="50%">Research on the fusion modeling method of artificial intelligence model and epidemic dynamic model</td>
                </tr>
                <tr>
                    <td width="10%">Russia</td>
                    <td width="50%">Research on the modeling of microscopic propagation process based on agent-based model</td>
                </tr>
                <tr>
                    <td width="10%">Brazil</td>
                    <td width="50%">Research on Modeling of Compartmental Model for Macro-group</td>
                </tr>   

                <tr>
                    <td width="10%" rowspan="3">Application</td>
                    <td width="30%" rowspan="3">This project will select several representative epidemic prevention and control scenarios to carry out model application research</td>
                    <td width="10%">China</td>
                    <td width="50%">Prediction and simulation of prevention and control measures in sudden epidemic rebound events, and the interaction between epidemic and economy under normalized prevention and control</td>
                </tr>
                <tr>
                    <td width="10%">Russia</td>
                    <td width="50%">Epidemic prediction and simulation research of some typical cities (Moscow, Wuhan) in the outbreak stage</td>
                </tr>
                <tr>
                    <td width="10%">Brazil</td>
                    <td width="50%">Epidemic control application of the model in hospitals, communities, vaccination groups, etc.</td>
                </tr>                
            </table>
            <br>
            <p>In addition, the teams of the three countries will also carry out the application research of the model in the application scenarios of their own cities according to the unique epidemic situation in their own countries</p>
            <br>
            <div class="toolkitbig">
                <div style="width: 80%; margin: 10px auto 20px auto; text-align: center">
                <img
                    src="../../assets/img/proj.png"
                    alt="toolkit"
                    height="600"
                />
                </div>
            </div>
            <br>
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
.container {
  margin: auto;
  width: 100%;
  height: auto;
  /* border: red solid 1px; */
}
.header {
  width: 100%;
  min-height: 250px;
  background:  rgb(27, 140, 233) linear-gradient(to right,  rgb(27, 140, 233), rgb(11, 247, 188));
  /* border: blue solid 1px; */
}
.content {
    width: 80%;
    height: auto;
    margin: 50px auto 0px auto;
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
.code {
    color: #f8f8f2;
    background-color: #272822;
    tab-size: 4;
    overflow: auto;
    width: 100%;
    padding: 10px 20px;
    margin: 0px 0px 16px 0px;
    text-align: left;
    border: 1px solid #e5e5e5;
    border-radius: 10px;
    line-height: 1.5;
}
table {
  color: rgba(0, 0, 0, 0.65);
  font-size: 14px;
  font-variant: tabular-nums;
  line-height: 1.5;
  list-style: none;
  font-feature-settings: "tnum";
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
  font-family: Nunito, "Microsoft YaHei", Arial, Helvetica, sans-serif;
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
  font-family: Nunito, "Microsoft YaHei", Arial, Helvetica, sans-serif;
}
.dataset {
  color: rgb(27, 140, 233);
}
/* .dataset:hover {
    color:rgb(27, 140, 233)
} */
.model {
  color: black;
}
.model:hover {
  color: rgb(27, 140, 233);
}
.paper {
  /* color: black; */
  color: rgb(27, 140, 233);
}
/* .paper:hover {
  color: rgb(27, 140, 233);
} */
.toolkitbig {
  height: 660px;
  background-color: white;
  padding-top: 20px;
  padding-bottom: 20px;
}
.news-header {
  min-width: 1000px;
  width: 80%;
  margin: auto;
}
</style>