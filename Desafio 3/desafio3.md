
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
---

### :camera_flash: Prévia da Página - Desafio 3:

* Criando o erro na página: 
![erro](https://user-images.githubusercontent.com/74005813/201416316-35a33fa7-2d7b-4dfa-84a0-2ac5754fed44.jpg)

---
* Conferindo o erro no repositório do GitHub após commit+push:
![erro github](https://user-images.githubusercontent.com/74005813/201416325-47c1c6c3-b531-441f-b0aa-f07f50b4fcf6.jpg)

---
* Fazendo o revert pelo Terminal do VSCode:
![revert](https://user-images.githubusercontent.com/74005813/201416333-58d124e6-4cd5-4223-a089-8b6f72ca2ccf.jpg)
