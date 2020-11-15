# Conceitos Básicos de GitHub

## O que é GitHub?

GitHub é uma plataforma de hospedagem de código para controle de versão e colaboração. Ele permite que você e outras pessoas trabalhem juntos em projetos de qualquer lugar.

Este tutorial ensina os fundamentos do GitHub, como repositórios , branches , commits e pull Requests . Você criará seu próprio repositório Hello World e aprenderá o fluxo de trabalho Pull Request do GitHub, uma forma popular de criar e revisar código.

## Etapa 1. Criar um Repositório

Um repositório geralmente é usado para organizar um único projeto. Os repositórios podem conter pastas e arquivos, imagens, vídeos, planilhas e conjuntos de dados - qualquer coisa que seu projeto precisar. Recomendamos incluir um README ou um arquivo com informações sobre seu projeto. O GitHub facilita a adição de um ao mesmo tempo que você cria seu novo repositório. Ele também oferece outras opções comuns, como um arquivo de licença.

Seu hello-worldrepositório pode ser um lugar onde você armazena ideias, recursos ou até mesmo compartilha e discute coisas com outras pessoas.

### Para criar um novo repositório

1. No canto superior direito, próximo ao seu avatar ou ícone de identidade, clique em e selecione Novo repositório .
2. Nomeie seu repositório hello-world.
3. Escreva uma breve descrição.
4. Selecione Inicializar este repositório com um README .

## Etapa 2. Criar uma Branch
Ramificação é a maneira de trabalhar em diferentes versões de um repositório ao mesmo tempo.

Por padrão, seu repositório tem um branch chamado mainque é considerado o branch definitivo. Usamos branches para experimentar e fazer edições antes de enviá-los main.

Quando você cria um branch fora do mainbranch, você está fazendo uma cópia, ou instantâneo, de maincomo ele era naquele momento. Se outra pessoa fez alterações no mainbranch enquanto você estava trabalhando em seu branch, você poderia obter essas atualizações.

### To create a new Branch

1. Go to your new repository hello-world.
2. Click the drop down at the top of the file list that says branch: main.
3. Type a branch name, readme-edits, into the new branch text box.
4. Select the blue Create branch box or hit “Enter” on your keyboard.

## Step 3. Make and commit changes

Bravo! Now, you’re on the code view for your readme-edits branch, which is a copy of main. Let’s make some edits.

On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes, so other contributors can understand what you’ve done and why.

### Make and commit changes

1. Click the README.md file.
2. Click the  pencil icon in the upper right corner of the file view to edit.
3. In the editor, write a bit about yourself.
4. Write a commit message that describes your changes.
5. Click Commit changes button.

These changes will be made to just the README file on your readme-edits branch, so now this branch contains content that’s different from main.

## Step 4. Open a Pull Request
Nice edits! Now that you have changes in a branch off of main, you can open a pull request.

Pull Requests are the heart of collaboration on GitHub. When you open a pull request, you’re proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in green and red.

As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.

### Abra uma solicitação pull para alterações no README
1. Clique no  Pedido Pull guia, em seguida, a partir da página de solicitação de recebimento, clique no verde Novo pedido puxar botão.
2. Na caixa Comparações de exemplo , selecione o ramo que você fez readme-edits,, para comparar com main(o original).
3. Examine suas mudanças nos diffs na página Compare, certifique-se de que são o que você deseja enviar.
4. Quando estiver satisfeito com as alterações que deseja enviar, clique no grande botão verde Criar solicitação pull .
5. Dê um título à sua solicitação de pull e escreva uma breve descrição de suas alterações.

Quando terminar sua mensagem, clique em Criar solicitação de pull !

## Etapa 5. Mesclar sua solicitação pull
Nesta etapa final, é hora de reunir suas alterações - mesclando seu readme-editsbranch com o mainbranch.

1. Clique no botão verde Merge pull request para mesclar as alterações em main.
2. Clique em Confirmar mesclagem .
3. Vá em frente e exclua o branch, uma vez que suas alterações foram incorporadas, com o botão Excluir branch na caixa roxa.
