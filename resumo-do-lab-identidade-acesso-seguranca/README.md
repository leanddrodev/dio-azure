# Identidade, Acesso e Segurança na Azure

## Acessar o Microsoft Entra ID

![entra-id](https://github.com/devcaiada/az-900-certification/blob/main/assets/Microsoft-Entra-ID-1.png?raw=true)

### 1. Entrar no Portal do Azure:

- Acesse o [Portal do Azure](https://azure.microsoft.com/pt-br/get-started/azure-portal/).
- No menu lateral, selecione **Microsoft Entra ID**.

### 2. Gerenciar Funções e Administradores

1.  Visualizar Funções:

- No painel do **Microsoft Entra ID**, selecione **Funções e Administradores**.
- Aqui, você pode ver todas as funções disponíveis. Clique em uma função para ver os detalhes e os membros atribuídos.

2.  Adicionar Administradores:

- Para adicionar um novo administrador, selecione a função desejada e clique em **Adicionar membro**.
- Procure e selecione o usuário que deseja adicionar.

### 3. Configurar Redefinição de Senha Self-Service (SSPR)

1.  Ativar SSPR:

- No painel do Microsoft Entra ID, selecione **Redefinição de senha**.
- Ative a opção **Self-service password reset**.

![ssrp](https://github.com/devcaiada/az-900-certification/blob/main/assets/self%20service%20reset.png?raw=true)

2.  Configurar Métodos de Autenticação:

- Defina os métodos de autenticação que os usuários devem usar para redefinir suas senhas, como e-mail, telefone ou perguntas de segurança.
- Salve as configurações.

### 4. Criar Novo Usuário ou Convidar Usuário Externo

1.  Criar Novo Usuário:

- No painel do Microsoft Entra ID, selecione **Usuários**.
- Clique em **Novo usuário** e preencha as informações necessárias, como nome, nome de usuário e grupo de funções.
- Salve o novo usuário.

2.  Convidar Usuário Externo:

- No painel do Microsoft Entra ID, selecione **Usuários**.
- Clique em **Novo usuário** e selecione **Convidar usuário**.
- Insira o e-mail do usuário externo e configure as permissões e grupos aos quais ele terá acesso.
- Envie o convite.

### 5. Utilizar o Microsoft Defender for Cloud como Validador de Segurança

1.  Configurar o **Microsoft Defender for Cloud**:

- No Portal do Azure, navegue até **Microsoft Defender for Cloud**.
- Ative o Microsoft Defender for Cloud para suas assinaturas e recursos.

2.  Monitorar e Validar Segurança:

- O Microsoft Defender for Cloud fornece uma visão geral da postura de segurança da sua organização.
- Ele identifica vulnerabilidades e recomendações de segurança para proteger seus recursos.
- Utilize as recomendações para melhorar a segurança e conformidade dos seus recursos na Azure.

### EXTRA

- **Os usuários são excluídos permanentemente de forma automática 30 dias após serem deletados.**