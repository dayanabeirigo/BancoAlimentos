# Especificações do Projeto

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Administrador       | Alterar permissões e cadastrar novos usuários do BMA e CRAS | Permitir a administração de contas e o controle de usuários |
|Usuário BMA/CRAS | Cadastrar beneficiários |Inserir no sistema pessoas aptas ao recebimento do benefício  |
|Usuário BMA/CRAS | Alterar cadastro de beneficiários| Permitir a atualização/correção de dados do beneficiário |
|Usuário BMA/CRAS | Registrar cestas básicas/verdes e pontos para os quais as cestas foram enviadas | Registrar nº de cestas básicas e local de distribuição para prestação de contas |
|Usuário BMA/CRAS | Consultar se beneficiário já recebeu auxílio durante o período de referência | Evitar concessão de cesta básica em duplicidade |
|Usuário BMA/CRAS | Registrar o benefício entregue ao beneficiário | Deduzir saldo e deixar registrado que o beneficiário já recebeu o benefício |
|Beneficiário | Consultar data de recebimento do próximo benefício | Evitar deslocamento desnecessário para recebimento de benefício |
|Beneficiário | Consultar locais com cestas disponíveis | Localizar o endereço mais próximo com cestas em estoque |
|Cidadão| Quantidade de cestas doadas e quantidade de família atendidas| 	Dar transparência ao trabalho do BMA| 
|Cidadão|	Quantidade de alimentos doados por fonte|	Dar transparência ao trabalho do BMA |

O quadro abaixo apresenta uma breve definição de cada perfil: 

|Perfil| Descrição
|--------------------|------------------------------------|
|Administrador|	Servidor do BMA/CRAS com grau máximo de visualização e controle do sistema|
|Usuário BMA/CRAS |	Servidor/colaborador vinculado ao BMA/CRAS que recebe, separa e prepara as cestas básicas e cestas verdes, cadastra beneficiários|
|Beneficiário| 	Pessoa que recebe a cesta básica ou a cesta verde|
|Cidadão |	Qualquer pessoa que acesse o site para buscar infomações sobre o Banco de Alimentos|



## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário faça login de entrada| ALTA | 
|RF-002| Permitir que o usuário faça logoff do sistema| ALTA |
|RF-003| Permitir que o administrador cadastre os usuários do sistema| ALTA |
|RF-004| Permitir que o administrador consulte, altere e exclua o cadastro dos usuários do sistema| ALTA |
|RF-005| Permitir que o usuário cadastre os beneficiários| ALTA |
|RF-006| Permitir que o usuário consulte, altere e exclua o cadastro dos beneficiários| ALTA |
|RF-007| Permitir que o usuário registre as retiradas de cestas pelo beneficiário| ALTA |
|RF-008| Restringir a retirada de cesta, conforme periodicidade estabelecida pelo município| ALTA |
|RF-009| Permitir que o usuário visualize histórico de retirada dos beneficiários| MÉDIA |
|RF-010| Permitir que o usuário realize a redefinição de senha| MÉDIA |
|RF-011| Tela informativa sobre o programa de entrega das cestas| BAIXA |
|RF-012| Permitir o controle de estoque de cestas básicas| ALTA |
|RF-013| Apresentar prestação de contas das ações do Banco de Alimentos| ALTA |
|RF-014| Registrar a quantidade de alimentos doados| ALTA |




### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| Utilizar o SCRUM como metodologia de desenvolvimento| ALTA | 
|RNF-002| O sistema deve ser web |MÉDIA | 
|RNF-003| O sistema será desenvolvido em HTML5, CSS3 e JS| MÉDIA| 
|RNF-004| O sistema deve ser executado nos principais navegadores (Chrome, mozila e Edge)| MÉDIA | 
|RNF-005| O sistema deve ser responsivo para adaptação em dispositivos móveis | MÉDIA | 
|RNF-006| Deve processar requisições do usuário em no máximo 3s| BAIXA| 
|RNF-007| Para que o sistema seja acessado, é necessário estar conectado a internet| MÉDIA| 
|RNF-008| Utilizar um banco de dados para verificar informações de usuários, cestas, beneficiários e instituições| MÉDIA| 
|RNF-009| O sistema deve exigir autenticação prévia de usuários| MÉDIA| 
|RNF-010| O sistema deve fazer backup a cada 24 horas| MÉDIA| 
|RNF-011| O sistema deve ter boa usabilidade| MÉDIA| 
|RNF-012| O sistema deve conter mensagens que informem erros de utilização| MÉDIA| 


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre|
|02| As informações de perfil de beneficiário não devem estar disponíveis para todos usuários do sistema|

