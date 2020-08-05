# Desfazer Alterações

Desfazendo alteração antes do commit: `git reset HEAD nome_do_arquivo`

Desfazendo alteração depois do commit:

1. Acesse o `git log` e pegue o código do commit que quer desfazer;
2. Com o código do commit use: `git revert código_do_commit`

> Com revert ele vai criar um novo commit dizendo que foi revertido
