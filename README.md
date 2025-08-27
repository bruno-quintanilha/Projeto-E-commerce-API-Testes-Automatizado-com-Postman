# Projeto-E-commerce-API-Testes-Automatizado-com-Postman
Este projeto é uma simulação de e-commerce, criado com o objetivo de aprender testes automatizados de APIs REST usando o Postman. O foco é testar o fluxo CRUD (Create, Read, Update, Delete) de produtos, garantindo que a API responda corretamente a cada operação. Este projeto não é um e-commerce real, mas um teste para desenvolver habilidades de QA.

🎯 **Objetivo**

•Criar, listar, atualizar, pegar e deletar produtos via API 📝

•Automatizar testes de cada operação no Postman 🤖

•Utilizar variáveis de ambiente para controlar dados entre requests 🛠️

⚙️ **Pré-requisitos**

•Postman instalado (Desktop ou Web)

•Conta gratuita no [MockAPI](https://mockapi.io/)

•Conhecimento básico de HTTP e APIs REST

•API:
<img width="1294" height="337" alt="image" src="https://github.com/user-attachments/assets/c71feea4-ad16-4078-9ba6-09356ce690b4" />

<img width="678" height="523" alt="image" src="https://github.com/user-attachments/assets/e9e2c76c-c135-4a07-9718-5cb6738ccc3b" />


🌐 **Variáveis de Ambiente**

•O projeto utiliza um Environment no Postman para armazenar variáveis importantes:
<img width="1359" height="718" alt="image" src="https://github.com/user-attachments/assets/12442763-aaa1-4008-aebe-6fa7647b2a53" />

💡 Observação: O **productId** é atualizado automaticamente após criar um produto e é utilizado nos requests de **GET** específico, **PUT** e **DELETE**.

📦 **Requests e Testes**
1️⃣ **POST** - Criar um produto

•Objetivo: Criar um novo produto na API

•URL: {{baseUrl}}/products

•Body (JSON):
<img width="725" height="238" alt="image" src="https://github.com/user-attachments/assets/e2ee97cd-33ea-47a9-accd-4bfe29c87633" />

•Testes automatizados:
<img width="639" height="392" alt="image" src="https://github.com/user-attachments/assets/41d07108-5cf6-4d1c-896a-3910a003d414" />

2️⃣ **GET** - Listar todos os produtos

•Objetivo: Recuperar todos os produtos

•URL: {{baseUrl}}/products

•Body: Nenhum

•Testes automatizados:
<img width="913" height="401" alt="image" src="https://github.com/user-attachments/assets/9cf0f598-01ef-4989-b2e9-833a7cf9d68a" />

3️⃣ **GET** - Pegar um produto específico

•Objetivo: Recuperar detalhes de um produto pelo ID

•URL: {{baseUrl}}/products/{{productId}}

•Body: Nenhum

Testes automatizados:
<img width="923" height="380" alt="image" src="https://github.com/user-attachments/assets/5493cf7c-26ae-4456-9a33-f80ae0eb0a2e" />

4️⃣ **PUT** - Atualizar um produto

•Objetivo: Atualizar dados de um produto existente

•URL: {{baseUrl}}/products/{{productId}}

•Body (JSON):
<img width="914" height="346" alt="image" src="https://github.com/user-attachments/assets/31d1548a-49b5-454f-9221-131f96b64e38" />

•Testes automatizados:
<img width="921" height="405" alt="image" src="https://github.com/user-attachments/assets/c3014e63-3238-4fde-88f1-231c29d6e84e" />

5️⃣ **DELETE** - Deletar um produto

•Objetivo: Remover um produto existente pelo ID

•URL: {{baseUrl}}/products/{{productId}}

•Body: Nenhum

•Testes automatizados:
<img width="914" height="368" alt="image" src="https://github.com/user-attachments/assets/6c1baba2-7bab-4cdb-a909-b82850e967aa" />

🔄 **Fluxo do Projeto**

•Criar um produto → POST

•Listar todos os produtos → GET

•Pegar um produto específico → GET

•Atualizar o produto → PUT

•Deletar o produto → DELETE

•Resultado: 
<img width="923" height="428" alt="image" src="https://github.com/user-attachments/assets/f505d5eb-7f9c-486b-8d52-d7498a3856a4" />

📝 **Observações**

•Todas as requests usam a {{baseUrl}} como variável de ambiente

•O productId é atualizado automaticamente

•GET e DELETE não precisam de body

•Este projeto serve como portfólio de QA, mostrando habilidades de testes de API automatizados








