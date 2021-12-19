# git hub 설치

우선 vscode에서 사용한다는 가정하에 git 다운받고 설치중에 중간꺼 vscode로만 바꾸고 나머지는 그냥 next ㄱㄱㄱ

다 설치되면 git bash 들어가서 git --version 치고 git version 뭐시기 나오면 git 설치는 완료된것

다음

이름 설정 : git config --global user.name "유저이름"

이메일 설정 : git config --global user.email "이메일주소"

위에 두가지 설정하기

git config --list

아래쪽 이름하고 이메일 바뀌었나 확인하기



# create a new repository on the command line

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin git@github.com:mucheol/git-start.git

git push -u origin main

#push an exi
