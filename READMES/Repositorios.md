# Repositórios

Iniciando um novo repositório: `git init`;

Agora você pode o estado da sua aplicação, o que foi alterado, o que foi salvado. `git status`

## Adicionando arquivos no repositório

Para adicionar **um arquivo** use `git add nome_do_arquivo`
Para adicionar **varios arquivos** use `git add .`

> Após adicionar um arquivo você precisa dar um *commit* para que sejam salvos

## Commits

Os commits são como um checkpoint da sua aplicação que **precisam ter uma mensagem**

Criando um novo checkpoint na aplicação: `git commit -m "sua mensagem"`

> O -m serve para que você possa adicionar uma mensagem  

Após da um commit e usar o `git status` você vai perceber que seu arquivo não ta lá, pois seu arquivo já está salvo.

## Log

Log é um historico de checkpoint salvo da sua aplicação, para executar use: `git log`

## Puxar arquivos de um repositório remoto

Antes de enviar arquivos para um repositório remoto, devemos puxar as novas atualizações do nosso código. Claro isso se você estiver trabalhando em equipes

Puxar arquivos: `git pull origin master`

## Enviando arquivos para repositório remoto

> Caso não tenha criado um repositório remote veja em [Remote.md](Remote.md)

Enviando o arquivos salvos no repositório remoto: 

Na primeira vez use: `git push -u origin master`
Caso não seja a primeira vez use: `git push`