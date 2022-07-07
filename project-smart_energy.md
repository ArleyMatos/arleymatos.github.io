---
layout: page
#title: Smart Energy
cover-img: /assets/img/smart_energy/back-ground_Smart_Energy.png
---

# Smart Energy

## Apresentação

O projeto Smart Energy consiste no desenvolvimento de um sistema de automação residencial focado na eficiência energética e conforto. Serão utilizadas lâmpadas inteligentes com funções de otimizar, captar, registrar e armazenar o consumo energético, além da regulação de suas propriedades luminosas a fim de proporcionar o bem-estar dos usuários baseando-se no ciclo circadiano. Ademais, também irá contar com a automatização de um ventilador por meio de sensores com parâmetros de temperatura e umidade do ar, a fim de promover, simultaneamente, o conforto térmico e a eficiência energética no ambiente residencial.

## Desenvolvimento

Após analisar as possibilidades de integração do arduino com a lâmpada, serão utilizados 2 sensores e 1 módulo wifi. O primeiro sensor, Fotoresistor LDR, é responsável por captar a luz emitida pelo ambiente e de acordo com a luminosidade, enviar informações ao Arduino de quanto está sendo incidido sobre o componente, ou seja, possibilitando a customização da dimerização do LED. Já o segundo sensor, Movimento Presença PIR, tem como finalidade analisar o ambiente em que está alocado e emitir uma resposta ao detectar qualquer movimento, no caso desse projeto a resposta seria ligar, ao detectar algum deslocamento, ou desligar as luzes, caso não fosse registrado nenhum movimento após certo período de tempo. Por fim, o módulo wifi ESP8266 tem como objetivo integrar a lâmpada com o Google Assistente (assistente virtual) para que seja possível a criação de comandos de voz para manipulação da lâmpada.
Além disso, a conexão entre Arduino e Lâmpada será por meio do Módulo Relé que possibilita controlar circuitos externos de grandes correntes a partir de pequenas correntes ou tensões.

### Lista de materiais 

* Sensor Fotoresistor LDR de 5mm
* Sensor de Movimento Presença PIR HC-SR501
* Módulo WiFi ESP8266 ESP-01
* Arduino Uno R3 + Cabo USB
* Protoboard 400 Pontos
* Jumpers - Macho/Fêmea - 20 Unidades de 20cm
* Resistor 10K 1/4W (10 Unidades)
* Resistor 220R 1/4W (10 Unidades)
* Módulo Relé 5V 2 Canais


### Esquemático do projeto

<p style="text-align: center;"> <img src="/assets/img/smart_energy/Smart_Energy-Esquematico.jpg" alt="Esquema" height="394" width="634"/> </p>

Então, o projeto é dividido em 2 etapas: automação da lâmpada LED e coleta de dados sobre o consumo energético para fins de análise.

### Próximos passos

Agora em diante, serão feitas pesquisas sobre circuitos elétricos, banco de dados e Power BI. Em relação a banco de dados e PowerBI, o intuito é gerar um relatório com o consumo energético da lâmpada para analisar os dados. Já o estudo sobre circuitos elétricos será utilizado para entender e aplicar os conceitos no esquemático eletrônico do projeto.
Com a chegada dos materiais para montagem do projeto, serão realizadas as primeiras experimentações. Será preciso configurar os sensores e o módulo de acordo com os parâmetros que já foram estabelecidos. Também será necessário integrar o arduino com um banco de dados para tabelar o quanto de energia está sendo consumido pela lâmpada e tabular esses dados para o relatório do PowerBI.
Por fim, após a conclusão de testes e a obtenção de resultados satisfatórios, o projeto estará preparado para melhorar o conforto e o custo energético dos usuários.


### Equipe de Desenvolvimento
<div class="row">
  <div class=" col-xl-auto offset-xl-0 col-lg-4 offset-lg-0">
    <div class="mobile-side-scroller">
      <table class="table-borderless highlight">
        <thead>
          <tr>
            <th><center><img src="{{ 'assets/img/voluntarios/daniel_araujo.jpeg' | relative_url }}" width="100" alt="daniel" class="img-fluid rounded-circle" /></center></th>
            <th></th>
            <th><center><img src="{{ 'assets/img/voluntarios/matheus_sa.png' | relative_url }}" width="100" alt="matheus" class="img-fluid rounded-circle"/></center></th>
          </tr>
        </thead>
        <tbody>
          <tr class="font-weight-bolder" style="text-align: center margin-top: 0">
            <td width="25%"><center>Daniel Araujo</center></td>
            <td></td>
            <td width="25%"><center>Matheus Sá</center></td>
          </tr>
          <tr style="text-align: center" >
            <td style="vertical-align: top"><small><center>Voluntário desde 2020 <p/> Líder do projeto</center></small></td>
            <td></td>
            <td style="vertical-align: top"><small><center>Voluntário desde 2021</center></small></td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</div>
