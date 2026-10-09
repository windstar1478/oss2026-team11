# 작업 방법

1. `git checkout main` 과 `git pull` 로 main 을 최신으로 받는다.
2. `git checkout -b <브랜치>` 로 브랜치를 만든다. 한 브랜치에는 한 가지 일만.
3. 커밋하고 `git push -u origin <브랜치>`.
4. GitHub 에서 PR 을 열고 Reviewers 에 팀원 한 명을 지정한다.
5. 승인을 받으면 작성자가 머지하고 브랜치를 지운다.
6. 충돌이 나면 내 브랜치에서 `git fetch`, `git merge origin/main` 으로 푼다.