# Armazenamento e Migração de Dados na Azure

Vamos criar um passo a passo para criar uma conta de armazenamento no Azure e falar sobre os serviços de transferência de dados, como o AzCopy.

## 1. Acesse o Portal do Azure:

- Vá para o [Portal do Azure](https://azure.microsoft.com/pt-br/get-started/azure-portal/) e faça login com sua conta.

![menu_storage](https://github.com/devcaiada/az-900-certification/blob/main/assets/Menu-storage.jpg?raw=true)

## 2. Criar uma Nova Conta de Armazenamento:

- No menu à esquerda, selecione “Contas de armazenamento”.
- Clique em “Criar” para iniciar o processo de criação.

![create_button](https://github.com/devcaiada/az-900-certification/blob/main/assets/create-button.jpg?raw=true)

- Preencha os detalhes necessários:
  - Assinatura: Selecione sua assinatura do Azure.
  - Grupo de Recursos: Escolha um grupo de recursos existente ou crie um novo.
  - Nome da Conta de Armazenamento: Insira um nome único para sua conta.
  - Região: Selecione a região onde deseja criar a conta.
  - Desempenho: Escolha entre Standard ou Premium, dependendo de suas necessidades.
  - Replicação: Selecione a opção de replicação desejada (LRS, GRS, RA-GRS, etc.).

![basic](https://github.com/devcaiada/az-900-certification/blob/main/assets/basic.jpg?raw=true)

## 3. Configurações Adicionais:

- Configure as opções adicionais conforme necessário, como redes virtuais, tags, etc.
- Clique em “Revisar e criar” e depois em “Criar” para finalizar a criação da conta.

<br></br>

# Serviços de Transferência e Migração de Dados

## 1. AzCopy:

![azcopy](https://github.com/devcaiada/az-900-certification/blob/main/assets/azcopy.jpg?raw=true)

- AzCopy é uma ferramenta de linha de comando que permite copiar dados de e para contas de armazenamento do Azure de forma eficiente.
- Instalação: Baixe e instale o AzCopy a partir do site oficial.

### Uso Básico:

- Para copiar um arquivo local para um contêiner de blob:

```
azcopy copy 'C:\local\path\to\file.txt' 'https://<storage-account-name>.blob.core.windows.net/<container-name>/file.txt'
```

- Para copiar um blob para um arquivo local:

```
azcopy copy 'https://<storage-account-name>.blob.core.windows.net/<container-name>/file.txt' 'C:\local\path\to\file.txt'
```

## 2. Azure Data Factory:

- Azure Data Factory é um serviço de integração de dados baseado em nuvem que permite criar, agendar e orquestrar fluxos de trabalho de dados.
- Ele suporta a movimentação de dados entre uma variedade de fontes de dados, incluindo armazenamento do Azure, bancos de dados SQL, e muito mais.

## 3. Azure Storage Explorer:

- Azure Storage Explorer é uma ferramenta gráfica que facilita a gestão de dados no armazenamento do Azure.
- Permite visualizar, carregar, baixar e gerenciar blobs, arquivos, filas e tabelas.