# Design Template
lazypic 디자인에 사용되는 에셋을 저장하는 리포지터리입니다.
영상로고, CI, BI, 디자인 가이드를 다룹니다.

#### Bitmap to Vector
- Potrace : http://potrace.sourceforge.net

#### SVG to PNG
- macOS 에서는 qlmanage 명령어를 이용해서 svg파일을 png로 바꿀 수 있습니다.

```
$ qlmanage -t -s 1000 -o . logo.svg
```

#### 콘텐츠 부합성 체크
- Adult, Spoof, Medical, Violence, Racy 항목을 체크할 수 있다.
- https://cloud.google.com/vision/

#### Font
lazypic에서 자주 사용되는 글꼴은 "고도마음체" 입니다.


- 고도마음체 : https://design.godo.co.kr/custom/free-font.php


