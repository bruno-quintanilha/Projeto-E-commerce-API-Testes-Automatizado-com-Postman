# Projeto-E-commerce-API-Testes-Automatizado-com-Postman
Este projeto é uma simulação de e-commerce, criado com o objetivo de aprender testes automatizados de APIs REST usando o Postman. O foco é testar o fluxo CRUD (Create, Read, Update, Delete) de produtos, garantindo que a API responda corretamente a cada operação. Este projeto não é um e-commerce real, mas um teste para desenvolver habilidades de QA.

🎯 Objetivo

Criar, listar, atualizar, pegar e deletar produtos via API 📝

Automatizar testes de cada operação no Postman 🤖

Utilizar variáveis de ambiente para controlar dados entre requests 🛠️

⚙️ Pré-requisitos

Postman instalado (Desktop ou Web)

Conta gratuita no [MockAPI](https://mockapi.io/)

Conhecimento básico de HTTP e APIs REST

🌐 Variáveis de Ambiente

O projeto utiliza um Environment no Postman para armazenar variáveis importantes:

Variável	Finalidade	Initial Value	Current Value
baseUrl	URL base da API	https://SEU_MOCKAPI_URL/api/v1	https://SEU_MOCKAPI_URL/api/v1
productId	Armazena o ID do produto criado	(vazio)	(vazio)
updatedName	Nome do produto atualizado	Ex: Produto Teste Atualizado	Ex: Produto Teste Atualizado
updatedPrice	Preço do produto atualizado	Ex: 100	Ex: 100

💡 Observação: O productId é atualizado automaticamente após criar um produto e é utilizado nos requests de GET específico, PUT e DELETE.
