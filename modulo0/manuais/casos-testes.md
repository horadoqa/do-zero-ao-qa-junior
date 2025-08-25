# **Casos de teste** (ou *test cases*, em inglês).

São **documentos ou instruções que descrevem um cenário específico a ser testado em um sistema ou aplicação**, com o objetivo de verificar se ela está funcionando corretamente de acordo com os requisitos esperados.

### ✅ Em outras palavras:

Um **caso de teste** define **o que será testado**, **como será testado** e **qual o resultado esperado**.

---

### 🧩 Um caso de teste geralmente contém:

| Item                    | Descrição                                                                 |
| ----------------------- | ------------------------------------------------------------------------- |
| **ID do caso de teste** | Um identificador único (ex: TC-001)                                       |
| **Título/Nome**         | Descreve o que está sendo testado (ex: "Login com credenciais válidas")   |
| **Pré-condições**       | O que precisa estar pronto antes do teste (ex: "Usuário já cadastrado")   |
| **Passos**              | Etapas a serem seguidas (ex: "Acessar página de login, digitar email...") |
| **Dados de entrada**    | Informações usadas no teste (ex: email, senha)                            |
| **Resultado esperado**  | O que o sistema deve fazer (ex: "Usuário redirecionado para dashboard")   |
| **Resultado real**      | O que realmente aconteceu (preenchido após o teste)                       |
| **Status**              | Aprovado (Pass) ou Reprovado (Fail)                                       |

---

### 📌 Exemplo de caso de teste simples:

| Campo                  | Exemplo                                                                                   |
| ---------------------- | ----------------------------------------------------------------------------------------- |
| **ID**                 | TC-001                                                                                    |
| **Título**             | Testar login com dados válidos                                                            |
| **Pré-condição**       | Usuário com email válido está cadastrado                                                  |
| **Passos**             | 1. Acessar a página de login<br>2. Inserir email e senha válidos<br>3. Clicar em "Entrar" |
| **Dados de entrada**   | Email: `usuario@exemplo.com`<br>Senha: `Senha123`                                         |
| **Resultado esperado** | Usuário é redirecionado para a tela inicial                                               |
| **Resultado real**     | Usuário foi redirecionado corretamente                                                    |
| **Status**             | ✅ Aprovado                                                                                |

---

### 📎 Dica:

Casos de teste são muito usados em **testes manuais**, mas também servem como **base para testes automatizados**.
