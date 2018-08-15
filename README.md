# Design Template
lazypic 디자인에 사용되는 에셋을 저장하는 리포지터리입니다.
영상로고, 명함, CI, BI, 디자인 가이드를 다룹니다.

#### Bitmap to Vector
bitmap이미지를 Vector로 바꾸기 쉬운 방법은 potrace 명령어를 사용하는 것 입니다.

- Potrace : http://potrace.sourceforge.net

#### SVG to PNG
- macOS 에서는 Inkscape를 이용해서 svg파일을 png로 바꿀 수 있습니다.

```bash
$ /Applications/Inkscape.app/Contents/Resources/bin/inkscape -z /Users/woong/design-template/logo_1080p.svg -e /Users/woong/design-template/logo_1080p.png
```

#### SVG to PDF
- 간혹 인쇄업체에서 pdf를 요구하는 경우가 있다.

```
/Applications/Inkscape.app/Contents/Resources/bin/Inkscape --without-gui -A /filepaht/filename.pdf /filepath/filename.svg
```

#### 컨버팅 서비스
- ZAMZAR : https://www.zamzar.com

#### 콘텐츠 부합성 체크
- google Vision 서비스를 이용하면 Adult, Spoof, Medical, Violence, Racy 항목에 대한 콘텐츠 부합성 체크를 할 수 있습니다.
- https://cloud.google.com/vision/

#### Font
lazypic에서 자주 사용되는 글꼴은 "고도마음체" 입니다.

- 고도마음체 : https://design.godo.co.kr/custom/free-font.php

#### 명함
- 명함의 종이는 스텐다드, 둥근모서리
- 꼭 SVG를 PDF로 변환해서 보낼 것
- https://www.ohprint.me/store/business-card/intro/basic

#### 스티커
- 원형 : 50mm x 50mm
- 꼭 SVG를 PDF로 변환해서 보낼 것
- https://www.ohprint.me/store/sticker/intro/circle
