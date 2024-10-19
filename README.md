# Y클로버체

[배포처 바로가기](https://www.yspotlight.co.kr/download/font?tabNo=4)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `YClover`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/YClover/YClover.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/YClover/YClover.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'YClover';
  font-weight: 400;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/YClover/YClover-Regular.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/YClover/YClover-Regular.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/YClover/YClover-Regular.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/YClover/YClover-Regular.ttf') format('truetype');
}
@font-face {
  font-family: 'YClover';
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/YClover/YClover-Bold.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/YClover/YClover-Bold.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/YClover/YClover-Bold.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/YClover/YClover-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/YClover/subsets/YClover-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url("https://cdn.jsdelivr.net/gh/fonts-archive/YClover/subsets/YClover-dynamic-subset.css");
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "YClover", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
Y클로버체는 누구나 제약 없이 자유롭게 사용하고 재배포 하실 수 있습니다.
```
