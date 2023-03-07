# Git

<br>

![git](https://img.shields.io/badge/Git-2.30.1-red)

<br>

## 목차
[기본 설정](#기본-설정)

[SSH KEY 생성](#SSH-KEY-생성)

---
<br>

## 기본 설정
- 코드를 작성한 사람과 그 사람의 이메일을 알기 위한 설정

    ```
    git config --global user.name "name"
    git config --global user.email "email"
    ```

    ![1](./imgs/Git-1.png)

    - --global: 현재 PC 사용자(계정)에게 적용(전체 시스템 X)

---
<br>

## SSH KEY 생성
[자료 참조 - SSH 키 만들기](https://white-blank.tistory.com/8)

 - SSH(Secure SHell)란? 원격 호스트(여기서는 Git)에 접속하기 위해 사용되는 보안 프로토콜 ([자료 참조 - SSH 명칭부터 접속까지 한 번에 이해하기](https://library.gabia.com/contents/infrahosting/9002/))

   - 개인키(.pem)와 공개키(.pub)를 이용해 상대를 인증하고 통신

        > shell: 명령어와 프로그램을 실행할 때 사용하는 인터페이스. 커널과 사용자 간의 다리 역할. 사용자로부터 명령을 받아 그것을 해석하고 실행하는 역할

<br>

- Git 작업(push, pull, clone 등)을 위한 ssh key 생성
    - .ssh 디렉터리가 없어도 명령어(`ssh-keygen`) 실행하면 자동 생성
    - id_rsa: 개인키, id_rsa.pub: 공개키(GitHub에 등록)

    ![2](imgs/Git-2.png)
    ![3](imgs/Git-3.png)
    ![4](imgs/Git-4.png)