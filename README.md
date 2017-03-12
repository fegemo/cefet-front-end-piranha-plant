# cefet-front-end-piranha-plant

Um site informativo sobre plantas carnívoras.

## Atividade

Você tem um novo hobby: **criar plantas carnívoras**. Você encontrou um
documento solto em um antigo livro do seu tio Epaminondas e, depois de lê-lo,
decidiu **criar uma página web com seu conteúdo**.

### Exercício 1

Você deve pegar o documento do seu tio (arquivo:
`/documentos-do-tio/pagina-plantas.pdf`) e criar uma página web com o
mesmo conteúdo (não se preocupe com a formatação ainda).
Salve o arquivo como `plantas.html`.
  - A pasta `imagens` contém um dos arquivos de imagem a serem usados.
  - O título, que aparece na "aba" do navegador, deve ser "Plantas Carnívoras"
  - O arquivo `favicon.ico` deve ser usado como ícone da página

Você pode ver todas as _tags_ que precisará nos slides da aula, exceto o
ícone, cuja descrição está no FAQ a seguir.

### Exercício 2

Agora que você já criou a página, deve formatar os elementos usando código CSS.
Dentro do elemento `<head>...</head>`, ao seu final, crie um element
`<style></style>` para conter regras CSS.

## FAQ

- Quero colocar um ícone para minha página. #comofaz?
  - Salve uma imagem no formato `.ico` (já existe uma aqui) e, na página HTML,
    dentro do `<head></head>`, coloque:

    ```html
    <link rel="icon" href="favicon.ico">
    ```
- Devo colocar a imagem dentro de um parágrafo ou fora dele?
  - Depende do caso. A imagem deve estar dentro do parágrafo se ela
    é uma imagem "em linha", tipo um "emoji". Se ela for uma imagem mais alta,
    provavelmente deve estar fora do parágrafo.
