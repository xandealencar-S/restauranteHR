# Restaurante HR

Site de um restaurante fictício de comida caseira, feito com HTML e CSS.

## Páginas

- **Início** (`index.html`): boas-vindas, botão para o cardápio e prato em destaque.
- **Cardápio** (`cardapio.html`): pratos principais e bebidas, com foto, descrição e preço.
- **Sobre** (`sobre.html`): história e missão do restaurante.
- **Contato** (`contato.html`): telefone, e-mail, endereço e horário de funcionamento.
- **Pedido** (`pedido.html`): formulário com os dados do cliente para fazer o pedido.

## Cardápio

| Item | Preço |
|---|---|
| Filé com Fritas | R$ 35,00 |
| Frango Grelhado | R$ 25,00 |
| Feijoada | R$ 30,00 |
| Lasanha | R$ 32,00 |
| Suco Natural | R$ 8,00 |

## Formulário de pedido

Na página de pedido há um formulário com os dados do cliente:

- Nome
- Telefone
- CPF
- CEP
- Rua
- Número da casa
- Complemento (opcional)

Os campos obrigatórios usam `required`, e o CPF e o CEP têm limite de caracteres com `maxlength`. Como o projeto não tem servidor, os dados não são enviados nem guardados.

## Tecnologias

- **HTML5**: estrutura das páginas e do formulário.
- **CSS3**: cores, cards, botões, menu e organização visual.

## Estrutura do projeto

```text
restauranteHR/
├── index.html
├── cardapio.html
├── sobre.html
├── contato.html
├── pedido.html
├── style.css
├── README.md
└── img/
    ├── feijoada.jpg
    ├── file-com-fritas.jpg
    ├── frango-grelhado.jpg
    ├── lasanha.jpg
    └── suco-natural.jpg
```

## Como abrir

Abra o arquivo `index.html` no navegador.