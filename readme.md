# 개발의 시작
Markdown 과 git 등을 연습
-. 시작의 디렉토리
## Markdown
문서작성 도구
reference : [오픈튜토리얼](https://opentutorials.org/module/782)
#### 장점
1. 배우기 쉽고, 모바일환경에서 글작성하기 매우 편하다고함.
##### Italics & Bold
_Writing_ in Markdown is __not__ that ___hard !___
##### 코드블렄
```
a = 3;
b = 14;
print(a*b)
```
##### 링크
`[선일디엔씨](http://sunwill.iptime.org/)`
[선일디엔씨](http://sunwill.iptime.org/)에 연결합니다.
##### Image
`![title](image URL)`
상대경로 사용
'![Git 개념도](img/git_concept_dgr.png)'

## Git
  버전관리 도구

  1. Git의 개념도
    ![Git 개념도](img/git_concept_dgr.png)
  2. 개념의 이해 및 자유도를 높이기 위해서는 콘솔을 사용하라는 조언에 의하여 콘솔을 사용해봅니다.



## Other
### Configure
##### Batch File 만들기
```ECHO OFF
CLS
cd [프로젝트의 main directory]
F: (프로젝의 drive로 이동)
ECHO Welcome to first regeion for Developer.
ECHO ---
ECHO ON```
##### window cmd 바로가기
1. 바탕화면에서 바로가기를 만들
C:\Windows\system32\cmd.exe /k ""D:\git\first\first_env.bat""
