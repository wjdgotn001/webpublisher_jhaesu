# 웹퍼블리셔과정 20200727~20201218

1. git 계정 생성하기

2. new repository 생성

3. git자료를 복제 (웹사이트에 있는 사이트를 내컴퓨터로 연결, 옮겨오는 과정)
   
   1. 내 컴퓨터에서 git clone(복제) 생성한 repository(저장소) 
   
      **$ git clone https://github.com/wjdgotn001/webpublisher_jhaesu.git**
   
4. README.md 파일을 생성 및 내용 작성

   **$ cd webpublisher_jhaesu/**

   **$ touch README.md** (내용적고 저장)

   **$ cat README.md**

5. 계정을 연결(config ~을 설정하겠다.) 
   **--global 컴퓨터 전체에 git등록한 사람의 정보를 등록하겠다->*최초1번*  만 등록하면 됌.** **
   
   1. 자료를 올리는 사람의 이름과 이메일주소가 필요함.  
   
      **$ git config --global user.name "wjdgotn001"**
      **$ git config --global user.email "wjdgotn001@gmail.com"**
   
      **$ git config user.name / $ git config user.email**
   
   2. git status 상태확인-> 파일을 못찾겠다라고 하면->파일 추가하기 
      **$ git add README.md**
      **$ git status**
   
   3. 내용보내기(파일의 제목) ->  **$ commit -m "0000"** 내용을 요약해서 쓰겠다.
   
   4. 계정로그인 (id/pw가 필요)
   
6. github로 push(보내겠다는 뜻)

   **내용수정 시-수정하고 git status -> git add "현재 파일명" -> git status -> git commit -m "github" (수정할 "파일명" 작성) -> git push**

7. github의 자료를 pull 처리하여 가져오기 

   

- [x] < 중요중요 **full, add, commit, push** >

---

## *계정 로그아웃 

제어판->사용자계정->자격 증명 관리자->window자격증명->링크클릭 후 제거

**그대로 가는 내용**: git clone "주소"

**수시로 체크해야하는 내용**: git status(지금의 상태확인)

**복제 후 업데이트 갱신**: git pull , git add 파일/폴더 , git commit -m "설명" , git push

**주의할 점**: 

1. 한번에 100MB이상의 파일은 올릴 수 없다.
2. 한번에 100개 이상의 파일은 올릴 수 없다.

---

### 택배 보내는 순서

1. 물건을 포장한다.
2. 상자에 담는다.
3. 우체국에 간다.
4. 송장을 작성한다. (주소,이름,연락처,우편번호,물건의 내용)
5. 돈내고 보낸다.

---

CLI연습

마크다운연습

GIT연습

프로토타입 제작,,