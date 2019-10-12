# Hello Git World

## git의 주요 개념
- 작업 디렉토리 (Working Directory) : .git 디렉토리를 의미
- 준비 영역 (Staging Area, Stage/Index) : 커밋하기 전 어떤 파일을 커밋할건지 볼수있는 인덱스 영역
- 로컬 저장소 (Local Repository) : 커밋 내용이 저장되는 곳(.git 디렉토리 안쪽)
- 원격 저장소 (Remote Repository) :  github, gitlab 등등을 의미

## 기본 명령어
- git init : git 생성 명령어
- git status : git의 현재 상태를 알 수 있는 명령어
- git add : stage로 보내는 작업 명령어
- git rm --cached : 작업디렉토리에는 남아있고(stage) 준비영역, 버전관리대상에서만 사라짐
- git commit : 로컬 저장소에 저장하는 명령어
- git log : git commit 내역을 알려주는 명령어
- git reset --hard :  가장 최근에 커밋했던 상태로 돌아간다.
