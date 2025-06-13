# TaskMasterApp ✅  

## 📌 Visão Geral  
O **TaskMasterApp** é um aplicativo móvel de **gerenciamento de tarefas**, integrado com uma API back-end robusta. O sistema permite ao usuário **criar, editar, listar e excluir tarefas**, definir status e receber lembretes. O projeto foi concebido para oferecer uma experiência completa de desenvolvimento, utilizando boas práticas como **testes automatizados**, **segurança com JWT** e **otimizações de desempenho**.  

---

## 🔥 Principais Funcionalidades  
✔️ **Gestão de Tarefas:** Criar, editar, listar e excluir tarefas facilmente.  
✔️ **Organização por Status:** Classificação de tarefas em "pendente", "em andamento" e "concluída".  
✔️ **Autenticação Segura:** Proteção de acesso com **JWT**.  
✔️ **Notificações Inteligentes:** Lembretes para tarefas próximas do prazo.  
✔️ **Otimizações de Performance:** **Caching de requisições** para respostas rápidas.  
✔️ **Testes Automatizados:** **Flutter Test, JUnit e Mockito** para garantir estabilidade.  

---

## 🚀 Tecnologias Utilizadas  

### *📱 Front-end*  
- **Flutter** → Framework unificado para Web, Mobile e Desktop.  
- **Dart** → Linguagem otimizada para interfaces rápidas e fluidas.  

### *⚙ Back-end*  
- **Spring Boot (Java)** → API robusta e escalável.  
- **PostgreSQL** → Banco de dados seguro e otimizado.  

### *🔐 Segurança e Otimização*  
- **JWT** → Autenticação baseada em tokens.  
- **Caching de Requisições** → Otimização de consultas no banco de dados.  

### *🛠️ Testes e Performance*  
- **Flutter Test** → Testes automatizados no front-end.  
- **JUnit e Mockito** → Testes unitários e de integração no back-end.  

---

## 📂 Estrutura do Repositório  
```bash
📦 TaskMasterApp
 ├── 📂 frontend/       # Código do Flutter para Web/Mobile/Desktop
 │   ├── lib/          # Componentes principais
 │   ├── assets/       # Ícones e imagens
 │   ├── test/         # Testes unitários
 │   ├── pubspec.yaml  # Dependências do Flutter
 ├── 📂 backend/       # API em Spring Boot
 │   ├── src/          # Código principal
 │   ├── config/       # Configurações e autenticação JWT
 │   ├── services/     # Lógica do sistema
 │   ├── database/     # Scripts SQL para PostgreSQL
 │   ├── tests/        # Testes JUnit e Mockito
 ├── 📂 docs/          # Documentação do projeto
 ├── 📜 README.md      # Documento de apresentação do projeto
 ├── 📜 LICENSE        # Licença de código aberto
 ├── 📜 .gitignore     # Arquivos que devem ser ignorados no repositório
 ```  

---

## ✅ Checklist de Desenvolvimento  

- [ ] **Planejamento**  
  - [ ] Definir requisitos do aplicativo e API.  
  - [ ] Criar diagramas de fluxo e comunicação entre camadas.  
- [ ] **Configuração do Ambiente**  
  - [ ] Instalar e configurar Flutter e Spring Boot.  
  - [ ] Configurar banco de dados PostgreSQL.  
  - [ ] Implementar autenticação via JWT.  
- [ ] **Desenvolvimento do Front-end**  
  - [ ] Criar interface responsiva e interativa.  
  - [ ] Implementar notificações e lembretes.  
- [ ] **Desenvolvimento do Back-end**  
  - [ ] Desenvolver API REST para gerenciamento de tarefas.  
  - [ ] Implementar testes unitários e de integração.  
- [ ] **Otimizações e Segurança**  
  - [ ] Implementar caching para melhoria de performance.  
  - [ ] Proteger endpoints contra acessos não autorizados.  
- [ ] **Publicação e Deploy**  
  - [ ] Configurar CI/CD para deploy automatizado.  
  - [ ] Realizar testes finais de performance e segurança.  

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

### **2️⃣ Configurar Banco de Dados**  
```bash
psql -U seu-usuario -d taskmasterdb -f backend/database/init.sql
```

### **3️⃣ Executar o Back-end**  
```bash
cd backend
./mvnw spring-boot:run
```
(Ou `mvn spring-boot:run` se estiver usando Maven instalado)  

### **4️⃣ Executar o Front-end**  
```bash
cd frontend
flutter pub get
flutter run
```

Agora o **TaskMasterApp** está pronto para uso! 🚀  

---

## 🚀 Contribuições  

Quer colaborar com o **TaskMasterApp**? Qualquer melhoria é bem-vinda!  

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
6. **Aguarde revisão e sugestões! 🚀**  

🎯 Sugestões de contribuição:  
✔️ **Correção de bugs**  
✔️ **Melhorias na performance**  
✔️ **Novas funcionalidades (ex. integração com calendário)**  
✔️ **Refatoração do código**  
✔️ **Melhorias na interface e usabilidade**  

---

## 📄 Licença  

Este projeto está sob a licença MIT, permitindo colaboração aberta! 📝  

