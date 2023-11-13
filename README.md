# Finance

## Análise de requisitos do Back-End

### Requisitos Funcionais

- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível editar informações do perfil do usuário após o cadastro;
- [ ] Deve ser possível a recuperação de senha do usuário;
- [ ] Deve ser possível a exclusão permanente de uma conta de usuário;
- [ ] Deve ser possível obter o perfil do usuário logado;

<!-- - [ ] Deve ser possível cadastrar uma carteira de investimentos; -->

- [ ] Deve ser possível cadastrar opções para cada modalidade de pagamento(Cartão de credito, cartão de débito e etc).
- [ ] Deve ser possível criar uma despesa fixa;
- [ ] Deve ser possível criar uma despesa variável;
- [ ] Deve ser possível cadastrar uma fatura;
- [ ] Deve ser possível listar todas as despesas e receitas, com filtros para um determinado periodo de tempo ou categoria;
- [ ] Deve ser possível cadastrar uma fonte de receita;
- [ ] Deve ser possível marcar despesas como pagas por meio de uma opção de pagamentos;

- [ ] Deve ser possível listar as opções de pagamento;
- [ ] Deve ser possível listar as modalidades de pagamentos;
- [ ] Deve ser possível listar as categorias de pagamento;
- [ ] Deve ser possível listar as opções de pagamento;

- [ ] Deve ser possível visualizar o histórico de pagamentos e/ou faturas, com filtros para um determinado periodo de tempo ou categoria;

- [ ] Integrar um sistema de notificações para lembretes de vencimento de despesas;
- [ ] Deve ser possível gerar relatórios mensais ou anuais para análise financeira;
- [ ] Deve ser possível a sincronização com serviços externos de finanças e afins;

### Regras de Negócio

- [ ] Apenas o proprio usuário pode deletar sua conta;
- [ ] Categorias e metódos de pagamentos devem estar criados previamente na aplicação.
- [ ] Toda despesa fixa ou variável deve ter uma categoria atribuída;
- [ ] A modalidade de pagamento de Débito automático só pode ser usado como opção para despesas fixas;
- [ ] Despesas fixas só podem ter uma opção de pagamento;
- [ ] Uma despesa variável que conter varias parcelas podem ser pagas de uma só vez, mas o valor dessa antecipação só cairá na próxima fatura;
- [ ] Cartões diferentes podem compartilhar a mesma fatura;

### Requisitos Não Funcionais

- [ ] A Aplicação deve fazer uso do banco de dados PostgreSQL;
- [ ] A Aplicação deve fazer uso de WebSockets;
- [ ] A senha do usuário deve ser salva com um hash no Banco de dados;
- [ ] Criptografar informações sensíveis antes de armazenar no banco de dados. Ex: CPF, número de cartão, senha de cartões e afins, caso houver;
