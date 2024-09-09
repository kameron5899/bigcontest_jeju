# branch 규칙
* main이 아닌 새로운 브랜치를 생성하여 작업
    * 브랜치명 규칙 : <이름>_<현재 진행 작업>
* 최신 이력 정보 확인
    * git remote update : 원격 저장소의 모든 브랜치에 대한 최신 이력 정보 확인
    * git fetch --all : 현재 위치한 브랜치의 최신 이력 정보 확인
* branch 확인 및 이동
    * git branch : 현재 작업 중인 브랜치 확인
    * git checkout <브랜치명> : <브랜치명>으로 checkout
* git pull : 브랜치의 최신 변경사항을 로컬로 가져옴
* 변경사항 저장
    * git add <file명> : git add . 를 통해 모든 파일을 staging area에 추가 가능
    * git commit -m "커밋메세지"
    * git push
