# ui_facebook
> Sass/SCSS를 사용하여 페이스북 UI(게시물) 마크업

### 참고자료
- [Sass 기초 _박재선 ★유용](https://sass.urbanzakapa.kr/)
- [Sass Guidelines](https://sass-guidelin.es/)
- [Sass Guidelines(번역본)](https://sass-guidelin.es/ko/)

### 설치
- [Ruby 설치](https://rubyinstaller.org/downloads/)
<pre><code>gem install sass</code></pre>

### 컴파일
- compile 후 불필요한 sourceMap을 제거
<pre><code>sass input.scss output.css --style compact --sourcemap=none</code></pre>

- compact 컴파일 (공백 없이 모든 속성이 한 줄로)
- compressed 컴파일 (minify, 속성 간 공백과 줄 바꿈 없이)
