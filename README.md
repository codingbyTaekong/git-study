# git-study
git을 제대로 공부하자

### 브런치 조회
```bash
    # 현재 브런치 조회
    git branch
    # 모든 브런치 조회
    git branch -a
    # 브런치 상세 조회
    git branch -v
    # 브런치 상세 조회
    git branch -vv
    # 브런치 상세 조회
    git status
```

### 브런치 생성
```bash
    git branch <branch-name>
```

### 브런치 삭제
```bash
    git branch -d <branch-name>
```

### 생성한 브런치에 연결
```bash
git checkout <branch-name>
```

### 브런치에 커밋
```bash
    git commit -m "commit message"
```

### 브런치에 push
```bash
    git push origin <branch-name>
```