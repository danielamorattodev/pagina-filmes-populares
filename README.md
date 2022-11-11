# :pushpin: Desafio 7daysofcode Alura - Git e GitHub

## :dart: Desafio 1: Criando um repositório e adicionando um projeto.

Criar um repositório com os arquivos HTML e CSS de um template de página, feito diretamente a partir da própria página repositório no GitHub, 
copiando e colando o código manualmente. Assim que cada arquivo fosse criado, deveria ser realizar o commit do mesmo, ao final da página. 
A segunda parte do desafio era fazer o upload de uma pasta "imagens" para o repositório, contendo as 4 imagens padrão do template proposto.

## :white_check_mark: :bulb: Minha solução - Desafio 1:
* Utilizei a IDE do Visual Studio Code para realizar o desafio. 
* Criei um workspace com os arquivos de HTML e CSS. 
* Posteriormente baixei as imagens do respositório apresentado no desafio e as transferi para a pasta do workspace.
* Refiz a linkagem de cada imagem para que pudessem ser apresentadas dentro do HTML sem quebra e criei este respositório no GitHub.
* Por último, utilizei os comandos do Git para enviar os arquivos para o respositório criado.

### :camera_flash: Prévia da Página criada deste repositório - Desafio 1:

![pagina-filmes-polulares](https://user-images.githubusercontent.com/74005813/194572420-c991dd66-cd8b-41a1-b687-2e0b931e7c09.jpg)

## :dart: Desafio 2: Clonando um repositório e realizando um commit a partir do VSCode.
Seguindo com as edições de arquivo a partir da IDE, o mesmo filme está sendo repetido três vezes, o texto de descrição não tem nada relevante e a imagem também está igual para todos. O desafio é alterar o arquivo "index.html" a partir do Visual Studio Code para que se tenha três filmes diferentes, cada um com a sua descrição, imagem e nota correspondente, salvar e realizar o commit.

## :white_check_mark: :bulb: Minha solução - Desafio 2:
* Para realizar o desafio, fiz a clonagem do repositório do GitHub para o Visual Studio Code.
* Realizei as alterações dos filmes, selecionando os 3 filmes estreados no cinema que assisti e mais gostei de 2022, indexando as devidas imagens e suas descrições.
* Atualizei as imagens de icones que haviam sido clonadas para manter a estética do template.
* Por último, criei o commit proposto e enviei o projeto atualizado para o GitHub através do Terminal da IDE usando os comandos de Git.

### :camera_flash: Prévia da Página - Desafio 2:
![Desafio 2](https://user-images.githubusercontent.com/74005813/200876931-e1292187-02a0-4975-904d-933802d92d3b.jpg)


## :dart: Desafio 3: Revertendo um commit.
Altere algo que vá quebrar o seu código (como o fechamento de uma ‘div’ ou de um ‘h2’) e faça o commit e o Push dessas alterações para a sua master. Pode tentar abrir o "index.html" para ver o erro. O desafio será reverter esse commit para remover o erro do código.
## :white_check_mark: :bulb: Minha solução - Desafio 3:
* Para realizar o desafio removi a tag `<div class="movie">` do último filme.
* Criei o commit e fiz o push para o repositório.
* Confirmei o erro no GitHub e na página criada.
* Para desfazer o push, realizei os seguintes passos no terminal do VSCode:
    1. Usei o comando `$ git reset --mixed` com o **hash** do último commit e em seguida utilizei o comando `$ git stash -m "revertendo o erro proposital` para salvar o stash com um contexto do que foi feito. Assim criei um 'ponto de restauração' com o git stash para não perder as modificações enviadas.
    2. Como usei apenas a branch main, em seguida usei o comando `$ git revert HEAD~0`, revertendo o commit anterior e apagando as modificações realizadas.
    3. Em seguida confirmei o **revert**, salvei o arquivo, commitei e dei push novamente revertendo o erro no repositório.

### :camera_flash: Prévia da Página - Desafio 3:

___
### :computer: Tecnologias e ferramentas usadas:
* Visual Studio Code
* HTML e CSS
* Git e GitHub





