- `git init`
    → 새로운 Git 저장소(repository)를 생성할 때 사용하는 Git 명령어 이다. 
    
- `git remote add origin <remote repository url>`
    -> git remote add [alias] [url]을 이용하여 특정 url을 alias로 다룰 수 있도록한다.(alias는 아무렇게나 설정이 가능하다.)(여기서 origin은 별칭을 의미)
- `git add <file name>`
    →  작업 디렉터리(working directory) 상의 변경 내용을 스테이징 영역(staging area)에 추가하기 위해서 사용하는 Git 명령어이다.
    
- `git commit`
    → 파일 및 폴더의 추가/변경 사항을 저장소에 기록하기 위해 사용한다.
    → Git commit이라고 명령어를 치면 여러줄의 메세지를 입력할 수 있으며 Git commit -m이라 하고 ""에 남기고 싶은 메시지를 사용하면 메세지 한 줄이 남는다.
    
- `git push origin <branch name>`
    → 원격 저장소(remote repository)에 코드 변경 분을 업로드하기 위해 사용하는 명령어(여기서 origin은 별칭을 의미)
    
- `git pull origin <branch name>`
   → 원격 저장소에서 변경된 메타데이터 정보를 확인할 뿐만 아니라 최신 데이터를 복사하여 로컬 Git에 가져온다.(여기서 origin은 별칭을 의미)
   
- `git merge <branch name>`
  → 작업했던 브랜치들을 병합할 때 사용할 수 있다.
