# Virtualbox

#오라클virutalbox 설치

https://www.virtualbox.org/wiki/Downloads

Windows hosts 다운로드 후 설치 (VirtualBox-5.2.4-119785-Win.exe)

#가상머신생성

-이름 및 운영체제 : Linux / Red hat(64-bit)

-메모리: 4096

-새가상하드디스크: 고정크기 8GB

#호스트키설정(창 밖으로 빠져나가는 키)

파일->환경설정->입력->가상머신->호스트키조합->Ctrl + Alt

#가상머신설정(생성한 가상머신 선택 후 진행)

-시스템>프로세서>2개

-저장소>컨트롤러IDE>CentOS-7-x86_64-Everything-1708.iso 파일 지정>확인

-네트워크>고급>포트포워딩>ADD>호스트포트와 게스트포트에 22 입력 후 확인(노트북에서 PUUTY로 접속하기 위함)

#가상서버 선택 후 시작하여 리눅스설치: 타임존 Asia/Seoul, 랜카드ON, root암호지정

#가상서버접속하기

ipconfig하여 사설NAT IP주소 확인

putty다운로드하여 위 IP주소로 접속

#(선택사항)가상서버클론

shutdown -h now

가상서버선택>마우스오른쪽클릭>복제>이름지정하기>완전복제

-End-



