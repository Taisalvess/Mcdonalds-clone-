# 🍔 McDonald's Clone - Sistema de Autoatendimento

🚀 **Projeto desenvolvido como uma réplica do site do McDonald's, focado em um sistema de autoatendimento para restaurantes.** Utilizei tecnologias modernas para criar uma experiência eficiente, intuitiva e escalável para os usuários.

## 🔥 Tecnologias Utilizadas

- **Front-end:** Next.js, React, TypeScript, Tailwind CSS
- **Back-end:** Node.js, Prisma
- **Banco de Dados:** PostgreSQL

## ✨ Funcionalidades

✅ Interface interativa para adicionar pedidos de hambúrguer 🍔
✅ Cálculo automático dos valores dos pedidos 💰
✅ Experiência intuitiva e otimizada para usuários 📱
✅ Código escalável e otimizado para desempenho 🚀

## 📸 Preview do Projeto

![Preview do Projeto](https://github.com/Taisalvess/Mcdonalds-clone-/blob/main/ProjetoMcdonalds.jpg)

## 📂 Como Executar o Projeto

### 🔧 Pré-requisitos

Certifique-se de ter instalado em sua máquina:
- [Node.js](https://nodejs.org/)
- [PostgreSQL](https://www.postgresql.org/)
- Gerenciador de pacotes (NPM ou Yarn)

### 🚀 Instalação e Execução

1. **Clone este repositório**
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. **Acesse a pasta do projeto**
   ```sh
   cd nome-do-projeto
   ```
3. **Instale as dependências**
   ```sh
   npm install  # ou yarn install
   ```
4. **Configure o banco de dados**
   - Crie um arquivo `.env` com as credenciais do seu banco PostgreSQL
   ```env
   DATABASE_URL="postgresql://usuario:senha@localhost:5432/nome_do_banco"
   ```
   - Execute as migrações do Prisma
   ```sh
   npx prisma migrate dev --name init
   ```
5. **Inicie o servidor**
   ```sh
   npm run dev  # ou yarn dev
   ```

O projeto estará disponível em `http://localhost:3000` 🚀

## 🙌 Agradecimentos

Agradecimento especial à **Full Stack Club** por esse evento incrível e pela oportunidade de aprendizado!

