# st_page
멋쟁이사자처럼 부트캠프

# 처음사용자를 위한 github으로 local파일 올리는 방법

# 이 모든것 이전에 git을 설치하여야 합니다. 
git download-> https://git-scm.com/downloads

# git bash를 열고 환경설정을 몇가지 해주어야 해요. 


1) user name 설정하기 git config --global user.name "hyung ju kim"
2) user email 설정하기 git config --global user.email "hyungjukim749@gmail.com"
   * 여기서 이메일은 반드시 깃헙 회원가입시 설정한 이메일로!!
3) git config --list  


ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ
# github 과 vscode 연결방법(vscode 사용)
 1) (st_venv) D:\likelion\st_page>git init
 2) (st_venv) D:\likelion\st_page>git add main_page.py
 3) (st_venv) D:\likelion\st_page>git status
 4) (st_venv) D:\likelion\st_page>git commit -m "first commit"
 5) (st_venv) D:\likelion\st_page>git branch -M main
 6) (st_venv) D:\likelion\st_page>git remote add origin https://github.com/hyungjukim749/st_page.git
 7) (st_venv) D:\likelion\st_page>git remote -v
 8) (st_venv) D:\likelion\st_page>git push -u origin main



# git에 계속 올리는 방법
  1) (st_venv) D:\likelion\st_page>git add.requirments.txt
  2) (st_venv) D:\likelion\st_page>git commit -m "second commit"
  3) (st_venv) D:\likelion\st_page>git push -u origin main
