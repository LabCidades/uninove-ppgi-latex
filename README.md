# Template LaTeX PPGIGC - Uninove

Este é um template LaTeX para teses e dissertações desenvolvido para o PPGIGC (Programa de Pós Graduação em Informática e Gestão do Conhecimento) da Universidade Nove de Julho - Uninove. Ele é uma modificação e extensão do template do IME-USP desenvolvido pelo professor Jesús P. Mena-Chalco:

* [http://latex-exemplo.blogspot.com.br/2015/11/modelo-latex-para-dissertacoes-e-teses.html](http://latex-exemplo.blogspot.com.br/2015/11/modelo-latex-para-dissertacoes-e-teses.html)

* Este template foi **atualizado* com base no desenvolvimento de Charles Gobber (2018) [https://github.com/gobber/uninove-ppgi-latex](https://github.com/gobber/uninove-ppgi-latex)

## Orientações

O arquivo **main.tex** contém diversos exemplos de como utilizar os comandos disponíveis no *template* como a inclusão de:
+ Algoritmos;
+ Equações;
+ Figuras;
+ Quadros;
+ Tabelas.

Além da:
+ Criação de seções e subseções;
+ Inclusão de Apêndices e Anexos;
+ Inclusão de resumos de capítulos;
+ Marcação com tachado (colorido);
+ Inclusão de observações (coloridas).

Bibliografia
+ O arquivo *refs.bib* contém exemplos de como realizar a inclusão dos dados bibliográficos (esses dados podem ser incluídos manualmente ou com auxílio de um gerenciador de bibliografia como o [Mendeley](https://www.mendeley.com/)).
+ Os títulos das publicações devem estar entre o comando **\titleset{}** para ficarem com destaque em negrito.

## Extras

Dentro do exemplo é fornecido um arquivo de *shell* linux **clean.sh** para excluir arquivos temporários gerados pelo LaTeX que muitas vezes atrapalham o desenvolvimento (arquivos de *cash* do bibtex as vezes não adicionam as referências novas):
```
# executar o arquivo pelo terminal
sh ./clean.sh
```
Para usuários *windows* existe um arquivo **clean.bat** que faz o mesmo papel.
```
# executar o arquivo pelo terminal (cmd)
clean.bat
```

## Modificações

As modificações no *template* são livres para adequação de cada um, desde que estejam dentro das normas estabelecidas pela universidade (ABNT).

## Dicas úteis

Este *template* pode ser utilizado em algum ambiente **LaTex** como o TextStudio ou MikText ([Vide Tutorial aqui](https://www.profmat.cefetmg.br/modelos-dissertacao/latex/instalacao-do-latex/)), ou de forma *online* com o [Overleaf](https://overleaf.com/) que é um sistema *free* em nuvem.
