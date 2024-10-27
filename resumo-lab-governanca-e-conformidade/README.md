# Gerenciando Políticas e Governança em Acessos Azure

## Acessar o Portal de Confiança do Serviço

![porta_confianca](https://github.com/devcaiada/az-900-certification/blob/main/assets/portal%20confian%C3%A7a.png?raw=true)

### 1. Acesse o Portal de Confiança do Serviço:

- Vá para o Portal de **[Confiança do Serviço](https://servicetrust.microsoft.com/)**.
- Faça login com sua conta de serviços de nuvem da Microsoft (**Microsoft Entra**).

### 2. Aceite o Contrato de Não Divulgação:

- Se for a primeira vez que você acessa, será necessário aceitar o Contrato de Não Divulgação da Microsoft para Materiais de Conformidade.

### 3. Navegue pelo Portal:

- Utilize o menu principal para acessar relatórios de auditoria, **whitepapers** e outros recursos sobre segurança e conformidade.

## Configurar o Microsoft Purview

![purview](https://raw.githubusercontent.com/devcaiada/az-900-certification/refs/heads/main/assets/purview.png)

### 1. Acesse o Portal do Azure:

- Vá para o **Portal do Azure** e faça login.

### 2. Crie um Cofre de Chaves:

- No menu do portal, selecione “**Criar um recurso**” e procure por “**Cofre de Chaves**”.
- Siga as instruções para criar um novo **Cofre de Chaves**.

### 3. Configurar o Microsoft Purview:

- No portal do Azure, navegue até “**Microsoft Purview**”.
- Siga as instruções para configurar o Microsoft Purview, incluindo a definição de políticas de segurança e conformidade.

## Utilizar o Azure Policy

### 1. Acesse o Azure Policy:

- No portal do Azure, selecione “**Política**” no menu principal.

### 2. Criar uma Política:

- Clique em “**Definições**” e depois em “**Adicionar definição**”.
- Escolha uma definição de política existente ou crie uma nova conforme suas necessidades.

### 3. Atribuir a Política:

- Após criar a política, vá para “**Atribuições**” e clique em “**Adicionar atribuição**”.
- Selecione a política que você criou e atribua-a ao escopo desejado (assinatura, grupo de recursos, etc.).

### 4. Monitorar a Conformidade:

- Use o painel de conformidade do **Azure Policy** para monitorar e gerenciar a conformidade das suas políticas.

![policy-compliance](https://github.com/devcaiada/az-900-certification/blob/main/assets/policy-compliance.png?raw=true)

## EXTRA

## Governança de Dados

- **Mapeamento de Dados**: O Microsoft Purview Data Map permite registrar e escanear suas fontes de dados para criar um mapa atualizado do seu patrimônio de dados, incluindo classificação de dados e linhagem de ponta a ponta.
- **Catálogo de Dados**: O Microsoft Purview Data Catalog ajuda a curar suas fontes de dados, gerenciar a integridade dos dados, governar seu patrimônio de dados, proteger dados sensíveis e extrair valor comercial das fontes de dados existentes.

## Segurança de Dados

- **Proteção de Informações**: Inclui soluções como Microsoft Purview Data Loss Prevention (DLP), Information Protection e Insider Risk Management para descobrir e proteger informações sensíveis.
- **Gerenciamento de Acesso**: Permite gerenciar o acesso aos dados de forma segura e em escala, garantindo que apenas usuários autorizados possam acessar informações sensíveis.

## Conformidade e Riscos

- **Gerenciamento de Conformidade**: Ferramentas como Microsoft Purview Compliance Manager e Communication Compliance ajudam a minimizar riscos de conformidade e atender aos requisitos regulatórios.
- **Auditoria**: O Microsoft Purview Audit oferece capacidades de auditoria para monitorar e registrar atividades relacionadas aos dados, ajudando a garantir a conformidade e a segurança.

## Visibilidade e Integração

- **Visibilidade de Dados**: Proporciona visibilidade sobre os dados em toda a organização, ajudando a identificar onde os dados sensíveis estão armazenados e como são utilizados.
- **Integração com Serviços de Nuvem**: Suporta a governança de dados em serviços de armazenamento do Azure, Power BI, bancos de dados como SQL ou Hive, serviços de arquivos como Amazon S3, entre outros.