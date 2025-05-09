📌 Backlog da Sprint 1 - Projeto Finanças

✅ Infraestrutura e Preparação

[ ] Criar os repositórios no GitHub → pf-auth-service, pf-user-service, pf-finance-service

[ ] Subir o projeto base (Spring Boot ou Node.js por exemplo) com:

[ ] README

[ ] Dockerfile inicial

[ ] Estrutura inicial de pastas

[ ] Configurar .env para cada serviço

✅ pf-auth-service

[ ] Configurar login e registro básico (JWT)

[ ] Validar autenticação em endpoints protegidos

✅ pf-user-service

[ ] CRUD básico de usuários (create, read, update, delete)

[ ] Integração com o Auth (quando necessário)

✅ pf-finance-service

[ ] CRUD básico de transações (despesas e receitas)

[ ] Definir modelo inicial de dados (categorias, valores, datas)

✅ Integração entre serviços

[ ] Configurar comunicação entre os serviços (via HTTP ou RabbitMQ/Kafka se desejarem desde já)

[ ] Garantir autenticação no pf-finance-service usando o pf-auth-service

🎯 Objetivo de entrega da Sprint 1

Usuário consegue registrar → logar → cadastrar transações de despesas e receitas

Serviços rodando via Docker localmente

Integração básica funcionando entre os serviços

🛠️ Próximos passos para a Sprint 2 (MVP avançado)

Refinar pf-finance-service (regras de negócio e categorias detalhadas)

Iniciar pf-notification-service (notificações e alertas)

Iniciar pf-report-service (relatórios e exportação)

Refatorar e integrar melhor o Frontend com os microserviços

