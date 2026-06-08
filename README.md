# Sistema de Cadastro de Clientes

Aplicação desktop desenvolvida em Python utilizando a biblioteca CustomTkinter para criar uma interface gráfica moderna e intuitiva. O sistema permite gerenciar perfis de usuários, configurar preferências e visualizar um painel de controle com simulação de carregamento.

---

## ✨ Funcionalidades

### 👤 Perfil do Usuário

- Cadastro de nome do usuário
- Seleção de nível de acesso:
  - Básico
  - Administrador
- Configuração de recebimento de notificações
- Atualização dinâmica das informações na barra lateral

### ⚙️ Preferências

- Seleção de idioma:
  - Português
  - Inglês
  - Espanhol
- Controle de volume por slider
- Atualização em tempo real do valor selecionado

### 📊 Dashboard

- Simulação de carregamento do sistema
- Barra de progresso animada
- Navegação rápida entre abas

### 🎨 Interface

- Tema moderno com CustomTkinter
- Alternância entre modo claro e escuro
- Layout responsivo
- Navegação intuitiva por abas

---

## 🚀 Tecnologias Utilizadas

- Python 3.14+
- CustomTkinter 5.2.2+
- UV (Gerenciador de pacotes e ambientes Python)

---

## 📋 Pré-requisitos

Antes de iniciar, certifique-se de ter instalado:

- Python 3.14 ou superior
- Git
- UV (opcional, recomendado)

### Instalando o UV

#### Windows

```bash
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

#### Linux e macOS

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

Verifique a instalação:

```bash
uv --version
```

---

# 📦 Instalação usando UV (Recomendado)

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/estudo-tkinter.git
cd estudo-tkinter
```

### 2. Sincronize as dependências

```bash
uv sync
```

O UV criará automaticamente um ambiente virtual e instalará todas as dependências definidas no arquivo `pyproject.toml`.

### 3. Execute a aplicação

```bash
uv run python app.py
```

---

# 📦 Instalação usando Pip

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/estudo-tkinter.git
cd estudo-tkinter
```

### 2. Crie um ambiente virtual

```bash
python -m venv .venv
```

### 3. Ative o ambiente virtual

#### Windows

```bash
.venv\Scripts\activate
```

#### Linux/macOS

```bash
source .venv/bin/activate
```

### 4. Instale as dependências

```bash
pip install customtkinter
```

### 5. Execute a aplicação

```bash
python app.py
```

---

## 📁 Estrutura do Projeto

```text
estudo-tkinter/
│
├── app.py
├── pyproject.toml
├── README.md
└── .venv/
```

---

## 🖥️ Funcionalidades das Telas

### Barra Lateral

- Exibição do nome do aplicativo
- Informações do usuário
- Botão de acesso rápido ao Dashboard
- Controle do modo escuro

### Aba Perfil

- Campo para inserção do nome
- Seleção de nível de usuário
- Configuração de notificações
- Botão para salvar perfil

### Aba Preferências

- Seleção de idioma
- Ajuste de volume

### Aba Dashboard

- Simulação de carregamento do sistema
- Barra de progresso interativa

---

## 🔧 Melhorias Futuras

- Banco de dados SQLite
- Cadastro completo de clientes
- Sistema de login
- Relatórios em PDF
- Exportação para Excel
- Integração com APIs
- Persistência das configurações do usuário

---

## 📚 Objetivo do Projeto

Este projeto foi desenvolvido para fins educacionais com foco em:

- Programação Orientada a Objetos (POO)
- Desenvolvimento Desktop com Python
- Construção de Interfaces Gráficas
- Manipulação de Eventos
- Organização de Projetos Python
- Utilização do CustomTkinter
- Gerenciamento de dependências com UV

---

## 👨‍💻 Autor

Robert Melo

🔗 LinkedIn: https://www.linkedin.com/in/robertdemelo/  
🐍 Python | IA | Machine Learning | LangChain | Data Science

---

## 📄 Licença

Este projeto está licenciado sob a licença MIT.

Sinta-se à vontade para estudar, modificar e compartilhar.