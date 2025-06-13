# TaskMasterApp

## 📌 Visão Geral

**TaskMasterApp** é um aplicativo móvel de gerenciamento de tarefas que integra uma API back-end robusta. O sistema permite ao usuário criar, editar, listar e excluir tarefas, definir status e receber lembretes, simulando uma comunicação completa entre front-end e back-end. O projeto foi concebido para oferecer uma experiência completa de desenvolvimento, utilizando boas práticas de testes, segurança (autenticação via JWT) e otimizações de desempenho (caching e melhorias nas queries do banco de dados). A seguir, veja as principais funcionalidades que fazem o TaskMasterApp ser uma solução completa para gestão de tarefas.

---

## 🔥 Principais Funcionalidades
- ✔️ **Gerenciamento de Tarefas:** Permite criar, editar e excluir tarefas com facilidade.
- ✔️ **Organização por Status:** Categorize tarefas como "pendente", "em andamento" ou "concluída".
- ✔️ **Autenticação Segura:** Protege o acesso com autenticação JWT.
- ✔️ **Notificações:** Envia lembretes para manter o usuário produtivo.
- ✔️ **Otimização de Performance:** Usa caching para carregamento rápido.
- ✔️ **Testes Automatizados:** Verifica funcionalidade e estabilidade do código.

---

## 🚀 Tecnologias Utilizadas

### *🖥 Front-end*  
- *Flutter* → Framework unificado para Web, Mobile e Desktop.  
- *Dart* → Linguagem otimizada para interfaces rápidas e fluidas.  

### *⚙ Back-end*  
- *Spring Boot (Java)* → API robusta e escalável.  
- *PostgreSQL* → Banco de dados seguro e otimizado para grande volume de usuários.
  
### *🛠️ Testes*
  - *Front-end:* `flutter_test`
  - *Back-end:* JUnit e Mockito
- **Segurança:** Autenticação via JWT com implementação de medidas para CORS e proteção de endpoints
- **Otimizações:** Caching de requisições e otimização de queries no banco de dados

---

## 📂 Estrutura do Repositório  
```bash
📦 TaskMasterApp
 ├── 📂 frontend/       # Código do Flutter para Web/Mobile/Desktop
 ├── 📂 backend/        # API em Spring Boot e lógica do sistema
 ├── 📂 database/       # Scripts SQL e estrutura do PostgreSQL
 ├── 📂 docs/           # Documentação do projeto
 ├── 📂 assets/         # Logos, ícones e materiais gráficos
 ├── 📜 README.md       # Documento de apresentação do projeto
 ├── 📜 LICENSE         # Licença de código aberto
 ├── 📜 .gitignore      # Arquivos que devem ser ignorados no repositório
 ```

---

## ✅ Checklist de Desenvolvimento

Aqui está um roteiro estruturado para o desenvolvimento do projeto, garantindo que todas as etapas sejam cumpridas com eficiência.

- [ ] **Planejamento**  
  - [ ] Definir requisitos e funcionalidades do aplicativo  
  - [ ] Elaborar diagrama da comunicação entre front-end e back-end
- [ ] **Configuração do Ambiente**  
  - [ ] Instalar e configurar Flutter e suas dependências  
  - [ ] Configurar ambiente Java com Spring Boot  
  - [ ] Inicializar o banco de dados PostgreSQL  
  - [ ] Configurar o versionamento com Git
- [ ] **Desenvolvimento do Front-end**  
  - [ ] Criar a estrutura básica do aplicativo Flutter  
  - [ ] Implementar telas para criação, edição, listagem e exclusão de tarefas  
  - [ ] Integrar chamadas à API  
  - [ ] Desenvolver testes unitários com `flutter_test`
- [ ] **Desenvolvimento do Back-end**  
  - [ ] Configurar projeto Spring Boot  
  - [ ] Desenvolver a API REST para gerenciamento de tarefas  
  - [ ] Implementar autenticação via JWT  
  - [ ] Desenvolver testes unitários e de integração com JUnit e Mockito
- [ ] **Otimizações e Segurança**  
  - [ ] Implementar caching para melhoria de performance  
  - [ ] Otimizar queries e transações no banco de dados  
  - [ ] Configurar medidas de segurança (CORS, proteção de endpoints, etc.)
- [ ] **Integração e Testes Finais**  
  - [ ] Integrar front-end e back-end  
  - [ ] Realizar testes finais de performance e segurança  
  - [ ] Atualizar a documentação conforme necessário

---

## 🔧 Como Rodar o Projeto

### **Pré-requisitos**

Antes de iniciar, certifique-se de ter instalado:
- [Flutter](https://flutter.dev/docs/get-started/install)
- [Java JDK 17+](https://www.oracle.com/java/technologies/javase-downloads.html)
- [PostgreSQL](https://www.postgresql.org/download/)
- [Git](https://git-scm.com/downloads)

### **1️⃣ Clonar o Repositório**
```bash
git clone https://github.com/seu-usuario/TaskMasterApp.git
cd TaskMasterApp
```

### **2️⃣ Configurar o Back-end**
```bash
cd backend
./mvnw spring-boot:run
```
(Ou `mvn spring-boot:run` se estiver usando o Maven instalado)

### **3️⃣ Configurar o Banco de Dados**
```bash
psql -U seu-usuario -d taskmasterdb -f database/init.sql
```

### **4️⃣ Rodar o Front-end**
```bash
cd frontend
flutter pub get
flutter run
```

Agora você pode acessar o aplicativo e testar todas as funcionalidades! 🚀

---

## 🚀 Contribuições

Quer ajudar a tornar o **TaskMasterApp** ainda melhor? Qualquer contribuição é bem-vinda! ✨  

Siga o guia abaixo para colaborar com melhorias no projeto.

### 🔹 Como contribuir  

1. **Fork o repositório** para ter uma cópia no seu GitHub.  
2. **Crie uma nova branch** para suas melhorias:  
   ```bash
   git checkout -b minha-feature
   ```
3. **Implemente suas alterações**, seguindo as boas práticas do projeto.  
4. **Faça um commit das suas mudanças:**  
   ```bash
   git commit -m "feat: descrição da melhoria"
   ```
5. **Envie para o seu repositório e abra um Pull Request:**  
   ```bash
   git push origin minha-feature
   ```
6. **Descreva claramente** sua contribuição e aguarde a revisão! 🚀  

### 🎯 Algumas sugestões de contribuição: 
- ✔️ **Correção de bugs**
- ✔️ **Melhoria na performance**
- ✔️ **Adição de novas funcionalidades**
- ✔️ **Aprimoramento da documentação**
- ✔️ **Refatoração do código**  

---

## 📄 Licença

Este projeto está sob a licença MIT, permitindo o uso livre e melhorias colaborativas! 📝

