# Monitoramento Inteligente com o Azure

Vamos explorar o **Azure Monitor Insights** e o **Azure Advisor Recommendations** para realizar monitoramentos inteligentes de nossas máquinas virtuais e serviços Azure.

## Azure Monitor Insights

![azure-monitor](https://github.com/devcaiada/az-900-certification/blob/main/assets/azure-monitor.jpg?raw=true)

O **Azure Monitor Insights** é uma coleção de visualizações e funcionalidades personalizadas que ajudam a monitorar e analisar o desempenho e a saúde dos seus recursos no Azure. Aqui estão alguns dos principais componentes:

1.  **VM Insights**: Monitora o desempenho e a saúde das suas Máquinas Virtuais (VMs) e Conjuntos de Escala de Máquinas Virtuais. Ele analisa processos e dependências, fornecendo uma visão abrangente do estado das VMs.

2.  **Container Insights**: Monitora o desempenho de cargas de trabalho de contêineres implantadas em clusters **Kubernetes** gerenciados no **Azure Kubernetes Service (AKS)**. Coleta métricas e logs dos controladores, nós e contêineres.

3.  **Network Insights**: Oferece uma visão abrangente da saúde e métricas de todos os seus recursos de rede. Ajuda a identificar dependências de recursos e a resolver problemas de rede.

4.  **Storage Insights**: Fornece monitoramento abrangente das suas contas de armazenamento Azure, oferecendo uma visão unificada do desempenho, capacidade e disponibilidade dos serviços de armazenamento.

![monitor-dashboard](https://github.com/devcaiada/az-900-certification/blob/main/assets/azure-monitoring-dashboard.png?raw=true)

## Azure Advisor Recommendations

O **Azure Advisor** é um assistente digital que fornece recomendações personalizadas para ajudar a otimizar suas implantações no Azure. Ele analisa a configuração e o uso dos seus recursos e oferece sugestões para melhorar a eficácia de custos, desempenho, confiabilidade e segurança. Aqui estão algumas das principais funcionalidades:

![azure-advisor](https://github.com/devcaiada/az-900-certification/blob/main/assets/azure-advisor.png?raw=true)

1.  **Recomendações de Confiabilidade**: Para garantir e melhorar a continuidade das suas aplicações críticas para o negócio.

2.  **Recomendações de Segurança**: Para detectar ameaças e vulnerabilidades que podem levar a violações de segurança.

3.  **Recomendações de Desempenho**: Para melhorar a velocidade das suas aplicações.

4.  **Recomendações de Custo**: Para otimizar e reduzir seus gastos gerais com o Azure.

5.  **Excelência Operacional**: Para ajudar a alcançar eficiência de processos e fluxos de trabalho, gerenciabilidade de recursos e melhores práticas de implantação.

Além disso, o Azure Advisor está integrado com o **Azure Monitor Log Analytics Workspace**, permitindo que você visualize as recomendações diretamente no portal do Azure.