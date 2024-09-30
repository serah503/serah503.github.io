---
title: 01. Github를 활용한 개발 환경 설정
author: Serah Choi
date: 2024-09-30
category: iM뱅크 데이터 분석가
layout: post
mermaid: true
---

Github 사용법과 통합 개발 환경 설정하기:

통합개발환경(IDE, Integrated Development Environment)의 대표적인 프로그램
- VSCode: Microsoft에서 개발한 IDE
- PyCharm: JetBrains에서 제공하는 IDE
둘 다 Python에 최적화되었으나 이번 교육 과정에서는 VSCode를 사용한다.

개발 환경 세팅
-------------

Github에서.....

1. 새로운 Repo 생성(README.md 체크하기)
2. VSCode에서 Clone Respiratory하고 Git 푸시

```markdown
git add .
git commit -m "test"
git push
```

3. Github 페이지 반영

### VSCode로 Python 실행하기

1. 가상환경설정
   - virtualenv
   - conda
   교육 과정에서는 더 보편적으로 사용되는 virtualenv를 사용하였다.
   이때, Mac에서는 vi편집기를 사용해야한다.
2. requirements.txt
   패키지를 불러오고 버전을 기록할 수 있다.
3. 파일의 경로 확인 및 인터페이스 열기
   주로 jupyer lab을 사용하였다.

참고 사항:
- .ipynb ⇒ 분석가들을 위한 파일
- .py ⇒ 개발자

### Google Colab으로 Python 실행하기
클라우드 기반인 Colab에서는 별도의 설치나 자동 환경 설정이 불필요하다.
