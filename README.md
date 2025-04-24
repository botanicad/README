# 🌿 Botanica

**Botanica** é uma aplicação web para cadastro e visualização de espécies de plantas. O projeto conta com um modal estilizado com Tailwind CSS e um backend robusto desenvolvido em Java 21 com Spring Boot, utilizando banco de dados em nuvem via [Aiven](https://aiven.io/).

---

## ✨ Funcionalidades

- Adição de novas espécies com imagem, nome popular e científico, história, irrigação, iluminação e bioma.
- Interface moderna baseada em design com fonte Poppins e paleta #344E41.
- Upload e preview de imagem no modal.
- Integração com API REST em Java.

---

## 🖼️ Frontend

### Tecnologias
- [Vite](https://vitejs.dev/)
- [React](https://react.dev/)
- [Tailwind CSS](https://tailwindcss.com/)
- Axios

### Destaques do Modal
- Tamanho fixo: `777x500px`
- Fonte do título: **Poppins**, tamanho `35px`, cor `#344E41`
- Área de imagem interativa com preview
- Inputs personalizados com `rounded`, `shadow`, `px-4 py-2`

### Comando para rodar localmente
```bash
npm install
npm run dev
```

---

## 🧠 Backend

### Tecnologias
- Java 21
- Spring Boot 3
- Maven
- Banco de Dados mysql (Aiven Cloud)
- Spring Data JPA
- Spring Web

### Endpoints principais
| Método | Endpoint         | Descrição                  |
|--------|------------------|----------------------------|
| POST   | `/flora`  | Salvar nova planta         |
| GET    | `/flora`         | Listar todas as plantas    |
| GET    | `/flora/{id}`    | Buscar planta por ID       |
| DELETE | `/flora/{id}`    | Deletar planta por ID      |
| PUT    | `/flora/{id}`    | Atualizar planta existente |

```

### Conexão com banco Aiven
```properties
spring.datasource.url=jdbc:mysql://<seu-host-aiven>:<porta>/<database>
spring.datasource.username=<usuario>
spring.datasource.password=<senha>
spring.jpa.hibernate.ddl-auto=update
```

---

## 🚀 Deploy (em breve)
- Frontend: Vercel / Netlify / Azure
- Backend: Azure

---

## 🧑‍💻 Desenvolvedor
Desenvolvido por Leticia e Nicolas com 💚
