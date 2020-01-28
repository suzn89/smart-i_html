# Smart-i 통합플랫폼

## 미디어쿼리 분기
- overflow: hidden 처리하고, 분기별 디자인 다르게 고정 px 작업
- min-width: 1920px (FHD)
- min-width: 3840px (4K)

## CSS
- base.css : reset, normalize, font 포함
- common.css : 컴포넌트 공통 스타일
- layout.css : 기본 레이아웃 css
- layout_4k.css : 4K 레이아웃 css

## fonts
font-weight: 300,400,500,700,900

[ Google font helper ] (https://google-webfonts-helper.herokuapp.com/fonts/noto-sans-kr?subsets=latin)

```css
/* noto-sans-kr-300 - latin */
@font-face {
  font-family: 'Noto Sans KR';
  font-style: normal;
  font-weight: 300;
  src: url('../fonts/noto-sans-kr-v12-latin-300.eot'); /* IE9 Compat Modes */
  src: local('Noto Sans KR Light'), local('NotoSansKR-Light'),
       url('../fonts/noto-sans-kr-v12-latin-300.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
       url('../fonts/noto-sans-kr-v12-latin-300.woff2') format('woff2'), /* Super Modern Browsers */
       url('../fonts/noto-sans-kr-v12-latin-300.woff') format('woff'), /* Modern Browsers */
       url('../fonts/noto-sans-kr-v12-latin-300.ttf') format('truetype'), /* Safari, Android, iOS */
       url('../fonts/noto-sans-kr-v12-latin-300.svg#NotoSansKR') format('svg'); /* Legacy iOS */
}
/* noto-sans-kr-regular - latin */
@font-face {
  font-family: 'Noto Sans KR';
  font-style: normal;
  font-weight: 400;
  src: url('../fonts/noto-sans-kr-v12-latin-regular.eot'); /* IE9 Compat Modes */
  src: local('Noto Sans KR Regular'), local('NotoSansKR-Regular'),
       url('../fonts/noto-sans-kr-v12-latin-regular.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
       url('../fonts/noto-sans-kr-v12-latin-regular.woff2') format('woff2'), /* Super Modern Browsers */
       url('../fonts/noto-sans-kr-v12-latin-regular.woff') format('woff'), /* Modern Browsers */
       url('../fonts/noto-sans-kr-v12-latin-regular.ttf') format('truetype'), /* Safari, Android, iOS */
       url('../fonts/noto-sans-kr-v12-latin-regular.svg#NotoSansKR') format('svg'); /* Legacy iOS */
}
/* noto-sans-kr-500 - latin */
@font-face {
  font-family: 'Noto Sans KR';
  font-style: normal;
  font-weight: 500;
  src: url('../fonts/noto-sans-kr-v12-latin-500.eot'); /* IE9 Compat Modes */
  src: local('Noto Sans KR Medium'), local('NotoSansKR-Medium'),
       url('../fonts/noto-sans-kr-v12-latin-500.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
       url('../fonts/noto-sans-kr-v12-latin-500.woff2') format('woff2'), /* Super Modern Browsers */
       url('../fonts/noto-sans-kr-v12-latin-500.woff') format('woff'), /* Modern Browsers */
       url('../fonts/noto-sans-kr-v12-latin-500.ttf') format('truetype'), /* Safari, Android, iOS */
       url('../fonts/noto-sans-kr-v12-latin-500.svg#NotoSansKR') format('svg'); /* Legacy iOS */
}
/* noto-sans-kr-700 - latin */
@font-face {
  font-family: 'Noto Sans KR';
  font-style: normal;
  font-weight: 700;
  src: url('../fonts/noto-sans-kr-v12-latin-700.eot'); /* IE9 Compat Modes */
  src: local('Noto Sans KR Bold'), local('NotoSansKR-Bold'),
       url('../fonts/noto-sans-kr-v12-latin-700.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
       url('../fonts/noto-sans-kr-v12-latin-700.woff2') format('woff2'), /* Super Modern Browsers */
       url('../fonts/noto-sans-kr-v12-latin-700.woff') format('woff'), /* Modern Browsers */
       url('../fonts/noto-sans-kr-v12-latin-700.ttf') format('truetype'), /* Safari, Android, iOS */
       url('../fonts/noto-sans-kr-v12-latin-700.svg#NotoSansKR') format('svg'); /* Legacy iOS */
}
/* noto-sans-kr-900 - latin */
@font-face {
  font-family: 'Noto Sans KR';
  font-style: normal;
  font-weight: 900;
  src: url('../fonts/noto-sans-kr-v12-latin-900.eot'); /* IE9 Compat Modes */
  src: local('Noto Sans KR Black'), local('NotoSansKR-Black'),
       url('../fonts/noto-sans-kr-v12-latin-900.eot?#iefix') format('embedded-opentype'), /* IE6-IE8 */
       url('../fonts/noto-sans-kr-v12-latin-900.woff2') format('woff2'), /* Super Modern Browsers */
       url('../fonts/noto-sans-kr-v12-latin-900.woff') format('woff'), /* Modern Browsers */
       url('../fonts/noto-sans-kr-v12-latin-900.ttf') format('truetype'), /* Safari, Android, iOS */
       url('../fonts/noto-sans-kr-v12-latin-900.svg#NotoSansKR') format('svg'); /* Legacy iOS */
}
```