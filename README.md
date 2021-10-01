## GIT 기본 명령어

### 1. git remote 
```
git remote add origin 'gihub repository 주소'
```
github의 repository를 연동시켜준 다음,

```
git remote -v 
```
위 명령을 통해 remote repository와 연결이 되었는지 확인할 수 있다,

### 2. git status

다음과 같이 현재상태를 확인할 수 있다.

```
현재 브랜치 main
브랜치가 'origin/main'에 맞게 업데이트된 상태입니다.

추적하지 않는 파일:
  (커밋할 사항에 포함하려면 "git add <파일>..."을 사용하십시오)
        README.md

커밋할 사항을 추가하지 않았지만 추적하지 않는 파일이 있습니다 (추적하려면 "git
add"를 사용하십시오)
```
### git log

다음과 같이 커밋 변경사항을 추적할 수 있다.

```
commit 7c5c050c324f21cd6889d18e544cce739cb325f9 (HEAD -> main, origin/main, feature/README)
Author: kjhabc2002 <juhju2022@gmail.com>
Date:   Fri Oct 1 11:16:57 2021 +0900

    initial commit
```
