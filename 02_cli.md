# VSCode를 위한 명령어

```bash
#VSCode로 현재 작업 위치에서 해당하는 file_path를 실행
#파일이 존재하지 않으면 새로 생성
$ code (file_path)
```

# directory create
```bash
$ mkdir dir_name
```

# 현재 위치의 list
```bash
$ ls
```

# 파일 생성
```bash
$touch (file_path)
```

# 이동, 수정
```bash
#new_path에 dir path 넣고 싶으면 dirName/ 으로 /이거 붙여주기
#mv가 없는 경로를 지칭한다면 old_path에 들어가는 dir이름을 없는 경로의 이름으로 바꿈
$ mv {old_path} {new_path}
```

# 삭제
```bash
#dir 삭제와 파일 삭제는 방법이 다름 -> rm은 단일 객체만 삭제 가능
$ rm {file_path}
$ rm -r {file_path}
# r -> recursion
```

# 작업 위치
```bash
$ cd {dir_path}
$ cd ..
# .. -> 현재 위치의 상위 경로로 이동
```
# 경로
```bash
$ pwd
```

# 절대 경로
- Root ~ 현재 위치까지 작성

# 상대 경로
- 현재 작업하고 있는 디렉토리를 기준으로 계산된 상대적 위치를 작성한 것
```bash
#현재 위치
$ . 
```