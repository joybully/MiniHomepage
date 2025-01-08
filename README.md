# Git 기초

## 목차
- [Git이란?](https://www.miricanvas.com/v/13sin0x)
- [Git 기본 명령어](https://www.miricanvas.com/v/13siuyd)
- [브랜치와 병합](https://www.miricanvas.com/v/13sm5mv)
- [Github 사용](https://www.miricanvas.com/v/13sjizq)
- [추가 리소스](https://docs.google.com/document/d/1Se6HsILhCsNbqsjtrBktUzRz8_XBm-FFXcJQodZoSH8/edit?tab=t.0#heading=h.10ccv8j1pujz)
---
## Git이란?

**Git**은 분산형 버전 관리 시스템입니다. 여러 명이 동시에 작업할 수 있도록 코드를 관리하고, 작업 내역을 기록하는 데 사용됩니다.
<br>
*예를 들어*, 다음과 같은 상황에서 유용합니다:
- 여러 개발자가 동시에 코드를 수정할 때
- 프로젝트의 특정 시점으로 되돌리고 싶을 때
- 실수로 파일을 지웠을 때 복구하고 싶을 때

> "분산형 버전 관리 시스템 Git은 모든 파일의 변경 이력을 기록하여 협업을 쉽게 해줍니다." - Git 사용자

## Git 기본 명령어
**1. Git 저장소 초기화**
```
git init
```
- 새로운 Git 저장소를 초기화합니다.

**2. 파일 추가 및 커밋**
```
git add <파일명>
git commit -m "첫 번째 커밋"
```
- 스페이징 영역에 파일을 추가하고, 커밋을 생성합니다.
## GitHub 사용
GitHub는 Git을 기반으로 한 협업 플랫폼입니다. 다음 단계를 통해 원격 저장소를 사용할 수 있습니다.
1. **GitHub 계정 생성**
2. **새로운 리포지토리 생성**
3. **원격 저장소 연결**:
```
git remote add origin <GitHb 저장소 URL>
git push origin main
```
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ54N0tDCIIyp1dWyc8z6R6YsF-t47Bw_SOfw&s)
---
## 추가 리소스
- Git에 대해 더 알고 싶다면, [Git 공식문서](https://git-scm.com/)를 확인하세요
- GitHub 사용법에 대한 자세한 정보는 [GitHub Docs](https://docs.github.com/ko)에서 찾아볼 수 있습니다.

## 스타일구성
- style.md 추가하기

## 서비스 소개 페이지
- about.md 추가