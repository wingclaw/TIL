git init : 깃 생성. , .gt 폴더 생성.
git add . : 깃 대상 전부,앞으로도 추가
git commit -m '메시지' :메세지 버전 남김
git status : git 상태 확인
git log :기록된 커밋 조회

---
git log --oneline -2
---

git remote add origin https://github.com/wingclaw/232.git : 깃 연격 저장소(remote) 추가(add) origin 이름으로 주소를
git push -u origin master : 깃 원격 저장소로 보내(push)

git remote -v

---
커밋 남기고 다시 push

--

---
로컬에서 원격저장소로 저장
git add

git commit

git push main
---

git remote add origin https://github.com/username/repositoryname.git
깃 원격저장소(remote) 추가(add) origin 이름으로 주소를
git push origin main 
깃 원격저장소로 보내(push) origin/main으로

git remote rm origin 
삭제(rm)
git remote -v
원격저장소 목록 조회

공백문자
' ' 묶거나
공\ 백 (이스케이프문자)