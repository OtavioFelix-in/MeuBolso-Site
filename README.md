<div align="center">

<img src="docs/readme/banner.svg" width="100%" alt="Meu Bolso — o site oficial do app" />

<br />

[![Site no ar](https://img.shields.io/website?url=https%3A%2F%2Fotaviofelix-in.github.io%2FMeuBolso-Site%2F&label=site&up_message=no%20ar&up_color=2CCB71&down_message=fora%20do%20ar&style=for-the-badge)](https://otaviofelix-in.github.io/MeuBolso-Site/)
[![Release](https://img.shields.io/github/v/release/OtavioFelix-in/MeuBolso-Site?label=APK&color=2CCB71&style=for-the-badge)](https://github.com/OtavioFelix-in/MeuBolso-Site/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/OtavioFelix-in/MeuBolso-Site/total?label=downloads&color=0B2A1F&style=for-the-badge)](https://github.com/OtavioFelix-in/MeuBolso-Site/releases)
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-main-222225?logo=github&logoColor=white&style=for-the-badge)](https://pages.github.com/)

<br />

[**Abrir o site**](https://otaviofelix-in.github.io/MeuBolso-Site/)
&nbsp;&nbsp;·&nbsp;&nbsp;
[**Baixar o APK**](https://github.com/OtavioFelix-in/MeuBolso-Site/releases/latest/download/MeuBolso.apk)
&nbsp;&nbsp;·&nbsp;&nbsp;
[**Código do app**](https://github.com/OtavioFelix-in/MeuBolso)
&nbsp;&nbsp;·&nbsp;&nbsp;
[**Vídeo de 60 s**](https://youtube.com/shorts/s7te0wb4iUE)

<br /><br />

<a href="https://otaviofelix-in.github.io/MeuBolso-Site/">
<img src="docs/readme/preview.jpg" width="100%" alt="O site do Meu Bolso no computador e no celular" />
</a>

</div>

<br />

## Sobre

Site promocional do **[Meu Bolso](https://github.com/OtavioFelix-in/MeuBolso)**, app de controle financeiro pessoal **100% offline**: sem conta, sem servidor e sem anúncio.

É uma página única, em HTML e CSS puros, **sem framework e sem build**. As fontes e a paleta são as mesmas do app, então o site e o app parecem uma coisa só.

## O que tem na página

<table>
<tr>
<td width="50%" valign="top">

**Apresentação**
- Abertura com o print da tela inicial do app
- Vídeo de apresentação de 60 s (YouTube, sem cookies)
- "Como funciona" em três passos

</td>
<td width="50%" valign="top">

**Funcionalidades**
- Seções de meses, parcelas, cartões e patrimônio, cada uma com o print real da tela
- Grade de relatórios e galeria de telas
- Bloco de privacidade

</td>
</tr>
<tr>
<td colspan="2">

**Download:** o botão aponta sempre para a **última release** deste repositório, com o passo a passo de instalação do APK logo abaixo.

</td>
</tr>
</table>

## Estrutura

| Arquivo | O que é |
|---|---|
| `index.html` | página única |
| `style.css` | estilos; tokens de cor da paleta escura do app e da logo |
| `assets/icon.png` | ícone do app (o mesmo de `assets/icon.png` do repositório do app) |
| `assets/icon-launcher.png` | `icon.png` recortado na área que o Android mostra; usado no favicon, no topo e no rodapé |
| `assets/telas/` | prints das telas |
| `assets/*.ttf` | Inter e Feather, as mesmas fontes do app |
| `docs/readme/` | banner e imagem de capa deste README (não vão para a página) |

## Rodar localmente

É HTML estático, sem build. Sirva a pasta com qualquer servidor, por exemplo:

```bash
npx serve .
```

## Publicação

```mermaid
flowchart LR
    A[push na main] --> B[GitHub Pages] --> C([site no ar])
    D[release com MeuBolso.apk] --> E[botão Baixar do site]
```

- O **GitHub Pages** publica a branch `main`, pasta raiz. O que entra na `main` vai ao ar.
- O **APK** é publicado como asset `MeuBolso.apk` em uma release deste repositório.

> [!IMPORTANT]
> O arquivo da release precisa se chamar exatamente **`MeuBolso.apk`**: o botão do site baixa `releases/latest/download/MeuBolso.apk`.

---

<div align="center">

<img src="assets/icon-launcher.png" width="64" alt="Meu Bolso" />

Feito por **Otávio Felix Da Silva**.

</div>
