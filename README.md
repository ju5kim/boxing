# Boxing + Exciting

복싱 사이트
//-------------로컬에 git 사용하기
git bash 에서 로컬 저장소로 이동한다
이동 후 
git init; 을 실행한다.
파일을 만든다 작업환다.
그런다음

git add 파일명.확장자
(git add . ) 하면 모든 파일 
내가 업데이트 하고 싶은 파일들을 선택하는 것 - 스테이지에 올린다.
(변동 사항이 없는 것들은 stage에 이미 올라와 있다.한번이라도 add 했으면 자동으로 추적이 된다.)

git commit -m "파일 설명추가" -- 사진을 찍는다 - 

git log  커밋 정보들 보기

위에 까지 하면 로컬에서 git을 사용하는 것을 완료 한것이다.\
//-------------------------------------------------------------

//-- 깃헙 사이트에 내가 작업한 로컬폴더에 git과 깃헙을 연동 시킨다.

git remote add  origin http://github.com/아이디/깃헙저장소이름.gita
remote 이름을 origin으로 추가한다 

만들어 놓은 커밋을 푸쉬하기
git push origin master
마스터 브랜치로 푸쉬하기

//--------------------------------------------------------------

//다른 사람의 깃을 받아오기
클론 
pull = 최신버전으로 다시받아오기 업데이트 받아오기
push = 다른 사람의 깃을 push 할 수 있지만 그럴러면 다른사람 깃에서 그걸 허용을 해줘야한다.

//깃 클론 = 복사하기
일단 로컬에 다운 받을 폴더를 만들어 두고 거기서 
git bash에 들어가 해당 폴더로 이동 후
git clone https://github.com/ju5kim/깃헙저장소주소.git 를 실행하면 된다.
이렇게 하면 해당 폴더에 깃헙저장소이름으로 폴더가 생성된다.
rm -rf boxing/ 하면 해당 폴더와 파일을 지운다.
그냥 현재 폴더에 받을려면
git clone https://github.com/ju5kim/깃헙저장소주소.git . 을 실행한다.


//깃 pull

git pull origin master 
깃헙에 최신버전으로 소스 업데이트 하기
//------------------------------------------------------------------------



// ------소스트리 사용법
소스트리에서 일단 +, add를 사용해서 
git을 사용한 로컬저장소를 지정해서 실행시킨다.

그런 다음 add 로 변경사항을 스테이지에 올리고 커밋을 실행한다.
여기서  도구 옵션으로 commit할 계정을 선택할 수 있다.

commit할때 코멘트는 항상 달아야 한다. 주의할 것

origin/master 와 master의 차이
origin/master는 깃헙과 로컬에 있는것
maser는 로컬에만 있는것



