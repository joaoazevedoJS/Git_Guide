Antes de qualquer interação com o git, você precisa informar quem é você para que ele armazene corretamente os dados do autor de cada uma das alterações no código.

> Se existe **mais de um usuário** utilizando o pc use:

``` powershell
git config --local user.name "Seu nome aqui"
git config --local user.email "seu@email.aqui"
```

> Se **só você** utiliza o pc use:

``` powershell
git config --global user.name "Seu nome aqui"
git config --global user.email "seu@email.aqui"
```

## Remover configs

``` powershell
git config --global --unset user.name
git config --global --unset user.email
```