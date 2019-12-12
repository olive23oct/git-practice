# git practice

#### clone
- git clone - -depth [number][url] 
	- 마지막 number 개의 커밋만 포함하여 저장소 복제하기

#### 기능별로 개발하기
- branch 생성 
	- git branch [name] 
- 브랜치/버전 이동하기
	- git checkout [name]
- 브랜치 합치기
	- git merge [name]
- 브랜치 합치기(2)
	- git rebase master
- 브랜치 지우기
	- 사용을 끝낸 브랜치는 삭제해야함
	- git branch -d [name]

#### 협업
- 협업할 멤버 collaborators 추가하기
- 실수한 커밋은 reset으로 삭제할 수 있지만 revert로 지우는 기록을 추가하자
- git reset [option][branch]
- git revert [branch] 
#### log
- git log
- git log --all --decorate --graph --oneline
- git config --global alias.showlog "git log --all --decorate --graph --oneline"
- git log --pretty=format:"%h %s" --graph

#### fetch 가져오기
- 원격 저장소와 동기화 

#### pull 
- 원격 저장소와 동기화하고 merge