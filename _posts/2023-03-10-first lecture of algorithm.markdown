---
layout: post
title:  "Algorithm 1 week: how to make my own git hub server and blog"
date:   2023-03-10 15:00:00 +0900
categories: jekyll update
---
1.	Ruby 설치하기 

https://rubyinstaller.org/downloads/
---

2.	Ruby 를 통해 지킬 설치

chcp65001   (한국어인코딩)
gem (package manager)
chcp 65001 
gem install jekyll bundler
jekyll -v(버전확인)
jekyll new @@ (blog 경로에 새로운 디랙토리 설정 및 생성)
cd @@ (change working directory)
bundle exec jekyll serve (서버생성) (ip 확인) 

---

3.	Git 설치

https://git-scm.com/download/win

cmd로 실행

---

4.	Git을 통해 내 github 계정에 있는거 #git clone 이용

추가적인 git 명령어

깃 초기화
#clone /복제 – github 외부저장소 접근 > 복제

git clone https://github.com/Juno0002/juno0002.github.io.git potato chip 라는 블로그 복제

#init

버전관리
파일수정후 사용
#add
#commit 무엇이 바뀌었는지 알려줌
#push
#(pull)

상태 관리
Status

https://github.com/new
에서 새로운거 만들기


5.	새로운 문서 포스트 제작 – markdown 언어 사용하여 새로운 파일생성
---

6.	cmd에서는 cd@@를 통해 주소 왔다갔다 가능함
---

7.	새로운 파일을 만들었다면 순서대로 하여 적용

1) git add .

2) git commit -m “코맨트 달기”

3) git push

이과정이 모두 끝났다면 깃 깃허브 루비 마크다운 지킬 설치완료 블로그 포스팅 가능한 환경 완성 

이후의 작업은 ruby cmd를사용하여 하면 좋을것으로 보임
---

8.	루비를 통해 directory 이동 후 #bundle exec jekyll serve 를 사용(서버열기)

https://juno0002.github.io/ 지금부터 이 블로그가 생성됨

포스팅 하고싶을때는 _post 에서 계속 마크다운 파일을 만들어내면됩니다
