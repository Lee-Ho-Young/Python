1. CentOS의 경우 대부분 python 설치되어 있다.

2. sys를 제외한 패키지를 import 하기 위해서는 pip 설치가 우선되어야 한다.
   [pip : python package manager]
   
   -- import requests를 사용하고자 하지만 [ImportError: No module named requests 에러 발생]
   -- pip install requests 명령어를 실행하고자 하지만, pip command not found
   
   [https://jjig810906.tistory.com/6]
   -- >> sudo yum install epel-release
   -- >> sudo yum -y update
   -- >> sudo yum install python-pip
   -- >> pip install requests 
   -- >> python test.py
