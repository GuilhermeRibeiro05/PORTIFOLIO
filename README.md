# Portfólio — Guilherme Ribeiro Costa

Site pessoal desenvolvido como projeto final da disciplina **Desenvolvimento de Front-End para Web**.

## Tecnologias utilizadas

- **HTML5:** estrutura e conteúdo das seções.
- **CSS3:** identidade visual, animações e layout responsivo.
- **JavaScript:** menu para celular, animações ao rolar a página, botão de voltar ao topo e atualização automática do ano.
- **SVG:** ilustração vetorial local do futevôlei e ícone do site.

## Estrutura de pastas

```text
portfolio-guilherme/
├── index.html          # Página principal e conteúdo HTML
├── README.md            # Documentação e instruções
├── css/
│   └── style.css        # Estilos e regras responsivas
├── js/
│   └── script.js        # Interações JavaScript
└── images/
    ├── favicon.svg      # Ícone da aba do navegador
    └── futvolei.svg     # Ilustração do hobby
```

## Como visualizar no computador

1. Extraia a pasta do projeto.
2. Abra a pasta `portfolio-guilherme`.
3. Dê dois cliques no arquivo `index.html` para abrir o site no navegador.
4. Para editar o conteúdo, abra `index.html` e altere os textos. Para mudar cores e aparência, edite `css/style.css`.

Não é necessário instalar programas ou bibliotecas para visualizar a versão atual.

## Personalizações antes de publicar

No arquivo `index.html`, procure por `SEU-EMAIL@EXEMPLO.COM` e `SEU-USUARIO` e substitua pelos seus dados reais:

- `SEU-EMAIL@EXEMPLO.COM`: seu endereço de e-mail.
- `SEU-USUARIO` em `https://github.com/SEU-USUARIO`: seu usuário do GitHub.

Também confira se os textos dos projetos representam exatamente os trabalhos que você deseja apresentar.

## Como publicar no GitHub Pages

1. Entre em [github.com](https://github.com/) e faça login.
2. Clique em **New repository** para criar um repositório.
3. Dê um nome, por exemplo `meu-portfolio`, escolha **Public** e crie o repositório.
4. Dentro do repositório, clique em **Add file > Upload files**.
5. Envie os arquivos e pastas que estão dentro de `portfolio-guilherme` (envie `index.html`, `css`, `js`, `images` e `README.md`; não envie apenas o arquivo ZIP).
6. Clique em **Commit changes**.
7. Abra **Settings > Pages**.
8. Em **Build and deployment**, escolha **Deploy from a branch**.
9. Em **Branch**, selecione `main` e a pasta `/ (root)`. Clique em **Save**.
10. Aguarde a publicação indicada na própria página do GitHub Pages. O endereço normalmente será `https://SEU-USUARIO.github.io/meu-portfolio/`.

Se o repositório tiver outro nome, o endereço do site também mudará. A publicação pode levar alguns minutos.

## Recursos responsivos e interativos

- Menu de navegação adaptado para celulares.
- Layout com grades que se reorganizam em telas menores.
- Botão para voltar ao topo.
- Animações de entrada ao rolar a página, respeitando a preferência do sistema por movimento reduzido.
- Navegação por âncoras entre as seções.

## Observação sobre o contato

O botão de e-mail utiliza um link `mailto`. Ele abre o aplicativo de e-mail configurado no dispositivo; não existe envio de formulário nem servidor conectado neste projeto.
