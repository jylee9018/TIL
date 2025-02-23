# Linux Command (Basic)
### 파일 보기
ls (list)
- -a (all) -  숨김 파일 및 폴더까지 보기
- -l (long list)
- -al (all + long list)
```
ls
ls -a
ls -l
ls -al

ls *.py
ls hel*
```

### 파일 생성
```
touch {hello.py}
```
- 텍스트 문서 생성 가능: .txt
- 프로그래밍 언어 문서 생성 가능: .py, .java, .go 등

### 파일 내용 보기
cat (concatenate)
```
cat hello.py
```

### 파일/폴더 이동 & 이름 바꾸기
mv (move)
```
mv hello.py
mv hello.py hello-world.py # 이름 바꾸기
```

### 파일 삭제
rm (remove)
```
rm {hello.py}
```

### 폴더 생성
mkdir (make directory)
```
mkdir {dir1} 
mkdir {dir2/sub1}
mkdir {dir2/sub2}
```

* 하위 폴더를 생성할 때 (상위 폴더와 하위 폴더를 한 번에 생성)
  - mkdir - -p (make directory -parent)
```
mkdir -p {dir3/sub1}
```

### 폴더 삭제
rmdir (remove directory)
```
rmdir {dir1}
```

* 하위 폴더를 삭제할 때 (상위 폴더와 하위 폴더를 한 번에 삭제)
  - rmdir -p (remove directory -parent)
```
rmdir -p {dir3/sub1}
```

### 폴더 이동
cd (change directory)
```
cd dir2
cd dir2/sub1
```

### 현재 작업 폴더 경로
pwd (present working directory)
```
pwd
```

### 터미널 지우기
```
clear
```

# Git Command
```
git clone https://github.com/jylee9018/TIL.git

git add 240419-Git-Command.md
git commit
git push origin main
```

# VIM Command
- I - Insert mode
- ESC - Normal mode
- Normal mode + : + q! - 파일 종료(저장 하지 않음)
- Normal mode + : + wq - 저장 후 파일 종료
- Normal mode + : + {number} - 해당 줄 번호로 이동
- Normal mode + / + {keyword} - 해당 키위드가 있는 위치로 이동
- Normal mode + u - Undo
- Normal mode + Ctrl + r - Redo
- Ctrl + C - 실행 취소

