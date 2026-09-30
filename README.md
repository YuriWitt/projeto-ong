# Projeto ONG Esperanca Viva

Projeto front-end desenvolvido em HTML5 e CSS3 para uma ONG ficticia, com foco
em estrutura semantica, acessibilidade, formulario validado e organizacao de
assets.

## Estrutura

```text
projeto-ong/
  index.html
  projetos.html
  cadastro.html
  feedback.html
  capturas/
    captura-feedback-desktop.png
    captura-feedback-mobile.png
  assets/
    css/
      style.css
    img/
      logo.svg
      logo.png
      logo.webp
      institucional.jpg
      institucional.webp
      voluntariado.jpg
      voluntariado.webp
      doacoes.jpg
      doacoes.webp
      educacao.jpg
      educacao.webp
```

## Paginas

- `index.html`: pagina inicial com apresentacao institucional e contatos.
- `projetos.html`: blocos de voluntariado, doacoes e educacao comunitaria.
- `cadastro.html`: formulario com `fieldset`, `legend`, `label`, tipos corretos
  de `input` e validacoes nativas com `required` e `pattern`.
- `feedback.html`: pagina de demonstracao dos componentes de feedback visual,
  incluindo badges, alertas, toast e modal.

Todas as paginas possuem menu principal com links para `index.html`,
`projetos.html`, `cadastro.html` e `feedback.html`.

## Acessibilidade

As paginas usam tags semanticas como `header`, `nav`, `main`, `section`,
`article`, `address` e `footer`. As imagens possuem `alt` descritivo, e os
campos do formulario possuem `label` associado ao respectivo controle.

## Feedback visual

O arquivo `feedback.html` utiliza os estilos definidos em `assets/css/style.css`
para exibir componentes prontos para integracao futura com JavaScript ou back-end:
badges de status, alertas semanticos, toast e modal com atributos ARIA.
