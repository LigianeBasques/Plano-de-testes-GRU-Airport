# 💡Plano-de-testes-GRU-Airport💡 #
O plano de testes para o projeto GRU Airport detalha: os objetivos, o escopo, a abordagem e os recursos necessários para validar as funcionalidades do sistema, garantindo que a experiência dos usuários seja funcional e acessível
___
<p><b>Código da Demanda</b>: 001<p/>
<p><b>Nome do Projeto</b>: GRU Airport Site<p/>
<p><b>Autor(a) da Documentação</b>: Ligiane Basques<p/>
<p><b>Contato</b>: ligianealzie25@gmail.com<p/>
<p><b>Data Início</b>: 09/10/2024 <b>Data Fim</b>: 07/11/2024 <p/>
  
___

### Histórico de Versões ###

| Data | Nr Versão | Autor(a) | Descrição |
|----------|----------|----------|----------|
| 09/10/2024  | 1.0  | Ligiane Basques| Versão inicial do documento |
|  |   |  |  |
|  |  |  |  |

### 1-Visão Geral do Projeto ### 
O projeto visa o desenvolvimento do site do Aeroporto de Guarulhos (GRU 
Airport) com foco na experiência do usuário e facilidade de administração. O site 
será responsivo, multi-idioma, com busca de voos, reservas, lojas e gestão via 
SharePoint.

### 2-Premissas e Restrições ### 
**2.1 Premissas Gerais**
<li>O site do aeroporto de Guarulhos deve ser responsivo (com duas 
resoluções: Destkop: 1290x768 Mobile: 360x480), exceto nos portais 
Cargo e de Investidores que serão links externos. </li>
<li>O site deve ser multi-idioma considerando os idiomas português, 
inglês e espanhol</li>
<li>Todas as páginas de conteúdo deverão ser editáveis pelo 
administrador do site através de um painel administrativo.</li>
<li>Utilizar os conceitos básicos de SEO. </li>

**2.2 Restrições**
<li>O backend do site deve ser administrado utilizando o Microsoft 
Sharepoint em sua versão 2013 (15.0.4805.1000 - KB3114822). </li>
<li>O servidor onde a aplicação será instalada será um Windows Server 
2012 = NT 6.2. 9600</li>
<li>O servidor de banco de dados da aplicação será um SQL Server 2014 
SP1 CU5 = 12.0.4439.1 - KB3130926. </li>
<li>O frontend do site deve ser plenamente compatível com os 
navegadores: Internet Explorer 9 ou superior, Mozilla Firefox 3 ou 
superior, Safari 5 ou superior, Safari iOS e Google Chrome 47 ou 
superior. </li>
<li>Alguns links do projeto remeterão à URLs externas e devem abrir em 
outra janela (_blank): - Trabalhe Conosco: https://site.vagas.com.br/gru - GRU Cargo: http://www.grucargo.com.br/index.aspx - RI: http://ri.gru.com.br/default_pt.asp?idioma=0&conta=28</li>

### 3- Declaração de Escopo ### 
| O escopo de teste cobre | O escopo de teste não cobre|
|----------|----------|
| Funcionalidade: Cabeçalho da Home para passageiros (Desktop)   | Teste Unitários serão executados pela equipe de desenvolvimento |
|Funcionalidade: Menu de “como chegar” (Desktop)  | Testes que fogem do escopo da demanda  |

### 4- Cronograma ### 

![Cronogrma](https://imgur.com/5OTekBa.png)

### 5- Abordagem de testes ### 
**5.1 Tipos de testes**

![Tipos de testes](https://imgur.com/BPMkfz9.png)












