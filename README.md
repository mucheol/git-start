# git hub 설치
1. VSCode에서 사용한다는 가정하에 git 다운받고 설치중에 중간꺼 vscode로만 바꾸고 나머지는 그냥 next ㄱㄱㄱ
2. git bash 들어가서 git --version 치고 git version 뭐시기 나오면 git 설치는 완료된것
3. 이름 설정 : git config --global user.name "유저이름"
3. 이메일 설정 : git config --global user.email "이메일주소"
4. git config --list
5. 아래쪽 이름하고 이메일 바뀌었나 확인하기


# VSCODE에 git 연동하기
1. Github에서 repository 생성
2. VSCode열고 git에 연동할 폴더 열고 왼쪽에 Source Control 탭 누르기
3. Initialize Repository버튼을 눌러 초기화하기
4. Changes에 있는 파일중 commit할 파일 옆의 +버튼 눌러 추가하기(Change 옆의 +는 전체선택)
5. 상단에 있는 V표시 눌러서 Commit 메세지 적고 Commit 하기
6. Terminal 들어가기(상단 View -> Terminal)
7. git remote add origin [ 복사한 저장소 주소 ] ----- ex) git remote add origin 
