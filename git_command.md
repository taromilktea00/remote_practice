# git 명령어

## 초기
```bash
$ git init
```

## staging area에 넣기
```bash
$ git add {file/directory name}
```
## staging area에 있는 파일 삭제하기
```bash
$ git rm -r --cached {dir_path}
# -r 은 directory에 있는 파일들 지우려고 사용함
# 파일 단일로 삭제하려면
$ git rm --cached {dir_path}
```
## 현재 staging area 상태 보기
```bash
$ git status
```
## 사용자 정보 넣기(넣어야 commit 가능)
```bash
$ git config --global user.email "사용자 이메일"
$ git config --global user.name "이름"
```

## staging area에 있는 것들 repository 에 넣기
```bash
$ git commit -m "주석달기"
```

## repository 상태 보기
```bash
$ git log
#1줄로 보기
$ git log --oneline
```

## remote repository 사용하기
```bash
$ git remote add origin {github repository 주소}
# origin -> github repository 주소를 일일히 입력하지 않고 별칭으로 쓰기 위함

#repository에 파일 넣기(앞서 add-commit의 과정을 거친 후 사용)
$ git push origin master
```

## github에서 받아오기
```bash
#저장하려는 pc에 아무것도 없는 상태라면
$ git clone {github repository 주소}
#저장하려는 pc에 어느정도 있는 상태라면
$ git pull origin master
```
