<p align="center">
  <h1 align="center">Projeto Base de Testes de Performance com K6</h1>
</p> 

<p align="center">
  <a href="#-produto">Produto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-stack">Stack</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-objetivo">Objetivo</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-estrutura">Estrutura</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-execução">Execução</a>
</p> 

<p align="center">
  <img alt="License" src="https://camo.githubusercontent.com/540c8be779fe5bb1d1733d3b4e082c353fc464cf3704fe0eaf105659d973bb22/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f7374796c653d666f722d7468652d6261646765266d6573736167653d6b3626636f6c6f723d374436344646266c6f676f3d6b36266c6f676f436f6c6f723d464646464646266c6162656c3d">
  <img alt="License" src="https://camo.githubusercontent.com/b266791f8bd47724a510885e147661a76f4c76677f8ed67768bbbbda1825e0b8/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f7374796c653d666f722d7468652d6261646765266d6573736167653d47726166616e6126636f6c6f723d463436383030266c6f676f3d47726166616e61266c6f676f436f6c6f723d464646464646266c6162656c3d">
  <img alt="License" src="https://camo.githubusercontent.com/81eb6065c195ff479bd67efc20d51cdb256ea25dbe2a454f45269c8f7275a6af/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f7374796c653d666f722d7468652d6261646765266d6573736167653d496e666c7578444226636f6c6f723d323241444636266c6f676f3d496e666c75784442266c6f676f436f6c6f723d464646464646266c6162656c3d">
  <img alt="License" src="https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white">
  <img alt="License" src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E">
  <img alt="License" src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white">
  <img alt="License" src="https://img.shields.io/badge/json-5E5C5C?style=for-the-badge&logo=json&logoColor=white">
</p>

<p align = "center">
<b> :earth_americas: Solution XXX  | :crossed_swords: Squad XXX </b>
</p>

## :racehorse: Produto
<p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum
</p>

## ⚙ Stack

Esse projeto foi desenvolvido com as seguintes tecnologias:

|                                          |        Tecnologias                          |                                          |
| :-------------------:                    | :-------------------:                       |:---------------:                         |
| [Docker](https://www.docker.com/)        | [K6](https://k6.io/)                        | [InfluxDB](https://www.influxdata.com/)  |
| [Docker Compose](https://www.docker.com/)| [Grafana](https://grafana.com/)             |                                          |        

## 🎯 Objetivo
Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum

## 🌌 Estrutura
Para organização do sistema o mesmo foi separado em diversas pastas para que ficassem distribuidas de acordo com suas funções.
  - ### **base-apm-k6-qa**
    - ***Dashboards***
        - Contém os arquivos JSON com a estrutura para geração dos Dashboards no Grafana
        
    - ***Scripts*** 
        - Contém os arquivos js com os scripts de testes de performance 

    - ***docker-compose.yml*** 
        - Este é o arquivo que contém toda a estrutura necessária para rodar os testes. Duas redes e três serviços são definidos, sendo eles: InfluxDB, Grafana e K6

    - ***grafana-dashboard.yaml*** 
      - Configuração do Grafana para carregar o dashboard do K6 a partir da pasta /var/lib/grafana/dashboards que está dentro do container. Por padrão o Grafana não tem nenhum dashboard.
      
    - ***grafana-datasource.yaml*** 
      - Configuração do Grafana para utilizar como fonte de dados o InfluxDB.

    - ***Dockerfile*** 
      - Dockerfile é o arquivo de configuração que é usado para construir uma imagem Docker. Ele contém uma série de instruções que são executadas sequencialmente pelo Docker para criar uma imagem.
           
## ⏩ Execução
Acesse a documentação no nosso Confluence e siga o Passo a Passo: https://docktech.atlassian.net/l/cp/KrwmhePB
