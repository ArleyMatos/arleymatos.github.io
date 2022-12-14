---
layout: page
title: 
cover-img: /assets/img/Trackieeers/Background_Trackieeers_verde.png
---

   O projeto Trackieeer consiste na construção de um Tracker, Seguidor Solar, utilizando um circuito de arduino, capaz de aumentar a capacidade de captação de energia solar dos módulos fotovoltaicos. Além da criação de um aplicativo mobile para tratamento de dados e análise da produção de energia.

   Inclui-se no projeto: Modelagem 3D no software SolidWorks, cálculos de ganhos de geração de energia, criação do protótipo do Tracker e do software.
   
   
## Desenvolvimento
   Inicialmento analisamos as possibilidades de modelos de Solar Tracker (Seguidor Solar) de eixo único (movimentando-se em uma direção) através de pesquisas. Posteriormente, elaboramos um modelo original da PES CIMATEC no softwatre de modelagem 3D (SOLIDWORKS e ONSHAPE), levando em consideração os cenários climáticos e de design que proporciona um melhor desempenho. A partir disso, projeto foi dividido em 4 entregáveis: 
   
   * Modelagem 3D; 
   * Circuito eletrônico;
   * Aplicativo mobile (React-native);
   * Banco de dados (FIREBASE). 

### Lista de materiais 

* Filamento ABS para impressão 3D
* Sensor de corrente e tensão
* Módulo WiFi ESP8266 ESP-01
* Arduino Uno R3 + Cabo USB
* Protoboard 400 Pontos
* Jumpers - Macho/Fêmea - 20 Unidades de 20cm
* Resistor 220R 1/4W (10 Unidades)
* Fotoresistor LDR (2 unidades)
* Micro Servo 9g SG90 TowerPro


### Esquemático do projeto

<p style="text-align: center;"> <img src="/assets/img/smart_energy/Equemático_Smart.png" alt="Esquema"/> </p>

---

### Modelagem 3D                   

O softwares utilizados para cosntrução das peças e montagem foi o [**SOLIDWORKS**](https://www.solidworks.com/pt-br) e o [**ONSHAPE**](https://onshape.com/en/). A partir deles, possibilitou-se a confecção das peças do projeto e sua montagem posterior, podendo serem vistas logo abaixo:

##### Caixa Organizadora   
 
<style type="text/css">
  .sketchfab-embed-wrapper iframe{
   float: left;
  } 
  </style>
   
   <div class="sketchfab-embed-wrapper"> 
      
   <iframe title="Caixa" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share width="300" height="220" margin="15" src="https://sketchfab.com/models/69b3af6570604f478b9484e68334d02f/embed?autospin=1&autostart=1&ui_theme=dark"> </iframe>
   
   <p align="justify" style="text-align: justify" margin-left="2" > Esta caixa foi projetada para acolher os componente eletrônicos, visando uma maior organização e segurança do circuito. Dentro dela tem: Sensor de corrente e tensão; Módulo WiFi ESP8266 ESP-01; Arduino Uno R3 + Cabo USB; Protoboard 400 Pontos; Jumpers; Resistor 220R 1/4W ; Micro Servo 9g SG90 TowerPro. </p>
   
  </div>  
  

---
 
##### Suporte triangular 


   <div
   class="sketchfab-embed-wrapper"> <iframe title="Suporte Triangular" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share width="300" height="220" margin="15"  src="https://sketchfab.com/models/ef47ce964eb04a20bb9606e5213fcfc8/embed?autospin=1&autostart=1&preload=1&ui_theme=dark"> </iframe> 
   <p  align="justify" style="text-align: center" margin-left="2"> Elaborado para apoiar a suspensão do eixo, evitando danos de cisaliamento mecânico na estrutura. </p>
   <br>
   <br>
  </div>

<br>

---

##### Suporte do Painel

 <div class="sketchfab-embed-wrapper"> <iframe title="SuportePainel" frameborder="0" allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" allow="autoplay; fullscreen; xr-spatial-tracking" xr-spatial-tracking execution-while-out-of-viewport execution-while-not-rendered web-share width="300" height="220"  margin-left="5" src="https://sketchfab.com/models/64863a20b9b544eeadbf5f3486f78764/embed?autospin=1&autostart=1&preload=1&ui_theme=dark"> </iframe> 
   
   <p  align="justify" style="text-align: center" margin-left="2"> Estrura principal onde estão os sensores LDR e a placa solar. </p>
   
</div>

<br>

<br>

<br>

---
   
### Etapa atual do projeto
   
   A etapa atual do projeto consiste na integração do arduno com o banco de dados FIREBASE, para que possamos acessar os dados de coleta do aplicativo mobile através do FIREBASE. Com a conclusão desta etapa, iremos finalizar com a impressão definitiva das peças para montagem.

<br>

---
   
### Equipe de Desenvolvimento

<div class="row">
  <div class=" col-xl-auto offset-xl-0 col-lg-4 offset-lg-0">
    <div class="mobile-side-scroller">
      <table class="table-borderless highlight">
          <tr>
            <th><center><img src="{{ 'assets/img/voluntarios/arley_matos.png' | relative_url }}" width="100" alt="Arley" class="img-fluid rounded-circle" /></center></th>
            <th></th>
            <th><center><img src="{{ 'assets/img/voluntarios/felipe_leao.jpg' | relative_url }}" width="100" alt="Felipe" class="img-fluid rounded-circle"/></center></th>
            <th></th>
            <th><center><img src="{{ 'assets/img/voluntarios/joao_gabriel.jpeg' | relative_url }}" width="100" alt="João Gabriel" class="img-fluid rounded-circle"/></center></th>
            <th></th>
          <tr class="font-weight-bolder" style="text-align: center margin-top: 0">
            <td width="25%"><center>Arley Matos</center></td>
            <td></td>
            <td width="25%"><center>Felipe Leão</center></td>
            <td></td>
            <td width="25%"><center>João Gabriel</center></td>
            <td></td>
          <tr style="text-align: center" >
            <td style="vertical-align: top"><small><center>Voluntário desde 2021 <p/> Líder do projeto</center></small></td>
            <td></td>
            <td style="vertical-align: top"><small><center>Voluntário desde 2021</center></small></td>
            <td></td>
            <td style="vertical-align: top"><small><center>Voluntário desde 2021</center></small></td>
            <td></td>



