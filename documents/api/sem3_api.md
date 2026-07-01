# API 3 - 3º Semestre BD, 2022-2

## Projeto: Sistema Meteorológico ioWeather.

[![Generic badge](https://img.shields.io/badge/GitHub-Repositório-blue.svg)](https://github.com/GroupHextech/HEXTECH-API3sem)

Parceiro Acadêmico: [IACIT Soluções Tecnológicas](https://www.iacit.com.br/).

## Resumo do projeto.
<p align="justify">IACIT é uma empresa brasileira, fundada em 1986, São 36 anos de experiência que começaram com a prestação de suporte técnico à Tecnasa, fabricante de equipamentos para o segmento de navegação aérea. Com capacitação tecnológica para o desenvolvimento de produtos e sistemas aplicados às áreas de Auxílio do Controle e do Tráfego Aéreo e Marítimo; Defesa e Segurança Pública; Fábrica de Software; Meteorologia; Pesquisa, Desenvolvimento e Inovação; Telemetria e Agronegócio.</p>

<p align="justify">O problema apresentado é a necessidade em armazenar os dados das estações em um banco de dados e a partir destes dados conseguir gertar relátorios e gráficos a seus clientes.</p>

## Tecnologias adotadas.
<summary>Front-End</summary>

- [JavaScript](https://www.javascript.com)
- [CSS3](https://www.w3schools.com/css/)
- [Vue](https://vuejs.org/guide/quick-start)

<summary>Back-End</summary>

- [Java](https://www.java.com/pt-BR/)
- [Spring boot](https://spring.io/projects/spring-boot)
- [Thymeleaf](https://www.thymeleaf.org/)
- [Hibernate](https://hibernate.org/)

<summary>Banco de Dados</summary>

- [PostgreSQL](https://www.postgresql.org/)

<summary>Metodologia ágil</summary>

- [Atlassian JIRA](https://www.atlassian.com/br/software/jira)

## Projeto em funcionamento.
<div align="center">

[![](http://img.youtube.com/vi/h1t4SODqV5s/0.jpg)](https://youtu.be/h1t4SODqV5s "HexTech ioWeather")

*Wireframes do projeto em funcionamento, link para o youtube*
</div>

## Contribuições pessoais.
<p align="justify">Para esta API fiquei responsável por dois papeis o de desenvolvedor e o de SCRUM MASTER da equipe
Tais tarefas me trouxeram maturidade para o desenvolvimento e também conhecimento para analisar, planejar e separar as tarefas de cada menbro dentro da atividade proposta e tempo.</p>

<p align="justify">Utlização de materiais e estudos novos como JPA, Thymeleaf, PostgreSQL, Maven, Spring Boot e outros itens que foram necessários aumentar o tempo de estudo para poder entender e executar com as melhores prática.<p>

- <p align="justify">Modelagem e gerenciamento do SGBD PostgreSQL.</p>
- <p align="justify">Utilização de Springboot e Arquitetura rest.</p>
- <p align="justify">Utilização de ferramentas novas JPA, Thymeleaf e Hibernate.<p>

<details>
<summary>Banco de Dados</summary>
  
### Modelagem do BD e Utilização do PostgreSQL:
<p align="justify">Realizei a integração do SGBD com a aplicação, utilizando um ambiente local em host. Foi a primeira vez que trabalhei com esse tipo de SGBD, que, embora relacional, possui suas particularidades. Para garantir a aplicação correta e eficaz da estrutura modelada, aprofundei meu conhecimento na ferramenta, o que me permitiu criar triggers e procedures de maneira precisa. Além de ser responsável por todas as atividades relacionadas ao banco de dados, também atuei como Scrum Master, coordenando o time e assegurando o alinhamento das entregas conforme as metodologias ágeis.</p>
</details>

<details>
<summary>Back-end</summary>

### Spring boot:
<p align="justify">Utilizei pela primeira vez o framework Spring Boot para a criação de um projeto web e microservice. A ferramenta simplificou significativamente a configuração e facilitou a implementação do Modelo MVC. O empacotamento em JAR com o servidor Tomcat integrado proporcionou uma execução mais simples e eficiente. A configuração do POM.xml com as dependências necessárias foi intuitiva e prática. Esse processo me permitiu entender claramente o desenvolvimento e a evolução do projeto, contribuindo não apenas para o meu aprendizado, mas também para o sucesso das entregas do grupo.</p>

### JPA:
<p align="justify">O JPA (Java Persistence API) simplifica a interação entre a aplicação Java e o banco de dados relacional, convertendo objetos Java em registros de tabelas do banco. Essa integração é realizada por meio da criação de classes Java que representam as tabelas, possibilitando uma abstração eficiente e intuitiva. Assim, operações de CRUD (Create, Read, Update e Delete) são realizadas de forma simplificada e com menos código repetitivo.</p>

<p align="justify">No projeto, o JPA garantiu a persistência eficiente dos dados, facilitando a implementação de funcionalidades que interagem com o banco de dados e promovendo uma estrutura mais organizada e escalável.</p>
</details>

<details>
<summary>Front-end</summary>

### Thymeleaf:
<p align="justify">O Thymeleaf proporcionou uma interface web dinâmica e perfeitamente integrada ao back-end, facilitando a construção e manutenção das páginas HTML. Esse recurso foi fundamental para o desenvolvimento de uma aplicação robusta e funcional, especialmente ao aplicar o padrão MVC (Model-View-Controller).</p>

<p align="justify">O template engine simplificou a passagem de dados entre o controller e a view, garantindo que as informações fossem exibidas de forma dinâmica e coerente. Além disso, o uso do Thymeleaf facilitou futuras manutenções nas páginas, proporcionando uma estrutura mais organizada e de fácil atualização após a implementação. </p>
</details>

## Aprendizados efetivos.

### Hard Skills:

- **Java / Spring Boot:** Uso com ajuda: criação de projeto web/microservice, empacotamento JAR com Tomcat embutido, configuração de POM.xml.</p>
- **JPA / Hibernate:** Uso com ajuda: mapeamento objeto-relacional e CRUD com menos código repetitivo.</p>
- **Thymeleaf:** Uso com ajuda: construção de views dinâmicas integradas ao padrão MVC.</p>
- **PostgreSQL:** Uso com autonomia: modelagem, integração local e criação de triggers e procedures.</p>
- **Metodologia Ágil (JIRA/Scrum):** Uso com autonomia: atuação como Scrum Master, planejamento e distribuição de tarefas da equipe.</p>
- **GIT:** Uso com autonomia: controle de versão consolidado.

### Soft Skills:

- **Organização:** Atuando simultaneamente como desenvolvedor e Scrum Master, precisei organizar minhas próprias entregas técnicas junto ao planejamento e acompanhamento das tarefas da equipe, estruturando as sprints no JIRA e garantindo que os prazos fossem cumpridos.</p>
- **Analitico:** O contato com ferramentas novas como PostgreSQL, JPA, Thymeleaf e Maven exigiu uma análise cuidadosa de cada tecnologia antes de aplicá-la ao projeto, além da necessidade de avaliar o desempenho da equipe para distribuir tarefas de acordo com as habilidades e o tempo disponível de cada integrante.</p>
- **Trabalho em Equipe:** Como Scrum Master, atuei diretamente na coordenação do time, promovendo o alinhamento entre os membros e assegurando que as entregas seguissem as metodologias ágeis, o que fortaleceu minha capacidade de colaborar e mediar o trabalho em grupo.</p>
- **Empatia:** O papel de Scrum Master exigiu compreender as dificuldades individuais de cada membro da equipe diante de ferramentas novas e complexas, buscando apoiar e ajustar as demandas conforme a realidade e o ritmo de cada um.</p>

<br>

<hr>

  <p align="right">
    <a href="#ioweather">⬆️ Voltar ao topo deste semestre</a> &nbsp; | &nbsp; 
    <a href="#meus-projetos">🏠 Voltar para o início da página</a>
  </p>