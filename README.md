청주대학교 git 수업 내용입니다.
===================

## Git 설치하기
- git [홈페이지](https://git-scm.com/) 방문
- 개인별 운영체제에 맞는 설치 파일 다운로드 $\to$ 설치


## 작업 폴더 만들기


## Github.com 세팅
- 회원가입하기
- Repository 만들기


## 개인 컴퓨터 세팅
- 작업 디렉토리 만들기
- git 초기화 하기
- git config
- 경고 메시지

```{code}
$ git add hello.py
hint: core.useBuiltinFSMonitor will be deprecated soon; use core.fsmonitor instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
```

윈도우와 리눅스 차이 - 재미있는 타자기 이야기
- 관련 블로그 [블로그 바로가기](https://velog.io/@jakeseo_me/LF%EC%99%80-CRLF%EC%9D%98-%EC%B0%A8%EC%9D%B4-Feat.-Prettier)
- 타자기 동영상 [유튜브 바로가기](https://youtu.be/FkUXn5bOwzk)


```{code}
warning: LF will be replaced by CRLF in hello.py.
The file will have its original line endings in your working directory
```

## Git 명령어
- add
- commit
- reset (staging 되돌리기)
- reset --soft (commit 되돌리기)
- revert
- branch
- checkout
  - checkout --patch (-p)
- diff
- log --graph
- reset --[hard | soft | mixed]
  - 주의: --hard 옵션의 경우 되돌아간 시점 이후 모든 버전은 삭제됨
- revert
  - 과거 시점으로 되돌아감, 소스코드는 모두 그대로 유지, hisory가 쌓이므로 추적 가능


## 원격 저장소 활용
- push
- pull
- fetch
