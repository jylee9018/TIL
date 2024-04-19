# Linux Command (Basic)
### 파일 생성
touch {name.py}
- 텍스트 문서 생성 가능: .txt
- 프로그래밍 언어 문서 생성 가능: .py, .java, .go 등

### 파일 삭제
rm {name.py}

### 폴더 생성
mkdir {dir1} 
mkdir {dir2/sub1}
mkdir {dir2/sub2}

* 상위 폴더와 하위 폴더를 한 번에 생성할 때
mkdir -p {dir3/sub1}

### 폴더 삭제
rmdir {dir1}

* 하위 파일 및 폴더가 존재할 때
rmdir -p {path/name.py}

# Git Command

```
git clone https://github.com/jylee9018/TIL.git

git add 240419-Git-Command.md
git commit
git push origin main
```

# VIM Command
- I - INSERT
- ESC - Normal mode
- Normal mode + : + q! - 파일 종료(저장 하지 않음)
- Normal mode + : + wq - 저장 후 파일 종료
- Normal mode + : + {number} - 해당 줄 번호로 이동
- Normal mode + / + {keyword} - 해당 키위드가 있는 위치로 이동
- Ctrl + C - 실행 취소

