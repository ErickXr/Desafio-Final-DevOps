# 🚀 Desafio Final DevOps – GitHub Actions Workflow
📚 Projeto acadêmico desenvolvido na faculdade Impacta, 3º semestre de ADS
💻 API simples em Flask com CI/CD via GitHub Actions

Este projeto demonstra integração contínua, automação de testes e deploy, seguindo boas práticas de DevOps.

👀 Demonstração Visual

GIF da API em funcionamento (exemplo de login e rota protegida):

📄 Screenshot do Swagger UI:

Dica: substitua os links acima pelos GIFs e prints reais da sua aplicação.

📌 Status do Projeto
Componentes	Status
Build	

Testes (pytest)	✔️ Automatizado via Actions
Dockerização	✔️ Containerização com Docker Compose
Deploy (opcional)	❗ Configurar ambiente de produção
📦 Tecnologias Utilizadas

🐍 Python

🧪 Flask (API Web)

⚙️ GitHub Actions (CI/CD)

🐳 Docker & Docker Compose

🔐 JWT Authentication

📄 Swagger UI

🛠️ Instalação e Uso
1) Clone o repositório
git clone https://github.com/ErickXr/desafio-final-devops.git
cd desafio-final-devops
2) Configure o ambiente

Requisitos:

Docker e Docker Compose

Python 3.10+ (se não usar Docker)

3) Build com Docker
docker build -t desafio-final-devops .
4) Rodar com Docker Compose
docker-compose up
5) A API estará disponível em:
http://localhost:1313
🚀 Endpoints Principais
Método	Endpoint	Descrição
GET	/	Status da API
GET	/items	Lista de itens estáticos
POST	/login	Realiza login e retorna JWT
GET (protegido)	/protected	Rota segura (precisa token)
🧪 Testes Automatizados
pip install -r requirements.txt
pytest

Testes automatizados via GitHub Actions garantem que o código funcione em cada push ou pull request.

🛠️ GitHub Actions (CI / Workflow)

Workflows automáticos configurados em .github/workflows/:

✅ Build da aplicação

✅ Testes automatizados

✅ Validação de código

Gatilho: push ou pull request.

📌 Próximos Passos / Melhorias

Deploy automático em ambiente de produção

Testes mais completos e cobertura de código

Documentação Swagger detalhada

Variáveis de ambiente para JWT e configuração

🧑‍💻 Contribuição

Fork o repositório

Crie uma nova branch: git checkout -b feature/nome-da-feature

Commit suas alterações

Abra um Pull Request

📄 Licença

MIT License – veja o arquivo LICENSE.
