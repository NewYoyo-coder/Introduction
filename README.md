# Introduction

# 자기소개

## Git 특강 실습 repository

### 나의 기본정보

- **Name: 이유경**
- _Age: 25_
- Desired Job: [AI Engineer] (https://www.google.com/search?q=ai+engineering)
- Hobbies: Reading & watching animations
- **Things I like: Cats**

---

- git status
- git diff
- git add
- git status
- git commit -m "~~"
- git log

- To update Github itself, you must
  git push origin main

---

Accidental adding? /n

1. check staged: git diff --staged
2. commit stage에서 제거하려면, 즉, unadd하려면: git restore --staged
   /n/n
   To additionally add(head가 있는 지난 commit에 추가)/n
   1. git commit --amend(전 commit 수정, 전 head 수정)
   2. git commit --fixup HEAD(전 head 유지, 새로운 commit 생김)
