# Bandit 0~8 풀이 메모

## 0 -> 1
### 목표
VSC 터미널에서 SSH로 bandit0 계정에 접속한 뒤, readme 파일을 읽을 수 있다.
### 새로 사용한 명령어
ssh bandit0@bandit.labs.overthewire.org -p 2220 # 계정 접속
ls # 파일 탐색
cat readme # 파일 읽기

## 1 -> 2
### 목표
파일 이름에 -이 들어간 파일을 읽을 수 있다.
### 새로 사용한 명령어
cat ./- # ./은 -을 파일명임을 명확히 지정한다.

## 2 -> 3
