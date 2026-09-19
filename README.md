# ONG Mãos que Ajudam

Site institucional estático desenvolvido em HTML5 semântico, com foco em acessibilidade e conformidade com os padrões oficiais do W3C.

## Objetivo

Apresentar a organização, seus projetos sociais e permitir o cadastro de novos voluntários através de um formulário validado e acessível.

## Tecnologias utilizadas

- **HTML5** — estruturação semântica (header, nav, main, section, footer)
- **Validação W3C** — todas as páginas validadas via [Nu Html Checker](https://validator.w3.org/nu/), sem erros ou avisos

## Estrutura do projeto

```
/
├── index.html
├── projetos.html
├── cadastro.html
└── assets/
    └── images/
        ├── logo-ong.png
        └── equipe-voluntarios.jpg
```

## Páginas

| Arquivo | Descrição |
|---|---|
| `index.html` | Página inicial — apresentação institucional e dados de contato |
| `projetos.html` | Formas de doação, chamada para voluntariado e campanhas ativas |
| `cadastro.html` | Formulário de cadastro de voluntários, com validação nativa (pattern, required) |

## Acessibilidade e boas práticas

- Hierarquia de cabeçalhos (`h1` a `h6`) respeitada em todas as páginas
- Atributo `alt` obrigatório em todas as imagens
- Formulário organizado com `fieldset` e `legend` para agrupamento semântico de campos
- Validação nativa via atributos `type`, `pattern` e `required` (CPF, telefone e CEP)
- Todas as páginas validadas individualmente no W3C Nu Html Checker, sem erros ou avisos

## Como visualizar

1. Clone o repositório
2. Certifique-se de que a pasta `assets/images/` contém as imagens referenciadas
3. Abra `index.html` diretamente no navegador
