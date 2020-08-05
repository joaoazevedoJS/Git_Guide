## Guardar alteração

Caso queira guardar alteração para depois você pode salvar a alteração sem gerar um commit com: `git stash`

## Lista de alterações armazenadas

Acessar lista: `git stash list`

## Pegar dados das alterações

Pegando a alteração: `git stash apply numero_da_stash`
Pegar a ultima alteração e deletar ela em seguida: `git stash pop`

## Deletando uma stash

> Mesmo pegando uma stash ela continua na lista de stash
Deletar uma alteração: `git stash drop numero_da_stash`