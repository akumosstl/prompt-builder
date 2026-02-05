### PromptBuilder

O projeto PromptBuilder é um projeto criado para auxiliar na criação, ou escrita, de prompts para IA.

#### Funcionalidades

- Ao iniciar o projeto ele verifica a existência de um diretório chamado ".agenti" em <user.home> 
caso não exista ele cria um.

- Ao iniciar ele também realiza a leitura do diretório: <user.home>/.agenti/templates.

- Ao iniciar a página web, arquivo index.html, o usuário verá a esquerda uma coluna com vários 
botões cada um com um label do mesmo valor referente ao nome de um template (somente arquivos .md são considerados template) encontrado no diretório de templates.

Em index.html ainda encontramos um textarea e os botões "Adicionar" e "Mostrar".

Adicionar: adiciona o conteúdo do textarea ao final do prompt atual.
Mostrar: exibe o prompt atual em um alert/bootstra modal.

Ao clicar em um dos botões de template, o conteúdo do arquivo .md referente ao template é carregado como novos botões 
que são exibidos abaixo do textarea e dos botões "Adicionar" e "Mostrar".

E ao se clicar em um desses novos botões, o conteúdo do arquivo .md referente ao template é adicionado ao textarea.

Quando clicado em "Mostrar", e o prompt atual está sendo exibido em um alert/bootstra modal, qualquer edição do usuário no textarea do modal 
deve ser refletida no prompt atual se o usuário clicar no botão "Salvar", que só se torna visível quando o usuário edita algo no conteúdo do 
textarea do modal..
