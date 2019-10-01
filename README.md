## Quiz


*git branch -d solution
*git push origin --delete solution


```
cd C:\Users\IME17\Desktop\PatternRecognition              #주어진 폴더로 이동한다
git clone https://github.com/BaekSohyeon0420/Quiz.git     #해당 폴더에 Quiz repository를 연결한다
cd Quiz   #깃허브 폴더로 이동한다
git config --global user.name "nameee"  #사용자 이름을 설정한다
git config --global user.email "namdfhake@mail.com"   #사용자 메일을 설정한다
git add .  #Quiz폴더에 생성한 파일을 올린다
git commit -m "add file"  #올라온 파일을 commit한다
git status   #commit이 잘 되었나 확인한다
git push     #저장소에 업로드한다
git branch solution   #솔루션 branch를 추가한다
git checkout solution     #branch위치를 솔루션으로 옮긴다
git branch   #확인한다
git add 20190924_Quiz1_solution.py   #해당 파일만을 솔루션branch에 올린다
git commit -m "new solution"   #올라온 파일을 commit한다
git push origin solution  #솔루션 branch와 내부 파일을 repository에 업로드한다
git branch   #branch의 위치를 확인한다
git checkout master   #branch의 위치를 마스터로 옮긴다
git branch   #branch의 위치를 확인한다
git merge solution   #솔루션을 마스터로 merge한다
git push   #저장소에 업로드한다

```
