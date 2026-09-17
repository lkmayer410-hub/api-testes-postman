🧪 api-testes-postman
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Newman](https://img.shields.io/badge/Newman-CLI-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
> Projeto de estudos e prática em testes de API REST desenvolvido durante formação completa em Quality Assurance. Cobre desde os fundamentos de HTTP até automação com Newman, testes orientados a dados e geração de relatórios profissionais.
---
📋 Sobre o Projeto
Este repositório reúne as collections, environments e massa de dados utilizados ao longo de uma formação prática de 45 aulas em testes de API com Postman. A API alvo é a Northwind, uma API REST com endpoints de produtos, categorias, fornecedores e clientes — ideal para simular cenários reais de QA.

A jornada passou por fundamentos de HTTP, leitura de contratos Swagger, criação de testes automatizados, execução em escala com dados externos e publicação de relatórios em HTML — tudo que um QA Engineer precisa no dia a dia.
🔗 API de estudo: Northwind API Docs
🎓 Novos cursos: Gotas de Tecnologia
---
📚 Módulos da Formação
Módulo 1 — Fundamentos de APIs e HTTP
Conceitos essenciais: o que é uma API, como funciona o HTTP, estrutura de URLs, métodos GET, POST, PUT, PATCH e DELETE e operações CRUD.
Módulo 2 — Documentação Swagger e JSON
Leitura e interpretação de contratos de API via Swagger UI. Análise de endpoints, parâmetros, request body e respostas. Sintaxe JSON e uso do cURL.
Módulo 3 — Configuração de Workspace e Collections
Criação de workspaces e estruturação profissional de collections no Postman, com foco em organização e reuso.
Módulo 4 — Execução e Estruturação de Requisições HTTP
Construção completa de requisições: headers, authorization, query params, path params e validação de status codes para todos os métodos HTTP.
Módulo 5 — Importação de Requisições e Integração com APIs
Importação de cURL direto para o Postman e importação de collections a partir da documentação oficial da API.
Módulo 6 — Variáveis e Ambientes
Uso de environments, variáveis de collection e geração de dados dinâmicos com Faker para parametrizar e reutilizar requisições.
Módulo 7 — Data Driven Tests com Inteligência Artificial
Geração de massa de dados em JSON com apoio de IA e execução de testes com arquivos CSV.
Módulo 8 — Automação de Testes no Postman
Escrita de testes com JavaScript (pm.test), partindo de User Stories até snippets funcionais. Validação de campos obrigatórios, nulos, vazios, tamanho, paginação, ordenação, upload de arquivos e contrato de payload.
Módulo 9 — Testes em Escala com Múltiplos Dados
Automação com Collection Runner usando JSON e CSV, geração de token dinâmico via Pre-request Script e encadeamento de requisições para controle de cenários end-to-end.
Módulo 10 — IA Generativa do Postman
Uso prático da inteligência artificial nativa do Postman para apoiar a criação de testes sem perder o controle técnico sobre os cenários.
Módulo 11 — Documentação e Relatórios Profissionais
Execução via Newman com geração de relatórios em JSON, JUnit e HTML (htmlextra). Boas práticas de nomenclatura moderna de testes.
Módulo 12 — Portfólio e Encerramento
Publicação do projeto no GitHub com estrutura organizada e README profissional voltado para o mercado.
---
📸 Evidências
✅ Collection Runner — Resultado dos Testes HTML
![Runner](docs/assets/testes-runner.PNG)
🧪 Testes Automatizados com Runner
![Postman Testes](docs/assets/postman-automation.PNG)
🧪 Testes Automatizados no Postman
![Postman Testes](docs/assets/testes-postman-results.PNG)
📂 Data Driven — Massa de Dados
![Data Driven](docs/assets/data-driven-json.PNG)
📂 SWAGGER UI
![Swagger](docs/assets/swagger.PNG)
---
💡 Lições Aprendidas
Ler o contrato antes de testar — o Swagger evita erros e acelera a escrita dos testes
Variáveis desde o início — parametrizar a base URL e o token desde a primeira requisição economiza retrabalho
Dados dinâmicos evitam conflitos — usar Faker, UUID e timestamp no payload impede falhas por duplicidade
Pre-request Script é poderoso — gerar token automaticamente elimina dependência manual entre testes
Newman transforma o Postman em CI — a execução via CLI abre caminho para pipelines de integração contínua
Nomenclatura importa — nomear testes com clareza (dado, quando, então) facilita a leitura dos relatórios
Relatório HTML conta uma história — o htmlextra entrega evidências visuais que qualquer stakeholder entende
---
🛠️ Tecnologias Utilizadas
Ferramenta	Uso
Postman	Criação e execução de requisições e testes
Newman	Execução de testes via linha de comando
htmlextra	Geração de relatórios HTML profissionais
Swagger UI	Leitura e validação de contratos de API
JavaScript	Scripts de teste (pm.test) e Pre-request Scripts
IA (ChatGPT / Postman AI)	Geração de massa de dados e apoio na criação de testes
---
👤 Autor
Desenvolvido durante formação prática em testes de API REST.
![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
---
> *"Qualidade não é um ato, é um hábito."* — Aristóteles
