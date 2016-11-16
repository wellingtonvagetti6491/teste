# Nota de Liberação

[![N|Solid](http://boredzo.org/blog/wp-content/uploads/2008/02/network-128.png)](http://)



## Informações adicionais na Wiki



### Nomes

* Guilherme Beneti, RA: 448850

* João Paulo Oliveira, RA: 402796

* Maycon Henrique Ferreira Martins, RA: 537640

* Paulo Sergio Bonfim Cristanello, RA: 527998

* Wellington dos Santos Vagetti, RA: 541567




### INTRODUÇÃO

Este documento provê uma visão geral da versão do aplicativo Filterlog que está sendo liberado. Aqui descreveremos as funcionalidades do aplicativo, bem como seus 

problemas e limitações conhecidos. Por último são descritas as demandas e os problemas que foram resolvidos para liberação da versão atual.\
Para empresas de telecomunicações cujo é identificar problemas de autenticação SIP, comunicação do ATA (adaptador telefônico analógico) entre o nosso servidor de 
Telefonia. \
O FilterLog é um Syslog que identifica problemas de tempo de autenticação SIP, o qual cada equipamento deve enviar uma requisição de autorização de registro na plataforma, neste caso, existem tempos padrões de comunicação entre 6 minutos ou 2 minutos, neste caso, se os padrões de tempo de envio de requisição e resposta forem menores ou maiores que o tempo padrão, devemos notificar o cliente através de um evento informando o horário que houve o problema, Diferentemente da ferramenta 
atualmente usada pela empresa, o qual foi implantada para monitoramento em tempo real e filtrar informações armazenadas em banco de dados, a nossa aplicação irá fornecer informações de problemas de quedas ou falhas na rede, caso houver problemas em um
determinado cliente, o nosso produto em tempo real irá mostrar informações para tomada de decisão do setor nível 2 de suporte.

#### LINK DE ACESSO A APLICAÇÃO ONLINE


[Filter Log](http://)


**1. NOTA DE RELEASE A SER PUBLICADO**


* Função de gestão de usuários;

* Análise monitoramento de log;

* Mostrar clientes em monitoramento;

* Filtro de informações;
* Dashboard de informações de clientes em monitoramento; 



**2. PROBLEMAS CONHECIDOS E LIMITAÇÕES**


* Não envia e-mail de notificação;

* Não envia SMS de notificação;



**3.	DATAS IMPORTANTES** \

**Segue abaixo as datas importante do desenvolvimento:**


| Data           | Evento                  

| -------------- | -------------------------------------------------------------

| **07/10/2016** | Levantamento do escopo do projeto 

| **08/10/2016** | Inicio da interface WEB inicial do projeto  

| **10/10/2016** | Criação e manipulação do armazenamento das informações no BD 

| **18/10/2016** | Criado interface para Login de Usuário  

| **19/10/2016** | Feito teste do Login de Usuário  

| **19/10/2016** | Inicio do Algoritmo  

| **20/10/2016** | Levantamento de indicadores 

| **27/10/2016** | Reunião, agregado mais um membro na equipe  

| **31/10/2016** | Mudanças no Layout do projeto  



**4. COMPATIBILIDADE** \

**Segue abaixo os requisitos:**



| Requisitos | Ferramenta  |

|-----------|----------------------------------------|

| Navegadores | Mozilla Firefox, Chrome, e Microsoft Edge|

| Sistema operacional | Linux e Windows | 
| Dispositivos Móveis | IOS e Android | 


| 

**Tecnologias** 	 |   				|
|---------------------- |-----------------------------|
|Linguagem de programação| PHP e JavaScript|

|Tecnologia WEB	         | HTML 5 e CSS                 |
|IDE                     | PHPStorm e Sublime Text      |

|Servidor Web            | LIFE                         |

| Banco de Dados         | Mysql                        |
| Outras tecnologias     | Travis-CI, Heroku, New Relic, PostgreSql e JQuery |



**5. PROCEDIMENTO E ALTERAÇAO DE CONFIGURAÇÃO DO AMBIENTE** \

O Projeto foi feito com base em PHP e JavaScript, pelo conhecimento dos membros do grupo. Parte visual foi usado HTML e CSS3, pela sua fácil adesão e modificação. 

Hospedagem feita no Servidor da LIFE.

