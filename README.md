# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Nome do projeto - Implementando Algoritmos de Machine Learning com Scikit-Learn

![Designer.jpeg](https://github.com/IolandaManzali/MaquinaAgricola_fase4/blob/main/assets/assetsfase4/CAP1FASE4.png)



## Nome do grupo - Grupo 15

## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/guilherme-dos-santos-barbosa-58397b176">Guilherme dos Santos Barbosa</a>
- <a href="https://www.linkedin.com/in/iolanda-helena-fabbrini-manzali-de-oliveira-14ab8ab0">Iolanda Helena Fabbrini Manzali de Oliveira</a>
- <a href="https://www.linkedin.com/company/inova-fusca">Murilo Carone Nasser</a> 
- <a href="https://www.linkedin.com/in/pedro-eduardo-soares-de-sousa-439552309">Pedro Eduardo Soares de Sousa</a> 
- <a href="https://www.linkedin.com/company/inova-fusca">Yago Brendon Iama</a>

## 👩‍🏫 Professores:
### Tutor(a) 
- <a href="https://www.linkedin.com/in/lucas-gomes-moreira-15a8452a">Lucas Gomes Moreira</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/company/inova-fusca">Andre Godoi Chaviato</a>

## 📜 Descrição
Modelo Wokwi versão 1.2

<p align="justify">
 
Este projeto implementa um sistema de irrigação automatizado utilizando um microcontrolador ESP32, um sensor de umidade DHT22, um sensor de luminosidade (LDR) para simular níveis de nutrientes e um display LCD para monitoramento. O sistema controla uma bomba d'água através de um relé, ligando-a quando a umidade do solo estiver abaixo de 40% e desligando-a quando a umidade ultrapassar 80%. 
Na versao atualizada, o projeto conta com um banco de dados mais robusto do que o anterior e, alem de exibir os dados coletados em tempo real no display, apresenta interface grafica amigável para facilitar o monitoramento e compreensão dos dados analisados.


 Funcionalidades:
 
 * Monitoramento da umidade do solo: Utiliza um sensor DHT22 para medir a umidade do solo.
 * Simulação de níveis de nutrientes: Utiliza um LDR para simular a leitura de níveis de nutrientes no solo pH
 * Controle automático da irrigação: Liga e desliga a bomba d'água automaticamente com base na umidade do solo.
 * Interface de usuário: Exibe informações relevantes em um display LCD 20x4, incluindo umidade, níveis de nutrientes simulados, status da irrigação e temperatura.
 * Comunicação serial: Envia dados do sistema para o monitor serial para depuração e monitoramento.
 * Serial plotter : Exibe as informaçoes do sensor LRD (pH) do solo

Atualizações no codigo c++:

 * inclusao do codigo para utilização do LCD

   ![Designer.jpeg](https://github.com/IolandaManzali/MaquinaAgricola_fase4/blob/main/assets/assetsfase4/iniciaLCD.png)
   
 * troca de float por byte para leitura de umidade, com o objetivo de economizar memoria

   ![Designer.jpeg](https://github.com/IolandaManzali/MaquinaAgricola_fase4/blob/main/assets/assetsfase4/usodebyte.png)

 * codificação para parametrizar a visualização dos dados na tela LCD 

![Designer.jpeg](https://github.com/IolandaManzali/MaquinaAgricola_fase4/blob/main/assets/assetsfase4/mostrandoLCD.png)


Integração do Serial Plotter:

A leitura grafica do serial plotter mostra a relação entre a amplitude da curva e a intensidade luminosa: quanto maior a intensidade da luz menor é a amplitude da curva.

![Designer.jpeg](https://github.com/IolandaManzali/MaquinaAgricola_fase4/blob/main/assets/assetsfase4/sp4.png)


</p>

## 📁 Estrutura de pastas

Dentre os arquivos e pastas presentes na raiz do projeto, definem-se:

- - <b>assets</b>: imagens utilizadas no projeto

- <b>config</b>: arquivos de parâmetros e ajustes do projeto.

- <b>document</b>: documentos complementares do projeto

- <b>scripts</b>: scripts auxiliares

- <b>src</b>: código fonte principal

- <b>README.md</b>: FIAP FASE4. 

## 🔧 Como executar o código
 falta 






## 🗃 Histórico de lançamentos

* 0.5.0 - XX/XX/2024
    * 
* 0.4.0 - XX/XX/2024
    * 
* 0.3.0 - XX/XX/2024
    * 
* 0.2.0 - 06/12/2024
    * 
* 0.1.0 - 13/11/2024
    *
  
## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
