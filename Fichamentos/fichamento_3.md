# Robust Failure Diagnosis of Microservice System Through Multimodal Data

### S. Zhang et al., "Robust Failure Diagnosis of Microservice System Through Multimodal Data," in IEEE Transactions on Services Computing, vol. 16, no. 6, pp. 3851-3864, Nov.-Dec. 2023, doi: 10.1109/TSC.2023.3290018.

### 1. Fichamento de Conteúdo

O artigo aborda a importância da utilização de dados multimodais (métricas, logs e traces) para o diagnóstico de falhas em sistemas baseados em microserviços.
Objetivo:
Desenvolver um método robusto para diagnóstico de falhas em sistemas de microserviços utilizando múltiplas fontes de dados.
Metodologia:
Análise empírica de falhas em sistemas reais.
Desenvolvimento do modelo DiagFusion, que usa técnicas de aprendizado de máquina, aprendizado de representações e redes neurais gráficas para diagnóstico de falhas.
Comparação com métodos existentes e avaliação em dois conjuntos de dados reais.
Principais Argumentos:
Limitações dos métodos tradicionais: Diagnósticos baseados apenas em um único tipo de dado (traces, logs ou métricas) são insuficientes.
Uso de dados multimodais: Combinar logs, métricas e traces melhora a precisão do diagnóstico.
DiagFusion: Novo modelo que representa dados multimodais e utiliza redes neurais gráficas para identificar falhas e localizar a origem do problema.
Resultados experimentais: O método melhora a precisão da localização da falha em até 368% e a determinação do tipo de falha em até 169%.
Resultados e Conclusão:
DiagFusion supera métodos tradicionais ao integrar diferentes fontes de dados.
O uso de aprendizado de máquina melhora a capacidade de adaptação do sistema.
A abordagem é promissora para aplicações industriais em larga escala.

### 2. Fichamento Bibliográfico

Microserviços e falhas: Arquiteturas baseadas em microserviços são altamente distribuídas e propensas a falhas em cadeia (p. 3852).

Dados multimodais: Logs, métricas e traces são usados para monitorar microserviços, cada um com suas limitações individuais (p. 3853).

DiagFusion: Novo modelo baseado em aprendizado de máquina que combina diferentes fontes de dados para diagnóstico de falhas (p. 3855).

Redes neurais gráficas (GNNs): Utilizadas para capturar padrões de propagação de falhas entre microserviços (p. 3856).

Eficiência do modelo: O DiagFusion reduz o tempo de diagnóstico para menos de 12 segundos por falha, tornando-se viável para sistemas em tempo real (p. 3859).

### 3. Fichamento de Citações

Citações Diretas:

-"Using just one data source cannot fully capture these patterns and accurately distinguish between different types of failures." (p. 3853)
-"DiagFusion achieves Avg@5 of 0.75 and 0.76 on the two datasets, respectively, improving the accuracy of root cause instance localization by 20.9% to 368%." (p. 3856)
-"By examining the existing literature and case studies, different libraries, this paper showcases the effectiveness of multimodal data in enhancing failure diagnosis." (p. 3859)
Citações Indiretas:

-O artigo destaca que métodos tradicionais falham em capturar padrões complexos de falhas porque utilizam apenas um tipo de dado.
-A análise empírica demonstra que a combinação de dados multimodais melhora significativamente a precisão do diagnóstico de falhas em microserviços.
-   O uso de redes neurais gráficas permite a identificação de padrões complexos de falha e a redução de falsos positivos no diagnóstico.
