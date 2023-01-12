# 01/11(수)



### Git/Github/VScode/Markdown



### 1. Linux 명령어

* mkdir : 디렉토리 만들기
* touch : 빈 파일 생성
* cd : 디렉토리 이동
* ls : 디렉토리 내 리스트 출력
* rm : 파일삭제
* rm -r : 디렉토리 삭제
* rm -rf : f속성 추가하면 지워지지 않는 파일도 강제 삭제



### 2. Markdown 명령어

* `(Shift+~) 세번 입력 : 코딩 창

  ```python
  print('Hello World!')
  ```

* 'README.md' 파일을 써서 오픈소스 파일 작성 가능

* 한 게시글당 제목(#)은 한개 미만으로 사용

* 링크 적용

  [string]+(link)

  e.g : [naver](https://www.naver.com/)

  ![string]+(image_url)

* 텍스트 강조

  \**문자** : **bold**

  \*문자* : *italic*

  \~~문자~~ : ~~가로줄~~

  \*** ___ --- : 가로구분선



### 3. Github 사용법

- Markdown파일을 README.md로 저장

- Repository : 저장소(Github에 저장해줌)

- ADD/COMMIT/PUSH

  - add : 내 컴퓨터의 자료를 Staging Area로 업로드
  - commit : Staging Area의 자료에 쪽지를 보내는 것
  - push : Staging Area의 자료를 Repository로 이동
  - add→commit→push 순서대로 사용

  ```markdown
  1. 저장하려는 파일이 있는 폴더의 주소창에서 cmd열기
  2. git init : 폴더에 .git폴더(git 저장소) 생성
  3. git status : 내가 어떤 명령을 해야할지 보여줌
  4. git add [README.md] : README.md를 Staging Area로 업로드
  5. config설정 : user이메일(github이메일), username(github이름) 설정
  6. git commit입력시 commit editor진입, 내용 입력 후 저장(vi editor와 사용법 동일)
  7. github에서 파일을 저장할 repository 생성
  8. git remote add origin [repository 주소]
  9. git push : github에 파일 업로드(최초 실행시 git push —set-upstream origin master)
  ```

- github에 업로드된 파일 수정

  ```markdown
  1. 파일이 저장된 폴더에서 필요한 내용 수정
  2. cmd진입
  3. git add [파일명]
  4. git status : 파일이 수정된 것 확인
  5. add 후 commit까지 완료해야 github에서 내용이 수정됨
  6. git commit, commit editor에서 수정내용 입력 후 저장
  7. git push
  ```

- Repository에서 commit을 누르면 이전 버전 확인 가능
