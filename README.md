# Bankprofile
Projeto de avaliação de clientes de um banco por algorítimos de ML não supervisionados.

## Autores

Utilize o link para o Linkedin para entrar em contato

Leandro Ferreira
[@LeandroFerreira](https://www.linkedin.com/in/leandrogomesf/)

## Descrição do projeto

Com esta aplicação é possível realizar um upload dos dados no formato previamente configurado para a produção de uma análise RFV. 

- R - Recência: tempo decorrido desde a última compra.

- F - Frequência: a quantidade de vezes no decorrer do periodo avaliado em que um produto foi adiquirido.

- V - Valor: somatório do valor de todos os produtos adquirido no decorrer do periodo avaliado.

## Utilização

Com os dados alinhados, é possível determinar ações internas para captação, manutenção, recaptação e valorização de clientes.

É possível identificar o perfil de um cliente com base nos 3 indicadores acima expostos. Consequentemente avaliar esforços que podem ou não serem empenhados.

### Dependencias

* A bibliotecas e suas respectivas versões usadas nesta aplicação estão listadas no arquivo requirements.txt. São elas:

pandas==2.2.0
XlsxWriter==3.1.9
streamlit==1.30.0
numpy==1.26.3

* A aplicação requer o uso de um browser/navegador compatível com Streamlit.

### Instalação

* É necessário acessar a página da aplicação pelo link: 

### Executando o projeto

* Entre na página pelo link acima.

* Na barra lateral, realizar o upload do arquivo em extensão .csv e aguardar os resultados.

## Ajuda

* Existe um formato específico previamente acordado entre as partes sobre a estrutura do arquivo .csv. Caso um arquivo com uma outra estrutura seja enviado, é possível que ele não seja lido pela engine e não retorne os resultados como esperado. 

* Para evitar o incômodo, verifique a extensão e estrutura do arquivo submetidos.

## Histórico de versões.

* 0.2
	* Ajustes de diversos bugs e otimização
* 0.1
    * Primeira versão

 ## Licença de uso

Esta aplicação não possui licença de uso.
