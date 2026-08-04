# Instalação no perfil do GitHub

Este pacote já está configurado para o usuário **1Deric1**.

## 1. Faça backup do README atual

Abra o repositório de perfil `1Deric1/1Deric1` e salve uma cópia do `README.md` atual, porque o arquivo deste pacote irá substituí-lo.

## 2. Envie os arquivos

Extraia o ZIP e envie **o conteúdo da pasta**, não a pasta inteira, para a raiz do repositório `1Deric1/1Deric1`.

A estrutura precisa ficar assim:

```text
1Deric1/
├── .github/
│   └── workflows/
│       └── jet-heatmap.yml
├── assets/
│   ├── avatar-source.png
│   └── portrait.txt
├── dist/
│   └── github-jet.svg
├── README.md
├── dark.svg
├── light.svg
├── generate.mjs
└── package.json
```

## 3. Permita que a Action grave no repositório

No GitHub, abra:

`Settings → Actions → General → Workflow permissions`

Selecione **Read and write permissions** e salve.

## 4. Gere o gráfico real

Abra:

`Actions → Update jet heatmap SVG → Run workflow`

Ao concluir, a Action substituirá o gráfico demonstrativo em `dist/github-jet.svg` pelos seus dados reais de contribuição. Depois disso, ela será executada automaticamente todos os dias.

## Dados já inseridos no painel

- Nome: Deric Santos
- Usuário: 1Deric1
- Localização: Salvador, Bahia, Brazil
- Formação: Software Engineering · UCSal
- Foco: Backend, PHP e Java
- Tecnologias: PHP, Java, Dart, C, HTML, CSS, Bootstrap, Flutter, Spring Boot, MySQL, SQLite, Docker, Linux e Git
- X: @DericSantos16

Para alterar qualquer texto, faça a mesma edição nos arquivos `dark.svg` e `light.svg`.
