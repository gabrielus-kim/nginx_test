# nginx_test

## bash 에서 docker run 실행
user@DESKTOP-14530KF MINGW64 ~/df<br>
$ winpty docker run -it --name n1 -v c:\\Users\\user\\nginx_test:/nginx_test -p 8888:80 ubuntu<br>

## container 의 Mount 된 내용에서 Dockerfile 과 install.sh 파일 생성딤
root@bba4e5138327:/nginx_test# ls <br>
Dockerfile  README.md  install.sh<br>

## docker build : Dockerfile
user@DESKTOP-14530KF MINGW64 ~/nginx_test (master)<br>
$ winpty docker build --tag gabriel111/nginx-test .<br>
