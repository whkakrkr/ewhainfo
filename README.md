#### http://ewhainfo.netlify.app

## 이화여대 입시링크   

이화여자대학교의 입시와 관련된 사이트의 링크들을 연결해주는 사이트입니다.

- 이화여자대학교 공식 입학처
- 이화그린 입시카페
- 자료모음 블로그   

Code referenced : [https://codepen.io/nightcl4w/pen/dEjreJ](https://codepen.io/nightcl4w/pen/dEjreJ)

<Mobile image>   
  <img src="https://user-images.githubusercontent.com/75469131/106314703-7400b600-62ad-11eb-8140-71dffeaeb8b7.jpg"  width="300" height="500">


--------
## 웹페이지 최적화 (Search Engine Optimization, SEO)

1. [네이버 웹마스터 도구](https://searchadvisor.naver.com/console/board)   
<br/>

2. 사이트 인증 : 메타태그 index.html <head>에 넣기   
```html
'<meta name="naver-site-verification" content="0f0f336b28a202e787105c4d2f350b9afb7682c9" />'
```   
<br/>
  
3. 크롤러 (*robot.txt*)
```
  User-agent: *
Allow:/
Sitemap: https://ewhainfo.netlify.app/sitemap.xml
```   
<br/>

4. 사이트맵 (*sitemap.xml*)   
[https://www.xml-sitemaps.com/](https://www.xml-sitemaps.com/) 에서 사이트맵 생성   
Sitemap: https://ewhainfo.netlify.app/sitemap.xml    
<br/>

5. Open Graph 제목, 미리보기, 설명
```html
 <meta property="og:title" content="이화여대 입시 링크">
 <meta property="og:image" content="miribogi.png">
 <meta property="og:description" content="이화여자대학교 입시를 위한 사이트로 연결해드립니다. (이화여대 입학처, 이화그린 입시카페,  자료모음 블로그)">
```
after put 'open graph'   
<img src="https://user-images.githubusercontent.com/75469131/106314696-719e5c00-62ad-11eb-8710-54eabd6c128e.jpg"  width="500" height="300">

