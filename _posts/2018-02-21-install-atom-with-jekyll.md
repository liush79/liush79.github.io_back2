---
layout: post
title: Install Atom with jekyll
date: 2018-02-21
comments: true
---
## atom.io 설치
* 홈페이지 가서 받으면 됨
* https://atom.io 설치는 별거 없으니 패스

## atom 설정
* Edit > preferences > 왼쪽 install 탭 에서
* language-liquid 와 Jekyll 찾아서 설치
* 추가로 다음 플러그인도 설치 (나중에 깔아도 되고 안 깔아도 됨.)
  * Markdown-preview-enhanced
  * preview 기본으로 제공하는데 좀 더 강화된 플러그인 임.

## project open
* open project -> 블로그 경로 선택.. 프로젝트 loading 됨

## jekyll 시작
* View > Toggle Command Palette (Shift+Ctrl+P) > jekyll: Toggle Server 하면 빌드 성공...
* (혹시 빌드가 실패하면  Edit > preferences > package > jekyll > setting 에서 환경을 맞춰줘야함.)
* localhost:3000 으로 접속하면 blog 뜸

## 블로그 포스팅 해보기
* _post 경로에 YYYY-MM-DD-[POST NAME].md 파일 생성
* 생성한 파일 오픈 해보면 창이 좌우로 나뉘어 뜸 (.md 파일은 자동으로 프리뷰 화면이 뜨는 것 같다.)
![setup-atom](/assets/images/setup-atom.png)
* 왼쪽에서 수정하면 바로 오른쪽 에서 결과를 볼 수 있으니 매우 편함.
* 이미지는 clip-board 에서 바로 올리는 것은 안되는 것 같고
  * assets/images 에 이미지 저장하고  \![Filename\](/assets/images/filename.png) 처럼 저장하면 됨.

## Reference
* http://futurecreator.github.io/2016/06/14/atom-as-markdown-editor/
* https://www.clien.net/service/board/lecture/8870683
