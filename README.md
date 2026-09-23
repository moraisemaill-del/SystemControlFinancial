# 💰 Sistema de Controle Financeiro

> **Organização financeira simples para uma rotina mais tranquila.**

## 📌 Sobre o Projeto

O **Sistema de Controle Financeiro** é uma aplicação desenvolvida pela **Morais Dev e Tech** com o objetivo de auxiliar pessoas no controle e na organização de suas finanças pessoais.

Diante do imediatismo presente de forma marcante no século XXI e de uma rotina cada vez mais dinâmica, muitas pessoas encontram dificuldades para acompanhar suas receitas, despesas e demais movimentações financeiras.

Pensando nessa necessidade, o sistema foi desenvolvido para oferecer uma forma **simples, rápida e prática** de realizar o controle financeiro no dia a dia.

A proposta é utilizar a tecnologia como uma ferramenta de apoio, permitindo que o usuário tenha maior clareza sobre sua situação financeira sem precisar dedicar muito tempo ao processo de organização.

---

## 🎯 Objetivo

O principal objetivo do sistema é **facilitar o controle das finanças pessoais**, permitindo que o usuário registre e acompanhe suas movimentações financeiras de maneira organizada e intuitiva.

O sistema busca auxiliar o usuário a:

- 💵 Registrar suas receitas;
- 💸 Registrar suas despesas;
- 📊 Acompanhar suas movimentações;
- 💰 Visualizar seu saldo;
- 📅 Organizar suas finanças por períodos;
- 🔎 Consultar informações financeiras;
- 📈 Obter uma visão geral de sua situação financeira.

---

## 👥 Público-Alvo

O aplicativo é destinado principalmente a **pessoas que possuem uma rotina agitada e buscam uma maneira simples, rápida e prática de controlar suas finanças pessoais**.

Entre os possíveis usuários estão:

- 👨‍💼 Trabalhadores;
- 🎓 Estudantes;
- 👨‍👩‍👧‍👦 Famílias;
- 💻 Profissionais autônomos;
- 🧑‍💻 Freelancers;
- 💰 Pessoas que desejam organizar melhor seus gastos;
- 📱 Usuários que procuram uma ferramenta simples para acompanhar sua vida financeira.

O sistema não exige conhecimentos avançados de finanças. Sua proposta é ser **acessível e fácil de utilizar**, permitindo que diferentes perfis de usuários possam realizar seu controle financeiro.

---

## 💡 Problema

A rotina das pessoas está cada vez mais dinâmica. Trabalho, estudos, compromissos pessoais e outras responsabilidades fazem com que muitas vezes o controle financeiro seja deixado em segundo plano.

A falta de organização pode dificultar a visualização de quanto dinheiro entra, quanto é gasto e quanto permanece disponível.

Diante desse cenário, surge a necessidade de uma ferramenta que permita realizar esse acompanhamento de maneira **rápida, simples e organizada**.

---

## 💡 Solução

O **Sistema de Controle Financeiro** busca solucionar esse problema centralizando as informações financeiras do usuário em uma única aplicação.

Por meio do sistema, o usuário poderá registrar suas movimentações e acompanhar suas informações financeiras, tornando o processo de organização mais simples e acessível.

A ideia é que o usuário consiga realizar seu controle financeiro sem precisar utilizar planilhas complexas ou métodos manuais demorados.

---

## 🚀 Funcionalidades

### 💰 Controle Financeiro

- [ ] Cadastro de receitas;
- [ ] Cadastro de despesas;
- [ ] Edição de movimentações;
- [ ] Exclusão de movimentações;
- [ ] Consulta de movimentações;
- [ ] Controle de entradas e saídas;
- [ ] Cálculo automático do saldo.

### 📊 Dashboard

- [ ] Saldo atual;
- [ ] Total de receitas;
- [ ] Total de despesas;
- [ ] Resumo financeiro;
- [ ] Gráficos;
- [ ] Indicadores financeiros.

