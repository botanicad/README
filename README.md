
# 🌿 Botanica - Plataforma Completa 🌿

Bem-vindo ao **Botanica**!  
Uma plataforma dedicada à gestão, exibição e apreciação do mundo das plantas, combinando um poderoso **Backend** em **Spring Boot** e um **Frontend** moderno em **React**. 🌱✨

---

## 🛠️ Tecnologias Utilizadas 💻

### Backend
- **Spring Boot** 🧰 — Framework para construção de APIs.
- **Java 21** ☕ — Linguagem de programação principal.
- **Spring Data JPA** 📊 — Persistência de dados com Hibernate.
- **Spring Validation** ✅ — Validação de dados.
- **MySQL** 🗄️ — Banco de dados relacional.
- **Maven** ⚙️ — Gerenciamento de dependências.
- **Spring Boot DevTools** 🔄 — Ferramentas de desenvolvimento.

### Frontend
- **React** 🧩 — Biblioteca para criação de interfaces.
- **Vite** 🚀 — Build tool ultrarrápida.
- **Tailwind CSS** 🌸 — Framework de estilização.
- **Axios** 🌐 — Comunicação com o Backend.
- **Font Awesome** 🎨 — Ícones.
- **Poppins** 🖋️ — Fonte principal.

---

## ✨ Funcionalidades Principais ✨

- **Gestão de Plantas** 🌿: Criação, leitura, atualização e exclusão de espécies.
- **Persistência e Validação de Dados** 💾✅: MySQL + Spring Validation para consistência dos dados.
- **Interface Responsiva** 📱💻: Frontend adaptável a diferentes dispositivos.
- **Modal de Adição/Edição** ➕✏️: Cadastro e atualização fácil de plantas.
- **Integração Front + Back** 🔗: Comunicação fluida via APIs REST.
- **Segurança e Autenticação** 🔐 (Planejado): Controle de acesso de usuários.
- **Filtros de Pesquisa** 🔎 (Em breve): Busque plantas rapidamente.

---

## 🚀 Instalação e Execução 🛠️

### 1️⃣ Clone ambos os repositórios

```bash
# Clone o Backend
git clone https://github.com/botanicad/Botanica-BackEnd.git

# Clone o Frontend
git clone https://github.com/botanicad/Botanica-FrontEnd.git
```

### 2️⃣ Rodando o Backend

```bash
cd Botanica-BackEnd
mvn install
mvn spring-boot:run
```

A API estará disponível em: [http://localhost:8080](http://localhost:8080).

### 3️⃣ Rodando o Frontend

```bash
cd Botanica-FrontEnd
npm install
npm run dev
```

O Frontend estará disponível em: [http://localhost:5173](http://localhost:5173).

---

## 📁 Estrutura Geral do Projeto 🏗️

```plaintext
Botanica/
│
├── Botanica-BackEnd/         # Backend (Spring Boot)
│   ├── src/main/java/        # Código Java (controllers, services, models)
│   ├── src/main/resources/   # Configurações
│   ├── pom.xml               # Dependências Maven
│
├── Botanica-FrontEnd/        # Frontend (React + Vite)
│   ├── public/               # Arquivos públicos
│   ├── src/                  # Código fonte React
│   ├── package.json          # Dependências NPM
│   ├── vite.config.js        # Configurações Vite
```

---

## 🧑‍💻 Como Contribuir 🤝

Quer nos ajudar a fazer o Botanica crescer? Siga os passos:

1. Faça um fork dos repositórios.
2. Clone seu fork.
3. Crie uma branch para suas alterações.
4. Faça commits claros e objetivos.
5. Abra um Pull Request.

---

**Obrigado por fazer parte do Botanica! 🌱**

#JuntosPelasPlantas 🌳
