# Git Branch

## Git 기초
- `git init`
- `git add`
- `git commit`
- `git log`

## Git 원격저장소(remote)
- `git remote add [저장소 이름] [저장소 주소]`
- `git remote `
- `git remote -V`


## 깃 커밋 메세지
깃 커밋 메세지는 주어빼고 동사원형으로!!

## 과거로 가는 법
- `git checkout [log_head]`
git branch

## 브랜치 사용법
`git branch` : branch 리스트
`git branch [브랜치명]` 새 브랜치 생성

`git checkout [브랜치 명]` 이동
`git swich [브랜치 명]`이동


`git checkout -b [브랜치 명]` 생성 이동
`git swich -c [브랜치 명]` 생성 이동

`git branch -d [브랜치명]` 브랜치 삭제

`git merge [브랜치 명]` : 현재 브랜치에서 특정 브랜치를 병합
ex)
@master
git merge develop
마스터에 develop 병합 하지만 develop 은 살아남

## merge 시나리오
### fast-forward 방식
앞으로 옮기는 방식
분화된 뒤에 병합 주체 브런치가 변화가 없으면 병합주체를 피 병합 주체의 끝으로 이동

### auto merge (without conflict)

### merge with conflict
