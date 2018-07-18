<p align="center">
  <img width="200" src="./logo.png" alt="Logo do myrp">
  <br>
</p>

## Changelog
O changelog do myrp é criado utilizando GitHub Pages e Jekyll.

Todas as alterações podem ser feitas pela interface do GitHub.

### Criando nova release
1. Crie um arquivo markdown para a release no diretório `/changelog-myrp/docs/docs`
    - Por exemplo: `/changelog-myrp/docs/docs/18.08.01.md`

2. Adicione um link para o arquivo criado no `README.md` do diretório `/changelog-myrp/docs`

3. Pronto! Em até 10 minutos o GH Pages irá forçar o rebuild e as atualizações estarão disponíveis em `https://myrp.github.io/changelog-myrp/`

### Forçando a publicação da release
Para forçar o rebuild do GH Pages é necessário seguir os passos abaixo no diretório `/changelog-myrp`
```
git pull

git commit --allow-empty -m "Forçando o rebuild do ghpages"

git push
```
