# Construindo Arquiteturas no Azure

### 1. Acesse o Portal do Azure:

- Entre no [Portal do Azure](https://azure.microsoft.com/pt-br/get-started/azure-portal/).

### 2. Navegue até Grupos de Recursos:

- No menu à esquerda, selecione **Grupos de Recursos**.

![resource_g](https://github.com/devcaiada/az-900-certification/blob/main/assets/resource%20group%201.png?raw=true)

### 3. Criar um Novo Grupo de Recursos:

- Clique em Criar.
- Preencha os seguintes campos:
  - **Assinatura**: Selecione sua assinatura do Azure.
  - **Grupo** de Recursos: Insira um nome para o novo grupo de recursos.
  - **Região**: Escolha uma localização do Azure, como “EUA Central”.
- Clique em **Examinar + Criar** e depois em **Criar**.

### 4. Verificar a Criação:

- Após alguns segundos, o grupo de recursos será criado. Você pode atualizá-lo na lista de grupos de recursos ou clicar na notificação para abrir o grupo recém-criado.

## Gerenciar Permissões

![permission](https://github.com/devcaiada/az-900-certification/blob/main/assets/resource%20group.png?raw=true)

### 1. Acessar Controle de Acesso (IAM):

- Dentro do grupo de recursos, selecione **Controle de Acesso (IAM)** no menu à esquerda.

### 2. Adicionar uma Função:

- Clique em **Adicionar** e depois em **Adicionar atribuição de função**.
- Escolha a função desejada (por exemplo, **Contribuidor**).
- Selecione o usuário ou grupo que receberá essa função.
- Clique em **Salvar** para aplicar as permissões.

## Aplicar Bloqueios

### 1. Acessar Configurações de Bloqueio:

- No menu do grupo de recursos, selecione **Bloqueios**.

### 2. Adicionar um Bloqueio:

- Clique em **Adicionar**.
- Preencha os seguintes campos:
  - **Nome**: Insira um nome para o bloqueio.
  - **Tipo de Bloqueio**: Escolha entre **Excluir** (impede a exclusão) ou **Somente leitura** (impede alterações).
  - **Notas**: Adicione qualquer informação adicional, se necessário.
- Clique em **OK** para aplicar o bloqueio.

<br></br>