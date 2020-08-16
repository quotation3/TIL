# linux 기초 문법

linux에서 사용가능한 기본 문법을 정리합니다.



### 현재 폴더위치

- pwd (print working directory)

```shell
$ pwd
```



### 폴더변경

- cd (change directory)

```shell
$ cd <이동하고 싶은 폴더이름>
```



### 현재 폴더에 있는 리스트 출력

- ls (list)
  - `-a` 옵션은 숨김파일까지 출력해준다

```shell
$ ls -a
```



### 파일 생성

- touch

```shell
$ touch <생성할파일이름>
```



### 파일 삭제

- rm
  - 만약 폴더를 삭제하고 싶으면 `-r` 옵션을 추가해서 삭제가능

```shell
$ rm <삭제하고싶은파일이름>
```



### 이미지 복사

- 파일 - 환경설정
- ![캡처](basic.assets/캡처-1594189492490.JPG)