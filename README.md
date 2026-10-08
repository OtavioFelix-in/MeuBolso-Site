# Meu Bolso — site

Site promocional do **Meu Bolso**, app de controle financeiro pessoal, 100% offline.

**No ar:** https://otaviofelix-in.github.io/MeuBolso-Site/

## O que tem

- Apresentação do app, seção por seção, com prints das telas reais (`assets/telas/`).
- Vídeo de apresentação de 60 s (YouTube).
- Botão de download do APK, que aponta para a última release deste repositório, e o passo a passo de instalação.

## Estrutura

| Arquivo | O que é |
|---|---|
| `index.html` | página única |
| `style.css` | estilos; tokens de cor da paleta escura do app e da logo |
| `assets/icon.png` | ícone do app (o mesmo de `assets/icon.png` do repositório do app) |
| `assets/icon-launcher.png` | `icon.png` recortado na área que o Android mostra; usado no favicon, no topo e no rodapé |
| `assets/telas/` | prints das telas |
| `assets/*.ttf` | Inter e Feather, as mesmas fontes do app |

## Rodar localmente

É HTML estático, sem build. Sirva a pasta com qualquer servidor, por exemplo:

```bash
npx serve .
```

## Publicação

O GitHub Pages publica a branch `main`, pasta raiz. O que entra na `main` vai ao ar.
O APK é publicado como asset `MeuBolso.apk` em uma release deste repositório.
