# 🚀 PromptBuilder

PromptBuilder é uma ferramenta inovadora para facilitar a criação e organização de prompts para Inteligência Artificial! 🤖✨

## ✨ Principais Funcionalidades

- 🗂️ **Gestão de Templates:**
  - Ao iniciar, o projeto verifica e cria automaticamente o diretório `.agenti` em seu diretório pessoal (`<user.home>`), se necessário.
  - Lê todos os templates `.md` do diretório `<user.home>/.agenti/templates`.

- 🖥️ **Interface Web Intuitiva:**
  - A página principal (`index.html`) exibe à esquerda uma coluna com botões, cada um representando um template encontrado.
  - Apenas arquivos `.md` são considerados templates.

- 📝 **Edição Dinâmica de Prompts:**
  - Área de texto (textarea) para compor e editar seu prompt.
  - Botão **Adicionar** ➕: adiciona o conteúdo do textarea ao final do prompt atual.
  - Botão **Mostrar** 👁️: exibe o prompt atual em um modal (alert/bootstrap).

- 📚 **Templates Aninhados:**
  - Ao clicar em um botão de template, o conteúdo do arquivo `.md` é carregado como novos botões abaixo do textarea.
  - Clicando nesses novos botões, o conteúdo do template é adicionado ao textarea.

- 💾 **Edição e Salvamento em Modal:**
  - Ao exibir o prompt no modal, qualquer edição feita no textarea do modal pode ser salva no prompt atual ao clicar em **Salvar** (botão visível apenas após edição).

## 🛠️ Como Usar

1. Clone o repositório e execute o projeto Java (Spring Boot).
2. Acesse a interface web em `http://localhost:8080`.
3. Gerencie seus templates em `<user.home>/.agenti/templates`.
4. Crie, edite e salve prompts de forma rápida e visual!

## 📦 Estrutura do Projeto

```
project-root/
├── src/
│   ├── main/java/io/github/akumosstl/agentic/
│   ├── resources/templates/index.html
│   └── ...
├── environment.bat
├── pom.xml
└── README.md
```

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests.

## 📄 Licença

Este projeto está sob a licença MIT.

---

Feito com 💡 por AkumoSTL
