## 수정한 파일 전체 임시 저장소에 올리기
```
git add .
```

## 수정한 파일 임시 저장소에 올리기
```
git add README.md
```
## 수정한 파일 로컬 저장소에 올리기
```
git commit -m "first commit"
```

## 로컬 브랜치 이름 변경하기 (원래 기본 master -> main)
```
git branch -M main
```

## 연결된 git 주소 확인
```
git remote -v
```
## 로컬 저장소 -> 원격 저장소로 올리기
```
git push origin main
```

### 브랜치는 따로 만들지 않을 예정 -> 만들면 많이 헷갈릴 수 있음