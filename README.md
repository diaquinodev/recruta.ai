# **Recruta.ai**

Plataforma de recrutamento online que permite aos candidatos se cadastrarem, fazerem login e acessarem uma área restrita com informações personalizadas sobre vagas, entrevistas, tarefas e feedbacks.

## **Tecnologias Utilizadas**

- **Frontend**:  
  - HTML5, CSS3  
  - JavaScript (ES6+)
  - Google Fonts e FontAwesome para tipografia e ícones.

- **Backend**:  
  - **Node.js** com **Express.js**
  - **Sequelize ORM** para gerenciamento do banco de dados
  - **SQLite** ou **PostgreSQL**
  - **bcryptjs** para hash de senhas
  - **jsonwebtoken (JWT)** para autenticação de usuários

- **Ferramentas de Log**:  
  - **Morgan** para logging de requisições HTTP  
  - **Winston** para gerenciamento e armazenamento de logs

---

## **Instalação e Execução**

### **Pré-requisitos**

Antes de iniciar o projeto, certifique-se de ter o **Node.js** e o **npm** instalados em seu ambiente de desenvolvimento. Você pode verificar as versões instaladas executando:

```bash
node -v
npm -v

Passo a Passo
Clone o repositório
bash
Copiar código
git clone https://github.com/seu-usuario/recruta-ai.git
Navegue até a pasta do projeto
bash
Copiar código
cd recruta-ai/server
Instale as dependências do backend
bash
Copiar código
npm install
Configuração do Banco de Dados

O projeto utiliza o Sequelize com SQLite (padrão), mas você pode configurar o PostgreSQL ou outro banco de dados conforme necessário.
Para SQLite, o banco de dados será gerado automaticamente.
Para PostgreSQL, edite o arquivo .env e configure as variáveis de ambiente como DB_HOST, DB_USER, DB_PASS, DB_NAME.
Sincronize o Banco de Dados

Após configurar o banco de dados, sincronize-o executando o servidor. Isso criará automaticamente as tabelas necessárias.

bash
Copiar código
npm start
Inicie o Servidor

Inicie o servidor de backend na porta padrão 3000:

bash
Copiar código
npm start
Você deverá ver a mensagem:

yaml
Copiar código
Servidor rodando na porta 3000
Banco de dados sincronizado
Acesse o Frontend
Para rodar o frontend localmente, instale o http-server:

bash
Copiar código
npm install -g http-server
Navegue até a pasta do frontend e inicie o servidor:

bash
Copiar código
http-server ./recrutaai-frontend -p 8080
Acesse o frontend no navegador através de:
http://localhost:8080
