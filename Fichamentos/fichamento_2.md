# Containerized Microservices: A Survey of Resource Management Frameworks

### L. M. Al Qassem, T. Stouraitis, E. Damiani and I. M. Elfadel, "Containerized Microservices: A Survey of Resource Management Frameworks," in IEEE Transactions on Network and Service Management, vol. 21, no. 4, pp. 3775-3796, Aug. 2024, doi: 10.1109/TNSM.2024.3388633.

### 1. Fichamento de Conteúdo

O artigo apresenta uma revisão abrangente sobre frameworks de gerenciamento de recursos para microserviços conteinerizados, analisando estratégias de alocação de recursos e técnicas para melhorar a eficiência e escalabilidade desses sistemas.
Objetivo:
Investigar e classificar frameworks de gerenciamento de recursos para microserviços conteinerizados, destacando tendências atuais e desafios, além de propor direções futuras para otimizar a alocação de recursos.

Metodologia:
Revisão sistemática da literatura em bases científicas entre 2015 e 2023.
Seleção de 65 artigos focados em microserviços conteinerizados.
Classificação dos frameworks em três categorias: reativos, preditivos e híbridos.
Principais Argumentos:

Microserviços conteinerizados vs. VMs: Containers são mais leves e eficientes do que máquinas virtuais, reduzindo o overhead de CPU e armazenamento.
Desafios no gerenciamento de recursos: Problemas como latência, consumo de energia e escalabilidade são críticos na arquitetura de microserviços.
Classificação dos frameworks:
Reativos: Alocam recursos dinamicamente com base na demanda observada. Exemplos: Kubernetes, Docker Swarm.
Preditivos: Usam aprendizado de máquina para prever carga de trabalho e alocar recursos de forma proativa. Exemplos: Sinan, RScale.
Híbridos: Combinam abordagens reativas e preditivas para maior eficiência. Exemplos: FIRM, ASFM.
Impacto no mercado: Empresas como Google, Amazon e Alibaba enfrentam problemas de subutilização de recursos (<40%), indicando a necessidade de melhores frameworks.
Tendências futuras: Desenvolvimento de técnicas de machine learning mais avançadas para otimizar a distribuição de carga e reduzir violações de SLA.
Resultados e Conclusão:
Os frameworks híbridos são os mais promissores, pois combinam a resposta rápida dos sistemas reativos com a previsibilidade dos modelos preditivos.
Ainda há desafios na padronização de técnicas de gerenciamento de recursos em larga escala.
O artigo propõe a evolução dos modelos atuais para frameworks que integram machine learning e algoritmos de otimização de alocação de recursos.

### 2. Fichamento Bibliográfico

Microserviços conteinerizados: Arquitetura moderna baseada em containers, que substitui máquinas virtuais para maior eficiência e flexibilidade (p. 3775).

Frameworks reativos: Técnicas como Kubernetes e Docker Swarm que ajustam automaticamente a alocação de recursos com base no uso atual (p. 3778).

Frameworks preditivos: Algoritmos que utilizam aprendizado de máquina para prever demanda de recursos e antecipar escalabilidade (p. 3782).

Frameworks híbridos: Combinação de abordagens reativas e preditivas para otimização da alocação de recursos em microserviços (p. 3786).

Violações de SLA: Problema comum em arquiteturas de microserviços devido a latências imprevisíveis e má distribuição de recursos (p. 3777).

Técnicas de otimização: Algoritmos como redes neurais, aprendizado por reforço e otimização baseada em heurísticas são utilizados para melhorar o gerenciamento de recursos (p. 3784).

### 3. Fichamento de Citações

Citações Diretas:

-"Microservice-based architectures provide flexibility and scalability but introduce new challenges in resource management and SLA enforcement." (p. 3776)
-"Reactive frameworks such as Kubernetes dynamically adjust resource allocation but may not prevent SLA violations under high workloads." (p. 3778)
-"Predictive approaches leverage machine learning to anticipate resource demand and optimize microservice performance." (p. 3782)
-"Hybrid frameworks combine the advantages of reactive and predictive models, providing more robust resource management solutions." (p. 3786)
Citações Indiretas:

-Os autores argumentam que a adoção de microserviços conteinerizados tem crescido rapidamente, mas desafios como escalabilidade eficiente e gestão de SLAs ainda não foram totalmente resolvidos.
-Estudos indicam que os frameworks híbridos são mais eficazes na alocação de recursos, reduzindo custos e melhorando a performance dos sistemas distribuídos.
-A pesquisa sugere que a aplicação de técnicas avançadas de machine learning pode melhorar significativamente a alocação preditiva de recursos, reduzindo desperdícios e aumentando a eficiência operacional.