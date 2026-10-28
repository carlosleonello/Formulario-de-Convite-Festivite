# 🎉 Festivite — Formulário de Convite

Projeto desenvolvido por mim como parte de um desafio da Rocketseat, utilizando HTML, CSS e um pequeno trecho de JavaScript para criar uma interface de personalização de convites para eventos.

## 💻 Sobre o projeto

O Festivite é um formulário para reunir as informações de um evento e escolher os detalhes visuais de um convite digital.

A interface permite:

- Preencher título, datas, local e descrição do evento.
- Escolher entre evento presencial ou online.
- Selecionar uma das 11 cores principais.
- Escolher entre 12 temas, como aniversário, casamento, formatura e Natal.
- Selecionar o estilo e um arquivo local para a foto de capa.
- Informar nome, e-mail e telefone para contato.
- Aceitar os termos e escolher as preferências de recebimento de promoções.

## 🚀 Tecnologias utilizadas

- **HTML5** para estruturar a página e os campos do formulário.
- **CSS3** para organizar o layout e personalizar os controles.
- **JavaScript** para remover caracteres que não sejam números do campo de telefone.
- **Google Fonts** para utilizar as fontes Leckerli One, Baloo 2 e Open Sans.
- **SVG** para os ícones e as imagens utilizadas na interface.

## 📚 Conceitos praticados

Durante o desenvolvimento, pratiquei:

- Estruturação de formulários com `form`, `fieldset`, `legend` e `label`.
- Organização dos elementos com CSS Grid e Flexbox.
- Uso de variáveis CSS para definir cores e tipografia.
- Personalização de campos, botões de opção, caixas de seleção e interruptores.
- Estilização dos estados de seleção, foco e validação.
- Uso de ícones com `mask-image`.
- Validação nativa de campos obrigatórios e do formato de e-mail.
- Separação dos estilos em arquivos CSS.

## 📁 Estrutura do projeto

```text
├── assets/
│   ├── icons/
│   ├── themes/
│   ├── Background.svg
│   └── Logo.svg
├── styles/
│   ├── forms.css
│   ├── global.css
│   └── styles.css
├── index.html
└── README.md
```

## 🚧 Etapa atual

O projeto é uma interface de estudo, com layout voltado para desktop. A seleção de cores, temas e estilo altera os controles, mas ainda não gera uma prévia do convite nem muda o tema da página.

O botão **Gerar convite** aciona a validação nativa do formulário. A geração do convite, o envio da foto de capa e o armazenamento dos dados ainda não foram implementados.

## ▶️ Como visualizar

1. Clique em **Code → Download ZIP** neste repositório.
2. Extraia os arquivos.
3. Abra o arquivo `index.html` no navegador.

Também é possível abrir a pasta no VS Code e visualizar a página com a extensão **Live Server**. Não é necessário instalar dependências.

## ✍️ Autor e créditos

Desenvolvido por [Carlos Leonello](https://github.com/carlosleonello) como parte de um desafio da [Rocketseat](https://www.rocketseat.com.br/).

Layout e materiais disponibilizados pela Rocketseat para a realização do desafio.
