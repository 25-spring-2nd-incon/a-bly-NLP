# a-bly 리뷰 분석 NLP 프로젝트

## Ground Rules

### Work Flow
아래의 워크 플로우를 준수하면서 프로젝트를 진행해보자!

1. 원격 레포지토리의 최신 변경사항을 로컬 main 브랜치에 반영하기.
```
git switch main
git pull origin main
```

2. 새로운 작업 브랜치 생성: 최신 main 브랜치에서 새 작업 브랜치를 생성
```
git switch -c <새 브랜치명>
```

3. 작업 및 커밋: 커밋은 중간 저장처럼 자주 해도 괜찮음.
```
# 작업 후
git add .
git commit -m "작업 내용 요약"
```

4. 작업 완료 후 원격 브랜치로 푸시
```
git push origin <내 브랜치명> #⚠️ 충돌 방지를 위해 main 브랜치에 직접 push하지 말 것!!
```

5. GitHub에서 Pull Request(PR) 생성
: 내 브랜치 → main 으로 PR 생성

6. 관리자가 Merge
: 리뷰가 승인되면 main 브랜치로 병합


7. 브랜치 정리: 작업이 끝난 브랜치는 로컬에서 삭제하여 브랜치 관리 간소화
```
git branch -d <내 브랜치명>
```

### Branch Name
<이름>/<작업내용>으로 브랜치 명 통일하기
| 예시) seungsik/nlp-preprocessing