# Título da Apresentação

## Introdução

Este é o slide de introdução.
Aqui podemos ter:

* Pontos
* De
* Discussão

## Fluxo de Trabalho

Como funciona:

1.  **Push** para o branch `main`.
2.  GitHub Actions detecta a alteração em `docs/`.
3.  O workflow `slides.yml` é executado.

## Conversão Pandoc

O Pandoc usa a classe Beamer do LaTeX:

`pandoc presentation.md -t beamer -o presentation.pdf`

---
* O separador `---` (regra horizontal) também pode iniciar um novo slide sem título.

## Conclusão

O PDF dos slides será:

* Publicado como **Artefato** na Action.
* Enviado para o branch `gh-pages` para **publicação web**.