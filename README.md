# Yoon 하이멜로디

[배포처 바로가기](https://fonts.google.com/specimen/Hi+Melody?subset=korean&preview.text=%ED%95%9C%EA%B8%80&preview.text_type=custom)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `Hi Melody`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/HiMelody/HiMelody.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/HiMelody/HiMelody.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'Hi Melody';
    font-weight: normal;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/HiMelody/HiMelody.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HiMelody/HiMelody.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HiMelody/HiMelody.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/HiMelody/HiMelody.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/HiMelody/subsets/HiMelody-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/HiMelody/subsets/HiMelody-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "Hi Melody", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
These fonts are licensed under the Open Font License. 
 
You can use them in your products & projects – print or digital, commercial or otherwise. 
 
This isn't legal advice, please consider consulting a lawyer and see the full license for all details.
```
