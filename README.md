[![Netlify Status](https://api.netlify.com/api/v1/badges/9f2f756f-e1fc-48d9-9c07-b7d7433d8aaa/deploy-status)](https://app.netlify.com/sites/dazzling-lovelace-035878/deploys)

# 유한양행 👨🏻‍⚕️ 💊

유한양행 웹페이지 리뉴얼 및 제작

[유한양행 웹페이지](https://dazzling-lovelace-035878.netlify.app/)

![유한양행 메인페이지](https://raw.githubusercontent.com/jiisunny/yuhan/master/_assets/main_screenshot.png)


## 오픈 그래프(The Open Graph protocol)

웹페이지가 소셜 미디어(페이스북, 카카오톡 등)로 공유될 때 우선적으로 활용되는 정보를 지정한다.

KakaoTalk -

![KakaoTalk Open Graph example](https://raw.githubusercontent.com/jiisunny/yuhan/master/_assets/kakao_opengraph_example.png)

[더 많은 오픈 그래프 속성 보기](https://ogp.me/)

```html
<meta property="og:type" content="website" />
<meta property="og:site_name" content="유한양행" />
<meta property="og:title" content="유한양행" />
<meta property="og:description" content="제약 전문업체, 창업자 유일한 박사, 연구소, 제품 등 소개, 건강소식, 채용정보 제공." />
<meta property="og:image" content="./images/yuhan_seo.png" />
<meta property="og:url" content="https://dazzling-lovelace-035878.netlify.app/" />
```

- `og:type`: 페이지의 유형(E.g, `website`, `video.movie`)
- `og:site_name`: 속한 사이트의 이름
- `og:title`: 페이지의 이름(제목)
- `og:description`: 페이지의 간단한 설명
- `og:image`: 페이지의 대표 이미지 주소(URL)
- `og:url`: 페이지 주소(URL)

## 트위터 카드(Twitter Cards)

웹페이지가 소셜 미디어(트위터)로 공유될 때 우선적으로 활용되는 정보를 지정한다.

[더 많은 트위터 카드 보기](https://developer.twitter.com/en/docs/twitter-for-websites/cards/guides/getting-started)

```html
<meta property="twitter:card" content="summary" />
<meta property="twitter:site" content="유한양행" />
<meta property="twitter:title" content="유한양행" />
<meta property="twitter:description" content="제약 전문업체, 창업자 유일한 박사, 연구소, 제품 등 소개, 건강소식, 채용정보 제공." />
<meta property="twitter:image" content="./images/yuhan_seo.png" />
<meta property="twitter:url" content="https://dazzling-lovelace-035878.netlify.app/" />
```

- `twitter:card`: 페이지(카드)의 유형(E.g. `summary`, `player`)
- `twitter:site`: 속한 사이트의 이름
- `twitter:title`: 페이지의 이름(제목)
- `twitter:description`: 페이지의 간단한 설명
- `twitter:image`: 페이지의 대표 이미지 주소(URL)
- `twitter:url`: 페이지 주소(URL)

## Favicon(파비콘, favorites icon)

웹페이지를 나타내는 아이콘, 웹페이지의 로고를 설정한다.<br/>
대부분의 경우 루트 경로에 `favicon.ico` 파일을 위치하면 자동으로 로딩하기 때문에 `<link />`를 작성할 필요가 없다. `favicon.png` 파일을 사용하려면 다음과 같이 `<link />`를 작성해야한다.

> 파비콘 이미지는 루트 경로에 있어야 한다
```html
<!--<link rel="shortcut icon" href="favicon.ico" />-->
<link rel="icon" href="./favicon.png" />
```
- `favicon.ico` 64 x 64 (px) 또는 32 x 32 또는 16 x 16
- `favicon.png` 500 x 500 (px)

<img src="https://raw.githubusercontent.com/jiisunny/yuhan/master/favicon.png" alt="yuhan" width="16" /><br />
<img src="https://raw.githubusercontent.com/jiisunny/yuhan/master/favicon.png" alt="yuhan" width="200" />

### .ico 파일 제작

이미지를 업로드하면 손쉽게 `.ico` 파일을 제작할 수 있다.

[iconifier.net](https://iconifier.net/)

## Reset.css

각 브라우저의 기본 스타일을 초기화 할 수 있는 css 파일 링크

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reset-css@5.0.1/reset.min.css" />
```