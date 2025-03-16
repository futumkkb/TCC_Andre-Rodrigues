# Circuit Breaker: A Resilience Mechanism for Cloud Native Architecture

### N. S. S. A and S. Sebastian, "Circuit Breaker: A Resilience Mechanism for Cloud Native Architecture," 2023 Global Conference on Information Technologies and Communications (GCITC), Bangalore, India, 2023, pp. 1-8, doi: 10.1109/GCITC60406.2023.10426195.

### 1. Fichamento de Conteúdo

O artigo discute a importância do padrão Circuit Breaker (CB) como um mecanismo de resiliência para aplicações cloud-native. Ele aborda seu funcionamento, implementação e melhores práticas, além de comparar diferentes bibliotecas que suportam CB.
O artigo visa apresentar uma revisão abrangente sobre o Circuit Breaker, destacando seu papel na arquitetura de microserviços e sua relevância para garantir disponibilidade e confiabilidade em sistemas distribuídos.
Os autores conduziram uma Revisão Sistemática da Literatura (SLR), categorizando pesquisas existentes sobre CB em microserviços e sistemas distribuídos. O estudo incluiu análise de diferentes bibliotecas e um modelo conceitual para aprimorar CBs.

Principais Argumentos:

-Aplicações cloud-native exigem mecanismos robustos de resiliência para evitar falhas catastróficas.

-O CB impede falhas em cascata ao monitorar o estado de serviços e bloquear chamadas para serviços instáveis.

-Comparando padrões de resiliência, CB se destaca por reduzir o impacto de falhas sem sobrecarregar sistemas.

-Foram revisadas bibliotecas populares como Hystrix, Resilience4j e Polly.

-Propõe-se uma melhoria no CB, permitindo a rerrotação dinâmica de solicitações em caso de falha.

O estudo confirma a eficácia do CB na melhoria da confiabilidade e tolerância a falhas em sistemas distribuídos. Conclui-se que a combinação do CB com outras técnicas de resiliência é essencial para sistemas modernos.

### 2. Fichamento Bibliográfico

Reutilização de software legado: Empresas continuam utilizando sistemas legados devido à sua relevância operacional e falta de recursos para substituição (p. 1).

Cloud Native Applications (CNAs): Aplicativos desenvolvidos especificamente para operação em ambientes de nuvem, aproveitando arquiteturas como microsserviços e containerização (p. 3).

Padrões de Resiliência: O CB é comparado com outros padrões, como Retry, Bulkhead e Timeout, demonstrando sua vantagem na prevenção de falhas recorrentes (p. 6).

Circuit Breaker em IoT: Algumas pesquisas indicam que CBs podem ser aplicados a dispositivos IoT para garantir disponibilidade e minimizar falhas de comunicação (p. 8).

Bibliotecas de Circuit Breaker: Hystrix, Resilience4j, Polly e Failsafe são comparadas quanto a suporte para métricas, sincronização e integração com microsserviços (p. 10).

### 3. Fichamento de Citações

Citações Diretas:

-"Circuit Breaker is a crucial resilience mechanism that prevents cascading failures in distributed systems." (p. 4)

-"By identifying failure patterns early, CB enables cloud applications to remain operational even during partial outages." (p. 7)

-"Retry mechanisms may lead to unnecessary load on failing services, whereas CB actively prevents further requests when failure is detected." (p. 9)

Citações Indiretas:

-O artigo enfatiza que a implementação de CB deve ser combinada com outros padrões de resiliência para maximizar a estabilidade de sistemas distribuídos.

-Estudos analisados indicam que, quando configurado corretamente, o CB reduz significativamente o tempo de inatividade de serviços críticos.

-A proposta de um CB dinâmico com rerroteamento de solicitações representa um avanço significativo na arquitetura de microserviços.


