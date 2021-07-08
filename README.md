# IntroLaTeXABPG

Neste repositório estão disponíveis a apresentação e um exemplo de documento do curso "LaTeX para Teses e Dissertações do INPE", oferecidos durante a II Semana de Imersão da ABPG.

## Instruções de Compilação

    xelatex -interaction=nonstopmode -shell-escape refs.tex
    bibtex refs
    xelatex -interaction=nonstopmode refs.tex
    xelatex -interaction=nonstopmode refs.tex 
    xelatex -interaction=nonstopmode -shell-escape redacao_cientifica_latex_abpg_06072021-cfbastarz.tex

O arquivo final PDF da apresentação será gerado com o nome `redacao_cientifica_latex_abpg_06072021-cfbastarz.pdf`.

## Transmissão

Link para a gravação da transmissão: https://youtu.be/86Ycq-nyHbs

## Outros recursos

Uma apostila completa pode ser obtida em https://github.com/cfbastarz/CursoIntroLaTeX/blob/master/apostila/publicacao.pdf

Carlos Frederico Bastarz (carlos.bastarz@inpe.br)
