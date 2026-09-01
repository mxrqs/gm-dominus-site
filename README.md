# GM Dominus — Agência de Marketing

Site institucional da **GM Dominus**, agência focada em criação de sites, automação de atendimento e otimização de Google Meu Negócio para negócios locais.

## Status do código

A estrutura do repositório foi preparada a partir do arquivo recebido. O arquivo original estava truncado antes do `<body>` e antes do restante do CSS, portanto o projeto inclui:

- metadados e fontes recuperados;
- favicon extraído do Base64;
- organização inicial de HTML, CSS e JavaScript;
- cópia do conteúdo recebido na pasta `source/`;
- página temporária indicando que o conteúdo integral ainda precisa ser incorporado.

## Estrutura

```text
gm-dominus-site/
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── images/
│   │   └── favicon.png
│   └── js/
│       └── main.js
├── source/
│   └── original-recebido.txt
├── .gitignore
├── index.html
└── README.md
```

## Executar localmente

Abra o arquivo `index.html` no navegador ou utilize a extensão **Live Server** no Visual Studio Code.

## Publicar no GitHub

```bash
git init
git add .
git commit -m "feat: estrutura inicial do site GM Dominus"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/gm-dominus-site.git
git push -u origin main
```

## Publicar com GitHub Pages

1. Abra o repositório no GitHub.
2. Acesse **Settings > Pages**.
3. Em **Build and deployment**, selecione **Deploy from a branch**.
4. Escolha a branch `main` e a pasta `/root`.
5. Salve e aguarde a publicação.

## Próxima etapa

Substituir o conteúdo temporário do `index.html` e completar o `styles.css` e o `main.js` usando o arquivo HTML original completo.
