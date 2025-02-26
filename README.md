# Bootcamp Bradesco Java native Cloud
# Digital Innovattion One

- Construindo Arquiteturas no Azure
- Lista de passos para criar um projeto de arquitetura na Azure

### Passo 1: Acessar o Portal do Azure
1. **Acesse o Portal do Azure**: Abra o navegador e vá para o [Portal do Azure](https://portal.azure.com/).
2. **Faça login**: Insira suas credenciais (e-mail e senha) para acessar sua conta Azure.

### Passo 2: Navegar até a seção de Grupos de Recursos
1. **No menu à esquerda**, clique em **"Grupos de recursos"**. Isso pode estar na seção **"Serviços do Azure"** ou você pode usar a barra de pesquisa no topo do portal para encontrar "Grupos de recursos".

### Passo 3: Criar um Novo Grupo de Recursos
1. **Clique em "Criar"**: No painel de Grupos de Recursos, clique no botão **"Criar"** para iniciar o processo de criação de um novo grupo de recursos.

### Passo 4: Preencher os Detalhes do Grupo de Recursos
1. **Selecione a Assinatura**: Escolha a assinatura na qual você deseja criar o grupo de recursos.
2. **Nome do Grupo de Recursos**: Insira um nome para o grupo de recursos. O nome deve ser único dentro da assinatura.
3. **Selecione a Região**: Escolha a região onde o grupo de recursos será criado. A região determina onde os metadados do grupo de recursos serão armazenados.
4. **Revisar e Criar**: Após preencher os detalhes, clique em **"Revisar + criar"** para validar as informações.

### Passo 5: Validar e Criar o Grupo de Recursos
1. **Validação**: O Azure validará as informações fornecidas. Se tudo estiver correto, você verá uma mensagem de validação bem-sucedida.
2. **Criar**: Clique em **"Criar"** para finalizar a criação do grupo de recursos.

### Passo 6: Verificar a Criação do Grupo de Recursos
1. **Notificação**: Após a criação, você receberá uma notificação no portal confirmando que o grupo de recursos foi criado com sucesso.
2. **Navegar até o Grupo de Recursos**: Você pode navegar até o grupo de recursos recém-criado clicando em **"Ir para o grupo de recursos"** na notificação ou buscando pelo nome do grupo de recursos na lista de grupos de recursos.

### Passo 7: Gerenciar Recursos no Grupo
1. **Adicionar Recursos**: Agora que o grupo de recursos está criado, você pode começar a adicionar recursos a ele, como máquinas virtuais, contas de armazenamento, bancos de dados, etc.
2. **Gerenciar e Monitorar**: Utilize o grupo de recursos para gerenciar e monitorar todos os recursos associados a ele de forma centralizada.

### Dicas Adicionais
- **Tags**: Considere adicionar tags ao grupo de recursos para facilitar a organização e a gestão de custos.
- **Políticas**: Você pode aplicar políticas do Azure ao grupo de recursos para garantir conformidade com as normas da sua organização.
  
# Mas por que eu deveria criar um grupo de recursos?

O **objetivo principal** ao criar um grupo de recursos no Microsoft Azure é **organizar e gerenciar recursos relacionados de forma lógica e eficiente**. Um grupo de recursos funciona como um contêiner que agrupa recursos (como máquinas virtuais, contas de armazenamento, bancos de dados, redes, etc.) que compartilham um ciclo de vida comum ou estão associados a uma aplicação ou projeto específico.

Aqui estão os principais objetivos e benefícios de usar grupos de recursos no Azure:

### 1. **Organização Lógica**
   - Agrupar recursos que estão relacionados entre si, como todos os componentes de uma aplicação (servidores, banco de dados, rede, etc.).
   - Facilitar a localização e o gerenciamento de recursos específicos.

### 2. **Gerenciamento do Ciclo de Vida**
   - Aplicar operações em massa aos recursos dentro do grupo, como:
     - Implantação.
     - Atualização.
     - Exclusão (ao excluir um grupo de recursos, todos os recursos dentro dele são excluídos automaticamente).
   - Isso simplifica o gerenciamento e a manutenção de recursos.

### 3. **Controle de Acesso (IAM - Identity and Access Management)**
   - Atribuir permissões (RBAC - Role-Based Access Control) ao grupo de recursos, o que se aplica a todos os recursos dentro dele.
   - Isso garante que apenas usuários ou grupos autorizados possam acessar ou modificar os recursos.

### 4. **Monitoramento e Análise de Custos**
   - Visualizar e monitorar o uso e os custos de todos os recursos dentro do grupo de recursos de forma centralizada.
   - Facilitar a identificação de gastos e a otimização de custos.

### 5. **Isolamento e Segurança**
   - Isolar recursos de diferentes projetos ou ambientes (como desenvolvimento, teste e produção) em grupos de recursos separados.
   - Aplicar políticas específicas (Azure Policy) para garantir conformidade com padrões de segurança e governança.

### 6. **Facilidade de Implantação**
   - Usar modelos do Azure Resource Manager (ARM templates) para implantar e configurar todos os recursos dentro de um grupo de recursos de forma automatizada e consistente.

### 7. **Escopo para Operações**
   - Definir um escopo claro para operações de gerenciamento, como backup, monitoramento e auditoria, que podem ser aplicados a todos os recursos dentro do grupo.

### Resumo
O grupo de recursos é uma ferramenta essencial no Azure para **organizar, gerenciar e controlar** recursos de forma eficiente. Ele permite que você:
- Mantenha seus recursos organizados.
- Aplique políticas e permissões de forma centralizada.
- Gerencie o ciclo de vida dos recursos de maneira simplificada.
- Monitore custos e desempenho de forma integrada.

Ao criar um grupo de recursos, estamos estabelecendo uma estrutura lógica que facilita a administração e a operação de seus recursos na nuvem.
