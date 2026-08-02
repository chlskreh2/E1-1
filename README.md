# 내 컴퓨터에 개발자용 '작업실' 꾸미기

## 미션 요약

## 실행 환경
- OS: macOS 15.7.4
- 쉘: zsh
- 터미널: Apple_Terminal
- Docker 버전:
- Git 버전: 2.53.0

## 수행 항목 체크리스트
- [o] 터미널 조작 로그 기록
- [] 권한 실습 및 증거 기록
- [] Docker 설치 및 기본 점검
- [] Docker 기본 운영 명령 수행
- [] 컨테이너 실행 실습
- [] 기존 Dockerfile 기반 커스텀 이미지 제작
- [] 포트 매핑 및 접속 증거
- [] Docker 볼륨 영속성 검증
- [] Git 설정 및 Github 연동
- [] 보안 및 개인정보 보호

## 터미널 조작 로그 기록
```zsh
# 현재 위치 확인
pwd
```
![pwd](./images/1-1/pwd.png)
```zsh
# 목록 확인 (숨김 파일 포함)
ls -al
```
![ls](./images/1-1/ls.png)
```zsh
# 디렉토리 이동
cd 경로
```
![cd](./images/1-1/cd.png)
```zsh
# 폴더 생성
mkdir 폴더명
# 빈 파일 생성
touch 파일명.txt
```
![mkdir_touch](./images/1-1/mkdir_touch.png)
```zsh
# 파일 복사
cp 원본 복사본
# 폴더 복사 (-r: 재귀)
cp -r 원본폴더 복사본폴더
```
![cp](./images/1-1/cp.png)
```zsh
# 이름 변경
mv 원본 새이름
# 파일 이동
mv 파일 경로
```
![mv1](./images/1-1/mv1.png)
![mv2](./images/1-1/mv2.png)
```zsh
# 파일 삭제
rm 파일명
# 폴더 삭제
rm -r 폴더명
```
![rm](./images/1-1/rm.png)
```zsh
# 파일 내용 확인
cat 파일명
```
![cat](./images/1-1/cat.png)

