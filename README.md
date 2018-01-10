# Virtualbox

#오라클virutalbox 설치
https://www.virtualbox.org/wiki/Downloads
Windows hosts 다운로드 (VirtualBox-5.2.4-119785-Win.exe)

#가상머신생성
유형 : Linux / Red hat(64-bit)
시스템>프로세서>2개
저장소>컨트롤러IDE>





#호스트키변경
파일->환경설정->입력->가상머신->호스트키조합->Ctrl + Alt



#CentOS7 설치
CentOS-7-x86_64-Everything-1708.iso

#초기설정

hostnamectl set-hostname dockerhost
yum update
yum install -y net-tools

yum install -y gcc make kernel-devel kernel sources kernel-headers

yum groupinstall -y "Development Tools"

shutdown -r now

#확장설치

가상머신콘솔창->장치->게스트확장CD이미지삽입


ls -al





















