- main
  - git checkout -b develop1
  - git checkout -b develop2

## develop1에서 작업

- git add & commit
- git push origin develop1

## main에서 merge

- git checkout main (main으로 이동)
- git pull origin develop1 (merge)
- git push (github에 푸시)

### main에서 수정했을때 다른브랜치에서 가져오기

- git add & commit & push origin main 했을 경우
  - git checkout develop1
  - git pull origin main
