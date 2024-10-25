# Configurando Recursos e Dimensionamentos em Máquinas Virtuais na Azure

## Passo 1: Criar uma Máquina Virtual

### 1. **Acesse o Portal do Azure**: Entre no [Portal do Azure](https://azure.microsoft.com/pt-br/get-started/azure-portal/).

### 2. **Criar um Recurso**: Clique em “Criar um recurso” e selecione “Máquina Virtual”.

### 3. **Configurações Básicas**:

- **Assinatura**: Selecione sua assinatura do Azure.
- **Grupo de Recursos**: Escolha um grupo de recursos existente ou crie um novo.
- **Nome da Máquina Virtual**: Dê um nome à sua VM.
- **Região**: Escolha a região onde a VM será hospedada.
- **Imagem**: Selecione o sistema operacional desejado (Windows ou Linux).
- **Tamanho**: Escolha o tamanho da VM com base nas suas necessidades de CPU e memória.

![vms](https://github.com/devcaiada/az-900-certification/blob/main/assets/VMs.jpg?raw=true)

## Passo 2: Configurar Recursos

### 1. Discos:

- **Disco do Sistema Operacional**: Escolha o tipo de disco (SSD ou HDD).
- **Discos de Dados**: Adicione discos adicionais conforme necessário.

### 2. Rede:

- **Rede Virtual**: Selecione uma rede virtual existente ou crie uma nova.
- **Sub-rede**: Escolha uma sub-rede.
- **Endereço IP Público**: Configure um endereço IP público se necessário.
- **Grupo de Segurança de Rede**: Configure regras de firewall para controlar o tráfego de entrada e saída.

## Passo 3: Dimensionamento

### 1. Dimensionamento Vertical:

- **Aumentar/Reduzir Tamanho**: Você pode redimensionar a VM para um tamanho maior ou menor conforme necessário. Isso pode ser feito na seção “Tamanho” da VM no portal do Azure.

### 2. Dimensionamento Horizontal:

- **Conjuntos de Dimensionamento de Máquinas Virtuais**: Use conjuntos de dimensionamento para criar e gerenciar um grupo de VMs idênticas. Isso permite que você escale automaticamente o número de VMs com base na demanda.

## Passo 4: Configurações Avançadas

### 1. Monitoramento:

- **Diagnóstico de Inicialização**: Ative o diagnóstico de inicialização para solucionar problemas de inicialização.
- Monitoramento de Desempenho: Use o Azure Monitor para acompanhar o desempenho da VM.

### 2. Automação:

- **Scripts de Inicialização**: Adicione scripts de inicialização para configurar a VM automaticamente ao iniciar.

## Passo 5: Revisar e Criar

#### 1. **Revisar**: Verifique todas as configurações.

#### 2. **Criar**: Clique em “Criar” para provisionar a VM.