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
            <div class="code">
                <code data-lang="bash">
                    git clone https://github.com/LibCity/Bigscity-LibCity.git<br>
                    cd Bigscity-LibCity
                </code>
            </div>
            <br>

            <p class="title">Research Content and Cooperations</p>
            <a-divider style="margin: 10px 0; background-image: linear-gradient(to right,  rgb(103, 179, 241),  rgb(103, 179, 241), #f6f6f6, #f6f6f6);"></a-divider>
            <p>This project aims to develop a set of multi-level, multi-angle and multi-method simulation and prediction models for the new crown pneumonia epidemic through the multilateral scientific research cooperation of China, Russia and Brazil, using their respective advantageous fields. The research content of this project includes four parts: data collection, extraction of influencing factors, model establishment, and model application of the new crown pneumonia epidemic modeling, covering the entire process of the new crown epidemic model from data input to practical application.</p>
            <p>In Data Level:</p>
            <div class="code">
                <code data-lang="bash">
                    pip install torch==1.7.1 torchvision==0.8.2 torchaudio==0.7.2
                </code>
            </div>
            <p>In Factor Level:</p>
            <div class="code">
                <code data-lang="bash">
                    conda install pytorch==1.7.1 torchvision==0.8.2 torchaudio==0.7.2 cudatoolkit=10.2 -c pytorch
                </code>
            </div>
            <p>In Model Level:</p>
            <div class="code">
                <code data-lang="bash">
                    pip install -r requirements.txt
                </code>
            </div>
            <p>In Application Level:</p>
            <div class="code">
                <code data-lang="bash">
                    pip install -r requirements.txt
                </code>
            </div>
            <p>In addition, the teams from the three countries will also conduct research on the application of the model in the application scenarios of their own cities according to their unique epidemic development trends.</p>
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
</style>