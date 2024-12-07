# **E-commerce em Flask**  
[![Python](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)  
Um projeto de **e-commerce básico** desenvolvido com Flask, projetado para ser usado como base para sites de vendas online ou para estudos na área de desenvolvimento web.

---

## **📋 Funcionalidades**  
O sistema possui as seguintes funcionalidades:  
1. **Home Page:** Exibe uma lista de produtos cadastrados no sistema.  
2. **Visualização de Produto:** Página com detalhes do produto, incluindo descrição, preço e imagem.  
3. **Carrinho de Compras:** Possibilidade de adicionar, visualizar e remover itens do carrinho.  
4. **Autenticação de Usuário:** Registro, login e logout com autenticação baseada em Flask-Login.  
5. **Banco de Dados:** Armazena informações de produtos, usuários e carrinhos usando SQLite.  

---

## **🛠️ Tecnologias Utilizadas**  
- **Linguagem:** Python  
- **Framework Web:** Flask  
- **Banco de Dados:** SQLite (pode ser substituído por PostgreSQL ou MySQL)  
- **Frontend:** HTML, CSS, Bootstrap  
- **Gerenciamento de Sessão:** Flask-Login  
- **Testes:** Pytest  

---

## **📂 Estrutura do Projeto**  

```bash
ecommerce/
├── app/
│ ├── __init__.py # Configuração da aplicação Flask
│ ├── models.py # Modelos do banco de dados
│ ├── routes.py # Rotas da aplicação
│ ├── templates/ # Templates HTML
│ └── static/ # Arquivos estáticos (CSS, JS, imagens)
├── migrations/ # Arquivos de migração do banco de dados
├── tests/ # Testes automatizados
├── config.py # Configurações da aplicação
├── requirements.txt # Lista de dependências do projeto
├── run.py # Arquivo principal para rodar a aplicação
└── README.md # Documentação do projeto


---

🎨 Capturas de Tela

1. Página Inicial

Exibe todos os produtos disponíveis no sistema.
(Adicione uma captura de tela aqui)

2. Detalhes do Produto

Mostra informações detalhadas sobre um produto.
(Adicione uma captura de tela aqui)

3. Carrinho de Compras

Lista os itens adicionados ao carrinho, com opções para ajustar quantidades.
(Adicione uma captura de tela aqui)


---

🚀 Como Executar Localmente

Pré-requisitos:

Python 3.8 ou superior instalado.

Pip (gerenciador de pacotes Python).


Passo a Passo:

1. Clone o repositório:

git clone https://github.com/seu-usuario/ecommerce-flask.git
cd ecommerce-flask


2. Crie um ambiente virtual e ative-o:

python -m venv venv
source venv/bin/activate # Linux/macOS
venv\Scripts\activate # Windows


3. Instale as dependências:

pip install -r requirements.txt


4. Configure o banco de dados:

flask db init
flask db migrate -m "Inicializando o banco de dados"
flask db upgrade


5. Execute a aplicação:

python run.py


6. Abra o navegador e acesse:

http://127.0.0.1:5000




---

🧪 Testes Automatizados

Este projeto utiliza Pytest para os testes. Para executar os testes, use:

pytest

Os testes incluem:

Testes de rotas principais (home, produto, carrinho).

Validação de modelos de dados.

Cobertura de funcionalidades básicas.



---

🌐 Como Fazer o Deploy

Opções Recomendadas:

1. Heroku:

Configure um arquivo Procfile para execução em ambiente de produção.

Suba o projeto com:

git push heroku main



2. Render:

Suba o repositório diretamente pela interface do Render.



3. Docker:

Configure um Dockerfile para criar a imagem do projeto.

Execute o contêiner com:

docker build -t ecommerce .
docker run -p 5000:5000 ecommerce





---

📜 Licença

Este projeto está licenciado sob a MIT License. Sinta-se livre para utilizá-lo, modificá-lo e distribuí-lo.


---

👨‍💻 Contribuições

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do repositório.


2. Crie um branch para suas mudanças:

git checkout -b minha-feature


3. Envie um pull request após testar.




---

📞 Contato

Caso tenha dúvidas ou sugestões, entre em contato:

Email: eduardo.aragao.chaves@gmail.com

GitHub: eduprogramadatas



---

Aproveitem bem o conteúdo!
