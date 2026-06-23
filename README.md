🧪 Teste de API de QA - ReqRes (Postman)

Projeto de automação de testes de API utilizando Postman com foco em validação de endpoints REST, aplicando cenários positivos e negativos.
📌 Projeto desenvolvido para portfólio de QA Júnior.

🎯 O que foi testado
Este projeto valida o comportamento de uma API REST simulada, cobrindo:

Validação de códigos de status HTTP
Estrutura e conteúdo da resposta JSON
Regras de negócio
Cenários positivos e negativos

🔗 Endpoints testados
✔ GET - Listar usuários

https://reqres.in/api/users?page=2

✔ Validação de status 200 e retorno de lista
✔ GET - Buscar por ID do usuário

https://reqres.in/api/users/2

✔ Validação do usuário existente
❌ GET - Usuário inexistente

https://reqres.in/api/users/999

✔ Validação de status 404
✔ POST - Criar usuário

https://reqres.in/api/users

✔ Validação de status 201

✔ Validação de nome, trabalho e ID gerado
✔ PUT - Atualizar usuário

https://reqres.in/api/users/2

✔ Validação de status 200

✔ Validação de dados atualizados

✔ Validação do campo updatedAt
✔ DELETE - Remover usuário

https://reqres.in/api/users/2

✔ Validação de status 204
✔ POST - Registro com sucesso

https://reqres.in/api/register

✔ Validação de status 201

✔ Validação dos campos email e id retornados
❌ POST - Registro sem senha

https://reqres.in/api/register

✔ Validação de status 400

✔ Mensagem: "Missing password"
🧠 O que foi validado

Códigos de status corretos (200, 201, 204, 400, 404)
Estrutura JSON das respostas
Campos obrigatórios (id, email, nome, cargo)
Cenários positivos e negativos

*Objetivo do projeto - 
Demonstrar conhecimento em testes de API REST, validação de respostas e automação básica de testes utilizando Postman.

📌 Projeto de estudos em QA / Testes de API
