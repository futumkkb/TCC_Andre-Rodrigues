# Microservices vs Monolith: A Comparative Analysis and Problem-Solving Approach in Web Development Area

### Fichamento de conteudo

Objetivo: Comparar arquiteturas monolíticas e de microsserviços no desenvolvimento web, por meio de implementação prática e testes de desempenho com uma aplicação de e-commerce desenvolvida em ambas as abordagens.
Resumo: O artigo investiga as vantagens e desvantagens das arquiteturas monolítica e de microsserviços, considerando escalabilidade, manutenção, desempenho e segurança. Para isso, os autores implementam uma aplicação web usando ambas as arquiteturas com a stack MERN (MongoDB, Express, React, Node.js), avaliada com testes de carga usando Apache JMeter.
Principais pontos:
A arquitetura monolítica é mais simples para projetos pequenos, mas limitada em escalabilidade e manutenção.
A arquitetura de microsserviços oferece maior escalabilidade, modularidade e flexibilidade, porém exige mais esforço em orquestração, testes e segurança.
Foram realizados testes com até 500 usuários concorrentes para comparar desempenho, taxa de erros e throughput.
Microserviços apresentaram:
Menor tempo de resposta (777ms vs. 1488ms no monólito com 200 usuários).
Menor taxa de erro (19,93% vs. 40,33%).
Maior throughput sob carga (até 178,2 req/s vs. 152,4 req/s).
Conclusão: A arquitetura de microsserviços é mais eficaz para aplicações com alta demanda de escalabilidade e flexibilidade, enquanto monólitos são adequados para aplicações menores e com menor complexidade. A escolha depende do contexto do projeto e da capacidade da equipe em lidar com a complexidade adicional dos microsserviços.

### Fichamento de citacoes

“Monolithic architecture allows the database [...] to be located in one place and thus internal communications [...] are simplified.” (p. 4)

“Microservices provide better scalability and flexible architectural solutions to traditional constraints.” (p. 2)

“Microservice architecture had a much lower error rate of 19.93% than the monolithic architecture (40.33%) at 200 concurrent users.” (p. 14)