# Ferramentas de Implatação na Azure - Command Line Interface (CLI)

![bicep](https://github.com/devcaiada/az-900-certification/blob/main/assets/bicep.png?raw=true)

## PowerShell (PS)

O **PowerShell** é uma linguagem de script e shell de linha de comando desenvolvida pela Microsoft. É amplamente utilizada para automação de tarefas administrativas e gerenciamento de sistemas. Algumas características principais do PowerShell incluem:

- **Objetos**: Diferente de muitos shells de linha de comando que trabalham com texto, o PowerShell trabalha com objetos. Isso permite manipular dados de forma mais robusta e flexível.
- **Cmdlets**: São comandos especializados que realizam tarefas específicas. Por exemplo, Get-Process para listar processos em execução.
- **Pipeline**: Permite encadear comandos, passando a saída de um comando como entrada para o próximo, facilitando a automação de tarefas complexas.
- **Cross-Platform**: Originalmente disponível apenas no Windows, o PowerShell agora é multiplataforma, funcionando também em Linux e macOS.

## Bicep

O **Bicep** é uma linguagem específica de domínio (DSL) desenvolvida pela Microsoft para a implantação de recursos no Azure. É uma alternativa ao uso de templates **JSON** do **Azure Resource Manager (ARM)**. Algumas características do Bicep incluem:

- **Sintaxe Declarativa**: Permite definir a infraestrutura que você deseja implantar de forma clara e concisa.
- **Suporte Completo ao Azure**: Suporta todos os tipos de recursos e versões de API do Azure, permitindo usar novos serviços assim que são lançados.
- **Facilidade de Uso**: Comparado aos modelos JSON, os arquivos Bicep são mais fáceis de ler e escrever.
- **Integração com CLI**: O Bicep pode ser usado diretamente com a CLI do Azure, facilitando a conversão de arquivos Bicep em templates ARM JSON e a implantação de recursos.

## Principais Comandos

### PowerShell (PS)

### 1. Conectar ao Azure:

```
Connect-AzAccount
```

- Este comando é usado para autenticar e conectar sua sessão do PowerShell ao Azure.

### 2. Implantar um arquivo Bicep em um grupo de recursos:

```
New-AzResourceGroupDeployment -ResourceGroupName <nome-do-grupo-de-recursos> -TemplateFile <caminho-para-o-arquivo-bicep>
```

- Este comando implanta os recursos definidos em um arquivo Bicep em um grupo de recursos específico.

### 3. Implantar em uma assinatura:

```
New-AzSubscriptionDeployment -Location <localização> -TemplateFile <caminho-para-o-arquivo-bicep>
```

- Use este comando para implantar recursos no nível da assinatura.

### 4. Implantar em um grupo de gerenciamento:

```
New-AzManagementGroupDeployment -ManagementGroupId <id-do-grupo-de-gerenciamento> -Location <localização> -TemplateFile <caminho-para-o-arquivo-bicep>
```

- Este comando é usado para implantar recursos no nível do grupo de gerenciamento.

### Bicep

### 1. Definir uma conta de armazenamento:

```
param location string = resourceGroup().location
param storageAccountName string = 'mystorageaccount${uniqueString(resourceGroup().id)}'

resource storageAccount 'Microsoft.Storage/storageAccounts@2023-04-01' = {
  name: storageAccountName
  location: location
  sku: {
    name: 'Standard_LRS'
  }
  kind: 'StorageV2'
  properties: {
    accessTier: 'Hot'
  }
}
```

- Este exemplo define uma conta de armazenamento no Azure.

### 2. Implantar um arquivo Bicep usando a CLI do Azure:

```
az deployment group create --resource-group <nome-do-grupo-de-recursos> --template-file <caminho-para-o-arquivo-bicep>
```

- Este comando usa a CLI do Azure para implantar os recursos definidos em um arquivo Bicep.