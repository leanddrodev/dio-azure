# Lab Benefícios da Nuvem

Este repositório contém o resumo do Lab Benefícios da Nuvem do Bootcamp Microsoft Azure Essentials na Dio. No Lab, foram abordados os benefícios da Nuvem: Alta Disponibilidade, Escalabilidade, Elasticidade, Confiabilidade, Previsibilidade, Segurança, Governança e Gerenciabilidade.

## Resumo do Lab

A instrutora Valéria Baptista - Head of Cloud and Cybersecurity at CloudData - apresentou de forma esclarecedora e com exemplos os benefícios que a Cloud da Azure pode proporcionar.

Abaixo a lista desses benefícios:

1. **Alta Disponibilidade** - Concentra-se em garantir a disponibilidade máxima, independentemente de interrupções ou eventos que possam ocorrer. O Azure é um ambiente de nuvem altamente disponível com garantias de tempo de atividade, dependendo do serviço. Essas garantias fazem parte dos SLAs (Contratos de Nível de Serviço).

2. **Escalabilidade** - Refere-se à capacidade de ajustar recursos para atender à demanda. A capacidade de escalar significa que você poderá adicionar mais recursos para lidar melhor com o aumento da demanda. O outro benefício da escalabilidade é que você não está pagando além do necessário pelos serviços. Como a nuvem é um modelo baseado em consumo, você paga apenas pelo que usa. Se a demanda cair, você poderá reduzir seus recursos e, assim, reduzir seus custos. Com a escala vertical, se você estivesse desenvolvendo um aplicativo e precisasse de mais capacidade de processamento, poderia escalar verticalmente para adicionar mais CPUs ou RAM à máquina virtual. 

3. **Elasticidade** - Com a elasticidade, se você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente). Por exemplo, você pode adicionar máquinas virtuais ou contêineres por meio da expansão. Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente (de maneira automática ou manual).

4. **Confiabilidade** - Devido ao design descentralizado, a nuvem naturalmente dá suporte a uma infraestrutura confiável e resiliente. A nuvem permite que você tenha recursos implantados em várias regiões do mundo. Com essa escala global, mesmo que ocorra um evento catastrófico em uma região, as outras regiões ainda estarão em funcionamento. 

5. **Previsibilidade** - A previsibilidade na nuvem permite que você avance com confiança, seja no desempenho ou no custo. Ambas são influenciadas pelo Microsoft Azure Well-Architected Framework. 

6. **Segurança** - A nuvem oferece ferramentas de segurança que atendem às necessidades dos clientes mas, é importante lembrar que a implementação de muitas delas devem ser realizadas pelo cliente. Se você quiser o controle máximo da segurança, a infraestrutura como serviço fornecerá recursos físicos, mas permitirá que você gerencie os sistemas operacionais e o software instalado, incluindo aplicação de patches e manutenção. Se você quiser que a aplicação de patches e a manutenção sejam tratadas automaticamente, as implantações de plataforma como serviço ou software como serviço podem ser as melhores estratégias de nuvem.

7. **Governança** - A auditoria baseada em nuvem ajuda a sinalizar qualquer recurso que esteja fora de conformidade com os padrões corporativos e fornece estratégias de mitigação. Dependendo do seu modelo operacional, patches de software e atualizações também podem ser aplicados automaticamente, o que ajuda na governança e na segurança. Ao estabelecer uma presença de governança o mais cedo possível, você poderá manter sua presença de nuvem atualizada, protegida e bem gerenciada.

8. **Gerenciabilidade** - Um dos principais benefícios da computação em nuvem são as opções de capacidade de gerenciamento. Há dois tipos de capacidade de gerenciamento para computação em nuvem e ambos trazem excelentes benefícios.
O gerenciamento da nuvem diz respeito a _gerenciar seus recursos de nuvem_. Por exemplo:
   - Escalar automaticamente a implantação de recursos com base na necessidade;
   - Implantar recursos com base em um modelo pré-configurado, removendo a necessidade de configuração manual.
   
   O gerenciamento na nuvem diz respeito à _maneira de gerenciar seu ambiente de nuvem e seus recursos_. Por exemplo:
   - Por meio de um portal da Web;
   - Usando uma interface de linha de comando (CLI);
   - Usando APIs;
   - Usando o PowerShell.