<template>
  <div class="container">
    <div class="header">
      <div style="padding-top: 20px;color: white;">
        <p style="margin: 20px 0 30px 130px; font-size: 60px">Oswaldo Cruz Foundation (Fiocruz)</p>
      </div>
    </div>

    <div class="content">
        <div class="metric">
            View
            <a-select default-value="all" style="width: 180px; font-size: 14px; margin-left: 10px" @change="metricsChange">
                <a-select-option value="all">
                    All Members
                </a-select-option>
                <a-select-option value="sci">
                    Senior Scientist
                </a-select-option>
                <a-select-option value="pro">
                    Professor
                </a-select-option>
            </a-select>
        </div>

        <div class="model-ranking">
            <table>
                <thead>
                    <tr>
                        <th>Name</th>
                        <th>title</th>
                        <th>institute</th>
                        <th>position</th>
                        <th>contact</th>
                    </tr>
                </thead>
                <tbody>
                    <tr v-for="item in rankingData" :key="item.name">
                        <td width="10%">{{item.name}}</td>
                        <td width="10%">{{item.title}}</td>
                        <td width="40%">{{item.institute}}</td>
                        <td width="10%">{{item.position}}</td>
                        <td width="20%">{{item.contact}}</td>
                    </tr>
                </tbody>
            </table>
        </div>
        <br>
        <br>
    </div>
  </div>
</template>

<script>
    const all = [
        {
            name: 'Daniel Villela',
            title: 'Senior Scientist',
            institute: 'Oswaldo Cruz Foundation (Fiocruz)',
            position: 'Lab Adminstrator',
            contact: 'daniel.villela@fiocruz.br'            
        },
        {
            name: 'Oswaldo Cruz',
            title: 'Senior Scientist',
            institute: 'Oswaldo Cruz Foundation (Fiocruz)',
            position: 'None',
            contact: 'oswaldo.cruz@fiocruz.br'            
        },
        {
            name: 'Leonardo Bastos',
            title: 'Senior Scientist',
            institute: 'Oswaldo Cruz Foundation (Fiocruz)',
            position: 'None',
            contact: 'leonardo.bastos@fiocruz.br'            
        },
        {
            name: 'Carlos Morel',
            title: 'Senior Scientist',
            institute: 'Oswaldo Cruz Foundation (Fiocruz)',
            position: 'None',
            contact: 'carlos.morel@fiocruz.br'            
        },
        {
            name: 'Thiago Souza',
            title: 'Senior Scientist',
            institute: 'Oswaldo Cruz Foundation (Fiocruz)',
            position: 'None',
            contact: 'thiago.moreno@fiocruz.br'            
        },
        {
            name: 'Claudio Struchiner',
            title: 'Professor',
            institute: 'Getulio Vargas Foundation',
            position: 'None',
            contact: 'claustru@gmail.com'            
        },
    ]
    const sci = [
        {
            name: 'Daniel Villela',
            title: 'Senior Scientist',
            institute: 'Oswaldo Cruz Foundation (Fiocruz)',
            position: 'Lab Adminstrator',
            contact: 'daniel.villela@fiocruz.br'            
        },
        {
            name: 'Oswaldo Cruz',
            title: 'Senior Scientist',
            institute: 'Oswaldo Cruz Foundation (Fiocruz)',
            position: 'None',
            contact: 'oswaldo.cruz@fiocruz.br'            
        },
        {
            name: 'Leonardo Bastos',
            title: 'Senior Scientist',
            institute: 'Oswaldo Cruz Foundation (Fiocruz)',
            position: 'None',
            contact: 'leonardo.bastos@fiocruz.br'            
        },
        {
            name: 'Carlos Morel',
            title: 'Senior Scientist',
            institute: 'Oswaldo Cruz Foundation (Fiocruz)',
            position: 'None',
            contact: 'carlos.morel@fiocruz.br'            
        },
        {
            name: 'Thiago Souza',
            title: 'Senior Scientist',
            institute: 'Oswaldo Cruz Foundation (Fiocruz)',
            position: 'None',
            contact: 'thiago.moreno@fiocruz.br'            
        },
    ]
    const pro = [
        {
            name: 'Claudio Struchiner',
            title: 'Professor',
            institute: 'Getulio Vargas Foundation',
            position: 'None',
            contact: 'claustru@gmail.com'            
        },
    ]
    

    export default {
        data() {
            return {
                rankingData: [],
                metrics: "all"
            };
        },
        components: {
        },
        mounted() {
            this.rankingData = all;
            this.metricsChange("all");
        },
        methods: {
            metricsChange(value) {
                if (value == 'all'){
                    this.rankingData = all;
                } else if (value == "sci") {
                    this.rankingData = sci;
                } else if (value == "pro") {
                    this.rankingData = pro;
                } else if (value == "stu") {
                     this.rankingData = stu;
                }
            },
        },
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
  min-height: 200px;
  background:  rgb(27, 140, 233) linear-gradient(to right,  rgb(27, 140, 233), rgb(11, 247, 188));
  /* border: blue solid 1px; */
}
.content {
    width: 80%;
    height: auto;
    margin: 50px auto 0 auto;
    /* border: blue solid 3px; */
}

.metric {
    font-size: 16px;
    font-family: 'Microsoft YaHei', Arial, Helvetica, sans-serif;
    margin-bottom: 16px;
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
.paper {
    color: black;
}
.paper:hover {
    color:rgb(27, 140, 233);
}
</style>