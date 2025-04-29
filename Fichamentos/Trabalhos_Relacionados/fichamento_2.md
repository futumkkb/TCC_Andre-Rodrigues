# From Monolith to Microservice: Measuring Architecture Maintainability

### HASAN, Muhammad Hafiz; ABDUL MALEK, Nurul Hidayah; ABDUL RAHMAN, Mohd Noor; MANSOOR, Waqas. From Monolith to Microservice: Measuring Architecture Maintainability. International Journal of Advanced Computer Science and Applications (IJACSA), v. 14, n. 5, p. 857–865, 2023. DOI: 10.14569/IJACSA.2023.01405104.


### Fichamento de conteudo

O artigo trata da migração de aplicações legadas com arquitetura monolítica para uma arquitetura de microsserviços, com ênfase na mensuração da manutenibilidade da arquitetura resultante. A motivação principal é superar as limitações dos sistemas monolíticos, como acoplamento forte, baixa escalabilidade e dificuldade de atualização, características que comprometem a modernização e adaptabilidade dos sistemas.

O trabalho propõe um modelo de métricas estruturais para avaliar a qualidade da arquitetura em termos de manutenibilidade após a migração. As métricas sugeridas incluem propriedades como acoplamento, coesão, complexidade e tamanho, associadas aos princípios da arquitetura nativa em nuvem (cloud-native). O estudo é fundamentado em modelos de qualidade pré-existentes, como QMOOD e ISO/IEC 25010, adaptando-os ao contexto de microsserviços.

Três perguntas de pesquisa guiam o estudo: (1) Quais métricas estruturais já existentes se aplicam à arquitetura baseada em serviços? (2) Como essas métricas se relacionam com características de sistemas cloud-native? (3) Quais métricas são mais viáveis para medir manutenibilidade em arquiteturas de microsserviços?

A principal contribuição é um conjunto de métricas matematicamente formalizadas para avaliar manutenibilidade de arquitetura antes da execução da migração, visando reduzir dívida técnica e assegurar os benefícios da nuvem. O artigo também destaca limitações, como a ausência de uma revisão sistemática rigorosa e a necessidade de validação empírica futura por meio de estudos de caso.

### Fichamento bibliografico

Monólito vs Microsserviços: Sistemas monolíticos são mais difíceis de manter e escalar; microsserviços oferecem modularidade, baixo acoplamento e alta coesão, ideais para ambientes de nuvem (p. 857).

Motivações da migração: A busca por escalabilidade, modifiabilidade e melhor manutenção impulsiona a transição para microsserviços (p. 857).

Métricas de Manutenibilidade: Acoplamento, coesão, complexidade e tamanho são propriedades estruturais chave para medir qualidade da arquitetura (p. 859).

Modelo ISO/IEC 25010: Referencial usado para alinhar métricas com subcaracterísticas de manutenibilidade como modularidade e reusabilidade (p. 860).

IDEALS: Princípios de design cloud-native usados para mapear métricas relevantes à arquitetura moderna (p. 861).

Métricas propostas: Incluem CBM (Coupling Between Microservices), NCAM (Normalized Cohesion Among Classes), TRM (Total Response for Microservice), MLOC (Microservice Lines of Code) (p. 861-862).

Limitações: Ausência de validação empírica e possibilidade de viés na seleção de métricas (p. 864).

### Citacoes

“To ensure that the migration to microservices is a sound decision for enhancing maintainability, designers must carefully consider the underlying factors driving this software architecture migration.” (p. 857)

“A successful decomposition should produce minimized coupling between microservices and maximized cohesion.” (p. 861)

“Measuring architecture quality for migrated monolith applications to microservice is crucial to ensure migration to the cloud achieves the migration objective.” (p. 863)

“The proposed metrics allow migration designers and developers to measure software architecture maintainability quality for microservice during design time.” (p. 865)