# **🚀 Sessão 1: O Passo a Passo da Criação e Envio**
O GitHub é uma plataforma usada para guardar, organizar e compartilhar projetos. Ele também permite acompanhar as alterações feitas no código ao longo do tempo.

## *O início*

Para começar, entro no GitHub e clico em New repository. Depois escolho o nome do projeto, faço uma breve descrição e defino se o repositório será público ou privado. Também posso adicionar um README e um .gitignore.

## *A conexão*

Depois de criar o repositório, abro a pasta do projeto no computador e inicio o Git:

git init
Depois conecto a pasta ao repositório do GitHub:

git remote add origin URL_DO_REPOSITORIO
Assim, o Git sabe para qual repositório enviar os arquivos.

## *O primeiro envio*

Para enviar os arquivos, sigo basicamente três etapas:

git add .
git commit -m "Primeiro commit"
git push -u origin main
O add seleciona os arquivos, o commit registra a alteração e o push envia tudo para o GitHub.



# **📖 Sessão 2: A Anatomia do README Perfeito**
### O **README.md** serve para explicar o projeto e ajudar outras pessoas a entenderem como ele funciona. Ele pode ser usado por outros programadores, professores ou qualquer pessoa que acessar o repositório.

Um README pode ter:

*Título:* nome do projeto.
*Descrição:* explica o que o projeto faz.
*Tecnologias:* mostra quais linguagens e ferramentas foram usadas.
*Instalação/execução:* explica como abrir ou executar o projeto.
*Status:* mostra se o projeto está em desenvolvimento ou finalizado.
*Como usar:* explica como utilizar o projeto.
*Licença:* informa as regras de uso do projeto.

## *Markdown*
O Markdown facilita a criação do README porque permite organizar o texto de forma simples, usando títulos, negrito, itálico, listas, links e códigos. Assim, o arquivo fica mais fácil de ler e entender.



# **🔄 Sessão 3: O Mapa das Atualizações (Commits e Pushes)**
### Existem diferentes maneiras de atualizar um projeto no GitHub.

## *GitHub Online*

É possível editar arquivos diretamente pelo navegador. É uma opção prática para pequenas alterações, como corrigir textos ou mudar alguma informação. Porém, não é tão prática para projetos grandes.

## *it via Linha de Comando (Terminal)*

Pelo terminal, o processo mais comum é:

git add .
git commit -m "Descrição da alteração"
git push
Essa é uma das formas mais tradicionais porque permite controlar as alterações diretamente pelos comandos do Git.

## *IDEs (Ex: VS Code)*

No VS Code, podemos usar a área de Controle do Código-Fonte para visualizar os arquivos modificados, fazer o commit e enviar as alterações para o GitHub. É uma opção mais visual e prática para quem está começando.

## *GitHub Desktop*

O GitHub Desktop também possui uma interface gráfica. Ele permite visualizar as alterações, criar commits e fazer o push sem precisar digitar os comandos no terminal.

## *A Filosofia da Atualização*

É melhor fazer atualizações pequenas e frequentes do que deixar tudo para o final. Assim, cada mudança fica registrada em um commit e fica mais fácil acompanhar o desenvolvimento, encontrar erros e voltar para uma versão anterior se for necessário.

Por isso, o ciclo básico é:

### Criar → Alterar → Commitar → Enviar → Continuar atualizando.
