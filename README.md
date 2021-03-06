[![Netlify Status](https://api.netlify.com/api/v1/badges/9f2f756f-e1fc-48d9-9c07-b7d7433d8aaa/deploy-status)](https://app.netlify.com/sites/dazzling-lovelace-035878/deploys)

# μ νμν π¨π»ββοΈ π

μ νμν μΉνμ΄μ§ λ¦¬λ΄μΌ λ° μ μ

[μ νμν μΉνμ΄μ§](https://dazzling-lovelace-035878.netlify.app/)

![μ νμν λ©μΈνμ΄μ§](https://raw.githubusercontent.com/jiisunny/yuhan/master/_assets/main_screenshot.png)


## μ€ν κ·Έλν(The Open Graph protocol)

μΉνμ΄μ§κ° μμ λ―Έλμ΄(νμ΄μ€λΆ, μΉ΄μΉ΄μ€ν‘ λ±)λ‘ κ³΅μ λ  λ μ°μ μ μΌλ‘ νμ©λλ μ λ³΄λ₯Ό μ§μ νλ€.

KakaoTalk -

![KakaoTalk Open Graph example](https://raw.githubusercontent.com/jiisunny/yuhan/master/_assets/kakao_opengraph_example.png)

[λ λ§μ μ€ν κ·Έλν μμ± λ³΄κΈ°](https://ogp.me/)

```html
<meta property="og:type" content="website" />
<meta property="og:site_name" content="μ νμν" />
<meta property="og:title" content="μ νμν" />
<meta property="og:description" content="μ μ½ μ λ¬Έμμ²΄, μ°½μμ μ μΌν λ°μ¬, μ°κ΅¬μ, μ ν λ± μκ°, κ±΄κ°μμ, μ±μ©μ λ³΄ μ κ³΅." />
<meta property="og:image" content="./images/yuhan_seo.png" />
<meta property="og:url" content="https://dazzling-lovelace-035878.netlify.app/" />
```

- `og:type`: νμ΄μ§μ μ ν(E.g, `website`, `video.movie`)
- `og:site_name`: μν μ¬μ΄νΈμ μ΄λ¦
- `og:title`: νμ΄μ§μ μ΄λ¦(μ λͺ©)
- `og:description`: νμ΄μ§μ κ°λ¨ν μ€λͺ
- `og:image`: νμ΄μ§μ λν μ΄λ―Έμ§ μ£Όμ(URL)
- `og:url`: νμ΄μ§ μ£Όμ(URL)

## νΈμν° μΉ΄λ(Twitter Cards)

μΉνμ΄μ§κ° μμ λ―Έλμ΄(νΈμν°)λ‘ κ³΅μ λ  λ μ°μ μ μΌλ‘ νμ©λλ μ λ³΄λ₯Ό μ§μ νλ€.

[λ λ§μ νΈμν° μΉ΄λ λ³΄κΈ°](https://developer.twitter.com/en/docs/twitter-for-websites/cards/guides/getting-started)

```html
<meta property="twitter:card" content="summary" />
<meta property="twitter:site" content="μ νμν" />
<meta property="twitter:title" content="μ νμν" />
<meta property="twitter:description" content="μ μ½ μ λ¬Έμμ²΄, μ°½μμ μ μΌν λ°μ¬, μ°κ΅¬μ, μ ν λ± μκ°, κ±΄κ°μμ, μ±μ©μ λ³΄ μ κ³΅." />
<meta property="twitter:image" content="./images/yuhan_seo.png" />
<meta property="twitter:url" content="https://dazzling-lovelace-035878.netlify.app/" />
```

- `twitter:card`: νμ΄μ§(μΉ΄λ)μ μ ν(E.g. `summary`, `player`)
- `twitter:site`: μν μ¬μ΄νΈμ μ΄λ¦
- `twitter:title`: νμ΄μ§μ μ΄λ¦(μ λͺ©)
- `twitter:description`: νμ΄μ§μ κ°λ¨ν μ€λͺ
- `twitter:image`: νμ΄μ§μ λν μ΄λ―Έμ§ μ£Όμ(URL)
- `twitter:url`: νμ΄μ§ μ£Όμ(URL)

## Favicon(νλΉμ½, favorites icon)

μΉνμ΄μ§λ₯Ό λνλ΄λ μμ΄μ½, μΉνμ΄μ§μ λ‘κ³ λ₯Ό μ€μ νλ€.<br/>
λλΆλΆμ κ²½μ° λ£¨νΈ κ²½λ‘μ `favicon.ico` νμΌμ μμΉνλ©΄ μλμΌλ‘ λ‘λ©νκΈ° λλ¬Έμ `<link />`λ₯Ό μμ±ν  νμκ° μλ€. `favicon.png` νμΌμ μ¬μ©νλ €λ©΄ λ€μκ³Ό κ°μ΄ `<link />`λ₯Ό μμ±ν΄μΌνλ€.

> νλΉμ½ μ΄λ―Έμ§λ λ£¨νΈ κ²½λ‘μ μμ΄μΌ νλ€
```html
<!--<link rel="shortcut icon" href="favicon.ico" />-->
<link rel="icon" href="./favicon.png" />
```
- `favicon.ico` 64 x 64 (px) λλ 32 x 32 λλ 16 x 16
- `favicon.png` 500 x 500 (px)

<img src="https://raw.githubusercontent.com/jiisunny/yuhan/master/favicon.png" alt="yuhan" width="16" /><br />
<img src="https://raw.githubusercontent.com/jiisunny/yuhan/master/favicon.png" alt="yuhan" width="200" />

### .ico νμΌ μ μ

μ΄λ―Έμ§λ₯Ό μλ‘λνλ©΄ μμ½κ² `.ico` νμΌμ μ μν  μ μλ€.

[iconifier.net](https://iconifier.net/)

## Reset.css

κ° λΈλΌμ°μ μ κΈ°λ³Έ μ€νμΌμ μ΄κΈ°ν ν  μ μλ css νμΌ λ§ν¬

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reset-css@5.0.1/reset.min.css" />
```