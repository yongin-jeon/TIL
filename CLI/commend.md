# CLI

command line interface 명령어를 정리합니다.



#### pwd

현재 위치한 폴더를 출력하는 명령어입니다.



```bash/shell
pwd
```



#### ls

list의 약자로 현재 폴더에 있는 모든 파일과 폴더를 출력하는 명령어 입니다.



```bash/shell
ls #숨김폴더는 출력 안함
ls -a #숨김폴더, 파일까지 모두 출력함
```





#### cd

change directory의 약자로 폴더를 이동하는 명령어입니다.



```base/shell
cd <PATH> #이동하고 싶은 폴더를 PATH에 입력
```



#### 생성

- `touch` : 파일을 생성

- `mkdir` : 폴더를 생성

  

#### vi

vim 에디터를 사용하여 편집

연습 할 수 있는 사이트 [빔어드벤쳐](https://vim-adventures.com/)

```
[제목](주소) ##하이퍼링크 ![제목](주소) ##이미지 -> 사실 걍 끌어다 담아도 됨
```





### .gitignore

무시할 파일 폴더 설정

푸시하기 전에 만들기 gitignore.io 홈페이지 / django python windows

### git 포트폴리오관리



bootstrap template 사이트 ->  view on github -> github에서 코드복사



 ->작업할 폴더에서 bash 실행

-> git clone <url> 복사한 url



 ->ls 를 하면 폴더생긴것을 확인가능

-> cd startbootstrap-resume 로 이동



-> git log --oneline    (나올때는 q)  

-> .gitignore 파일 생성할것 touch .gitignore

->git remote -v (원격저장소를 보는 명령어)  주소가 github로 되어있는것을 알 수 있다.

->git remote remove origin 주소가 github로 되어있어 지우고 컴퓨터 내부로 재 설정해야함

->git remote add origin <url> 원하는 git repository의 주소

-> git remote -v 로 확인



->작업폴더의 readme.txt를 삭제하기

->bash에서 add -m "" // add commit origin master

->깃 계정에서 페이지 실행하면 끝





수정이 필요하면 vscode가 편함

ctrl ` -> default terminal-> git bash shell로 바꾸고 수정이 있을때 마다 

git add . /git commit -m ""/git push 