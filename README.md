# Conceitos Básicos de GitHub

## O que é GitHub?

GitHub é uma plataforma de hospedagem de código para controle de versão e colaboração. Ele permite que você e outras pessoas trabalhem juntos em projetos de qualquer lugar.

Neste trabalho, iremos apresentar alguns conceitos básicos como a criação de repositórios, branches, commits e pull Requests.

## Etapa 1. Criar um Repositório

Um repositório geralmente é usado para organizar um único projeto. Os repositórios podem conter pastas e arquivos, imagens, vídeos, planilhas e conjuntos de dados - qualquer coisa que seu projeto precisar. Recomendamos incluir um README ou um arquivo com informações sobre seu projeto. O GitHub facilita a adição de um ao mesmo tempo que você cria seu novo repositório. Ele também oferece outras opções comuns, como um arquivo de licença.

Seu repositório pode ser um lugar onde você armazena ideias, recursos ou até mesmo compartilha e discute coisas com outras pessoas.

### Para criar um novo repositório

1. No canto superior direito, próximo ao seu ícone de identidade, clique e selecione Novo repositório.
2. Nomeie seu repositório.
3. Escreva uma breve descrição.
4. Selecione a opção "Initialize this repository with: Add a README file".

Obs: Se quiser usar direto no terminal, basta colocar na linha de comando git init para iniciar um novo repositório.

## Etapa 2. Criar uma Branch
Branch é a maneira de trabalhar em diferentes versões de um repositório ao mesmo tempo.

Por padrão, seu repositório tem um branch chamado "main" que é considerado o branch definitivo. Usamos branches para experimentar e fazer edições antes de enviá-los à main.

Quando você cria um branch fora do branch principal, você está fazendo uma cópia da main como ele era naquele momento. Se outra pessoa fez alterações na branch principal enquanto você estava trabalhando em seu branch, você poderia obter essas atualizações.

### Criando uma nova Branch

1. Vá para o seu novo repositório criado.
2. Clique em branch > main.
3. Coloque um nome para o novo branch, readme-edits por exemplo.

![Nova Branch](https://github.com/mariaeugeniamartins/mariaeugeniamartins.github.io/blob/main/readme-edits.gif)

Obs: Se quiser usar direto no terminal, basta colocar na linha de comando:
1. git branch [nome da branch]
2. Para trocar de branch, basta colocar na linha de comando: git checkout [branch de destino]

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

Obs: Se quiser usar direto no terminal, basta colocar na linha de comando:
1. Use o comando: git add [arquivos a serem adicionados ao commit]
2. Use o comando: git commit -m [mensagem]

## Pull
É uma atualização do repositório local. É feito um merge do repositório online com o local para que os conflitos sejam resolvidos e seja possível enviar o código (sem conflitos) para o repositório online por meio de um push.

1. Dentro do repositório use o comando: git pull [nome do repositório remoto]
Obs: No caso do github, o nome do repositório remoto costuma ser origin.

## Push
Envia (ou tenta enviar) o código para o repositório online.

1. Dentro do repositório.
2. Use o comando: git push [node do repositório remoto].

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

## Etapa 5. Merge Pull Request
Nesta etapa final, é hora de reunir suas alterações - mesclando seu readme-editsbranch com o mainbranch.

1. Clique no botão verde Merge pull Request para mesclar as alterações em main.
2. Clique em Confirmar Merge.
3. Vá em frente e exclua o branch, uma vez que suas alterações foram incorporadas, com o botão Excluir Branch na caixa roxa.

Obs: Se quiser usar direto no terminal, basta colocar na linha de comando:
1. Vá para a branch de destino (exemplo: git checkout master).
2. Use o comando: git merge [branch a unir]

## Criando um site com GitHub Pages
### Passo a passo

1. Mudar o nome do repositório (caso já exista) para <nome do usuário>.github.io.
2. Caso não tenha repositório, criar um com as características acima.
3. Clicar em settings e escolher um tema para o site.
4. Após isso, basta você colocar o seu conteúdo no README.md do repositório.

## Extras

Para colocar gifs, imagens e vídeos, basta ver o vídeo abaixo.

[![](http://img.youtube.com/vi/T70t3mDiwvg/0.jpg)](http://www.youtube.com/watch?v=T70t3mDiwvg "Vídeo - Ensinando a colocar imagem, gif, etc no GitHub")

Para criar um site com GitHub Pages: 

[![](http://img.youtube.com/vi/5B4bHSiOOO8/0.jpg)](http://www.youtube.com/watch?v=5B4bHSiOOO8 "Vídeo - Ensinando a criar um site no GitHub com GitHub Pages")
