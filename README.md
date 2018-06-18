<p align="center">
  <img width="200" src="./logo.png" alt="Logo do myrp">
  <br>
</p>

## Changelog
O changelog do myrp é criado utilizando GitHub Pages e Jekyll.

Todas as alterações podem ser feitas pela interface do GitHub.

### Criando nova release
1. Criar arquivo da release no diretório `/changelog-myrp/docs/docs`:
![Novo release](https://i.imgur.com/a5DXafS.png)

2. Adicionar link para a release no arquivo `README.md` no diretório `/changelog-myrp/docs`:
![Atualizar README.md](https://i.imgur.com/sCkI9pE.png)

### Publicando a release
Para forçar a publicação do changelog é necessário seguir os passos abaixo no diretório `/changelog-myrp`.
```
git pull

git commit --allow-empty -m "Forçando o rebuild do ghpages"

git push
```
