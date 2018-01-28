# springboot-simplepage

https://www.youtube.com/watch?v=sUdH_DuDr14

## 1-1. 로컬 개발 환경 세팅
* spring boot porject
    * web/mustache/dev-tools
* "Hello World" welcome 페이지
* live reload chrome extension 설치

## 1-2 bootstrap 활용한 html 페이지 개발
http://mvnrepository.com/ bootstrap webjar 
* bootstrap start html 추가
* bootstrap css 라이브러리 추가
* jquery javascript 라이브러리 추가
* index.html => navagation bar 추가
* 회원가입 페이지 개발

## 1-3. github에 소스 코드 추가
* sourcetree에 저장소 추가
* github에 소스 코드 추가

* local => 개발 서버/실 서버
* local => git/svn(버전관리시스템) => 개발 서버/실 서버
* local => github.com => 개발 서버/실 서버

## 서버구축 계정추가
* vagrant 서버구성
Vagrantfile
    config.vm.box = "hashicorp/precise64" 
vagrant init
vagrant up
* ssh로 서버 접속
ssh 127.0.0.1 -l vagrant -p 2222  암호 vagrant
* 계정 추가 및 sudo 권한 부여
sudo adduser <username> sudo
sudo usermod -a -G sudo <username>

## 각 계정별 UTF- 8 인코딩 설정
sudo locale-gen ko_KR.EUC-KR ko_KR.UTF-8
sudo dpkg-reconfigure locales
Home 디렉토리의 .bash_profile에 다음 설정 추가
    LANG="ko_KR.UTF-8"
    LANGUAGE="ko_KR:ko:en_US:en"
$source .bash_profile
$env 실행해 설정 

