<template>
  <div class="container">
    <div class="header">
      <div style="padding-top: 20px;color: white;">
        <p style="margin: 20px 0 30px 130px; font-size: 60px">Team</p>
        <p style="margin: 0px 0 20px 130px; font-size: 30px">
          Our team has professors and students from top insitutes in <br>
          China, Russia and Brazil. 
        </p>
      </div>
    </div>

    <div class="content">
      <div class="task-ranking">
        <p class="task-name">Institites and Team Members</p>
        <a-divider style="margin: 10px 0; background-image: linear-gradient(to right,  rgb(103, 179, 241),  rgb(103, 179, 241), #f6f6f6, #f6f6f6);"></a-divider>
        <rank-table :rankdata="speed"></rank-table>
        <br>
        <br>

        <!-- <p class="task-name">Trajectory Next-Location Prediction</p>
        <a-divider style="margin: 10px 0; background-image: linear-gradient(to right,  rgb(103, 179, 241),  rgb(103, 179, 241), #f6f6f6, #f6f6f6);"></a-divider>
        <rank-table :rankdata="location"></rank-table>
        <br>
        <br> -->
      </div>
    </div>
  </div>
</template>

<script>
import rankTable from "./ranking/rankingTable"

const speed = [
  {
    dataset: 'China',
    best: 'Chinese Center for Disease Control and Prevention',
    paper: 'The core department of China\'s disease prevention and control and public health technology management and services.',
    datasetlink: 'https://www.chinacdc.cn/',
    mlink: '#',
    plink: 'https://www.chinacdc.cn/',
    dlink: 'METR-LA'
  },
  {
    dataset: 'China',
    best: 'Beihang University',
    paper: 'The epidemic prediction support team of the Joint Prevention and Control Mechanism of the State Council has accumulated rich experience in modeling the COVID-19 epidemic based on big data and artificial intelligence.',
    datasetlink: 'https://buaa.edu.cn/',
    mlink: '#',
    plink: 'https://buaa.edu.cn/',
    dlink: 'PEMS-BAY'
  },
  {
    dataset: 'Russia',
    best: 'National Medical Research Center of Phthisiopulmonology and Infectious Diseases',
    paper: 'The core department of Russia\'s respiratory and infectious disease research, the Russian new coronary pneumonia vaccine research and development unit.',
    datasetlink: 'https://cyberleninka.ru/',
    mlink: '#',
    plink: 'https://cyberleninka.ru/',
    dlink: 'PEMSD4'
  },
  {
    dataset: 'Russia',
    best: 'Zababakhin Russian Research Institute for Technical Physics',
    paper: 'Russia\'s highest-level research institution in technical physics and applied physics has accumulated a lot in the micro-mathematical modeling of the new crown epidemic.',
    datasetlink: 'http://vniitf.ru/',
    mlink: '#',
    plink: 'http://vniitf.ru/',
    dlink: 'PEMSD8'
  },
  {
    dataset: 'Brazil',
    best: 'Oswaldo Cruz Foundation (Fiocruz)',
    paper: 'Brazil\'s national public health agency, the research and development department of Brazil\'s national infectious disease early warning system, and the consulting department for the formulation of new crown epidemic prevention and control policies.',
    datasetlink: 'https://portal.fiocruz.br/en',
    mlink: '#',
    plink: 'https://portal.fiocruz.br/en',
    dlink: 'T-Drive20150206'
  },
  
]

const location = [
  {
    dataset: 'foursqaure-tky',
    best: 'DeepMove',
    paper: '[WWW2018]DeepMove: Predicting Human Mobility with Attentional Recurrent Networks',
    datasetlink: 'https://bigscity-libcity-docs.readthedocs.io/en/latest/user_guide/data/raw_data.html#foursquare',
    mlink: '#',
    plink: 'https://dl.acm.org/doi/10.1145/3178876.3186058',
    dlink: 'foursqaure-tky'
  },
  {
    dataset: 'Gowalla',
    best: 'DeepMove',
    paper: '[WWW2018]DeepMove: Predicting Human Mobility with Attentional Recurrent Networks',
    datasetlink: 'https://bigscity-libcity-docs.readthedocs.io/en/latest/user_guide/data/raw_data.html#gowalla',
    mlink: '#',
    plink: 'https://dl.acm.org/doi/10.1145/3178876.3186058',
    dlink: 'Gowalla'
  },
]

export default {
  data() {
    return {
      speed,
      location
    };
  },
  components: {
    rankTable
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
  min-height: 300px;
  background: rgb(27, 140, 233)
    linear-gradient(to right, rgb(27, 140, 233), rgb(11, 247, 188));
  /* border: blue solid 1px; */
}
.content {
  width: 80%;
  height: auto;
  margin: 50px auto 0 auto;
  /* border: blue solid 3px; */
}
.task-name {
  font-size: 32px;
  font-weight: 700;
  font-family: "Open Sans", "Microsoft YaHei", Arial, Helvetica, sans-serif;
  margin-bottom: 0;
}
</style>