### 📅 Organização

- [ ] Filtro por período;
- [ ] Filtro por categoria;
- [ ] Histórico de movimentações;
- [ ] Organização mensal;
- [ ] Categorias financeiras.

### 👤 Usuário

- [ ] Cadastro;
- [ ] Login;
- [ ] Autenticação;
- [ ] Perfil do usuário;
- [ ] Controle de acesso.

---

## 🛠️ Tecnologias

As tecnologias utilizadas no projeto poderão ser atualizadas conforme o desenvolvimento da aplicação.

### Backend

- C#
- .NET
- ASP.NET Core
- Entity Framework Core

### Banco de Dados

- SQL Server

### Frontend

- HTML5
- CSS3
- JavaScript

### Ferramentas

- Git
- GitHub
- Visual Studio
- Visual Studio Code

---

## 🏗️ Estrutura do Projeto

```text
SistemaControleFinanceiro/
│
├── src/
│   ├── API/
│   ├── Application/
│   ├── Domain/
│   └── Infrastructure/
│
├── tests/
├── docs/
├── .gitignore
├── LICENSE.md
├── README.md
└── ...
```

---

## ⚙️ Como Executar

### 1. Clone o repositório

```bash
git clone URL_DO_REPOSITORIO
```

### 2. Acesse a pasta

```bash
cd SistemaControleFinanceiro
```

### 3. Configure o banco de dados

Configure a conexão com o banco de dados no arquivo de configuração da aplicação.

```json
{
  "ConnectionStrings": {
    "DefaultConnection": "SUA_STRING_DE_CONEXAO"
  }
}
```

> ⚠️ Nunca publique senhas ou credenciais reais no GitHub.

### 4. Execute as migrações

```bash
dotnet ef database update
```

### 5. Execute a aplicação

```bash
dotnet run
```

---

## 🔐 Segurança

O projeto busca aplicar boas práticas de desenvolvimento e segurança, incluindo:

- Autenticação;
- Controle de acesso;
- Validação de dados;
- Proteção de informações sensíveis;
- Integridade dos dados;
- Separação de responsabilidades.

---

## 🗺️ Roadmap

### Versão 1.0

- [ ] Estrutura inicial;
- [ ] Banco de dados;
- [ ] Cadastro de usuários;
- [ ] Cadastro de receitas;
- [ ] Cadastro de despesas;
- [ ] Controle de saldo;
- [ ] Dashboard;
- [ ] Histórico financeiro.

### Versões futuras

- [ ] Relatórios financeiros;
- [ ] Exportação para PDF;
- [ ] Exportação para Excel;
- [ ] Gráficos avançados;
- [ ] Notificações;
- [ ] Metas financeiras;
- [ ] Controle de contas;
- [ ] Aplicativo mobile;
- [ ] Melhorias de segurança.

---

## 📊 Benefícios Esperados

Com o desenvolvimento do sistema, espera-se proporcionar ao usuário:

- Maior organização financeira;
- Facilidade no acompanhamento de gastos;
- Economia de tempo;
- Visualização simplificada das informações;
- Maior praticidade no controle financeiro;
- Centralização das informações;
- Apoio à tomada de decisões financeiras pessoais.

---

## 📌 Status do Projeto

🚧 **Em desenvolvimento**

Novas funcionalidades e melhorias serão implementadas conforme a evolução do projeto.

---

## 👨‍💻 Desenvolvimento

### **Morais Dev e Tech**

> **Tecnologia para simplificar o seu dia a dia.**

---

## 📄 Licença

Este projeto é propriedade da **Morais Dev e Tech**.

O uso, cópia, modificação, distribuição ou comercialização do projeto está sujeito aos termos estabelecidos no arquivo [`LICENSE.md`](LICENSE.md).

© 2026 **Morais Dev e Tech**. Todos os direitos reservados.
