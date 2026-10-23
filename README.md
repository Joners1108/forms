# Forms — Perfil Digital

Site estático (HTML5 + CSS3) para o evento Qualifica 2026 da Escola Profissional Ruiz Costa. Inclui questionário de perfil digital com 10 perguntas e cálculo de resultado no frontend.

## Especificações técnicas

| Item | Valor |
|------|-------|
| Tecnologias | HTML5, CSS3, JavaScript (vanilla) |
| Backend | Nenhum (site estático) |
| Base de dados | Nenhuma |
| Armazenamento de dados do utilizador | Não armazena dados |
| Design | Responsivo (media queries a partir de 768px) |

## Estrutura do repositório

```
forms/
├── index.html          # Página inicial (hero + info cards + CTA)
├── form3.html          # Questionário de perfil digital (10 perguntas)
├── index.css           # Estilos da página inicial
├── style.css           # Estilos do questionário
├── script.js           # Lógica de cálculo do perfil (referenciado em form3.html)
├── cropped-favicon-32x32.png
├── ERC_hor_fundo.jpg   # Logotipo da escola
└── README.md
```

## Funcionalidades

- Navegação fixa com menu responsivo (toggle móvel).
- Página inicial com secção hero, três cartões informativos e chamada para ação.
- Questionário com 10 perguntas de escolha única (radio buttons).
- Cálculo de perfil digital no frontend via JavaScript.
- Sem envio de dados para servidor; nenhum dado do utilizador é armazenado.

## Instalação

1. Copie a pasta `forms` para o diretório de documentos do servidor web (ex.: `C:\laragon\www\forms`).
2. Inicie Apache ou abra o ficheiro `index.html` diretamente no navegador.
3. Aceda a `http://localhost/forms`.

## Notas

- O questionário referencia `script.js`; certifique-se de que o ficheiro está presente na mesma pasta que `form3.html`.
- Não há dependências externas, geradores de pacotes nem processo de build.

## Licença

© 2026 João Pereira — https://github.com/Joners1108

Este projeto está disponível para uso pessoal e académico. Para uso comercial ou redistribuição, contacte o autor através do GitHub.

O código é fornecido "tal como está", sem garantias de qualquer tipo.
