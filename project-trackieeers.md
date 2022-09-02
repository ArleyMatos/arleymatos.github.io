---
layout: page
title: 
cover-img: /assets/img/Trackieeers/Background_Trackieeers_verde.png
---

O projeto Trackieeer consiste na construção de um Tracker, Seguidor Solar, utilizando um circuito de arduino, capaz de aumentar a capacidade de captação de energia solar dos módulos fotovoltaicos. Além da criação de um aplicativo mobile para tratamento de dados e análise da produção de energia.

O projeto inclui modelagem 3D no software SolidWorks, cálculos de ganhos de geração de energia e a criação do protótipo do Tracker e do software.

## Desenvolvimento

Após analisar as possibilidades de integração do arduino com a lâmpada, serão utilizados 2 sensores e 1 módulo wifi. O primeiro sensor, Fotoresistor LDR, é responsável por captar a luz emitida pelo ambiente e de acordo com a luminosidade, enviar informações ao Arduino de quanto está sendo incidido sobre o componente, ou seja, possibilitando a customização da dimerização do LED. Já o segundo sensor, Movimento Presença PIR, tem como finalidade analisar o ambiente em que está alocado e emitir uma resposta ao detectar qualquer movimento, no caso desse projeto a resposta seria ligar, ao detectar algum deslocamento, ou desligar as luzes, caso não fosse registrado nenhum movimento após certo período de tempo. Por fim, o módulo wifi ESP8266 tem como objetivo integrar a lâmpada com o Google Assistente (assistente virtual) para que seja possível a criação de comandos de voz para manipulação da lâmpada.
Além disso, a conexão entre Arduino e Lâmpada será por meio do Módulo Relé que possibilita controlar circuitos externos de grandes correntes a partir de pequenas correntes ou tensões.

### Lista de materiais 

* Filamento ABS para impressão 3D
* Sensor de corrente e tensão
* Módulo WiFi ESP8266 ESP-01
* Arduino Uno R3 + Cabo USB
* Protoboard 400 Pontos
* Jumpers - Macho/Fêmea - 20 Unidades de 20cm
* Resistor 220R 1/4W (10 Unidades)
* Micro Servo 9g SG90 TowerPro


### Esquemático do projeto

<p style="text-align: center;"> <img src="/assets/img/smart_energy/Equemático_Smart.png" alt="Esquema"/> </p>

Então, o projeto é dividido em 4 etapas: Modelagem 3D, Circuito de controle, Aplicativo mobile e Integração com banco de dados FIREBASE.

### Etapa atual do projeto

      

### Próximos passos
Agora em diante, serão feitas pesquisas sobre circuitos elétricos, banco de dados e Power BI. Em relação a banco de dados e PowerBI, o intuito é gerar um relatório com o consumo energético da lâmpada para analisar os dados. Já o estudo sobre circuitos elétricos será utilizado para entender e aplicar os conceitos no esquemático eletrônico do projeto.
Com a chegada dos materiais para montagem do projeto, serão realizadas as primeiras experimentações. Será preciso configurar os sensores e o módulo de acordo com os parâmetros que já foram estabelecidos. Também será necessário integrar o arduino com um banco de dados para tabelar o quanto de energia está sendo consumido pela lâmpada e tabular esses dados para o relatório do PowerBI.
Por fim, após a conclusão de testes e a obtenção de resultados satisfatórios, o projeto estará preparado para melhorar o conforto e o custo energético dos usuários.



<p style="text-align: center;">
<iframe src="https://cad.onshape.com/documents/0ed58b03ec28049336219488/w/7801c4c72c73d761150a870d/e/10694c8eac4e2a62478f9c23" width="100%" height="800" frameborder="0" marginheight="0" marginwidth="0">Carregando…</iframe>
</p>


### Equipe de Desenvolvimento
<div class="row">
  <div class=" col-xl-auto offset-xl-0 col-lg-4 offset-lg-0">
    <div class="mobile-side-scroller">
      <table class="table-borderless highlight">
        <thead>
          <tr>
            <th><center><img src="{{ 'assets/img/voluntarios/arley_matos.png' | relative_url }}" width="100" alt="Arley" class="img-fluid rounded-circle" /></center></th>
            <th></th>
            <th><center><img src="{{ 'assets/img/voluntarios/felipe_leao.jpg' | relative_url }}" width="100" alt="Felipe" class="img-fluid rounded-circle"/></center></th>
            <th></th>
            <th><center><img src="{{ 'assets/img/voluntarios/joao_gabriel.jpeg' | relative_url }}" width="100" alt="João Gabriel" class="img-fluid rounded-circle"/></center></th>
            <th></th>
        </thead>
        <tbody>
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
        </tbody>
      </table>
    </div>
  </div>
</div>


