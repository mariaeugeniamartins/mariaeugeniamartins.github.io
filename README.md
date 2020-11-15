# Conceitos Básicos de GitHub

## O que é GitHub?

GitHub é uma plataforma de hospedagem de código para controle de versão e colaboração. Ele permite que você e outras pessoas trabalhem juntos em projetos de qualquer lugar.

Neste trabalho, iremos apresentar alguns conceitos básicos como a criação de repositórios, branches, commits e pull Requests.

## Etapa 1. Criar um Repositório

Um repositório geralmente é usado para organizar um único projeto. Os repositórios podem conter pastas e arquivos, imagens, vídeos, planilhas e conjuntos de dados - qualquer coisa que seu projeto precisar. Recomendamos incluir um README ou um arquivo com informações sobre seu projeto. O GitHub facilita a adição de um ao mesmo tempo que você cria seu novo repositório. Ele também oferece outras opções comuns, como um arquivo de licença.

Seu hello-world repositório pode ser um lugar onde você armazena ideias, recursos ou até mesmo compartilha e discute coisas com outras pessoas.

### Para criar um novo repositório

1. No canto superior direito, próximo ao seu avatar ou ícone de identidade, clique em e selecione Novo repositório .
2. Nomeie seu repositório hello-world.
3. Escreva uma breve descrição.
4. Selecione Inicializar este repositório com um README .

## Etapa 2. Criar uma Branch
Ramificação é a maneira de trabalhar em diferentes versões de um repositório ao mesmo tempo.

Por padrão, seu repositório tem um branch chamado mainque é considerado o branch definitivo. Usamos branches para experimentar e fazer edições antes de enviá-los main.

Quando você cria um branch fora do mainbranch, você está fazendo uma cópia, ou instantâneo, de maincomo ele era naquele momento. Se outra pessoa fez alterações no mainbranch enquanto você estava trabalhando em seu branch, você poderia obter essas atualizações.

### Criando uma nova Branch

1. Vá para o seu novo repositório criado.
2. Clique em branch > main.
3. Coloque um nome para o nomo branch, readme-edits por exemplo.

![Nova Branch](https://github.com/mariaeugeniamartins/mariaeugeniamartins.github.io/blob/main/readme-edits.gif)

## Etapa 3. Fazendo commits 

Agora com a branch feita, que é uma cópia do main, podemos fazer algumas edições.

No GitHub, as alterações salvas são chamadas de commits. Cada confirmação tem uma mensagem de confirmação associada, que é uma descrição que explica por que uma mudança específica foi feita. Mensagens de confirmação capturam o histórico de suas alterações, para que outros colaboradores possam entender o que você fez e por quê.


### Fazendo commits - Passo a passo

1. Clique no arquivo README.md.
2. Clique no ícone de canetinha para editar.
3. No editor, escreva algo.
4. Escreva uma mensagem de confirmação que descreva suas mudanças.
5. Clique no botão "commit changes".

Essas alterações serão feitas apenas no arquivo README em seu branch readme-edits, então agora este branch contém conteúdo diferente do main.

## Etapa 4. Pull Request

As solicitações pull são o principal objetivo da colaboração no GitHub. Quando você abre uma solicitação pull, está propondo suas alterações e solicitando que alguém analise e extraia sua contribuição e as mescle em seu branch. As solicitações pull mostram diffs, ou diferenças, do conteúdo de ambas as branches. As alterações, adições e subtrações são mostradas em verde e vermelho.

Assim que você fizer um commit, poderá abrir uma solicitação pull e iniciar uma discussão, mesmo antes de o código ser concluído.

### Abra uma solicitação pull para alterações no README
1. Clique no  Pedido Pull guia, em seguida, a partir da página de solicitação de recebimento, clique no verde Novo pedido puxar botão.
2. Na caixa Comparações de exemplo , selecione o ramo que você fez readme-edits,, para comparar com main(o original).
3. Examine suas mudanças nos diffs na página Compare, certifique-se de que são o que você deseja enviar.
4. Quando estiver satisfeito com as alterações que deseja enviar, clique no grande botão verde Criar solicitação pull .
5. Dê um título à sua solicitação de pull e escreva uma breve descrição de suas alterações.

Quando terminar sua mensagem, clique em Criar solicitação de pull!

## Etapa 5. Mesclar sua solicitação pull
Nesta etapa final, é hora de reunir suas alterações - mesclando seu readme-editsbranch com o mainbranch.

1. Clique no botão verde Merge pull request para mesclar as alterações em main.
2. Clique em Confirmar mesclagem .
3. Vá em frente e exclua o branch, uma vez que suas alterações foram incorporadas, com o botão Excluir branch na caixa roxa.

## Extras

Para colocar gifs, imagens e vídeos, basta ver o vídeo abaixo.

[![](http://img.youtube.com/vi/T70t3mDiwvg/0.jpg)](http://www.youtube.com/watch?v=T70t3mDiwvg "Vídeo - Ensinando a colocar imagem, gif, etc no GitHub")

Para criar um site com GitHub Pages: 

[![](http://img.youtube.com/vi/5B4bHSiOOO8/0.jpg)](http://www.youtube.com/watch?v=5B4bHSiOOO8 "Vídeo - Ensinando a criar um site no GitHub com GitHub Pages")
