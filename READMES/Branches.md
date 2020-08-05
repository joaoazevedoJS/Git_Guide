# Branches

Branches ("ramos") são utilizados para desenvolver funcionalidades isoladas umas das outras. A branch master é a branch "padrão" quando você cria um repositório.

É interessante separar o desenvolvimento de funcionalidades em branches diferentes, para que as mudanças no código para uma não influencie no funcionamento de outra.

Ver os branches atuais: `git branch`
Criar um novo Branch: `git branch nome_da_branch`
Trocar de branch `git checkout -b nome_da_branch`

## Unindo Branches

Git Merge: `git merge master nome_da_branch`

> O git merge ele vai juntar a master com a branch e vai criar um novo commit

Git Rebase: `git rebase nome_da_branch`

> O git rebase vai unir os log da master com o log da branch